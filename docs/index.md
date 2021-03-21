---
hide:
  - navigation 
  - toc        
---

<style>

    /* Application header should be static for the landing page */
    .md-header {
      position: initial;
    }

    /* Remove spacing, as we cannot hide it completely */
    .md-main__inner {
      margin: 0;
    }

    /* Hide main content for now */
    .md-content {
      display: none;
    }

    /* Hide table of contents */
    @media screen and (min-width: 60em) {
      .md-sidebar--secondary {
        display: none;
      }
    }

    /* Hide navigation */
    @media screen and (min-width: 76.25em) {
      .md-sidebar--primary {
        display: none;
      }
    }
    
</style>

  <!-- Hero for landing page -->
  <section class="mdx-container">
    <div class="md-grid md-typeset">
      <div class="mdx-hero">
        <div class="mdx-hero__image">
          <img
            src="assets/images/illustration.png"
            alt=""
            width="1659"
            height="1200"
            draggable="false"
          >
        </div>
        <div class="mdx-hero__content">
          <h1>SAGE Research Lab</h1>
          <p>The Software Automation, Generation, and Engineering (SAGE) research lab is a software engineering research group led by Dr. Kevin Moran at George Mason University.</p>
          <a
            href="{{ page.next_page.url | url }}"
            title="{{ page.next_page.title | e }}"
            class="md-button md-button--primary"
          >
            See the Team
          </a>
          <a
            href="{{ 'insiders/' | url }}"
            title="Material for MkDocs Insiders"
            class="md-button"
          >
            View Publications
          </a>
        </div>
      </div>
    </div>
  </section>

