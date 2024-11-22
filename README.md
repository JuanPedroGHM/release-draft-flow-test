# Release branching workflow

1) To start a release, create a new branch named 'pre-release/x.y.z' (Using the automated action from Claudia)

2) Create a 2 PRs merging 'pre-release/x.y.z' into 'release' and 'main'

3) Test, fix bugs and do any release preparation in 'pre-release/x.y.z'

4) Once ready, merge 'pre-release/x.y.z' into 'release' and 'main'

5) Done (or fix any issues that might have happend)