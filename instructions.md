---
editor_options: 
  markdown: 
    wrap: 72
---

1.  make github repo for R script

2.  RStudio \> New Project from git

3.  create personal access token for that guithib repo

-   Profile \> Settings \> Developer Settings (bottom left)

-   Personal access tokens

-   fine-grained tokens \> Generate new Token

-   name

-   [x] only selected repositories

-   Repository Permissions allow Content read/write

-   Generate Token

-   copy token into .git/config

```
    [remote "origin"]

        url =
        https://GITHUB_USERNAME:TOKEN\@github.com/REPOPATH/RProjectWithGithub.git
```

4. use git panel in RStudio