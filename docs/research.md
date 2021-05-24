---
hide:
  - navigation
  - toc
---

<style>

  .responsive-grid {
    display: grid;
    width: 100%;
    grid-template-columns: repeat(1, 1fr);
    gap: 2rem;
  }

  @media screen and (min-width: 64rem) {
    .responsive-grid {
      grid-template-columns: repeat(3, 1fr);
    }
  }

  .card-wrapper {
    text-decoration: none;
    transition: none;
    background: none;
    padding: 0;
  }

  .card {
    position: relative;
    padding: 1.5rem;
    display: flex;
    flex-direction: row;
    -moz-box-align: center;
    align-items: center;
    height: 100%;
    -moz-box-pack: start;
    justify-content: flex-start;
    box-shadow: rgba(0, 0, 0, 0.09) 0.3125rem 0.3125rem 0px -0.0625rem, rgba(0, 0, 0, 0.15) 0px 0.25rem 0.5rem 0px;
    transition: all 0.6s cubic-bezier(0.165, 0.84, 0.44, 1) 0s;
  }

  .card:hover {
    box-shadow: rgba(0, 0, 0, 0.2) 0.3125rem 0.3125rem 0px -0.0625rem, rgba(0, 0, 0, 0.26) 0px 0.25rem 0.5rem 0px;
  }

  @media screen and (min-width: 75rem) {
    .card {
      padding: 2rem 2.5rem;
      margin: 0px 1px;
      border-radius: 4px;
    }
  }

  @media screen and (min-width: 36rem) {
    .card {
      padding: 1rem 1.5rem;
      margin: 0px 1px;
      border-radius: 4px;

    }
  }

  .card .logo {
    margin-right: 0.75rem;
    width: 80px;
    height: 80px;
  }

  .card .card-content {
    display: flex;
    flex: 1 1 0%;
    flex-direction: column;
    width: 100%;
  }

  .card .card-content h5 {
    margin: 0;
  }

  .card .card-content p {
    margin-top: 0.25em;
    margin-bottom: 0;
    font-size: 12px;
  }
  
    .card .card-content li {
    font-size: 12px;
  }

  .card .card-content code {
    background: rgba(0, 0, 0, 0.05) none repeat scroll 0% 0%;
    padding: 2px 6px;
    border-radius: 4px;
  }


  .component-wrapper span.em {
    color: rgb(61, 61, 61);
  }

  .component-wrapper a {
    transition: color 125ms;
    padding: 2px 6px;
    margin: 0px 1px;
    border-radius: 4px;
    display: inline;
    cursor: pointer;
  }

  .component-wrapper a:hover {
    color: var(--md-typeset-a-color);
    background: var(--md-accent-fg-color--transparent);
  }
</style>

## Research Mission

Our research mission is to pursue a more complete understanding of how engineers develop software and to build the next generation of intelligent developer tools to help facilitate the software engineering process. In essence, we aim to make it as easy as possible for engineers to go from *ideas* to *working products*.

## Research Focus Areas

<div class="responsive-grid">
	<div class="card">
		<div class="logo">
			<img src="../images/smartphone.png" alt="Illustration of a modern smartphone.">
       </div>
<div class="card-content">
       	<h5>Mobile Applications</h5>
          <p>Given their ubiquity in today's society, creating effective developer tools and software engineering practices for mobile applications is essential. Our research looks to build forward-thinking programming tools for mobile apps.</p>
</div>
</div>
<!-- Networking -->
<div class="card">
	<div class="logo">
            <img src="../images/ai.png" alt="Depiction of Computer AI.">
          </div>
          <div class="card-content">
            <h5>AI and Software Engineering</h5>
            <p>Our lab conducts research that aims to leverage new advances in artificial intelligence (with a focus on Deep Learning) to help build automated developer tools. Additionally, we examine how we best design tools and practices to engineer reliable systems that make use of artificial intelligence.</p>
          </div>
        </div>
        <!-- Customize -->
<div class="card">
          <div class="logo">
            <img src="../images/bug.png" alt="Bug illustrated in Code.">
          </div>
          <div class="card-content">
            <h5>Bug Reporting</h5>
            <p>Given the complexity of modern applications, bugs often contnue to persist after release, and users need effective mechanisms to report them. Our research has pioneered interactive bug reporting systems, and we continue to advance error reporting methods for software.</p>
          </div>
        </div>
      </div>


  <div class="responsive-grid">
        <div class="card">
          <div class="logo">
            <img src="../images/security.png" alt="Depiction of a Lock denoting computer security.">
          </div>
          <div class="card-content">
            <h5>Software Security</h5>
            <p>Given that software is interwoven into user's personal lives, the stakes of software security and privacy have never been higher. Our research examines how we can apply software engineering principles and practices to help ensure the security of complex software systems.</p>
          </div>
        </div>
 <div class="card">
          <div class="logo">
            <img src="../images/gui.png" alt="Depiction of a Lock denoting computer security.">
          </div>
          <div class="card-content">
            <h5>Automated UI Analysis</h5>
            <p>The Graphical User Interface represents a reich source of information that describes software in a visual manner. They allow users to intuitively understand software functionality. Our research aims to automatically analyze users interfaces to automate software tasks.</p>
          </div>
        </div>
<div class="card">
          <div class="logo">
            <img src="../images/open.png" alt="Depiction of a Lock denoting computer security.">
          </div>
          <div class="card-content">
            <h5>Open Science</h5>
            <p>Our lab follows <i>open science</i> practices. We strive to make all our papers, software, and data freely available to the public to support replication, scientific progress, and the advancement of software engineering research.</p>
          </div>
        </div>
        <br>
        <br>
  </div>
  
  
  
## Research Sponsors

The SAGE Lab graciously acknowledges support from our sponsors including the [National Science Foundation](https://www.nsf.gov), and [Cisco Systems](https://research.cisco.com).


<div class="responsive-grid">
	<div class="card">
		<div class="logo">
			<img src="../images/nsf.png" alt="NSF Logo">
       </div>
<div class="card-content">
       	<h5>SHF: Small Towards a Holistic Causal Model for Continuous Software Traceability</h5>
          <ul>
          <li><b>Award Info: </b> National Science Foundation Award <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2007246&HistoricalAwards=false">CCF-2007246</a></li>
          <li><b>Funding Amount: </b> $500,000</li>
          <li><b>Funding Period: </b> October 1st, 2020 - September 30th, 2023</li>
          </ul>
</div>
</div>
<div class="card">
		<div class="logo">
			<img src="../images/nsf.png" alt="NSF Logo">
       </div>
<div class="card-content">
       	<h5>Collaborative Research: SHF: Medium: Bug Report Management 2.0</h5>
          <ul>
          <li><b>Award Info: </b> National Science Foundation Award <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1955853&HistoricalAwards=false">CCF-2007246</a></li>
          <li><b>Funding Amount: </b> $1,200,000</li>
          <li><b>Funding Period: </b> October 1st, 2020 - September 30th, 2024</li>
          </ul>
</div>
</div>
<div class="card">
		<div class="logo">
			<img src="../images/nsf.png" alt="NSF Logo">
       </div>
<div class="card-content">
       	<h5>EAGER: Mapping Future Synergies between Deep Learning and Software Engineering</h5>
          <ul>
          <li><b>Award Info: </b> National Science Foundation Award <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1927679">CCF-2007246</a></li>
          <li><b>Funding Amount: </b> $82,828</li>
          <li><b>Funding Period: </b> July 15th, 2019 - June 30th, 2020</li>
          </ul>
</div>
</div>
</div>
      
<div class="responsive-grid">
<div class="card">
		<div class="logo">
			<img src="../images/cisco.png" alt="NSF Logo">
       </div>
<div class="card-content">
       	<h5>Identifying and Tracing Security-Related Software Requirements</h5>
          <ul>
          <li><b>Award Info: </b> Cisco Advanced Security Research Grant</li>
          <li><b>Funding Amount: </b> $100,000</li>
          <li><b>Funding Period: </b> July, 2019 - July, 2020</li>
          </ul>
</div>
</div>
</div>
