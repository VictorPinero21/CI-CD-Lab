<h1 align="center">CI-CD-Lab</h1>

<p align="center">
  My hands-on learning notes and labs from the
  <a href="https://kodekloud.com/learning-path/ci-cd/">KodeKloud CI/CD learning path</a>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-in%20progress-yellow?style=flat-square" alt="Status: in progress">
  <img src="https://img.shields.io/badge/path-KodeKloud%20CI%2FCD-blue?style=flat-square" alt="KodeKloud CI/CD">
  <img src="https://img.shields.io/github/last-commit/YOUR_USER/CI-CD-Lab?style=flat-square" alt="Last commit">
</p>

<div align="center">
  <table>
    <tr>
      <td align="center" width="160">
        <a href="https://git-scm.com/doc">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="Git" width="112" height="112">
        </a><br>
        <b>Git</b>
      </td>
      <td align="center" width="160">
        <a href="https://docs.github.com/actions">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/githubactions/githubactions-original.svg" alt="GitHub Actions" width="112" height="112">
        </a><br>
        <b>GitHub Actions</b>
      </td>
      <td align="center" width="160">
        <a href="https://www.jenkins.io/doc/">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jenkins/jenkins-original.svg" alt="Jenkins" width="112" height="112">
        </a><br>
        <b>Jenkins</b>
      </td>
    </tr>
    <tr>
      <td align="center" width="160">
        <a href="https://docs.aws.amazon.com/codepipeline/">
          <img src="https://raw.githubusercontent.com/weibeld/aws-icons-svg/main/q1-2022/Architecture-Service-Icons_01312022/Arch_Developer-Tools/64/Arch_AWS-CodePipeline_64.svg" alt="AWS CodePipeline" width="112" height="112">
        </a><br>
        <b>AWS CodePipeline</b>
      </td>
      <td align="center" width="160">
        <a href="https://argo-cd.readthedocs.io/">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/argocd/argocd-original.svg" alt="ArgoCD" width="112" height="112">
        </a><br>
        <b>ArgoCD</b>
      </td>
      <td align="center" width="160">
        <a href="https://fluxcd.io/flux/">
          <img src="https://raw.githubusercontent.com/cncf/artwork/main/projects/flux/icon/color/flux-icon-color.svg" alt="FluxCD" width="112" height="112">
        </a><br>
        <b>FluxCD</b>
      </td>
    </tr>
  </table>
</div>

---

## 🎯 Goal

Learn CI/CD by doing: every topic gets its own folder with notes, configuration files and a small lab I can reproduce from scratch.

## 🗺️ Roadmap

| # | Topic | Focus | Status |
|---|-------|-------|--------|
| 1 | [Git](./01-git) | Branching, merging, rebasing, workflows | 🟡 In progress |
| 2 | [GitHub Actions](./02-github-actions) | Workflows, runners, secrets, reusable actions | ⬜ Pending |
| 3 | [Jenkins](./03-jenkins) | Pipelines, Jenkinsfile, agents, plugins | ⬜ Pending |
| 4 | [AWS CodePipeline](./04-aws-codepipeline) | CodeBuild, CodeDeploy, stages and approvals | ⬜ Pending |
| 5 | [ArgoCD](./05-argocd) | GitOps, applications, sync policies | ⬜ Pending |
| 6 | [FluxCD](./06-fluxcd) | GitOps toolkit, kustomizations, image automation | ⬜ Pending |

> Legend: ✅ Done · 🟡 In progress · ⬜ Pending

## 📁 Repository structure

```text
CI-CD-Lab/
├── 01-git/
├── 02-github-actions/
├── 03-jenkins/
├── 04-aws-codepipeline/
├── 05-argocd/
├── 06-fluxcd/
└── README.md
```

Each folder follows the same layout: a `README.md` with the notes, plus the files needed to run the lab.

## 🚀 How to use this repo

```bash
git clone https://github.com/YOUR_USER/CI-CD-Lab.git
cd CI-CD-Lab
```

Then open the folder of the topic you want and follow its `README.md`.

## 📚 Resources

- [KodeKloud CI/CD learning path](https://kodekloud.com/learning-path/ci-cd/)
- [Pro Git book](https://git-scm.com/book)
- [GitHub Actions docs](https://docs.github.com/actions)
- [Jenkins docs](https://www.jenkins.io/doc/)
- [AWS CodePipeline docs](https://docs.aws.amazon.com/codepipeline/)
- [Argo CD docs](https://argo-cd.readthedocs.io/)
- [Flux docs](https://fluxcd.io/flux/)

---

<p align="center"><i>Learning in public, one pipeline at a time.</i></p>
