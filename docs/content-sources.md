# Content audit — 2026-10-01

## Sources and decisions

- Group affiliation: the owner explicitly confirmed that EIPI is a research group directly at South China University of Technology. The organization and website therefore omit the Computational Intelligence Team hierarchy. Prof. Zhong's individual faculty affiliation remains the School of Computer Science and Engineering.
- Citation count: the owner supplied a Google Scholar screenshot showing 5,883 total citations and requested the rounded public wording **5,800+**. This is a manually maintained snapshot, not a live metric.
- Career, position, research interests, and top-2% recognition: [SCUT faculty profile](https://www2.scut.edu.cn/cs_en/_t239/2025/1016/c45160a605605/page.htm).
- The current publisher-hosted author biography in [this Neurocomputing article](https://www.sciencedirect.com/science/article/pii/S0925231226018837) reports more than 150 papers and more than 40 IEEE/ACM Transactions articles. These counts are attributed to Prof. Zhong, not to the research group.
- Publication metadata: publisher-deposited [Crossref metadata](https://api.crossref.org/works). The audit snapshot is in `publication-metadata.json`. Use issue publication years rather than the year embedded in the DOI. Corresponding-author asterisks were removed because Crossref does not establish that status.
- The corrected mobile-sink paper is [10.1109/JAS.2019.1911846](https://www.ieee-jas.net/en/article/doi/10.1109/JAS.2019.1911846), not 10.1109/JAS.2019.1911816.
- Award: [IEEE CIS AdCom minutes](https://cis.ieee.org/images/files/Documents/adcom-minutes/AdCom_Minutes_July_17_2022_hybrid_corrected.pdf) identify Yongliang Chen, Jinghui Zhong, Liang Feng, and Jun Zhang and the paper *An Adaptive Archive-Based Evolutionary Framework for Many-Task Optimization*. The minutes label the award 2022, while the SCUT faculty profile labels it 2023. The owner subsequently explicitly confirmed **2023** in the supplied awards list; public copy now uses 2023.
- Competition honors: the owner supplied award certificates and explicitly confirmed **four international competition championships**, with **eight tracks in one of the competitions**. At the owner’s request, public copy states four championships and names the IEEE World Congress on Computational Intelligence (WCCI) and the ACM Genetic and Evolutionary Computation Conference (GECCO), identifiable from the supplied certificates. It omits track details and does not infer the names of other competitions or the fine print in the low-resolution images.
- The owner also supplied an IEEE TETCI award certificate and explicitly provided the award list: Outstanding Industry-Academia Collaboration Case, KylinSoft (2024); IEEE TETCI Outstanding Paper Award, IEEE CIS (2023); Natural Science Award (First Class), Ministry of Education (2010). These are attributed to Prof. Jinghui Zhong rather than asserted to have been awarded to the current group. Public pages state honors directly; source attribution is retained here for maintenance rather than attached to each public statement.
- The **85+ members** figure and the claim that the TETCI award was the journal’s single annual award remain omitted pending confirmation.
- Book: the owner explicitly confirmed that *遗传编程算法及其应用* has already been published. Public copy lists Jinghui Zhong, Science Press, Beijing, 2026, consistent with the [companion repository](https://github.com/SCUT-EIPI/GP-and-its-applications), and retains the Chinese title with an English translation.
- [LawMind](https://github.com/SCUT-EIPI/LawMind) and [TriVAL](https://github.com/SCUT-EIPI/TriVAL): the public default branches contained only `.gitignore`, `LICENSE`, and `README.md` at audit time. They are described as documented projects with implementation files not yet released.

## Removed misattributions

The following papers do not list Jinghui Zhong among their authors and were removed from the selected publication list:

- *Improving Generalization of Genetic Programming for Symbolic Regression With Angle-Driven Geometric Semantic Operators*: Qi Chen, Bing Xue, Mengjie Zhang; [author paper](https://staff.fmi.uvt.ro/~daniela.zaharie/ma2019/Projects/ResearchPapers/GeneticProgramming/GeneticProgramming%2BGeometricSemanticOperators_2019.pdf), DOI 10.1109/TEVC.2018.2869621.
- *Genetic Programming Hyper Heuristic With Elitist Mutation for Integrated Order Batching and Picker Routing Problem*: Yuquan Wang, Naiming Xie, Nanlei Chen, Hui Ma, Gang Chen; DOI 10.1109/TEVC.2025.3532022.
- *Discrete-Event Systems Modeling and the Model Predictive Allocation Algorithm for Integrated Berth and Quay Crane Allocation*: Rully Tri Cahyono, Engel Jacob Flonk, Bayu Jayawardhana; DOI 10.1109/TITS.2019.2910283.

## Publishing hygiene

Unused template pages (including fictional CVs and generic privacy-policy text) are excluded through `_config.yml`. The template author and CV datasets were replaced with the group identity. Shared `/md/` and `/markdown.html` redirects were removed from the members, publications, and repositories pages to avoid conflicting destinations.

## Updates, 2026-10-04

- Team size (owner-supplied): one professor, one postdoctoral researcher, 12 PhD students, 20 master's students, and several undergraduates. No member names are published yet.
- Research directions and the seven industry projects on the Research page come from the owner's lab introduction poster (kept locally in `_source/`, not published, because it contains a personal phone number). Partner names were checked against public sources. The partner Amicro changed its name from 一微半导体 to 一微科技 in 2025; no official English name was found after the change, so the site writes "Amicro".
- Address: South China University of Technology, University Town Campus, 382 Waihuan East Road, Guangzhou Higher Education Mega Center, Panyu District, Guangzhou 510006. The owner stated that the School of Computer Science and Engineering is in Building B3. The map marker is the OpenStreetMap building "B3计算机学院" (23.047854, 113.403253).
- "Elsevier" was removed from the top-2% wording, so the site says "Stanford list".
- LawMind and TriVAL are listed only as arXiv preprints on the Papers page. The "Code" links and the Code and Learning Resources entries were removed because their repositories contain no implementation yet.
- Bibliographic details for five Scholar-sourced entries (multifactorial GP, GEP survey, railway timetable DE, crowd modeling survey, crowd video learning) were checked against Crossref on 2026-10-04. Two author names were corrected (Meie Shen, Mingbi Zhao).
- The home page numbers (papers, Transactions articles, citations) and the awards belong to Prof. Zhong, not to the group, and the text says so.
- Unused Academic Pages sample files (`files/`, sample comments, drafts, demo images) were deleted so they no longer appear in the published site or sitemap.
- Affiliation, updated 2026-10-04: the owner confirmed that EIPI is a research team of South China University of Technology, and that the site may give the School of Computer Science and Engineering as the contact address. This replaces the earlier decision to omit the school.
