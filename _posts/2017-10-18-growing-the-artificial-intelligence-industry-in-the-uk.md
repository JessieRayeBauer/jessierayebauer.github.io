---
layout: post
title: Growing the Artificial Intelligence Industry in the UK
mathjax: false
---

The recent report "Growing the Artificial Intelligence Industry in the UK"<sup><a href="#growing-the-artificial-intelligence-industry-in-the-uk">[1]</a></sup> contains many sensible recommendations for how to do just that. It includes recommendations for improving access to data, increasing the supply of skills related to AI, maximising the amount of AI research taking place in the UK and supporting the uptake of AI in industry.  The ethical implications of AI are not given a particularly thorough treatment as the authors consider the topic to be beyond the scope of the report:

> *Trust, ethics, governance and algorithmic accountability:* Resolving ethical and societal questions is beyond the scope and the expertise of this industry-focused review, and could not in any case be resolved in our short time-frame.

The way this is phrased draws a contrast between "ethical and societal questions" and "industry-focus", as though the two are largely or entirely separable. Despite this, the report touches on ethical issues at various points. For instance, it recommends attracting a diverse set of people to the discipline on the grounds that a diverse workforce will be better placed to recognise and resolve issues of bias in algorithms: "Diversity is particularly important for AI as the output quality of the algorithm depends on the assurance that the inherent bias of programmers does not transfer to code. A diverse group of programmers reduces the risk of bias embedding into the algorithm and enables a fairer and higher quality output."

The passage I found most interesting was a subsection on "Explainability of AI-enabled uses of data." As the authors put it, "[t]here is a growing consensus that decisions which affect people and are made on the basis that decisions based on data analysis data should be fair, and should be demonstrably fair." It references the General Data Protection Regulation, an EU regulation due to take effect 25th May 2018.  This regulation affords certain rights to people whose personal data is used as input to a decision-making algorithm. The exact nature of those rights is open to interpretation.<sup><a href="#european-union-regulations-on-algorithmic-decision-making-and-a-right-to-explanation">[2]</a><a href="#why-a-right-to-explanation-of-automated-decision-making-does-not-exist-in-the-general-data-protection-regulation">[3]</a></sup> On one reasonable interpretation, it includes a "right to not be discriminated against" and a "right to explainability". If an algorithm makes a decision that affects you then you have a right to that decision being fair and a right to an explanation of why it was made. The section concludes with a recommendation:

> *Recommendation 14: The Information Commissioner’s Office and the Alan Turing Institute should develop a framework for explaining processes, services and decisions delivered by AI, to improve transparency and accountability.*

This recommendation is welcome but doesn’t go far enough. The main problem is that it recommends developing a framework for explaining decisions delivered by AI, suggesting that the way AI makes decisions is something that is both explicable and predetermined. Neither is necessarily true. Many of the algorithms in widespread use today make decisions that are at least ostensibly inexplicable (whether in theory or in fact). For example, neural networks are often trained on datasets where each entry has thousands of variables. They train by making tiny adjustments to weights associated with each variable in an iterative process. A satisfying, human-understandable explanation of the significance of a particular set of weights may not be possible. The "black box" problem of AI has been well documented<sup><a href="#the-dark-secret-at-the-heart-of-ai">[4]</a></sup> and there are calls for public agencies to stop using such algorithms in areas like criminal justice, welfare and education.<sup><a href="#ai-now-2017-report">[5]</a></sup> These calls are already spreading to private industry, especially with respect to hiring practices and workplace monitoring.<sup><a href="#hiring-algorithms-are-not-neutral">[6]</a></sup> 

The solution is not only to develop a framework that explains decisions delivered by AI but also to invest in developing algorithms that are fair and transparent by design. It should be a given that if your research has applications in areas like criminal justice, welfare and so on, then transparency and freedom from bias are criteria against which the success of your algorithm will be measured. 

Even if they are unmoved by ideals, businesses should support this for self-interested reasons. Firstly, biased algorithms tend to preserve the status quo. When, for example, a company uses a hiring algorithm that makes biased decisions it can miss out on many high quality candidates simply because they don’t look like employees that have been successful in the past. Secondly, if it comes to light that a business has been using algorithms that discriminate it could do that business significant reputational damage. Finally, the use of opaque and biased algorithms is a form of technical debt. As public awareness and legislation catches up they will have to be detected and replaced. This will be costly and frustrating and, as a commitment to individual rights may preclude the use of many powerful AI algorithms, UK industry could be at a global disadvantage if research into approximately powerful alternatives is underdeveloped.

Concern for fairness and transparency should be embedded in the artificial intelligence industry and not considered a topic for only governments and academics to be concerned with. Although I thought the "Growing the Artificial Intelligence Industry in the UK" report was excellent, I do think it was lacking in this respect.

## References

1. <a id="growing-the-artificial-intelligence-industry-in-the-uk" href="https://www.gov.uk/government/publications/growing-the-artificial-intelligence-industry-in-the-uk">Growing the Artificial Intelligence Industry in the UK</a>
2. <a id="european-union-regulations-on-algorithmic-decision-making-and-a-right-to-explanation" href="https://arxiv.org/pdf/1606.08813.pdf">European Union regulations on algorithmic decision-making and a "right to explanation"</a>
3. <a id="why-a-right-to-explanation-of-automated-decision-making-does-not-exist-in-the-general-data-protection-regulation" href="https://www.academia.edu/31045353/Why_a_right_to_explanation_of_automated_decision-making_does_not_exist_in_the_General_Data_Protection_Regulation">Why a right to explanation of automated decision-making does not exist in the General Data Protection Regulation</a>
4. <a id="the-dark-secret-at-the-heart-of-ai" href="https://www.technologyreview.com/s/604087/the-dark-secret-at-the-heart-of-ai/">The Dark Secret at the Heart of AI</a>
5. <a id="ai-now-2017-report" href="https://assets.contentful.com/8wprhhvnpfc0/1A9c3ZTCZa2KEYM64Wsc2a/8636557c5fb14f2b74b2be64c3ce0c78/_AI_Now_Institute_2017_Report_.pdf">AI Now 2017 Report</a>
6. <a id="hiring-algorithms-are-not-neutral" href="https://hbr.org/2016/12/hiring-algorithms-are-not-neutral">Hiring Algorithms Are Not Neutral</a>
