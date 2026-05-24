---
title: Author's guide
permalink: /icpr2026/authors/
---

{: .centertext}
[![]({{ "assets/icpr26Logo.svg" | relative_url }}){: .width-14}](https://icpr2026.org/)
&nbsp;&nbsp;
[![]({{ "assets/logoTC22.png" | relative_url }}){: .width-7}](https://iapr-tc22.org/)

## Code requirements

Your code is eligible for the **Reproducible Research Label** if:

{: .checklist}
- it is **associated with a paper accepted at the main conference ICPR 2026**
- it is versioned with **Git**
- it may be **made public** at the end of the review process
  - the <span class="chairs">Reproducible Research Label chairs</span> will create a public clone of your Git repository if it obtains the label
- it has a **README or INSTALL file** that explains how to install dependencies and gives commands to compile and execute the code.
- it has the necessary **data publicly available**

Your code has a better chance of obtaining the **Reproducible Research Label** if:

{: .checklist}
- the **trained neural networks are available** for code that uses neural networks
  - we cannot guarantee that we will be able to review code that takes too long to train ("too long" will depend on the reviewer pool)
- it has **seeds of random generators available**
  - we cannot guarantee that we will label code if there are notable differences between the paper's results and those of the reviewer due to this lack of seeds.

We recommend that you consult the review report that the reviewers will have to complete to ensure your Git repository is set up in the best possible way.
It is available on the [reviewer's guide page]({{ "icpr2026/reviewers/"}}).

## Submit code

To submit your code, you need to have a GitHub account and **create an issue** in our dedicated repository:

{: .centertext}
[![]({{ "assets/logo-github.png" | relative_url }})](https://github.com/IAPR-TC22-RRL/ICPR-2026-Reproducible-Research-Label-submissions-test/)<br>
_[https://github.com/IAPR-TC22-RRL/ICPR-2026-Reproducible-Research-Label-submissions-test/](https://github.com/IAPR-TC22-RRL/ICPR-2026-Reproducible-Research-Label-submissions-test/)_

## Be responsive to be labeled

**The reviewer is encouraged to contact you if they encounter any errors.**
This can happen, for example, if they encounter problems during the review process, such as when installing a dependency or compiling/running your code.

**The reviewer may then contact you by commenting on your GitHub issue.**
By default, you receive an e-mail from GitHub when someone comments on an issue you created.
You can then answer the comment with your e-mail client or by continuing the discussion on the GitHub website.

**We strongly recommend that you be attentive and responsive to comments on your GitHub issue during the review phase**.
The more responsive you are, the more time the reviewer will have to try to reproduce your results.

The decision on whether or not to award the Label will be based on the reviewer's opinion at the end of the review process.
Code that is not reproducible at the start of the process may still be awarded the Label if it is reproducible by the end of the process.

{% include contact.markdown %}