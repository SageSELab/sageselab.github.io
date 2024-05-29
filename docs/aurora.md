## Online Appendix for "AURORA: Navigating UI Tarpits via Automated Neural Screen Understanding"

## Authors
* **<a href="https://mason.gmu.edu/~skhan89/">Safwat Ali Khan</a>,** George Mason University
* **Wenyu Wang,** StellarCyber Inc.
* **Yiran Ren,** Dragon Testing Technologies Inc.
* **Bin Zhu,** Dragon Testing Technologies Inc.
* **Jiangfan Shi,** Dragon Testing Technologies Inc.
* **<a href="https://mason.gmu.edu/~jmahmud/">Alyssa McGowan</a>,** Thomas Jefferson High School of Science & Technology
* **<a href="https://cs.gmu.edu/~winglam/">Wing Lam</a>,** George Mason University
* **<a href="https://www.kpmoran.com">Kevin Moran</a>,** University of Central Florida


## Abstract

Nearly a decade of research in software engineering has focused on automating mobile app testing to help engineers in overcoming the unique challenges associated with the software platform. Much of this work has come in the form of Automated Input Generation tools (AIG Tools) that dynamically explore app screens. However, such tools have repeatedly been demonstrated to achieve lower-than-expected code coverage -- particularly on sophisticated proprietary apps.
Prior work has illustrated that a primary cause of these coverage deficiencies is related to so-called *tarpits*, or complex screens that are difficult to navigate. 

In this paper, we take a critical step toward enabling AIG tools to effectively navigate tarpits during app exploration through a new form of automated semantic screen understanding. That is, we introduce AURORA, a technique that learns from the visual and textual patterns that exist in mobile app UIs to automatically detect common screen designs and navigate them accordingly. The key idea of AURORA is that there are a finite number of mobile app screen designs, albeit with subtle variations, such that the general patterns of different categories of UI designs can be *learned*. As such, AURORA employs a multi-modal, neural screen classifier that is able to recognize the most common types of UI screen designs. After recognizing a given screen, it then applies a set of flexible and generalizable heuristics to properly navigate the screen. We evaluated AURORA both on a set of 12 apps with known tarpits from prior work, and on a new set of five of the most popular apps from the Google Play store. 
Our results indicate that AURORA is able to effectively navigate tarpit screens, outperforming prior approaches that *avoid* tarpits by 19.6\% in terms of method coverage. 
Our analysis of the results finds that the improvements can be attributed to AURORA's UI design classification and heuristic navigation techniques.

## Dataset and Code

<center><a href="https://github.com/safwatalikhan/AURORA/" title="Click Here to Access the Clarity Dataset" class="md-button md-button--primary"> Click Here to Access the AURORA GitHub Repo with Code & Data </a></center>

<center><a href="https://arxiv.org/abs/2404.01240" title="Click Here to Access Experimental Data for SANER'22 Paper" class="md-button md-button--primary"> Click Here to Access the Full Paper PDF </a></center>

