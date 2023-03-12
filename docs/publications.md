---
hide:
  - navigation   
---

<!---
note = journal paper
tip = conference paper
example = tool demo paper 
abstract = dataset
-->

## 2023

???+ tip "AidUI: Toward Automated Recognition of Dark Patterns in User Interfaces"

    === "Paper Info"

        * :material-account-supervisor-outline:  Sajed Jalil, Suzzana Rafi, Thomas D. LaToza, Kevin Moran, & Wing Lam
	     * :material-map-marker: *Proceedings of the 2nd Software Testing Education Workshop (TestEd’23), co-located with ICST’23, Dublin, Ireland, April 16th, 2023*
	     *  [:material-file-pdf-box: pdf]() | [:material-database: data](https://doi.org/10.5281/zenodo.7578246) | [:material-github: github](https://github.com/SageSELab/AidUI)

    === "Abstract"

        Past studies have illustrated the prevalence of UI dark patterns, or user interfaces that can lead end-users toward (unknowingly) taking actions that they may not have intended. Such deceptive UI designs can be either intentional (to benefit an online service) or unintentional (through complicit design practices) and can result in adverse effects on end users, such as oversharing personal information or financial loss. While significant research progress has been made toward the development of dark pattern taxonomies across different software domains, developers and users currently lack guidance to help recognize, avoid, and navigate these often subtle design motifs. However, automated recognition of dark patterns is a challenging task, as the instantiation of a single type of pattern can take many forms, leading to significant variability. In this paper, we take the first step toward understanding the extent to which common UI dark patterns can be automatically recognized in modern software applications. To do this, we introduce AIDUI, a novel automated approach that uses computer vision and natural language processing techniques to recognize a set of visual and textual cues in application screenshots that signify the presence of ten unique UI dark patterns, allowing for their detection, classification, and localization. To evaluate our approach, we have constructed CONTEXTDP, the current largest dataset of fully-localized UI dark patterns that spans 175 mobile and 83 web UI screenshots containing 301 dark pattern instances. The results of our evaluation illustrate that AIDUI achieves an overall precision of 0.66, recall of 0.67, F1-score of 0.65 in detecting dark pattern instances, reports few false positives, and is able to localize detected patterns with an IoU score of 0.84. Furthermore, a significant subset of our studied dark patterns can be detected quite reliably (F1 score of over 0.82), and future research directions may allow for improved detection of additional patterns. This work demonstrates the plausibility of developing tools to aid developers in recognizing and appropriately rectifying deceptive UI patterns.

???+ tip "ChatGPT and Software Testing Education: Promises & Perils"

    === "Paper Info"

        * :material-account-supervisor-outline:  Sajed Jalil, Suzzana Rafi, Thomas D. LaToza, Kevin Moran, & Wing Lam
	     * :material-map-marker: *Proceedings of the 2nd Software Testing Education Workshop (TestEd’23), co-located with ICST’23, Dublin, Ireland, April 16th, 2023*
	     *  [:material-file-pdf-box: pdf](https://arxiv.org/abs/2302.03287) | [:material-database: data](https://doi.org/10.5281/zenodo.7700501) | [:material-github: github](https://github.com/sajedjalil/ChatGPT-Software-Testing-Study)

    === "Abstract"

        Over the past decade, predictive language modeling for code has proven to be a valuable tool for enabling new forms of automation for developers. More recently, we have seen the advent of general purpose "large language models", based on neural transformer architectures, that have been trained on massive datasets of human written text spanning code and natural language. However, despite the demonstrated representational power of such models, interacting with them has historically been constrained to specific task settings, limiting their general applicability. Many of these limitations were recently overcome with the introduction of ChatGPT, a language model created by OpenAI and trained to operate as a conversational agent, enabling it to answer questions and respond to a wide variety of commands from end-users. The introduction of models, such as ChatGPT, has already spurred fervent discussion from educators, ranging from fear that students could use these AI tools to circumvent learning, to excitement about the new types of learning opportunities that they might unlock. However, given the nascent nature of these tools, we currently lack fundamental knowledge related to how well they perform in different educational settings, and the potential promise (or danger) that they might pose to traditional forms of instruction. As such, in this paper, we examine how well ChatGPT performs when tasked with solving common questions in a popular software testing curriculum. Our findings indicate that ChatGPT can provide correct or partially correct answers in 44% of cases, provide correct or partially correct explanations of answers in 57% of cases, and that prompting the tool in a shared question context leads to a marginally higher rate of correct answers. Based on these findings, we discuss the potential promise, and dangers related to the use of ChatGPT by students and instructors.

???+ example "BURT: A Chatbot for Interactive Bug Reporting"

    === "Paper Info"

        * :material-account-supervisor-outline:  Yang Song, <u>Junayed Mahmud</u>, Nadasheen De Silva, Ying Zhou, Oscar Chaparro, Kevin Moran, Andrian Marcus, & Denys Poshyvanyk
	     * :material-map-marker: *Proceedings of the 45th IEEE/ACM International Conference on Software Engineering ([ICSE 2023](https://conf.researchr.org/home/icse-2023)), Formal Tool Demonstrations Track, Melbourne, Australia, May 14th-20th, 2023*
	     *  [:material-file-pdf-box: pdf](https://arxiv.org/abs/2302.06050) | [:material-database: data](https://doi.org/10.5281/zenodo.6977413) | [:material-github: github](https://github.com/sea-lab-wm/burt/tree/tool-demo)

    === "Abstract"

        This paper introduces BURT, a web-based chatbot for interactive reporting of Android app bugs. BURT is designed to assist Android app end-users in reporting high-quality defect information using an interactive interface. BURT guides the users in reporting essential bug report elements, i.e., the observed behavior, expected behavior, and the steps to reproduce the bug. It verifies the quality of the text written by the user and provides instant feedback. In addition, BURT provides graphical suggestions that the users can choose as alternatives to textual descriptions. We empirically evaluated BURT, asking end-users to report bugs from six Android apps. The reporters found that BURT's guidance and automated suggestions and clarifications are useful and BURT is easy to use.
        
    === "Video"

        <iframe width="560" height="315" src="https://www.youtube.com/embed/SyfOXpHYGRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


???+ example "AVGUST: A Tool for Generating Usage-Based Tests from Videos of App Executions"

    === "Paper Info"

        * :material-account-supervisor-outline:  Saghar Talebipour, Hyojae Park,  <u>Kesina Baral</u>, Leon Yee, <u>Safwat Ali Khan</u>, Kevin Moran, Yuriy Brun, Nenad Medvidovic, & Yixue Zhao
	     * :material-map-marker: *Proceedings of the 45th IEEE/ACM International Conference on Software Engineering ([ICSE 2023](https://conf.researchr.org/home/icse-2023)), Formal Tool Demonstrations Track, Melbourne, Australia, May 14th-20th, 2023*
	     *  [:material-file-pdf-box: pdf](https://arxiv.org/abs/2209.02577) | [:material-database: data](https://zenodo.org/record/7036218#.Y7RWzy-B3Ek) | [:material-github: github](https://github.com/felicitia/UsageTesting-Repo/tree/demo)

    === "Abstract"

        Many software bugs are reported manually, particularly bugs that manifest themselves visually in the user interface. End-users typically report these bugs via app reviewing websites, issue trackers, or in-app built-in bug reporting tools, if available. While these systems have various features that facilitate bug reporting (e.g., textual templates or forms), they often provide limited guidance, concrete feedback, or quality verification to end-users, who are often inexperienced at reporting bugs and submit low-quality bug reports that lead to excessive developer effort in bug report management tasks. We propose an interactive bug reporting system for end-users (Burt), implemented as a task-oriented chatbot. Unlike existing bug reporting systems, Burt provides guided reporting of essential bug report elements (i.e., the observed behavior, expected behavior, and steps to reproduce the bug), instant quality verification, and graphical suggestions for these elements. We implemented a version of Burt for Android and conducted an empirical evaluation study with end-users, who reported 12 bugs from six Android apps studied in prior work. The reporters found that Burt's guidance and automated suggestions/clarifications are useful and Burt is easy to use. We found that Burt reports contain higher-quality information than reports collected via a template-based bug reporting system. Improvements to Burt, informed by the reporters, include support for various wordings to describe bug report elements and improved quality verification. Our work marks an important paradigm shift from static to interactive bug reporting for end-users.
        
    === "Video"

        <iframe width="560" height="315" src="https://www.youtube.com/embed/LPICxVd0YAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## 2022

???+ tip "AVGUST: Automating Usage-based Test Generation from Videos of App Executions"

    === "Paper Info"

        * :material-account-supervisor-outline:  Yixue Zhao, Saghar Talebipour, Kesina Baral, Hyojae Park, Leon Yee, <u>Safwat Ali Khan</u>, Yuriy Brun, Nenad Medvidovic, & Kevin Moran
	     * :material-map-marker: *Proceedings of the 2022 ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering ([ESEC/FSE 2022](https://2022.esec-fse.org/)), Singapore, November 14th-18th, 2022 (22% Acceptance Rate)*
	     *  [:material-file-pdf-box: pdf](https://arxiv.org/abs/2209.02577) | [:material-database: data](https://zenodo.org/record/7036218#.Y7RWzy-B3Ek) | [:material-github: github](https://github.com/felicitia/UsageTesting-Repo/tree/demo)

    === "Abstract"

        Many software bugs are reported manually, particularly bugs that manifest themselves visually in the user interface. End-users typically report these bugs via app reviewing websites, issue trackers, or in-app built-in bug reporting tools, if available. While these systems have various features that facilitate bug reporting (e.g., textual templates or forms), they often provide limited guidance, concrete feedback, or quality verification to end-users, who are often inexperienced at reporting bugs and submit low-quality bug reports that lead to excessive developer effort in bug report management tasks. We propose an interactive bug reporting system for end-users (Burt), implemented as a task-oriented chatbot. Unlike existing bug reporting systems, Burt provides guided reporting of essential bug report elements (i.e., the observed behavior, expected behavior, and steps to reproduce the bug), instant quality verification, and graphical suggestions for these elements. We implemented a version of Burt for Android and conducted an empirical evaluation study with end-users, who reported 12 bugs from six Android apps studied in prior work. The reporters found that Burt's guidance and automated suggestions/clarifications are useful and Burt is easy to use. We found that Burt reports contain higher-quality information than reports collected via a template-based bug reporting system. Improvements to Burt, informed by the reporters, include support for various wordings to describe bug report elements and improved quality verification. Our work marks an important paradigm shift from static to interactive bug reporting for end-users.
        
    === "Video"

        <iframe width="560" height="315" src="https://www.youtube.com/embed/LPICxVd0YAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


???+ tip "Toward Interactive Bug Reporting for (Android App) End Users"

    === "Paper Info"

        * :material-account-supervisor-outline:  Yang Song, <u>Junayed Mahmud</u>, Ying Zhou, Oscar Chaparro, Kevin Moran, Andrian Marcus, and Denys Poshyvanyk
	     * :material-map-marker: *Proceedings of the 2022 ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering ([ESEC/FSE 2022](https://2022.esec-fse.org/)), Singapore, November 14th-18th, 2022 (22% Acceptance Rate)*
	     *  [:material-file-pdf-box: pdf](https://arxiv.org/abs/2209.10062) | [:material-database: data](https://doi.org/10.5281/zenodo.6977413) | [:material-github: github](https://github.com/sea-lab-wm/burt/tree/tool-demo)

    === "Abstract"

        Many software bugs are reported manually, particularly bugs that manifest themselves visually in the user interface. End-users typically report these bugs via app reviewing websites, issue trackers, or in-app built-in bug reporting tools, if available. While these systems have various features that facilitate bug reporting (e.g., textual templates or forms), they often provide limited guidance, concrete feedback, or quality verification to end-users, who are often inexperienced at reporting bugs and submit low-quality bug reports that lead to excessive developer effort in bug report management tasks. We propose an interactive bug reporting system for end-users (Burt), implemented as a task-oriented chatbot. Unlike existing bug reporting systems, Burt provides guided reporting of essential bug report elements (i.e., the observed behavior, expected behavior, and steps to reproduce the bug), instant quality verification, and graphical suggestions for these elements. We implemented a version of Burt for Android and conducted an empirical evaluation study with end-users, who reported 12 bugs from six Android apps studied in prior work. The reporters found that Burt's guidance and automated suggestions/clarifications are useful and Burt is easy to use. We found that Burt reports contain higher-quality information than reports collected via a template-based bug reporting system. Improvements to Burt, informed by the reporters, include support for various wordings to describe bug report elements and improved quality verification. Our work marks an important paradigm shift from static to interactive bug reporting for end-users.
        
    === "Video"

        <iframe width="560" height="315" src="https://www.youtube.com/embed/SyfOXpHYGRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

???+ note "Enhancing Mobile App Bug Reporting via Real-time Understanding of Reproduction Steps"

    === "Paper Info"

        * :material-account-supervisor-outline:  Mattia Fazzini, Kevin Moran, Carlos Bernal Cárdenas, Tyler Wendland, Alessandro Orso, and Denys Poshyvanyk 
	     * :material-map-marker: *IEEE Transactions on Software Engineering ([TSE](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=32))*
	     *  [:material-file-pdf-box: pdf](https://arxiv.org/abs/2203.12093) | [:material-database: data](https://www-users.cse.umn.edu/~mfazzini/ebug.html)

    === "Abstract"

        Screen recordings of mobile applications are easy to obtain and capture a wealth of information pertinent to software developers (e.g., bugs or feature requests), making them a popular mechanism for crowdsourced app feedback. Thus, these videos are becoming a common artifact that developers must manage. In light of unique mobile development constraints, including swift release cycles and rapidly evolving platforms, automated techniques for analyzing all types of rich software artifacts provide benefit to mobile developers. Unfortunately, automatically analyzing screen recordings presents serious challenges, due to their graphical nature, compared to other types of (textual) artifacts. To address these challenges, this paper introduces V2S+, an automated approach for translating video recordings of Android app usages into replayable scenarios. V2S+ is based primarily on computer vision techniques and adapts recent solutions for object detection and image classification to detect and classify user gestures captured in a video, and convert these into a replayable test scenario. Given that V2S+ takes a computer vision-based approach, it is applicable to both hybrid and native Android applications. We performed an extensive evaluation of V2S+ involving 243 videos depicting 4,028 GUI-based actions collected from users exercising features and reproducing bugs from a collection of over 90 popular native and hybrid Android apps. Our results illustrate that V2S+ can accurately replay scenarios from screen recordings, and is capable of reproducing ≈ 90.2% of sequential actions recorded in native application scenarios on physical devices, and ≈ 83% of sequential actions recorded in hybrid application scenarios on emulators, both with low overhead. A case study with three industrial partners illustrates the potential usefulness of V2S+ from the viewpoint of developers.

???+ note "Translating Video Recordings of Complex Mobile App UI Gestures into Replayable Scenarios for Native & Hybrid Apps"

    === "Paper Info"

        * :material-account-supervisor-outline:  Carlos Bernal Cárdenas, Nathan Cooper, Madeleine Havranek, Kevin Moran, Oscar Chaparro, Denys Poshyvanyk, and Andrian Marcus
	     * :material-map-marker: *IEEE Transactions on Software Engineering ([TSE](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=32))*
	     *  [:material-file-pdf-box: pdf](https://arxiv.org/abs/2301.01191) | [:material-database: data](https://sites.google.com/email.wm.edu/video2scenario/home)

    === "Abstract"

        Screen recordings of mobile applications are easy to obtain and capture a wealth of information pertinent to software developers (e.g., bugs or feature requests), making them a popular mechanism for crowdsourced app feedback. Thus, these videos are becoming a common artifact that developers must manage. In light of unique mobile development constraints, including swift release cycles and rapidly evolving platforms, automated techniques for analyzing all types of rich software artifacts provide benefit to mobile developers. Unfortunately, automatically analyzing screen recordings presents serious challenges, due to their graphical nature, compared to other types of (textual) artifacts. To address these challenges, this paper introduces V2S+, an automated approach for translating video recordings of Android app usages into replayable scenarios. V2S+ is based primarily on computer vision techniques and adapts recent solutions for object detection and image classification to detect and classify user gestures captured in a video, and convert these into a replayable test scenario. Given that V2S+ takes a computer vision-based approach, it is applicable to both hybrid and native Android applications. We performed an extensive evaluation of V2S+ involving 243 videos depicting 4,028 GUI-based actions collected from users exercising features and reproducing bugs from a collection of over 90 popular native and hybrid Android apps. Our results illustrate that V2S+ can accurately replay scenarios from screen recordings, and is capable of reproducing ≈ 90.2% of sequential actions recorded in native application scenarios on physical devices, and ≈ 83% of sequential actions recorded in hybrid application scenarios on emulators, both with low overhead. A case study with three industrial partners illustrates the potential usefulness of V2S+ from the viewpoint of developers.


???+ tip "Learning Patterns from User Interfaces to Support Software Engineering Tasks"

    === "Paper Info"

        * :material-account-supervisor-outline:  Kevin Moran
	     * :material-map-marker: *Proceedings of CHI 2022 Workshop on Computational Approaches for Understanding, Generating, and Adapting User Interfaces ([Computational UI@CHI’22](https://sites.google.com/nd.edu/computational-uichi22))*
	     *  [:material-file-pdf-box: pdf]() | [:material-database: data](http://sagelab.io/Clarity/)

    === "Abstract"

        In the field of software engineering (SE) research, there has long been a focus on automating various development tasks in an attempt to facilitate or augment the abilities of developers. Research aligned with this objective typically aims to learn models from information mined from software repositories and then apply these models to automate a given SE task. The large majority of this work has focused on artifacts consisting of two main modalities of information -- *code* and *natural language*. However, one information source which has been comparatively underutilized is the *visual* modality of software expressed via User Interfaces (UIs). UIs serve as an important medium of interaction between the logic of an application and users, and as such, they encode salient information about underlying program functionality into rich, pixel-based data representations. Given the latent information contained within UIs, and the rapid advancement of Deep Learning (DL) techniques for computer vision and natural language processing in recent years, there is a tremendous opportunity to leverage UI-related software artifacts to offer novel forms of software development automation. This position paper reflects on past work conducted at the intersection of software engineering and automated reasoning of user interfaces, discusses promising future directions, and potential challenges in enabling new forms of UI-centric automation for developers.

???+ tip "An Empirical Investigation into the Use of Image Captioning for Automated Software Documentation"

    === "Paper Info"

        * :material-account-supervisor-outline:  Kevin Moran, Ali Yachnes, George Purnell, <u>Junayed Mahmud</u>, Michele Tufano, Carlos Bernal-Cárdenas, Denys Poshyvanyk, and Zach H-Doubler
	     * :material-map-marker: ***Oral Presentation*** *at the 29th IEEE International Conference on Software Analysis, Evolution and Reengineering ([SANER’22](https://saner2022.uom.gr)), Honolulu, Hawaii, March 15-18, 2022 (24% Acceptance Rate)*
	     *  [:material-file-pdf-box: pdf](https://arxiv.org/abs/2301.01224) | [:material-database: data](http://sagelab.io/Clarity/)

    === "Abstract"

        Existing automated techniques for software documentation typically attempt to reason between two main sources of information: code and natural language. However, this reason- ing process is often complicated by the lexical gap between more abstract natural language and more structured programming languages. One potential bridge for this gap is the Graphical User Interface (GUI), as GUIs inherently encode salient information about underlying program functionality into rich, pixel-based data representations. This paper offers one of the first comprehensive empirical investigations into the connection between GUIs and functional, natural language descriptions of software. First, we collect, analyze, and open source a large dataset of functional GUI descriptions consisting of 45,998 descriptions for 10,204 screenshots from popular Android applications. The descriptions were obtained from human labelers and underwent several quality control mechanisms. To gain insight into the representational potential of GUIs, we investigate the ability of four Neural Image Captioning models to predict natural language descriptions of varying granularity when provided a screenshot as input. We evaluate these models quantitatively, using common machine translation metrics, and qualitatively through a large- scale user study. Finally, we offer learned lessons and a discussion of the potential shown by multimodal models to enhance future techniques for automated software documentation.


???+ tip "An Empirical Investigation into the Reproduction of Bug Reports for Android Apps"

    === "Paper Info"

        * :material-account-supervisor-outline: Jack Johnson, <u>Junayed Mahmud</u>, Tyler Wendland, Kevin Moran, Julia Rubin and Mattia Fazzini
	     * :material-map-marker: ***Oral Presentation*** *at the 29th IEEE International Conference on Software Analysis, Evolution and Reengineering ([SANER’22](https://saner2022.uom.gr)), Honolulu, Hawaii, March 15-18, 2022 (24% Acceptance Rate)*
	     *  [:material-file-pdf-box: pdf](https://arxiv.org/abs/2301.01235) | [:material-database: data](https://github.com/se-umn/2022_saner_bug_report_reproduction_study)

    === "Abstract"

        One of the key tasks related to ensuring mobile app quality is the reporting, management, and resolution of bug reports. As such, researchers have committed considerable resources toward automating various tasks of the bug management process for mobile apps, such as reproduction and triaging. However, the success of these automated approaches is largely dictated by the characteristics and properties of the bug reports they operate upon. As such, understanding mobile app bug reports is imperative to drive the continued advancement of report management techniques. While prior studies have examined high-level statistics of large sets of reports, we currently lack an in-depth investigation of how the information typically reported in mobile app issue trackers relates to the specific details generally required to reproduce the underlying bugs. In this paper, we perform an in-depth analysis of 180 reproducible bug reports systematically mined from Android apps on GitHub and investigate how the information contained in the reports relates to the task of reproducing the described bugs. In our analysis, we focus on three pieces of information: the environment needed to reproduce the bug report, the steps to reproduce (S2Rs), and the observed behavior. Focusing on this information, we characterize failure types, identify the modality used to report the information, and characterize the information quality within the reports. We find that bugs are reported in a multi-modal fashion, the environment is not always provided, and S2Rs often contain missing or non-specific information. These findings carry with them important implications on automated bug reproduction techniques as well as automated bug report management approaches more generally.


???+ note "A Systematic Literature Review on the Use of Deep Learning in Software Engineering Research"

    === "Paper Info"

        * :material-account-supervisor-outline: Cody Watson, Nathan Cooper, David N. Palacio, Kevin Moran, and Denys Poshyvanyk
	     * :material-map-marker: *ACM Transactions on Software Engineering & Methodology [(TOSEM)](https://dl.acm.org/journal/tosem), accepted*
	     * [:material-file-pdf-box: pdf](https://arxiv.org/abs/2009.06520) | [:material-database: tool](https://wm-semeru.github.io/dl4se/)

    === "Abstract"

        An increasingly popular set of techniques adopted by software engineering (SE) researchers to automate development tasks are those rooted in the concept of Deep Learning (DL). The popularity of such techniques largely stems from their automated feature engineering capabilities, which aid in modeling software artifacts. However, due to the rapid pace at which DL techniques have been adopted, it is difficult to distill the current successes, failures, and opportunities of the current research landscape. In an effort to bring clarity to this cross- cutting area of work, from its modern inception to the present, this paper presents a systematic literature review of research at the intersection of SE & DL. The review canvases work appearing in the most prominent SE and DL conferences and journals and spans 128 papers across 23 unique SE tasks. We center our analysis around the components of learning, a set of principles that govern the application of machine learning techniques (ML) to a given problem domain, discussing several aspects of the surveyed work at a granular level. The end result of our analysis is a research roadmap that both delineates the foundations of DL techniques applied to SE research, and highlights likely areas of fertile exploration for the future.
        


???+ tip "Why Crypto-detectors Fail: A Systematic Evaluation of Cryptographic Misuse Detection Techniques"

    === "Paper Info"

        * :material-account-supervisor-outline: Amit Seal Ami, Nathan Cooper, Kaushal Kafle, Kevin Moran, Denys Poshyvanyk, and Adwait Nadkarni
	     * :material-map-marker: *Proceedings of the IEEE Symposium on Security and Privacy [(Oakland)](https://www.ieee-security.org/TC/SP2022/), May  22nd-26th, 2022, to appear, 18 pages*
	     *  [:material-file-pdf-box: pdf](https://arxiv.org/abs/2107.07065) | [:material-database: data](https://github.com/Secure-Platforms-Lab-W-M/MASC-Artifact)

    === "Abstract"

        The correct use of cryptography is central to ensuring data security in modern software systems. Hence, several academic and commercial static analysis tools have been developed for detecting and mitigating crypto-API misuse. While developers are optimistically adopting these crypto-API misuse detectors (or crypto-detectors) in their software development cycles, this momentum must be accompanied by a rigorous understanding of their effectiveness at finding crypto-API misuse in practice. This paper presents the MASC framework, which enables a systematic and data-driven evaluation of crypto-detectors using mutation testing. We ground MASC in a comprehensive view of the problem space by developing a data-driven taxonomy of existing crypto-API misuse, containing 105 misuse cases organized among nine semantic clusters. We develop 12 generalizable usage-based mutation operators and three mutation scopes that can expressively instantiate thousands of compilable variants of the misuse cases for thoroughly evaluating crypto-detectors. Using MASC, we evaluate nine major crypto-detectors and discover 19 unique, undocumented flaws that severely impact the ability of crypto-detectors to discover misuses in practice. We conclude with a discussion on the diverse perspectives that influence the design of crypto-detectors and future directions towards building security-focused crypto-detectors by design.

-------------------
## 2021

???+ tip "Code to Comment Translation: A Comparative Study on Model Effectiveness & Errors"

    === "Paper Info"

        * :material-account-supervisor-outline: <u>Junayed Mahmud</u>, Fahim Faisal, Raihan Islam Arnob, Antonios Anastasopoulos, and Kevin Moran
	     * :material-map-marker: *Proceedings of the First Workshop on Natural Language Processing for Programming [(NLP4Prog’21)](https://nlp4prog.github.io/2021/) Co-Located with [ACL-IJCNLP’21](https://2021.aclweb.org/), Virtual (originally Bangkok, Thailand), August  6th, 2021, to appear, 9 pages*
	     *  [:material-file-pdf-box: pdf](https://arxiv.org/abs/2106.08415) | [:material-database: data](https://github.com/SageSELab/CodeSumStudy)

    === "Abstract"

        Automated source code summarization is a popular software engineering research topic wherein machine translation models are em- ployed to “translate” code snippets into relevant natural language descriptions. Most evaluations of such models are conducted us- ing automatic reference-based metrics. How- ever, given the relatively large semantic gap between programming languages and natural language, we argue that this line of research would benefit from a qualitative investigation into the various error modes of current state- of-the-art models. Therefore, in this work, we perform both a quantitative and qualitative comparison of three recently proposed source code summarization models. In our quantitative evaluation, we compare the models based on the smoothed BLEU-4, METEOR, and ROUGE-L machine translation metrics, and in our qualitative evaluation, we perform a manual open-coding of the most common errors committed by the models when com- pared to ground truth captions. Our investigation reveals new insights into the relationship between metric-based performance and model prediction errors grounded in an empirically derived error taxonomy that can be used to drive future research efforts.

    === "Video"

        <iframe width="560" height="315" src="https://www.youtube.com/embed/62fTyk2xokc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


???+ abstract "AndroR2: A Dataset of Manually-Reproduced Bug Reports for Android Apps"

    === "Paper Info"

        * :material-account-supervisor-outline: Tyler Wendland, Jingyang Sun, <u>Junayed Mahmud</u>, <u>S.M. Hasan Mansur</u>, Steven Huang, Kevin Moran, Julia Rubin, Mattia Fazzini
	     * :material-map-marker: *Proceedings of the 2021 International Conference on Mining Software Repositories [(MSR’21)](https://2021.msrconf.org), Data Showcase Track, Virtual (originally Madrid, Spain), May 17th - 19th, 2021, to appear, 5 pages*
	     * [:material-file-pdf-box: pdf](https://arxiv.org/abs/2106.08403) | [:material-database: data](https://github.com/SageSELab/AndroR2)

    === "Abstract"

        Software maintenance constitutes a large portion of the software development lifecycle. To carry out maintenance tasks, developers often need to understand and reproduce bug reports. As such, there has been increasing research activity coalescing around the notion of automating various activities related to bug reporting. A sizable portion of this research interest has focused on the domain of mobile apps. However, as research around mobile app bug reporting progresses, there is a clear need for a large, manually vetted, and reproducible set of real-world bug reports that can serve as a benchmark for future work. This paper presents AndroR2: a dataset of 90 manually reproduced bug reports for Android apps listed on Google Play and hosted on GitHub, systematically collected via an in-depth analysis of 459 reports extracted from the GitHub issue tracker. For each reproduced report, AndroR2 includes an apk file for the buggy version of the app, detailed reproduction steps, an executable reproduction script, and annotations on the quality of the reproduction steps associated with the original report. We believe that the AndroR2 dataset can be used to facilitate research in automatically analyzing, understanding, reproducing, localizing, and fixing bugs for mobile applications as well as other software maintenance activities more broadly in the future.


???+ tip "It Takes Two to Tango: Combining Visual and Textual Information for Detecting Duplicate Video-Based Bug Reports"

    === "Paper Info"

        * :material-account-supervisor-outline: Nathan Cooper, Carlos Bernal-Cárdenas, Oscar Chaparro, Kevin Moran, and Denys Poshyvanyk
	     * :material-map-marker: *Proceedings of the 43rd International Conference on Software Engineering [(ICSE’21)](https://conf.researchr.org/home/icse-2021), Virtual (originally Madrid, Spain), May 25th - 28th, 2021, to appear, 13 pages*
	     *  [:material-file-pdf-box: pdf](https://arxiv.org/abs/2101.09194) | [:material-database: data](https://two-to-tango.github.io/tango/) | [:material-tools: tool](https://two-to-tango.github.io/tango/)

    === "Abstract"

        When a bug manifests in a user-facing application, it is likely to be exposed through the graphical user interface (GUI). Given the importance of visual information to the process of identifying and understanding such bugs, users are increasingly making use of screenshots and screen-recordings as a means to report issues to developers. However, when such information is reported en masse, such as during crowd-sourced testing, managing these artifacts can be a time-consuming process. As the reporting of screen-recordings in particular becomes more popular, developers are likely to face challenges related to manually identifying videos that depict duplicate bugs. Due to their graphical nature, screen-recordings present challenges for automated analysis that preclude the use of current duplicate bug report detection techniques. To overcome these challenges and aid developers in this task, this paper presents Tango, a duplicate detection technique that operates purely on video-based bug reports by leveraging both visual and textual information. Tango combines tailored computer vision techniques, optical character recognition, and text retrieval. We evaluated multiple configurations of Tango in a comprehensive empirical evaluation on 4,860 duplicate detection tasks that involved a total of 180 screen-recordings from six Android apps. Additionally, we conducted a user study investigating the effort required for developers to manually detect duplicate video-based bug reports and compared this to the effort required to use Tango. The results reveal that Tango's optimal configuration is highly effective at detecting duplicate video-based bug reports, accurately ranking target duplicate videos in the top-2 returned results in 83% of the tasks. Additionally, our user study shows that, on average, Tango can reduce developer effort by over 60%, illustrating its practicality.

    === "Video"

        <iframe width="560" height="315" src="https://www.youtube.com/embed/Mjf6P_D9Q1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


???+ example "V2S: A Tool for Translating Video Recordings of Mobile App Usages into Replayable Scenarios"

    === "Paper Info"

        * :material-account-supervisor-outline: Madeleine Havranek, Carlos Bernal-Cárdenas, Nathan Cooper, Oscar Chaparro, Denys Poshyvanyk, and Kevin Moran
	     * :material-map-marker: *Proceedings of the 43rd International Conference on Software Engineering [(ICSE’21)](https://conf.researchr.org/home/icse-2021) - Formal Tool Demonstrations Track, Virtual (originally Madrid, Spain), May 25th - 28th, 2021, to appear, 4 pages (37% Acceptance Rate)*
	     * [:material-file-pdf-box: pdf](https://arxiv.org/abs/2103.04531) | [:material-tools: tool](https://gitlab.com/SEMERU-Code-Public/Android/video2scenario/-/tree/master/python_v2s)

    === "Abstract"

        Screen recordings are becoming increasingly important as rich software artifacts that inform mobile application development processes. However, the amount of manual effort required to extract information from these graphical artifacts can hinder resource-constrained mobile developers. This paper presents Video2Scenario (V2S), an automated tool that processes video recordings of Android app usages, utilizes neural object detection and image classification techniques to classify the depicted user actions, and translates these actions into a replayable scenario. We conducted a comprehensive evaluation to demonstrate V2S's ability to reproduce recorded scenarios across a range of devices and a diverse set of usage cases and applications. The results indicate that, based on its performance with 175 videos depicting 3,534 GUI-based actions, V2S is accurate in reproducing ≈89% of actions from collected videos.
        
        
???+ example "Mutation-based Evaluation of Security-focused Static Analysis Tools for Android"

    === "Paper Info"

        * :material-account-supervisor-outline: Amit Seal Ami, Kaushal Kafle, Kevin Moran, Adwait Nadkarni, and Denys Poshyvanyk
	     * :material-map-marker: *Proceedings of the 43rd International Conference on Software Engineering [(ICSE’21)](https://conf.researchr.org/home/icse-2021) - Formal Tool Demonstrations Track, Virtual (originally Madrid, Spain), May 25th - 28th, 2021, to appear, 4 pages (37% Acceptance Rate)*
	     * [:material-file-pdf-box: pdf](https://arxiv.org/abs/2102.06823) | [:material-tools: tool](https://secure-platforms-lab-w-m.github.io/muse/)

    === "Abstract"

        This demo paper presents the technical details and usage scenarios of μSE: a mutation-based tool for evaluating security-focused static analysis tools for Android. Mutation testing is generally used by software practitioners to assess the robustness of a given test-suite. However, we leverage this technique to systematically evaluate static analysis tools and uncover and document soundness issues. μSE's analysis has found 25 previously undocumented flaws in static data leak detection tools for Android. μSE offers four mutation schemes, namely Reachability, Complex-reachability, TaintSink, and ScopeSink, which determine the locations of seeded mutants. Furthermore, the user can extend μSE by customizing the API calls targeted by the mutation analysis. μSE is also practical, as it makes use of filtering techniques based on compilation and execution criteria that reduces the number of ineffective mutations.
 

???+ note "Systematic Mutation-based Evaluation of the Soundness of Security-focused Android Static Analysis Techniques"

    === "Paper Info"

        * :material-account-supervisor-outline: Amit Seal Ami, Kaushal Kafle, Kevin Moran, Adwait Nadkarni, and Denys Poshyvanyk
	     * :material-map-marker: *ACM Transactions on Security & Privacy [(TOPS)](https://dl.acm.org/journal/tops), accepted*
	     * [:material-file-pdf-box: pdf](https://arxiv.org/abs/2102.06829) | [:material-tools: tool](https://secure-platforms-lab-w-m.github.io/muse/)

    === "Abstract"

        Mobile application security has been a major area of focus for security research over the course of the last decade. Numerous application analysis tools have been proposed in response to malicious, curious, or vulnerable apps. However, existing tools, and specifically, static analysis tools, trade soundness of the analysis for precision and performance and are hence soundy. Unfortunately, the specific unsound choices or flaws in the design of these tools is often not known or well-documented, leading to misplaced confidence among researchers, developers, and users. This paper describes the Mutation-based Soundness Evaluation (μSE) framework, which systematically evaluates Android static analysis tools to discover, document, and fix flaws, by leveraging the well-founded practice of mutation analysis. We implemented μSE and applied it to a set of prominent Android static analysis tools that detect private data leaks in apps. In a study conducted previously, we used μSE to discover 13 previously undocumented flaws in FlowDroid, one of the most prominent data leak detectors for Android apps. Moreover, we discovered that flaws also propagated to other tools that build upon the design or implementation of FlowDroid or its components. This paper substantially extends our μSE framework and offers an new in-depth analysis of two more major tools in our 2020 study, we find 12 new, undocumented flaws and demonstrate that all 25 flaws are found in more than one tool, regardless of any inheritance-relation among the tools. Our results motivate the need for systematic discovery and documentation of unsound choices in soundy tools and demonstrate the opportunities in leveraging mutation testing in achieving this goal.
        
        
???+ note "Security in Centralized Data Store-based Home Automation Platforms: A Systematic Analysis of Nest and Hue"

    === "Paper Info"

        * :material-account-supervisor-outline: Kaushal Kafle, Kevin Moran, Sunil Manandhar, Adwait Nadkarni, and Denys Poshyvanyk
	     * :material-map-marker: *ACM Transactions on Cyber Physical Systems [(TCPS)](https://dl.acm.org/journal/tcps), accepted*
	     * [:material-file-pdf-box: pdf](https://arxiv.org/abs/2102.06829)

    === "Abstract"

        Home automation platforms enable consumers to conveniently automate various physical aspects of their homes. However, the security flaws in the platforms or integrated third-party products can have serious security and safety implications for the user’s physical environment. This article describes our systematic security evaluation of two popular smart home platforms, Google’s Nest platform and Philips Hue, which implement home automation “routines” (i.e., trigger-action programs involving apps and devices) via manipulation of state variables in a centralized data store. Our semi-automated analysis examines, among other things, platform access control enforcement, the rigor of non-system enforcement procedures, and the potential for misuse of routines, and it leads to 11 key findings with serious security implications. We combine several of the vulnerabilities we find to demonstrate the first end-to-end instance of lateral privilege escalation in the smart home, wherein we remotely disable the Nest Security Camera via a compromised light switch app. Finally, we discuss potential defenses, and the impact of the continuous evolution of smart home platforms on the practicality of security analysis. Our findings draw attention to the unique security challenges of smart home platforms and highlight the importance of enforcing security by design.