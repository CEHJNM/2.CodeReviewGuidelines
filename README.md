# 2.CodeReviewGuidelines
Guidelines for Code Review

In the analysis phase, the person/people responsible for coding should clearly comment throughout all their steps on different options and choices.
After all analyses have concluded and the first manuscript draft is ready, a code reviewer is indentified (different person that the one(s) involved in primary analysis).

The code reviewer is responsible for (1) reviewing the code, (2) checking that all numbers in the paper have been correctly pasted, (3) ensuring that the functions used correspond to what is described in the Methods Section.

If the code reviewer has access to all data required for analysis, it is advisable that they rerun analyses.

If the code reviewer does not have access to all or part of the data or the analysis is computationally expensive, then the code reviewer does not need to rerun analyses. They can just review the code and all raw output. The primary analysis person should comment out any lines that output raw data and exclude any raw data segments from the output (e.g., avoid including head(dataset) if the data are identifiable).

Given the code reviewer's engagement with the project, we recommend that the code reviewer is a co-author on the paper (author position would depend on relative contribution).

We have found that this practice (1) minimizes the risk of coding and pasting errors; (2) helps both primary coder(s) and code reviewer improve their coding skills; (3) increases reproducibility, especially if coupled with including the link to the code in the manuscript. The only potential concern could be that code review could delay publication. In practice, if a code reviewer is identified as soon as the first manuscript draft is available, code review can be conducted in parallel to sending the manuscript draft to co-authors, resulting in no additional time to submission.

We strongly encourage Center members to engage in practicing code review. If you have any questions about implementing this in your group and/or would like help identifying code reviewers, please do not hesitate to reach out to the Study Design and Data Science Facility Core Co-Directors, Pam (prf1@cumc.columbia.edu) and Sen (sp3449@cumc.columbia.edu).
