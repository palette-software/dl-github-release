Github Release Downloader for Private Repositories

This package is designed to use with CI tools so that they can download the latest release of a private project. For the program to work you will need a personal access token for a user who has rights to download releases from the given project.

To get the acces token go to (Github)[https://github.com/settings/tokens/new] and create the token with the repo root permission checked in. 

Usage:

dl-github-release <owner> <repository> <token>

This will download the binaries of the latest release to the working directory.
