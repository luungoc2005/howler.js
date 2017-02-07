# Description

This is a fork of [Howlerjs](https://howlerjs.com/) for use with Electron.

Basically Howlerjs might not be able to make xhr requests to local files from Chromium - for security concerns.

This modification switches Nodejs's FileStream instead to buffer local files if it sees the "file:///" protocol.