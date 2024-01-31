---
permalink: /contributions/
title: "Contributions"
toc: true

---

This page is dedicated to the open source projects I have contributed to during my studies and professional career.

## [XWiki Helm](https://github.com/xwiki-contrib/xwiki-helm/)

<a href="https://github.com/xwiki-contrib/xwiki-helm/network/members">
  <img src="https://img.shields.io/github/forks/xwiki-contrib/xwiki-helm?style=flat" alt="forks" />
</a>
<a href="https://github.com/xwiki-contrib/xwiki-helm/">
  <img src="https://img.shields.io/github/stars/xwiki-contrib/xwiki-helm?style=flat" alt="stars" />
</a>
<a href="https://github.com/xwiki-contrib/xwiki-helm/graphs/contributors">
  <img src="https://img.shields.io/github/contributors/xwiki-contrib/xwiki-helm" alt="contributors" />
</a>

XWiki is a powerful Open Source wiki platform allowing companies of all sizes to save time and money while enhancing collaboration on both team and organizational level.
Xwiki Helm is the official repository for the Helm charts of XWiki. I contributed to this project during my internship at XWiki SAS. 

### Key facts

- State of the project : deployed
- Community : active
- Stack : Helm, Kubernetes, Docker

### Contributions

- Integrate The Bitnami Solr Helm chart to the XWiki Helm chart
- Improve the CI/CD of the project with e2e tests and a release workflow
- Improve the documentation of the project


## [Cryptpad Helm Chart](https://github.com/cryptpad/Helm/)
<a href="https://github.com/cryptpad/Helm/network/members">
  <img src="https://img.shields.io/github/forks/cryptpad/Helm?style=flat" alt="forks" />
</a>
<a href="https://github.com/cryptpad/Helm/">
  <img src="https://img.shields.io/github/stars/cryptpad/Helm?style=flat" alt="stars" />
</a>
<a href="https://github.com/cryptpad/Helm/graphs/contributors">
  <img src="https://img.shields.io/github/contributors/cryptpad/Helm" alt="contributors" />
</a>

Cryptpad is a private-by-design alternative to popular office tools and cloud services. This repository contains the Helm chart for Cryptpad. I contributed to this project during my internship at XWiki SAS.

### Key facts

- State of the project : deployed
- Community : active
- Stack : Helm, Kubernetes, Docker

### Contributions

- Migrate the project from Gitlab to Github
- Add CI/CD workflows to the project
- Improve the documentation of the project

## [Aster](https://github.com/aster-do/aster)

<a href="https://github.com/aster-do/aster/network/members">
  <img src="https://img.shields.io/github/forks/aster-do/aster?style=flat" alt="forks" />
</a>
<a href="https://github.com/aster-do/aster">
  <img src="https://img.shields.io/github/stars/aster-do/aster?style=flat" alt="stars" />
</a>
<a href="https://github.com/aster-do/aster/graphs/contributors">
  <img src="https://img.shields.io/github/contributors/aster-do/aster" alt="contributors" />
</a>

Aster is a metrics collector that can be used to charge customers based on these metrics, it also includes a dashboard to configure how the user is billed based on the different metrics and explore the metrics data.

### Key facts

- State of the project : not deployed
- Community : inactive
- Stack : Rust, Axum, Typescript, React.js

### Contributions

- Create the Billing API in Rust with Axum
- Create the Frontend Dashboard for the Billing configuration

## [R2Devops Hub](https://gitlab.com/r2devops/hub)

<a href="https://gitlab.com/r2devops/hub/-/project_members">
  <img src="https://img.shields.io/gitlab/forks/r2devops/hub?style=flat" alt="forks" />
</a>
<a href="https://gitlab.com/r2devops/hub">
  <img src="https://img.shields.io/gitlab/stars/r2devops/hub?style=flat" alt="stars" />
</a>
<a href="https://gitlab.com/r2devops/hub/graphs/contributors">
  <img src="https://img.shields.io/gitlab/contributors/r2devops/hub" alt="contributors" />
</a>

R2Devops is a platform aims to make CI/CD easier for developers. It provides designed templates to help developers to build, test and deploy their applications. The Hub is the main component of the platform, it is a GitLab repository that contains the community templates validated by the R2Devops team.
I worked on this project during my 2 years internship at R2Devops.

### Key facts

- State of the project : deployed
- Community : active
- Stack : GitLab, Docker

### Contributions

- Creation and update of most all the templates
- Continuous amelioration of the CI/CD of the project


## [Template Picker](https://gitlab.com/r2devops/template-picker/)

<a href="https://gitlab.com/r2devops/template-picker">
  <img src="https://img.shields.io/gitlab/stars/r2devops/template-picker?style=flat" alt="stars" />
</a>
<a href="https://gitlab.com/r2devops/template-picker/graphs/contributors">
  <img src="https://img.shields.io/gitlab/contributors/r2devops/template-picker" alt="contributors" />
</a>
<a href="https://marketplace.visualstudio.com/items?itemName=r2devops.template-picker-extension">
  <img src="https://img.shields.io/visual-studio-marketplace/d/r2devops.template-picker-extension
" alt="vscode downloads" />
</a>

Template Picker is a Visual Studio Code extension that allows to search and insert templates from the R2Devops Hub directly in the IDE. It is a very useful tool for developers that want to use the R2Devops templates in their projects.

I developped this extension during my last year's internship at R2Devops.

## [Sarif-Codeclimate](https://github.com/GridexX/sarif-codeclimate)

<a href="https://github.com/GridexX/sarif-codeclimate/network/members">
  <img src="https://img.shields.io/github/forks/GridexX/sarif-codeclimate?style=flat" alt="forks" />
</a>
<a href="https://github.com/GridexX/sarif-codeclimate">
  <img src="https://img.shields.io/github/stars/GridexX/sarif-codeclimate?style=flat" alt="stars" />
</a>
<a href="https://www.npmjs.com/package/sarif-codeclimate">
  <img src="https://img.shields.io/npm/dw/sarif-codeclimate" alt="npm downloads" />
</a>

This NPM package allows to display the linting errors from Megalinter on a GitLab Merge Request.

One of the most used templates of the R2Devops platform is Megalinter. It is a linter that can be used to check the quality of a project. One feature of Megalinter is to generate a SARIF file that contains the result of the linter.
GitLab has a feature that allows to display the result of a linter on a Merge Request, but it only supports the CodeClimate format. This package was created to convert the result of a Megalinter run in SARIF into to CodeClimate compatible format.  

I developed this package during my last year of internship at R2Devops. This package is used by the R2Devops community. It was made like an open-source project, with a public repository and a public NPM package and contains all resources needed to use it.