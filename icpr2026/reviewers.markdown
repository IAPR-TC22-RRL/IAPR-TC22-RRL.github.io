---
title: Reviewer's guide
permalink: /icpr2026/reviewers/
---

{: .centertext}
[![]({{ "assets/icpr26Logo.svg" | relative_url }}){: .width-14}](https://icpr2026.org/)
&nbsp;&nbsp;
[![]({{ "assets/logoTC22.png" | relative_url }}){: .width-7}](https://iapr-tc22.org/)

## Our gratitude to ICPR RRPR Reviewers
First of all, let us first thank the Reviewers Board.
The RRPR Badge wouldn't be possible without your work and we must express our enormous gratitude for making this initiative a reality.
We absolutely appreciate your involvement in the review process. We hope that the label will help make more visible the problem of reproducibility in research and its need for reliable scientific advance.

The name of each of the reviewers will be acknowledged in both the ICPR proceedings and the websites of ICPR and TC-22 (unless a reviewer doesn't wish to, of course).

## The Review process
The authors of ICPR papers checked a checkbox during the submission to apply for the RRPR Badge. Once they got accepted for the main conference, they were eligible for the badge.

The review implies checking the code associated with the paper, although it’s expected not to be very time-consuming and each reviewer might use their own criteria for a quick or more thorough evaluation. We nevertheless provide a guide with indications to what the reviewer might check. Note that the guide contains indications for the reviewer, but again this doesn't mean that these need to be taken as requests for the evaluation. The reviewers may use their own criteria to decide about the reproducibility of the submission. Of course, the more thorough the review is, the better.

We assume that, in principle, all the submissions are already reproducible and therefore the task of the reviewers is simply to check that this is the case. Note that under no circumstances the work of the reviewers is to make the submissions of the authors reproducible.

A review might end up with an immediate rejection in case the submission fails to comply with requirements that are judged as fundamental by the reviewer, as for example not releasing the source code or the required data, or having a license which is incompatible with open science, for example. In those cases, the badge might be discarded right away and the report of the reviewer would simply indicate those faults without the need of more checks.

As the evaluation is expected to be a check, we will have just one round for which the outcome will be to recommend or not the badge, along with a short comment. Eventually, the recommendation of the reviewers will be completed by the ICPR Reproducibility Chairs, who will act as meta-reviewers.

It may happen that a submission is mainly reproducible but some details are missing, but the reviewer considers that rather than refusing the badge, it could be granted if the authors make the required quick changes. In that case, the reviewers might write the requests in their report, and the Meta-Reviewers will make the request to the authors before their final decision.

If you accept to help us with this new initiative, please set the *"Reproducible Research in Pattern Recognition (RRPR) Badge"* option in your subject area.

Please note that you can reach by email the Reproducibility Chairs at any time if you need: rr_chairs@icpr2026.org


## The Reviewer's guide

## Start a review

You will be assigned a code to evaluate on the **CMT system**, where you will have access to the paper associated with the **code to review**.

## A Reviewer's guide
This section provides some hints for the reviewers. As pointed out before, each reviewer has the freedom to decide if the submission is reproducible or not by their own criteria and the suggestions in this section are not to be taken as requests for the evaluators. Of course, the more the reviewer checks to decide on the reproducibility of the submission, the better.

Some faults might be considered as major and therefore right away *disqualify a submission** from being granted the reproducibility badge. Thus, you may check the following items before any more detailed evaluation:

1. You have **access to the source code**
   - This might be typically a link to a public repository in Github or any other forge, or a compressed file that can be downloaded from the author's website.
2. There is a **README.md or INSTALL.md file** containing:
   - detailed instructions to build and run the code
   - versions of languages and libraries used by the authors and/or minimum required versions, notably for Python libraries and dependencies.
   - in general, instruction to build the environment. For example, a Dockerfile, or a requirements.txt file when using Python.
3. You have **access to the data** that is necessary to reproduce the results
   - For example, if the code uses a neural network, the authors should have provided access to the weights.
4. You have **access to all the elements you consider important to decide about the reproducibility** of the submission

In case the reviewers consider an important element is missing, they might write it as a request in the reviewer's report and condition their decision on the authors making the change. The Meta-Reviewers will request the authors to do the required changes and decide accordingly.

Some items you review might want to check:

- The source code is publicly available
- Any data required to run the method is publicly available. Ideally as FAIR (findable, accessible, interoperable, reusable)
- The license of the source code is open source/free software compatible, thus allowing for reuse
- The are clear and complete instructions on how to build the program
- The execution environment is well specified. For example, giving the Python requirements, the versions of the libraries, a Dockerfile, ... 
- The code compiles without errors after following the instructions
- The are clear and complete instructions on how to run the program and obtain results
- The code runs after following the execution instructions
- The reviewer is able to obtain the same or equivalent (for non-deterministic algorithms) results as given by the authors in their paper. For example, the reviewer is able to obtain the same tables or figures with the data provided.
- The code is properly versioned, and it can be referred with a proper PID (as for example, the SHWID)

In your short review report you might mention these items, or any other you judged important in your decision.

Remember that this are only indications, not a request to systematically review each of the items. Of course, the more detailed the review, the better to support their decision. Needless to0 say, the compilation, execution, and comparison with the results provided by the authors are key elements to determine the reproducibility of the submission.

The decision of the reviewers relies on their own criteria, which will be completed by the evaluation of the RR-Chairs acting as Meta-Reviewers.

In order to help te reviewers in their task, we're providing a review form can be uploaded along with the report.

{: .centertext}
[![]({{ "assets/icon_markdown.png" | relative_url }}){: .width-8}]({{ "template/review_template.md" | relative_url }})&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![]({{ "assets/icon_docx.png" | relative_url }}){: .width-8}]({{ "template/review_template.docx" | relative_url }})
[![]({{ "assets/icon_text.png" | relative_url }}){: .width-8}]({{ "template/review_template.txt" | relative_url }})


{: .centertext}
The form can be downloaded in different formats, at the convenience of the reviewer: markdown, docx, and plain text. You can download the templates by clicking on icons.

{% include contact.markdown %}
