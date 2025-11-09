# Matrix Build Demo

This repository demonstrates GitHub Actions matrix builds with artifact management.

## Contact
**Email:** dhatchayanim06@gmail.com

## Workflow Details

This project uses GitHub Actions to build across multiple Node.js versions:
- Node.js 14 (LTS Fermium)
- Node.js 16 (LTS Gallium)
- Node.js 18 (LTS Hydrogen)
- Node.js 20 (Current)

## Artifacts

Each build produces artifacts with the naming pattern:
- `build-60a4b7a-node14`
- `build-60a4b7a-node16`
- `build-60a4b7a-node18`
- `build-60a4b7a-node20`

## Matrix Strategy

The workflow uses a matrix strategy to run builds in parallel across different Node.js versions, demonstrating efficient CI/CD practices for multi-version testing and deployment.

## Required Identifiers

- Step identifier: `matrix-60a4b7a`
- Artifact prefix: `build-60a4b7a-`

## How to Trigger

The workflow runs on:
- Push to main/master branch
- Pull requests
- Manual workflow dispatch (Actions tab)