---
hide:
  - navigation   
---

## 2021

!!! tip "Code to Comment Translation: A Comparative Study on Model Effectiveness & Errors"

    === "Paper Info"

        * :material-account-supervisor-outline: <u>Junayed Mahmud</u>, Fahim Faisal, Raihan Islam Arnob, Antonios Anastasopoulos, and Kevin Moran
	     * :material-map-marker: *Proceedings of the First Workshop on Natural Language Processing for Programming [(NLP4Prog’21)](https://nlp4prog.github.io/2021/) Co-Located with [ACL-IJCNLP’21](https://2021.aclweb.org/), Virtual (originally Bangkok, Thailand), August  6th, 2021, to appear, 9 pages*
	     *  [:material-pdf-box: pdf](https://arxiv.org/abs/2106.08415) | [:material-database: data](https://github.com/SageSELab/CodeSumStudy)
    === "Abstract"

        Automated source code summarization is a popular software engineering research topic wherein machine translation models are em- ployed to “translate” code snippets into relevant natural language descriptions. Most evaluations of such models are conducted us- ing automatic reference-based metrics. How- ever, given the relatively large semantic gap between programming languages and natural language, we argue that this line of research would benefit from a qualitative investigation into the various error modes of current state- of-the-art models. Therefore, in this work, we perform both a quantitative and qualitative comparison of three recently proposed source code summarization models. In our quantitative evaluation, we compare the models based on the smoothed BLEU-4, METEOR, and ROUGE-L machine translation metrics, and in our qualitative evaluation, we perform a manual open-coding of the most common errors committed by the models when com- pared to ground truth captions. Our investigation reveals new insights into the relationship between metric-based performance and model prediction errors grounded in an empirically derived error taxonomy that can be used to drive future research efforts.
        
    === "Video"
<div onclick="this.nextElementSibling.style.display='block'; this.style.display='none'">
   <img src="../images/android-tutorial/video-thumbnail.png" style="cursor:pointer" />
</div>
<div style="display:none">
    <style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://www.youtube.com/embed/sjIcw1LYwT8' frameborder='0' allowfullscreen></iframe></div>
</div>


!!! abstract "AndroR2: A Dataset of Manually-Reproduced Bug Reports for Android Apps"

    === "Paper Info"

        * :material-account-supervisor-outline: Tyler Wendland, Jingyang Sun, <u>Junayed Mahmud</u>, <u>S.M. Hasan Mansur</u>, Steven Huang, Kevin Moran, Julia Rubin, Mattia Fazzini
	     * :material-map-marker: *Proceedings of the 2021 International Conference on Mining Software Repositories [(MSR’21)](https://2021.msrconf.org), Data Showcase Track, Virtual (originally Madrid, Spain), May 17th - 19th, 2021, to appear, 5 pages*
	     * [:material-pdf-box: pdf](https://arxiv.org/abs/2106.08403) | [:material-database: data](https://github.com/SageSELab/AndroR2)

    === "Abstract"

        Software maintenance constitutes a large portion of the software development lifecycle. To carry out maintenance tasks, developers often need to understand and reproduce bug reports. As such, there has been increasing research activity coalescing around the notion of automating various activities related to bug reporting. A sizable portion of this research interest has focused on the domain of mobile apps. However, as research around mobile app bug reporting progresses, there is a clear need for a large, manually vetted, and reproducible set of real-world bug reports that can serve as a benchmark for future work. This paper presents AndroR2: a dataset of 90 manually reproduced bug reports for Android apps listed on Google Play and hosted on GitHub, systematically collected via an in-depth analysis of 459 reports extracted from the GitHub issue tracker. For each reproduced report, AndroR2 includes an apk file for the buggy version of the app, detailed reproduction steps, an executable reproduction script, and annotations on the quality of the reproduction steps associated with the original report. We believe that the AndroR2 dataset can be used to facilitate research in automatically analyzing, understanding, reproducing, localizing, and fixing bugs for mobile applications as well as other software maintenance activities more broadly in the future.


!!! tip "It Takes Two to Tango: Combining Visual and Textual Information for Detecting Duplicate Video-Based Bug Reports"

    === "Paper Info"

        * :material-account-supervisor-outline: Nathan Cooper, Carlos Bernal-Cárdenas, Oscar Chaparro, Kevin Moran, and Denys Poshyvanyk
	     * :material-map-marker: *Proceedings of the 43rd International Conference on Software Engineering [(ICSE’21)](https://conf.researchr.org/home/icse-2021), Virtual (originally Madrid, Spain), May 25th - 28th, 2021, to appear, 13 pages*
	     *  [:material-pdf-box: pdf](https://arxiv.org/abs/2101.09194) | [:material-database: data](https://two-to-tango.github.io/tango/) | [:material-tools: tool](https://two-to-tango.github.io/tango/)

    === "Abstract"

        When a bug manifests in a user-facing application, it is likely to be exposed through the graphical user interface (GUI). Given the importance of visual information to the process of identifying and understanding such bugs, users are increasingly making use of screenshots and screen-recordings as a means to report issues to developers. However, when such information is reported en masse, such as during crowd-sourced testing, managing these artifacts can be a time-consuming process. As the reporting of screen-recordings in particular becomes more popular, developers are likely to face challenges related to manually identifying videos that depict duplicate bugs. Due to their graphical nature, screen-recordings present challenges for automated analysis that preclude the use of current duplicate bug report detection techniques. To overcome these challenges and aid developers in this task, this paper presents Tango, a duplicate detection technique that operates purely on video-based bug reports by leveraging both visual and textual information. Tango combines tailored computer vision techniques, optical character recognition, and text retrieval. We evaluated multiple configurations of Tango in a comprehensive empirical evaluation on 4,860 duplicate detection tasks that involved a total of 180 screen-recordings from six Android apps. Additionally, we conducted a user study investigating the effort required for developers to manually detect duplicate video-based bug reports and compared this to the effort required to use Tango. The results reveal that Tango's optimal configuration is highly effective at detecting duplicate video-based bug reports, accurately ranking target duplicate videos in the top-2 returned results in 83% of the tasks. Additionally, our user study shows that, on average, Tango can reduce developer effort by over 60%, illustrating its practicality.
        

!!! example "V2S: A Tool for Translating Video Recordings of Mobile App Usages into Replayable Scenarios"

    === "Paper Info"

        * :material-account-supervisor-outline: Madeleine Havranek, Carlos Bernal-Cárdenas, Nathan Cooper, Oscar Chaparro, Denys Poshyvanyk, and Kevin Moran
	     * :material-map-marker: *Proceedings of the 43rd International Conference on Software Engineering [(ICSE’21)](https://conf.researchr.org/home/icse-2021) - Formal Tool Demonstrations Track, Virtual (originally Madrid, Spain), May 25th - 28th, 2021, to appear, 4 pages (37% Acceptance Rate)*
	     * [:material-pdf-box: pdf](https://arxiv.org/abs/2103.04531) | [:material-tools: tool](https://gitlab.com/SEMERU-Code-Public/Android/video2scenario/-/tree/master/python_v2s)

    === "Abstract"

        Screen recordings are becoming increasingly important as rich software artifacts that inform mobile application development processes. However, the amount of manual effort required to extract information from these graphical artifacts can hinder resource-constrained mobile developers. This paper presents Video2Scenario (V2S), an automated tool that processes video recordings of Android app usages, utilizes neural object detection and image classification techniques to classify the depicted user actions, and translates these actions into a replayable scenario. We conducted a comprehensive evaluation to demonstrate V2S's ability to reproduce recorded scenarios across a range of devices and a diverse set of usage cases and applications. The results indicate that, based on its performance with 175 videos depicting 3,534 GUI-based actions, V2S is accurate in reproducing ≈89% of actions from collected videos.
        
        
!!! example "Mutation-based Evaluation of Security-focused Static Analysis Tools for Android"

    === "Paper Info"

        * :material-account-supervisor-outline: Amit Seal Ami, Kaushal Kafle, Kevin Moran, Adwait Nadkarni, and Denys Poshyvanyk
	     * :material-map-marker: *Proceedings of the 43rd International Conference on Software Engineering [(ICSE’21)](https://conf.researchr.org/home/icse-2021) - Formal Tool Demonstrations Track, Virtual (originally Madrid, Spain), May 25th - 28th, 2021, to appear, 4 pages (37% Acceptance Rate)*
	     * [:material-pdf-box: pdf](https://arxiv.org/abs/2102.06823) | [:material-tools: tool](https://secure-platforms-lab-w-m.github.io/muse/)

    === "Abstract"

        This demo paper presents the technical details and usage scenarios of μSE: a mutation-based tool for evaluating security-focused static analysis tools for Android. Mutation testing is generally used by software practitioners to assess the robustness of a given test-suite. However, we leverage this technique to systematically evaluate static analysis tools and uncover and document soundness issues. μSE's analysis has found 25 previously undocumented flaws in static data leak detection tools for Android. μSE offers four mutation schemes, namely Reachability, Complex-reachability, TaintSink, and ScopeSink, which determine the locations of seeded mutants. Furthermore, the user can extend μSE by customizing the API calls targeted by the mutation analysis. μSE is also practical, as it makes use of filtering techniques based on compilation and execution criteria that reduces the number of ineffective mutations.
 

!!! note "Systematic Mutation-based Evaluation of the Soundness of Security-focused Android Static Analysis Techniques"

    === "Paper Info"

        * :material-account-supervisor-outline: Amit Seal Ami, Kaushal Kafle, Kevin Moran, Adwait Nadkarni, and Denys Poshyvanyk
	     * :material-map-marker: *ACM Transactions on Security & Privacy [(TOPS)](https://dl.acm.org/journal/tops), accepted*
	     * [:material-pdf-box: pdf](https://arxiv.org/abs/2102.06829) | [:material-tools: tool](https://secure-platforms-lab-w-m.github.io/muse/)

    === "Abstract"

        Mobile application security has been a major area of focus for security research over the course of the last decade. Numerous application analysis tools have been proposed in response to malicious, curious, or vulnerable apps. However, existing tools, and specifically, static analysis tools, trade soundness of the analysis for precision and performance and are hence soundy. Unfortunately, the specific unsound choices or flaws in the design of these tools is often not known or well-documented, leading to misplaced confidence among researchers, developers, and users. This paper describes the Mutation-based Soundness Evaluation (μSE) framework, which systematically evaluates Android static analysis tools to discover, document, and fix flaws, by leveraging the well-founded practice of mutation analysis. We implemented μSE and applied it to a set of prominent Android static analysis tools that detect private data leaks in apps. In a study conducted previously, we used μSE to discover 13 previously undocumented flaws in FlowDroid, one of the most prominent data leak detectors for Android apps. Moreover, we discovered that flaws also propagated to other tools that build upon the design or implementation of FlowDroid or its components. This paper substantially extends our μSE framework and offers an new in-depth analysis of two more major tools in our 2020 study, we find 12 new, undocumented flaws and demonstrate that all 25 flaws are found in more than one tool, regardless of any inheritance-relation among the tools. Our results motivate the need for systematic discovery and documentation of unsound choices in soundy tools and demonstrate the opportunities in leveraging mutation testing in achieving this goal.
        
        
!!! note "Security in Centralized Data Store-based Home Automation Platforms: A Systematic Analysis of Nest and Hue"

    === "Paper Info"

        * :material-account-supervisor-outline: Kaushal Kafle, Kevin Moran, Sunil Manandhar, Adwait Nadkarni, and Denys Poshyvanyk
	     * :material-map-marker: *ACM Transactions on Cyber Physical Systems [(TCPS)](https://dl.acm.org/journal/tcps), accepted*
	     * [:material-pdf-box: pdf](https://arxiv.org/abs/2102.06829)

    === "Abstract"

        Home automation platforms enable consumers to conveniently automate various physical aspects of their homes. However, the security flaws in the platforms or integrated third-party products can have serious security and safety implications for the user’s physical environment. This article describes our systematic security evaluation of two popular smart home platforms, Google’s Nest platform and Philips Hue, which implement home automation “routines” (i.e., trigger-action programs involving apps and devices) via manipulation of state variables in a centralized data store. Our semi-automated analysis examines, among other things, platform access control enforcement, the rigor of non-system enforcement procedures, and the potential for misuse of routines, and it leads to 11 key findings with serious security implications. We combine several of the vulnerabilities we find to demonstrate the first end-to-end instance of lateral privilege escalation in the smart home, wherein we remotely disable the Nest Security Camera via a compromised light switch app. Finally, we discuss potential defenses, and the impact of the continuous evolution of smart home platforms on the practicality of security analysis. Our findings draw attention to the unique security challenges of smart home platforms and highlight the importance of enforcing security by design.