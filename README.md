# pokerogue-coop-cdn

Publishes the co-op build of [SunghoLee98/pokerogue](https://github.com/SunghoLee98/pokerogue)
(branch `claude/festive-davinci-49n6ht`) to GitHub Pages:
https://sungholee98.github.io/pokerogue-coop-cdn/

The fork itself can't use Pages, so `.github/workflows/deploy.yml` checks out the
fork, builds it and deploys the result. Run it from the Actions tab
("Deploy Co-op Pages") after the fork changes.

`SOURCE_REF` holds the commit of the fork to build. Pushing a new commit id there
redeploys the site; a manual run can also take a branch or commit as input.
