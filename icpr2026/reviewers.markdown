---
title: Reviewer's guide
permalink: /icpr2026/reviewers/
---

## The Github issue

To perform a review, **start from the [Github issue](https://github.com/IAPR-TC22-RRL/ICPR-2026-Reproducible-Research-Label-submissions-test/)** assigned to you.

If you encounter any errors or problems during your review, you can communicate with the author by posting comments at the bottom of the issue.
The task of the reviewer is not to fix a non-reproducible submission, but to **help the author improve their code so that their results are reproducible**, assuming that they're close to the objective. Submissions that fail to be reproducible beyond minor details are not expected get the badge recommendation from the reviewers. The reviews can be considered as a straightforward and little time-consuming check of the reproducibility of the submissions.

## Your review on CMT

You will be declared reviewer on the CMT system, where you will have access to:

- **the paper** associated with the code to review
- **a template for your review report** in Markdown and DOCX format

The report contains sections to complete **before, during and after** your review.
Once the review is completed, you must upload your completed report to the CMT system.

{: .centertext}
[![]({{ "assets/icon_markdown.png" | relative_url }}){: .width-8}]({{ "template/review_template.md" | relative_url }})&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![]({{ "assets/icon_docx.png" | relative_url }}){: .width-8}]({{ "template/review_template.docx" | relative_url }})

{: .centertext}
_Download templates by clicking on icons._

## Checks before the review

Before starting to install/build/run, make sure that:

1. You have **access to the Git repository**
   - Request access and specify that the repository will only be labeled if ICPR is authorized to fork it into a public repository at the end of the review process.
2. There is a **README.md or INSTALL.md file** containing:
   - instructions to build/run the code
   - versions of languages and libraries used by the authors and/or minimum required versions, notably for Python libraries and dependencies.
3. You have **access to the data** necessary to reproduce the results
   - If it's a neural network, ensure you have access to the pre-trained network.
4. You have **access to the items to reproduce** (data, figures, etc.)

## Procedure to follow during the review

Here is a non-exhaustive list of procedures to follow for situations that may arise:

1. If there is a **build or runtime error**:
   - Communicate with the author so that they can correct their submission if necessary (README.md/INSTALL.md instructions, code, data, etc.).
2. If there are **execution environment issues or dependency version problems**:
   a. Discuss the problem with the author and see how to resolve it.
   b. If the problem can be fixed, **ask the author to update their Git repository** accordingly (README.md/INSTALL.md instructions, code, data, etc.).
   c. If the problem cannot be fixed, contact the Reproducible Label chairs so that the case can be reassigned to another reviewer if possible, and finish filling out your report.

{% include contact.markdown %}
