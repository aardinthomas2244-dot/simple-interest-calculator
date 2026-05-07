Code Contributions
This is the most common form of contribution and includes specific rules for technical work.
Bug Fixes: Instructions on how to find existing issues, claim them, and submit a fix.Feature Requests: Guidelines for proposing new features, often requiring a discussion in an issue before implementation.Coding Standards: Details on preferred styling (e.g., indentations, naming conventions) and linting configurations.Testing: Requirements for writing and running unit tests to ensure that changes don't break existing functionality.
When adding a bug report section to your  
 file, the goal is to guide contributors to provide actionable information that minimizes back-and-forth communication. 
What to Include in Your Description 
A strong bug report section should ask contributors to perform the following steps before and during their submission: 

• Preliminary Checks: 

	• Search existing issues: Ask users to check both open and closed issues to avoid duplicates. 
	• Verify the latest version: Ensure the bug still exists in the most recent release or the / branch. 
	• Isolate the problem: Confirm the issue is caused by the project's code and not an external environment or configuration error. 

• The "Good Report" Checklist: 

	• Clear Title: Use a descriptive title that summarizes the problem (e.g., "Login fails with 401 error on Chrome" instead of just "Login broken"). 
	• Reproduction Steps: Provide a numbered, step-by-step list to recreate the bug. 
	• Expected vs. Actual Behavior: Clearly state what should have happened versus what actually occurred. 
	• Environment Details: Request specific information such as Operating System, version numbers, and relevant browser or hardware details. 
	• Supporting Media: Encourage attaching screenshots, animated GIFs, or screen recordings that demonstrate the issue. 
	• Code Snippets: Ask for a Minimal, Complete, and Verifiable Example (MCVE) or log outputs wrapped in Markdown code blocks for better readability. [1, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14]  

Sample Description for Your File 
You can adapt the following text for your  

: 
How to Report a BugBefore submitting a bug report, please search existing issues to see if it has already been reported. If you find a similar open issue, please add a comment with any additional information you have instead of opening a new one.When opening an issue, please use our Bug Report Template and include:A clear and descriptive title.Steps to reproduce: A detailed list of steps to help us see the bug ourselves.Expected behavior: What you expected to happen.Actual behavior: What actually happened, including any error messages or stack traces.Environment: Your OS, version, and any other relevant setup details.Screenshots or GIFs: Visual evidence is highly appreciated! Additional Best Practices 

• Security Vulnerabilities: Explicitly state that security-sensitive bugs should not be reported via public issues; provide a private contact method (like an email) instead. 
• Issue Templates: Consider setting up formal GitHub Issue Templates to enforce this structure automatically when a user clicks "New Issue". [11, 15, 16, 17, 18]  

AI responses may include mistakes.

[1] https://github.com/jessesquires/.github/blob/main/CONTRIBUTING.md
[2] https://github.com/jessesquires/.github/blob/main/CONTRIBUTING.md
[3] https://bioconductor.github.io/bioc_mentorship_docs/bioc-package.html
[4] https://docs.github.com/en/enterprise-cloud@latest/issues/tracking-your-work-with-issues/learning-about-issues/planning-and-tracking-work-for-your-team-or-project
[5] https://github.com/github/issue-metrics/blob/main/CONTRIBUTING.md
[6] https://github.com/developersIndia/website/blob/main/.github/CONTRIBUTING.md
[7] https://github.com/OpenSC/OpenSC/wiki/How-to-write-a-good-bug-report
[8] https://github.com/dell/common-github-actions/blob/main/docs/CONTRIBUTING.md
[9] https://medium.com/codetodeploy/creating-organization-wide-issue-pr-templates-using-a-github-repository-2abd693aa9ec
[10] https://github.com/OpenSC/OpenSC/wiki/How-to-write-a-good-bug-report
[11] https://github.com/svengreb/.github/blob/main/contributing.md
[12] https://github.com/svengreb/.github/blob/main/contributing.md
[13] https://github.com/roots/guidelines/blob/master/CONTRIBUTING.md
[14] https://www.youtube.com/watch?v=MymFnw2gt8U
[15] https://www.youtube.com/watch?v=JnSAHjMCkQQ
[16] https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository
[17] https://contributing.md/example/
[18] https://callowayproject.github.io/bump-my-version/CONTRIBUTING/

Include a "Bug Fixes" or "Reporting Bugs" section in your  
 to guide contributors on how to document and submit their corrections. Effective descriptions should provide enough context for maintainers to verify and merge the fix without extensive back-and-forth. 
Content for the Bug Fix Section 
A high-quality bug fix description in a GitHub CONTRIBUTING.md file often includes the following elements: 

• Problem Summary: A clear, concise title and description identifying the demonstrable problem. 
• Reproduction Steps: A numbered list of exact actions taken to trigger the bug. 
• Observed vs. Expected Behavior: A direct comparison of what actually happened versus what should have happened. 
• Environment Details: Relevant software versions (OS, browser, library versions) and hardware specs. 
• Supporting Evidence: Instructions to attach logs, stack traces, screenshots, or videos demonstrating the issue. 
• Minimal Working Example (MWE): A small, isolated code snippet or repository that reproduces the bug. [2, 5, 6, 7, 8, 9, 10, 11]  

Sample Descriptions to Copy 
You can adapt these templates for your file: 
1. Instructions for Reporting a Bug"Before opening a new issue, please search existing issues to avoid duplicates. When reporting a bug, use our Bug Report Template and include:Steps to Reproduce: A clear, numbered list.Expected Result: What you thought would happenActual Result: What actually happened, including error logs or screenshots."2. Requirements for Submitting a Fix"To contribute a fix, please:Link the Issue: Reference the original bug report in your Pull Request.Include Tests: Add a new unit test that fails without your patch but passes with itFollow Coding Standards: Ensure your code passes all existing linting and style checks."3. Handling "Obvious" Fixes"Small fixes (e.g., typos, grammar, or formatting) can be submitted directly as a Pull Request without first opening an issue. For more significant architectural changes, please open an issue for discussion first." 
AI responses may include mistakes.

[1] https://mozillascience.github.io/working-open-workshop/contributing/
[2] https://github.com/containers/common/blob/main/CONTRIBUTING.md
[3] https://github.com/svengreb/.github/blob/main/contributing.md
[4] https://rewind.com/blog/best-practices-for-using-github-issues/
[5] https://github.com/jessesquires/.github/blob/main/CONTRIBUTING.md
[6] https://github.com/svengreb/.github/blob/main/contributing.md
[7] https://github.com/roots/guidelines/blob/master/CONTRIBUTING.md
[8] https://birdeatsbug.com/blog/how-to-write-a-bug-report
[9] https://github.com/src-d/guide/blob/master/engineering/documents/CONTRIBUTING.md
[10] https://github.com/OpenSC/OpenSC/wiki/How-to-write-a-good-bug-report
[11] https://gitlab.com/tgdp/templates/-/blob/main/bug-report/template_bug-report.md

To improve the documentation section of a  
 file on GitHub,  
focus on making it easy for contributors to identify gaps and follow established writing standards. Effective guidelines encourage contributions ranging from minor typo fixes to extensive technical guides. 
Key Documentation Improvements to Include 

• Defining Contribution Types: Clearly state what documentation help is needed, such as technical and grammatical corrections, typo fixes, or expanded explanations for new features. 
• Style and Voice Guidelines: Provide a Style Guide to ensure consistency. Encourage the use of active voice, second-person ("you"), and inclusive language while avoiding technical jargon like "repo" or "PR". 
• Visual Aids: Encourage contributors to include screenshots, videos, or animated GIFs in their pull requests to demonstrate changes or new features. 
• Navigation and Skimmability: Use a Table of Contents with internal links to different headings so contributors can find information quickly. 
• Communication Process: Advise contributors to open an issue before starting large documentation updates to minimize duplication of effort, while allowing small fixes like typos to be submitted directly as PRs. 
• Markdown Standards: Specify the preferred flavor, such as  GitHub Flavored Markdown 
, and suggest using backticks for inline code and limiting line lengths to 100 characters for better readability. 
• Local Preview Instructions: Provide specific steps for building and viewing documentation locally so contributors can check for formatting issues before submitting. [1, 2, 4, 5, 6, 7, 8, 9, 10, 11, 12]  

Example "Improving Documentation" Section 
You can use or adapt this template for your  

: 
By following these  GitHub documentation guidelines 
, you can lower the barrier to entry for new contributors. 

AI responses may include mistakes.

[1] https://gist.github.com/anubra266/5e4fbe050c5dabbabe892d14111c7267
[2] https://github.com/github/docs/blob/main/.github/CONTRIBUTING.md
[3] https://github.com/svengreb/.github/blob/main/contributing.md
[4] https://www.youtube.com/watch?v=Ea0kDdwJXLQ
[5] https://mozillascience.github.io/working-open-workshop/contributing/
[6] https://github.com/svengreb/.github/blob/main/contributing.md
[7] https://github.com/pytorch/examples/blob/main/CONTRIBUTING.md
[8] https://community.ibm.com/community/user/blogs/hiren-dave/2025/05/27/markdown-documentation-best-practices-for-document
[9] https://thenewstack.io/best-practices-for-creating-markdown-documentation-for-your-apps/
[10] https://github.com/github/docs/blob/main/.github/CONTRIBUTING.md
[11] https://contributing.md/example/
[12] https://mozillascience.github.io/working-open-workshop/contributing/
[13] https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors
[14] https://github.blog/changelog/2025-08-07-contributing-guidelines-now-visible-in-repository-tab-and-sidebar/

Enhancing a  
 file goes beyond just listing rules; it creates a welcoming and efficient onboarding experience for new developers. Effective enhancements focus on discoverability, clear workflows, and community engagement. 
Essential Workflow Enhancements 

• Step-by-Step Local Setup: Provide a detailed guide for setting up the development environment, including specific commands like , , or virtual environment setup. 
• Issue and PR Templates: Use structured formats for bug reports and feature requests. Providing links to GitHub Issue Templates ensures you receive all necessary information, such as reproduction steps and environment details. 
• Clear Branching and Commit Policies: Specify branch naming conventions (e.g.,  or ) and commit message standards (e.g., using the imperative mood and limiting the first line to 72 characters). 
• Automated Style Enforcement: Recommend or require tools like , , or  hooks so contributors can automatically format their code before submitting. [5, 6, 7, 8, 9, 10, 11]  

Strategic Sections to Include 

• "Where to Get Help":  List reliable communication channels like Discord, Slack, or GitHub Discussions to show you are available to support contributors facing challenges 
. 
• Code of Conduct Link: Explicitly link to or include your Code of Conduct to set behavioral expectations and foster an inclusive environment. 
• Recognition and Rewards: Add a section acknowledging contributors or link to a  file. You can also use tools to provide  Contributor Badges 
 as a token of appreciation. 
• Glossary of Terms: For complex projects, define technical terms and "contribution types" (e.g., technical corrections, typo fixes, or documentation gaps) to help beginners understand how they can best help. [11, 12, 13, 14, 15, 16, 17]  

Visual and Interactive Elements 

• Contribution Checklist: Use Markdown task lists for first-time contributors (e.g., , ) to make the process less intimidating. 
• Visual Examples: Embed screenshots or animated GIFs to demonstrate the expected behavior of a new feature or the correct way to fill out a pull request. 
• Table of Contents: For longer guidelines, a clickable table of contents helps users quickly navigate to the information they need. [16, 18, 19, 20]  

By placing your  

 in the root, , or   directory,  GitHub 
 will automatically surface it in the repository sidebar and overview tab to maximize visibility 
. 

AI responses may include mistakes.

[1] https://github.com/appwrite/appwrite/issues/8953
[2] https://github.blog/changelog/2025-08-07-contributing-guidelines-now-visible-in-repository-tab-and-sidebar/
[3] https://github.blog/changelog/2025-08-07-contributing-guidelines-now-visible-in-repository-tab-and-sidebar/
[4] https://github.com/vercel-labs/openreview/pull/9
[5] https://github.com/jessesquires/.github/blob/main/CONTRIBUTING.md
[6] https://embeddedartistry.com/blog/2017/12/11/get-others-involved-in-your-project-with-a-contributing-guide/
[7] https://github.com/opencloud-eu/opencloud/blob/main/CONTRIBUTING.md
[8] https://github.com/huggingface/datasets/blob/main/CONTRIBUTING.md
[9] https://github.com/jessesquires/.github/blob/main/CONTRIBUTING.md
[10] https://www.youtube.com/watch?v=dLRA1lffWBw
[11] https://contributing.md/how-to-build-contributing-md/
[12] https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors
[13] https://mozillascience.github.io/working-open-workshop/contributing/
[14] https://mozillascience.github.io/working-open-workshop/contributing/
[15] https://github.com/github/docs/blob/main/.github/CONTRIBUTING.md
[16] https://daily.dev/blog/contribute-to-open-source-docs-in-5-steps
[17] https://www.reddit.com/r/learnprogramming/comments/1t48lcv/how_do_you_start_contributing_to_open_source_in/
[18] https://git-scm.com/book/ms/v2/GitHub-Contributing-to-a-Project
[19] https://contributing.md/example/
[20] https://github.com/you-dont-need/You-Dont-Need-Javascript/issues/877

In a  
 file, an "Ideas are Welcome" section signals that you value community input beyond just code fixes. It encourages users to propose improvements, new features, or process changes. 
What to Include in an "Ideas are Welcome" Section 

• Propose New Features: Encourage contributors to suggest new tools, functionalities, or enhancements. 
• Process Improvements: Invite ideas for better workflows, new development tools, or ways to streamline the project. 
• Documentation & Content: Welcome suggestions for expanding documentation, fixing typos, or clarifying language. 
• UI/UX Enhancements: Ask for visual mockups or screenshots for interface improvements. 
• Feedback Before Implementation: Explicitly ask contributors to discuss major ideas in an issue thread before spending time on the code. [2, 3, 5, 6, 7, 8]  

Structuring Your  
GitHub automatically highlights your contributing guidelines when someone opens a pull request or issue. Use these sections to provide a clear path for contributors: 

• Welcome Note: Start with a friendly invitation to make contributors feel valued. 
• Code of Conduct: Link to your Code of Conduct to set expectations for respectful behavior. 
• How to Report Bugs: Provide a clear bug report template including steps to reproduce and system info. 
• Submission Process: Outline your fork-and-pull-request workflow, including branch naming and commit message styles. 
• Development Setup: Give instructions on how to install dependencies and run tests locally. 
• Recognition: Optionally mention how contributors are credited, such as in a  file or via Contributor Badges. [1, 5, 7, 11, 12, 13, 14, 15, 16, 17, 18]  

For inspiration, you can explore high-quality examples like the Atom contributing guide or use the CONTRIBUTING.md Template. [7, 19]  

AI responses may include mistakes.

[1] https://mozillascience.github.io/working-open-workshop/contributing/
[2] https://www.thegooddocsproject.dev/template/contributing-guide
[3] https://github.com/standard/standard-www/blob/master/CONTRIBUTING.md
[4] https://www.youtube.com/watch?v=E6NO0rgFub4
[5] https://github.com/jazz-community/welcome/blob/master/CONTRIBUTING.md
[6] https://www.youtube.com/watch?v=DxyTPzOVgAI
[7] https://contributing.md/example/
[8] https://github.com/nayafia/contributing-template
[9] https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors
[10] https://docs.github.com/github-ae@latest/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors
[11] https://github.com/jessesquires/.github/blob/main/CONTRIBUTING.md
[12] https://contributing.md/how-to-build-contributing-md/
[13] https://gist.github.com/PurpleBooth/b24679402957c63ec426
[14] https://github.com/google/go-github/blob/master/CONTRIBUTING.md
[15] https://mozillascience.github.io/working-open-workshop/contributing/
[16] https://github.com/nayafia/contributing-template
[17] https://www.pyopensci.org/python-package-guide/documentation/repository-files/contributing-file.html
[18] https://www.youtube.com/watch?v=dLRA1lffWBw
[19] https://github.com/mntnr/awesome-contributing

