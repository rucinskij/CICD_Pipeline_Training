# CI/CD Pipeline Training

## Basic Setup

1. Fork the repo
2. Clone the repo: `git clone https://github.com/{username}/CICD_Pipeline_Training`
3. Create new branch to work on: `git checkout -b feature/pipeline`
4. Push this branch to the repo: `git push --set-upstream origin feature/pipeline`
5. Create new folder in the project: `.github` and then create folder: `workflows` in it

## Continous Integration

1. In `.github/workflows` create file `continous_integration.yaml`
2. Start by naming your new pipeline: `name: Your name of choice`
3. Determine when this pipeline should trigger: `on:...`
4. Create jobs which should be done in this pipeline: `jobs:...`

## Continous Delivery

1. In `.github/workflows` create file `continous_delivery.yaml`
2. Start by naming your new pipeline: `name: Your name of choice`
3. Determine when this pipeline should trigger: `on:...`
4. Create jobs which should be done in this pipeline: `jobs:...`