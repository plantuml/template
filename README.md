# template
Template repository used to create new repository

# Github content

```tree
.github/
├── ISSUE_TEMPLATE
│   ├── bug_report.md
│   ├── documentation_request.md
│   └── feature_request.md
└── workflows
    └── add-triage-label.yml
```

## Templates

### Issues templates

- [bug_report.md](./github/ISSUE_TEMPLATE/bug_report.md)
- [documentation_request.md](./github/ISSUE_TEMPLATE/documentation_request.md)
- [feature_request.md](./github/ISSUE_TEMPLATE/feature_request.md)

## Workflows

### Issue triage label

[add-triage-label.yml](.github/workflows/add-triage-label.yml) is used to add `triage` label on opened or reopened issues.

Contributors can use the `triage`label to filter new issues.
The idea is to remove the `triage` label and adding some label like `enhancement` for a feature request, `bug` for a regression, or `discussion`to transform the issue in a discussion. In the future we might use also milestones.

## Labels

```
#gh label list

bug               Something isn't working                     #d73a4a
documentation     Improvements or additions to documentation  #0075ca
duplicate         This issue or pull request already exists   #cfd3d7
enhancement       New feature or request                      #a2eeef
good first issue  Good for newcomers                          #7057ff
help wanted       Extra attention is needed                   #008672
invalid           This doesn't seem right                     #e4e669
question          Further information is requested            #d876e3
wontfix           This will not be worked on                  #ffffff
```