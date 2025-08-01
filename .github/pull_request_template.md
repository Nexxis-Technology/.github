<!--
Nexxis PR Template
Use this template for all pull requests: features, bugfixes, refactors, tech debt, etc.
Please remove or skip any sections that are not relevant to your PR.
-->

# Overview
<!-- Briefly describe the purpose of this PR. Aim for 2–3 sentences. -->
E.g., Implements X feature to support Y requirement; resolves bug Z found during integration testing.

# Type(s) of Change
<!-- Uncomment the most relevant type(s) for this PR. -->
<!-- - 🚀 Feature -->
<!-- - 🐞 Bugfix -->
<!-- - ♻️ Refactor / Code Cleanup -->
<!-- - 📈 Tech Debt Reduction -->
<!-- - 📄 Documentation -->
<!-- - ⚙️ Infrastructure / Build System -->

# Description of Changes
<!-- Describe what was changed and why. Use bullet points if helpful. -->
- Added ...
- Refactored ...
- Removed ...

# Testing
<!-- Describe what testing you have done and how someone else can reproduce it. -->
- Tested using [simulator/hardware version/etc.].
- Verified integration with [module/tool/hardware].

**Special notes for reviewers:**  
E.g., Requires [hardware setup] or [ROS2 bridge] running.

# Documentation
## Testing Documentation
<!-- If **Yes**, please provide a link and summarize the changes. -->
**Does this change require new or updated testing documentation?** [Yes/No]  
<!-- [Testing Documentation Link]() -->

**Changes to testing documentation:**
- ...
- ...

## LDR Documentation
<!-- Nexxis LDR repo (private): https://github.com/Nexxis-Technology/LDR -->

### LADR
<!-- If **Yes**, please provide a link to the decision document. -->
**Does this change require a LADR?** [Yes/No]  
<!-- [LADR Link]() -->

### LDDR
<!-- If **Yes**, please provide a link to the decision document. -->
**Does this change require a LDDR?** [Yes/No]  
<!-- [LDDR Link]() -->


# Additional Context (Optional)
<!-- Add any background, edge cases, or related PRs/issues that might help reviewers. -->


# PR Checklist

## Developer Submission Checklist
<!-- Please check off items you've completed before submitting. -->
- [ ] Code builds and passes local/unit tests on your development system
- [ ] Code conforms to repository linting and formatting standards
- [ ] Relevant documentation is updated (e.g., Testing Docs, LADR)

## Reviewer Merge Checklist
<!-- Reviewers, please check off items you've completed before merging. -->
- [ ] Code has been reviewed and all comments have been addressed *
- [ ] Testing documentation has been reviewed (or confirmed not needed)
- [ ] LDR documentation (ADR & DDR) has been reviewed (or confirmed not needed)
- [ ] A review comment has been added outlining what was done, such as:
    - Code review performed
    - Code built locally
    - Code tested on a developer machine or test hardware

> \* GitHub branch protection rules should enforce this before merge.



