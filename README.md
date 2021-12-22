# azure-devops-backup

This pipeline creates a backup of all repositories in an azure devops organization and uploads them to a storage account.

Requires a secret environment variable named "ACCESS_TOKEN" for the Personal Access Token for the Azure Devops organization and the azure subscription and storage account to backup the repos as zip.