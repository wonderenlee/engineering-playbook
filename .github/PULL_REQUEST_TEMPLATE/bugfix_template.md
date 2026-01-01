<!-- ⚠️ DELETE THIS ENTIRE SECTION BEFORE SUBMITTING THE PR ⚠️ -->

# Bugfix Branch PR Template

## Usage Instructions

### Checklist for Usage Instructions & Submission:

Before submitting this PR, please ensure:

1. [ ] **Add Reviewers**: At least **2 reviewers** have been added to this PR using the Reviewers panel. 

2. [ ] **Commit Squashing**: Ensure commits have been **squashed** before merging (or commits will be squashed during the merge process). 

3. **Verify that**:
   - [ ] Code passes linting checks (use `black`, `flake8`) with no error. 
   - [ ] Tests have been added for new features or bug fixes. 
   - [ ] Documentation (README, notebooks, etc.) is updated if applicable.

4. [ ] **Delete the Usage Instructions section** before submitting.

---
<!-- ⚠️ DELETE THIS ENTIRE SECTION BEFORE SUBMITTING THE PR ⚠️ -->

## Bugfix Summary

<!-- Briefly summarize the bugfix. 
Example:
   - Fixes incorrect handling of timemzones during datetime parsing.
-->


## Related Issues/Tickets

<!-- Add relevant links to Jira tickets or GitHub issues. 
Example:
   - Closes #123
   - Related to [PROJ-456](https://jira-url.com/browse/PROJ-456)
-->


## Steps to Reproduce

<!-- Provide steps to reproduce the bug. 
Example:
   1. Load a CSV file with timezone-aware datetime columns.
   2. Parse the datetime columns using `pd.to_datetime`.
   3. Observe incorrect timezone handling in the output.
-->

1. 
2. 
3. 

## Screenshots (if applicable) 

<!-- Add applicable screenshots: visualizations, tables, or graphs. Example:
   - Screenshot: ![Feature Screenshot](example-screenshot.png)
--> 


## Fix Implementation 

<!-- Describe the fix implemented to resolve the bug.
Example:
   - Updated datetime parsing logic to correctly handle timezone information using `dateutil` parser.
-->

<!-- TODO determine if this is a good place to add a note about the fix -->
## Quality Checklist

<!-- Ensure the following quality checks have been completed:
Example:
   - [ ] Bugfix tested on multiple datasets with timezone-aware datetime columns.
   - [ ] Added unit tests to cover the bugfix scenario.
   - [ ] Updated failing tests in 'test_datetime_parsing.py'. -->