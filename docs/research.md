---
hide:
  - navigation   
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

<h2>Research Focus Areas</h2>

<div class="responsive-grid">
	<div class="card">
		<div class="logo">
			<img src="images/smartphone.png" alt="Illustration of a modern smartphone.">
       </div>
       <div class="card-content">
       	<h5>Mobile Applications</h5>
          <p>Given their ubiquity in today's society, creating effective developer tools and software engineering practices for mobile applications is essential. Our research looks to build forward thinking programming tools for mobile apps.</p>
          </div>
        </div>

        <!-- Networking -->

        <div class="card">
          <div class="logo">
            <img src="images/ai.png" alt="Depiction of Computer AI.">
          </div>
          <div class="card-content">
            <h5>AI and Software Engineering</h5>
            <p>
              Advances in artifical intelligence continue at a rapid pace and are beginning to shape the way software is
              developed. Our lab conducts research on using new advances in artificial intelligene (with a focus on Deep
              Learning) to help build atuomated develoepr tools. Additionally, we examine how we best design tools and
              practices to engineer reliable systems that make use of artificial intelligence.
            </p>
          </div>
        </div>


        <!-- Customize -->

        <div class="card">
          <div class="logo">
            <img src="images/bug.png" alt="Bug illustrated in Code.">
          </div>
          <div class="card-content">
            <h5>Bug Reporting</h5>
            <p>
              Software is becoming increasingly important in user's lives as it permeates our daily activities. Given
              the complexity of modern applications, bugs often contnue to persist after release, and users need
              effective mechanisms to report them. Our research has pioneered interactive bug reporting systems, and we
              continue to advance error reporting methods for software.
            </p>
          </div>
        </div>
      </div>


  <div class="responsive-grid">
        <div class="card">
          <div class="logo">
            <img src="images/security.png" alt="Depiction of a Lock denoting computer security.">
          </div>
          <div class="card-content">
            <h5>Software Security</h5>
            <p>
              Given that software is interwoven into user's personal lives, the stakes of software security and privacy
              have never been higher. Our research examines how we can apply software engineering principles and
              practices to help ensure the security of complex software systems.
            </p>
          </div>
        </div>
      </div>