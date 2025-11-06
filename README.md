# Short-Story-Selection

Title

A Survey of LLM-based Deep Search Agents: Paradigm, Optimization, Evaluation, and Challenges

Authors

Yunjia Xi, Jianghao Lin, Yongzhao Xiao, Zheli Zhou, Rong Shan, Te Gao, Jiachen Zhu, Weiwen Liu, Yong Yu, Weinan Zhang. 
DBLP
+2
arXiv
+2

Publication Info

Preprint on arXiv (2025). 
arXiv
+1

Abstract / Purpose

The paper observes that the advent of large-language-models (LLMs) has significantly transformed web search, enabling more dynamic, autonomous systems rather than static query-responses. 
arXiv
+1

It focuses on a new paradigm: LLM-based deep search agents (sometimes called “search agents”) that:

Understand user intent and context,

Plan and execute multi-turn retrieval (not just one query → result),

Integrate information from multiple sources (web, private memory, databases) to answer complex queries. 
arXiv
+1

The survey systematically analyses prior work in this space from four major dimensions: architecture (“how to search”), optimization (“how to optimize”), application (“how to apply”), and evaluation (“how to evaluate”). 
arXiv
+1

It also identifies current open challenges and future research directions. 
arXiv
+1

Key Contributions

Task formulation: Defines what a deep search agent is — given user intent + context, the agent actively plans, acts (issue queries, retrieve, refine) and produces answers. 
arXiv
+1

Systematic taxonomy / categorisation: Offers an organized view of how search agents are built:

“How to Search” (search structures): sequential, parallel, hybrid. 
fugumt.com
+1

“How to Optimize”: tuning-free methods, supervised fine-tuning (SFT), reinforcement learning (RL). 
fugumt.com

“How to Apply”: internal agent enhancements (tool use, memory, reasoning), external applications (finance, healthcare, coding). 
arXiv

“How to Evaluate”: datasets, metrics, evaluators (human, LLM-as-judge). 
Sina Finance

Challenges & future outlook: Highlights issues like multi-source fusion, multimodality, reward design for RL, evaluation beyond final answer accuracy. 
fugumt.com
+1

Why It’s Relevant

If you’re working on data mining / extraction / web-search / scraping, this paper touches on the frontier of how LLMs are used not just for retrieval but for deeper, autonomous information seeking and mining.

Although it’s framed in “search agents,” the concepts overlap with data extraction + mining: multi-turn retrieval, dynamic planning, integrating multiple sources, reasoning over retrieved data.

It provides a strong structural framework you could adapt for survey work in the intersection of web-scraping/data mining + AI/ML agents.

How You Could Use It

Use its taxonomy (search structures, optimization methods, evaluation frameworks) as a template for your own survey, perhaps focusing specifically on web-scraping/data-mining agents.

Leverage the “open challenges” section to identify gaps in web-scraping/data-mining domain (e.g., autonomous agents that scrape + mine + reason) and propose how your survey will address them.

Use their references (they maintain a GitHub repo of papers) to pull further reading that span scraping + mining + search agents. 
GitHub
+1

Limitations / Considerations

The paper mainly focuses on search agents in the sense of retrieval and information seeking, rather than classic data mining tasks such as clustering, pattern mining, anomaly detection.

If your interest is strictly “web-scraping + data mining” (extraction of data, followed by mining), you may need to expand or adapt the survey’s scope to cover mining frameworks not detailed in this paper.

Some recent works (post‐2025) may not yet be included given the publication timeline.
