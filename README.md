# docker-bitbucket-backup-client
Docker image for the Bitbucket Backup Client from Atlassian

## Introduction

This simply wraps the Bitbucket Backup Client from Atlassian in a Docker image.

Use `docker run -it --rm redmatter/docker-bitbucket-backup-client` to start a shell within the image, then see https://confluence.atlassian.com/bitbucketserver/using-the-bitbucket-server-backup-client-776640064.html for instructions on how to use the backup and restore clients.

## TODO
* Add more content and examples to README.md
* Add entrypoint script so that backups and restores can be run simply, without needing to execute the script from within the image
* Consider using build arguments to build different versions of the client
