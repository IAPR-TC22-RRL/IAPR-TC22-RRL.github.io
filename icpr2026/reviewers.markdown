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
We honestly appreciate your involvement in the review process. We hope that the label will help make more visible the problem of reproducibility in research and its need for reliable scientific advance.

Each of the reviewers will be acknowledged in a dedicated section on the websites of **ICPR 2026** and the **IAPR Technical Committee 22** (TC-22).

## The Review process
The authors of ICPR papers checked a checkbox during the submission to apply for the RRPR Badge. Then, once they got accepted for the main conference, they were eligible for the badge.

The review implies a verification of the code associated with the paper, although it’s expected to be not very time-consuming and the reviewers might use their own criteria for a quick or more thorough evaluation, depending on the case of each particular submission. We nevertheless provide here a guide with indications about what the reviewer might check.

We assume that, in principle, all the submissions are already reproducible and therefore the task of the reviewers is simply to check that this is the case. Note that under no circumstances the work of the reviewers is to make the submissions of the authors reproducible.

A review might end up with an immediate rejection in case the submission fails to comply with requirements that are judged as fundamental by the reviewer, as for example not releasing the source code or the required data, or having a license which is incompatible with open science, for example. In those cases, the badge might be discarded right away and the report of the reviewer would simply indicate those faults without the need of more checks.

As the evaluation is expected to be a check, we will have just one round for which the outcome will be to recommend or not the badge, along with a short comment. Eventually, the recommendation of the reviewers will be completed by the ICPR Reproducibility Chairs, who will act as meta-reviewers.

It may happen that a submission is mainly reproducible but some details are missing, but the reviewer considers that rather than refusing the badge, it could be granted if the authors make the required quick changes. In that case, the reviewers might write the requests in their report, and the Meta-Reviewers will make the request to the authors before their final decision.

If you accept to help us with this new initiative, please set the *"Reproducible Research in Pattern Recognition (RRPR) Badge"* option in your subject area.

## Reviewer's guide
This section provides some hints for the reviewers.
Of course, the more the reviewer checks to decide on the reproducibility of the submission, the better.

Some faults might be considered as major and therefore immediately **disqualify a submission**. Thus, you may check the following items before any more detailed evaluation:

1. You have **access to the source code**
   - Typically a link to a public repository in Github or any other forge, or a compressed file that can be downloaded from the author's website.
2. There is a **README.md or INSTALL.md file** containing:
   - detailed instructions to build and run the code
   - versions of languages and libraries used by the authors and/or minimum required versions, notably for Python libraries and dependencies.
   - in general, instructions to build the environment. For example, a Dockerfile, or a requirements.txt file when using Python.
3. You have **access to the data** that is necessary to reproduce the results
   - For example, if the code uses a neural network, the authors should have provided access to the weights.
4. You have **access to all the elements you consider important to decide about the reproducibility** of the submission.

In case the reviewers consider that an important element is missing, they might write it as a request in the reviewer's report and condition the decision on the authors making the change. The work of the reviewers is finished at that point. The Meta-Reviewers will request the authors to do the required changes and decide accordingly.

Some items you might want to check as a reviewer:

- The source code is publicly available
- Any data required to run the program is publicly available. Ideally as FAIR (findable, accessible, interoperable, reusable)
- The license of the source code is open source/free software compatible, thus allowing for reuse
- There are clear and complete instructions on how to build the program
- The execution environment is well specified. This may include. for example, the Python requirements, the versions of the libraries, a Dockerfile, ... 
- The code compiles without errors after following the instructions
- There are clear and complete instructions on how to run the program and obtain results
- The code runs after following the execution instructions
- The reviewer is able to obtain the same or equivalent (for non-deterministic algorithms) results as given by the authors in their paper. For example, the reviewer is able to obtain the same tables or figures with the data provided.
- The code is properly versioned, and it can be referred with a proper PID (as for example, the SHWID)

In your short review report you might mention these items, or any other you judged important in your decision.

Remember that these are only indications, not a request to systematically review each of the items. Of course, the more detailed the review, the better justified the decision. In any case, the compilation, execution, and comparison with the results provided by the authors are key elements to determine the reproducibility of the submission.

The decision of the reviewers relies on their own criteria, which will be completed by the evaluation of the RR-Chairs acting as Meta-Reviewers.


Please note that you can reach by email the Reproducibility Chairs at any time if you need it: rr_chairs@icpr2026.org

{% include contact.markdown %}
