# youtube-creator-control
Content creators currently need to share credentials to their youtube channels in order for any employees (editors or collaborators) to make a post to the channel.
As a work around, editors instead need to send the completed video files over to the channel owner. The owner then has to download the video, and then upload it to youtube.

This application aims to simplify the collaboration process between channel owners and their editors. Owners are able to create an account and authenticate with their youtube channel.
Their editors also create an account, and the owners invite them to be a collaborator. Editors are then able to upload video files to a space where the owner can review the content and
if ready for publishing, the onwer can choose to publish the video to youtube directly instead of needing to download and reupload the file.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## Running the App
1. Run docker container to create containerized postgres db.
```bash
docker compose up 
```
2. Run go application
```bash
make run
```

## Makefile
Check out the make file for additional available commands
