---
title: "BugMiner: Automating Precise Bug Dataset Construction by Code Evolution History Mining"
collection: publications
category: conferences
permalink: /publication/BugMiner
excerpt: 'Bug dataset, Bug-fixing, Bug-inducing, Automatic bug mining'
date: 2023-9-01
venue: 'Proceedings of the 38th IEEE/ACM International Conference on Automated Software Engineering'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://Kiki2049.github.io/files/BugMiner.pdf'
citation: 'Xuezhi Song, Yijian Wu, Junming Cao, Bihuan Chen, Yun Lin, Zhengjie Lu, Dingji Wang, and Xin Peng. 2023. BugMiner: Automating Precise Bug Dataset Construction by Code Evolution History Mining. In Proceedings of the 38th IEEE/ACM International Conference on Automated Software Engineering. 1919–1929'
---

Bugs and their fixes in the code evolution histories are important assets for many software engineering tasks such as deriving new state-of-the-art automatic bug fixing techniques. Existing bug datasets are either manually built which is difficult to grow efficiently to a scale large enough for massive data analysis, or lack of precise information of how bugs are introduced and fixed which is critical for in-depth analysis such as buggy/fixing code identification. Moreover, the types of the bugs are typically missing in the existing bug datasets, limiting the possibility of developing high-precision type-specific approaches for enterprise-level purposes. In this work, we propose BugMiner, an approach to automatically collecting bugs from code repositories by isolating the critical changes of the bugs. We also propose a learning-based approach for automating bug type classification with relatively small manual labels of bug types. We evaluate our approach regarding the precision of bug information and the efficiency of the bug-mining process with 2,082 bugs automatically mined from 100 open-source projects. We demonstrate the improved effectiveness and efficiency in bug-fixing location identification, compared to the SOTA BugBuilder, and high recall and precision in bug-inducing location identification. We also compare our learning-based bug classification approach to traditional baseline method, indicating about 17 % improvement in classification effectiveness under macro-F1.