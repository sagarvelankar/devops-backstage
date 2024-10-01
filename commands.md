# Create
npx @backstage/create-app@latest
devops-backstage

# Database
yarn --cwd packages/backend add pg

# Auth
yarn --cwd packages/backend add @backstage/plugin-auth-backend-module-github-provider

# Jenkins
yarn --cwd packages/app add @backstage-community/plugin-jenkins
yarn --cwd packages/backend add @backstage-community/plugin-jenkins-backend

