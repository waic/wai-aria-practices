---
# This file was generated by scripts/pre-build/library/formatForJekyll.js
title: "About"
ref: /ARIA/apg/about/

github:
  repository: w3c/aria-practices
  branch: main
  path: content/about/about.html
feedbackmail: public-aria-practices@w3.org
permalink: /ARIA/apg/about/

sidebar: false



# Context here: https://github.com/w3c/wai-aria-practices/issues/31
type_of_guidance: APG

lang: en
---
<meta charset="UTF-8" />
<meta content="width=device-width, initial-scale=1.0" name="viewport" />
<title>About</title>

<script src="../../../content-assets/wai-aria-practices/shared/js/highlight.pack.js"></script>
<script src="../../../content-assets/wai-aria-practices/shared/js/app.js"></script>
<script src="../../../content-assets/wai-aria-practices/shared/js/skipto.js"></script>


<link 
  rel="stylesheet"
  href="{{ '/content-assets/wai-aria-practices/styles.css' | relative_url }}"
>
<!-- Code highlighting styles -->
<link 
  rel="stylesheet"
  href="{{ '/content-assets/wai-aria-practices/shared/css/github.css' | relative_url }}"
>


<script>
    const parentPage = window.location.pathname.match(
      /\/(patterns|practices|about)\//
    )?.[1];
    if (parentPage) {
      const parentHref = 'a[href*="' + parentPage + '"]';
      document.querySelector(parentHref).classList.add('active');
    }
  </script>
<div>

    <div>
      
      <ul class="content-list">
        <li>
          <h2><a href="introduction/">Introduction</a></h2>
          <p>
            To learn  about the purpose of the APG, the prerequisite knowledge it  assumes, and how it is organized, read the
            <a href="introduction/">Introduction</a>.
          </p>
        </li>
        <li>
          <h2><a href="aria-basics/">ARIA Basics</a></h2>
          <p>
            Facilitate success when applying APG guidance by developing a solid understanding of what ARIA is, what accessibility semantics are, and  their purpose and limitations with this section about
            <a href="aria-basics/">ARIA Basics</a>.
          </p>
        </li>
        <li>
          <h2><a href="acknowledgements/">Acknowledgements</a></h2>
            <p>
              To learn about the people and organizations who contribute to the development of the APG, read the <a href="acknowledgements/">Acknowledgements</a>.
            </p>
        </li>
        <li>
          <h2><a href="change-history/">Change History</a></h2>
          <p>
            A history of how the APG has changed, dating back to 2014, including easy access to the detailed commit log is available in the
            <a href="change-history/">Change History</a>.
          </p>
        </li>
        <li>
          <h2><a href="related-specifications/">Related Specifications</a></h2>
          <p>
            The APG synthesizes guidance based on information from several specifications.
            While the guidance contains contextual links to relevant specifications, it can be handy to have a consolidated list of all the
            <a href="related-specifications/">Related Specifications</a>.
          </p>
        </li>
        <li>
          <h2><a href="coverage-and-quality/">Coverage and Quality Report</a></h2>
          <p>
            Objectives of the APG Task Force include providing guidance or examples for all ARIA attributes and doing so with code that implements practices documented in the APG code guide.
            As the APG is revised, the build process updates our view of Progress toward these objectives in the
            <a href="coverage-and-quality/">Coverage and Quality Report</a>.
          </p>
        </li>
      </ul>
    </div>
  
</div>
<script 
  src="{{ '/content-assets/wai-aria-practices/shared/js/skipto.js' | relative_url }}"
></script>
