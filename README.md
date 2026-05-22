# Parrot OS Docker Lab

Reproducible Parrot OS-based security lab container for controlled learning, tooling, and CI-friendly experimentation.

## Overview

This repository packages a Parrot OS environment with commonly used security and diagnostics tools. The goal is repeatability: a clean lab container that can be rebuilt, tested, and extended without depending on a fragile local workstation setup.

## What This Demonstrates

- Docker image design for repeatable development environments
- GitHub Actions CI/CD for container builds
- Security-lab tooling organization
- Infrastructure documentation and setup hygiene

## What I Learned

- How to make a technical learning environment reproducible instead of depending on a fragile personal machine setup.
- How Docker and CI/CD can make experimentation cleaner, safer, and easier to share.
- How to describe security tooling responsibly, with clear boundaries around authorized use.

## Recruiter Takeaway

This project shows technical curiosity with operational discipline. I like learning powerful tools, but I also care about safe usage, documentation, repeatability, and the kind of structure that helps other people trust the work.

## Intended Use

Use this project only in authorized lab, training, and defensive research contexts. It is not intended for unauthorized access, exploitation, or misuse.

## Tech Stack

- Docker
- Parrot OS
- GitHub Actions
- Shell tooling

## Getting Started

```bash
docker build -t parrot-os-lab .
docker run --rm -it parrot-os-lab
```

Review the Dockerfile before extending the tool list so the image stays understandable and reproducible.

## Status

Maintained as a portfolio and lab-infrastructure project. Future improvements should add a tool manifest, usage examples, and CI badge documentation.
