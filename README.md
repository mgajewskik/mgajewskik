# Maciej Gajewski

Platform engineer based in Poland. At work I build and run Kubernetes platforms on AWS and on-prem. Outside work I
build the projects below.

CKA, CKAD, and AWS Certified Solutions Architect – Associate.

## What I'm working on

- **A private EKS reference platform.** The VPC, bastion, and CI checks are done. Next come EKS, Argo CD, Karpenter,
  and Istio.
- **Agent skills for AI-assisted engineering.** Instructions that make coding agents check their work, keep diffs
  small, and log every live change together with its revert.
- **A homelab.** Early days.

## Projects

### [aws-eks-platform](https://github.com/mgajewskik/aws-eks-platform)

A reference architecture for a private, disposable Amazon EKS platform. Terraform owns the AWS foundation, GitOps owns
cluster state, and every design decision is recorded as an ADR. I deploy it from my laptop and destroy it between
sessions to keep costs down.

### [dotfiles](https://github.com/mgajewskik/dotfiles)

My shell, editor, terminal, and Sway desktop, managed with chezmoi. One command sets up a desktop, a server, or a
container, and mise installs every tool at a version pinned in a lockfile.

### [skills](https://github.com/mgajewskik/skills)

Reusable skills shared across my coding agents. The main one, `work`, is a discipline for code, config, and
infrastructure tasks: playbooks, engineering principles, and a log of live changes and how to revert them.

## Tools I use

Kubernetes · AWS · Terraform · Ansible · Argo CD · Istio · Python · Go · Linux · Neovim · chezmoi · mise

## Find me

[LinkedIn](https://www.linkedin.com/in/mgajewskik/)
