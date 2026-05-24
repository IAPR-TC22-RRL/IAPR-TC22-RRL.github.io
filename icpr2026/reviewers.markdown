---
title: Reviewer's guide
permalink: /icpr2026/reviewers/
---

{: .centertext}
[![]({{ "assets/icpr26Logo.svg" | relative_url }}){: .width-14}](https://icpr2026.org/)
&nbsp;&nbsp;
[![]({{ "assets/logoTC22.png" | relative_url }}){: .width-7}](https://iapr-tc22.org/)

## Becoming a reviewer

To become a reviewer for the **Reproducible Research Label**, start by letting us know what resources you have available by filling out this very short form (it takes less than 2 minutes):

{: .centertext}
[![]({{ "assets/logo-limesurvey.svg" | relative_url }})](https://sondages.unistra.fr/index.php/341457)<br>
_[https://sondages.unistra.fr/index.php/341457](https://sondages.unistra.fr/index.php/341457)_

## Start a review

You will be assigned a code to evaluate on the CMT system, where you will have access to:

- **the paper** associated with the code to review
- **a template for your review report** in Markdown and DOCX format (the same as those available below)

The report template contains sections to complete **before, during and after** your review.
Once the review is completed, you must **upload your completed report to the CMT system**.

{: .centertext}
[![]({{ "assets/icon_markdown.png" | relative_url }}){: .width-8}]({{ "template/review_template.md" | relative_url }})&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![]({{ "assets/icon_docx.png" | relative_url }}){: .width-8}]({{ "template/review_template.docx" | relative_url }})

{: .centertext}
_Download templates by clicking on icons._

## The GitHub issue

To perform a review, **start from the [GitHub issue](https://github.com/IAPR-TC22-RRL/ICPR-2026-Reproducible-Research-Label-submissions-test/)** assigned to you.

{: .centertext}
[![]({{ "assets/logo-github.png" | relative_url }})](https://github.com/IAPR-TC22-RRL/ICPR-2026-Reproducible-Research-Label-submissions-test/)<br>
_[https://github.com/IAPR-TC22-RRL/ICPR-2026-Reproducible-Research-Label-submissions-test/](https://github.com/IAPR-TC22-RRL/ICPR-2026-Reproducible-Research-Label-submissions-test/)_

## Checks before starting the review

Before building/installing/running the code, make sure that:

1. You have **access to the Git repository**
   - Request access and specify that the repository will only be labeled if ICPR is authorized to fork it into a public repository at the end of the review process.
2. There is a **README.md or INSTALL.md file** containing:
   - instructions to build and run the code
   - versions of languages and libraries used by the authors and/or minimum required versions, notably for Python libraries and dependencies.
3. You have **access to the data** necessary to reproduce the results
   - If the code uses a neural network, ensure you have access to the pre-trained network.
4. You have **access to the items required to reproduce** the results (data, figures, etc.)

## During the review

The task of the reviewer is not to fix a non-reproducible submission, but to **help the author improve their code so that their results are reproducible**, assuming that they're close to the objective.
Submissions that fail to be reproducible beyond minor details are not expected to get the badge recommendation from the reviewers.
The reviews can be considered as straightforward and not very time-consuming check of the reproducibility of the submissions.

If you encounter any errors or problems during your review, **we encourage you to communicate with the author by posting comments at the bottom of the GitHub issue**, by indicating your error and, if possible, by copying the error message and an execution trace.

Here is a non-exhaustive **list of procedures** to follow for situations that may arise:

1. There is a **build or runtime error**:
   - Communicate with the author so that they can correct their submission if necessary (README.md/INSTALL.md instructions, code, data, etc.).
2. There are **execution environment issues or dependency version problems**:
   a. Discuss the problem with the author and see how to resolve it.
   b. If the problem can be fixed, **ask the author to update their Git repository** accordingly (README.md/INSTALL.md instructions, code, data, etc.).
   c. If the problem cannot be fixed, contact the <span class="chairs">Reproducible Research Label chairs</span> so the case can be reassigned to another reviewer if possible, and finish filling out your report.

## At the end of the review

Once the review is completed, you must **upload your completed report to the CMT system**.

{% include contact.markdown %}
