# testing-d2l-gh-actions

To test an action, the easiest option is to:

- create a branch (e.g. `action/some-action-name`)
- add the action code to .github/workflows/action-tester.yml, as a new job (and/or delete existing jobs)
- push the branch up
- trigger the action manually in the GH Actions tab, targeting the new branch

