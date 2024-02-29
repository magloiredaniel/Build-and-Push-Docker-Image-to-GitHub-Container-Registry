# Build and Publish Docker Image to gHCR | Scan with Trivy, a Vulnerability Scanner in GitHub Actions

In this workflow, i will describe how to use GitHub Actions to build a **docker image, publish/push the docker image to github container registry**, and **scan the publish image for vulnerabilities with trivy image scan tool**

## Architecture

![architecture](/images/architecture.png)

## Login to github Container Registry ()

We going to see in the official page on **ghcr.io**, clic [HERE](https://docs.github.com/fr/packages/working-with-a-github-packages-registry/working-with-the-container-registry#authentification-avec-un-personal-access-token-classic)

## Creation a Personal ACCESS TOKEN

**Profil** + **Settings** + **Developer settings** + **Personal access token** + **Tokens (classic)** + **Generate new token** + **Generate new token (classic)** + **Note**, write the name of your new token + **MyToken** + **Select scopes** + **Generate token**.


## Personal Access Token

