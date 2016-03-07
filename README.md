# Remove insecure server response headers site extension for Azure

Once installed, the following response headers are removed from all responses
* Server
* X-Powered-By
* X-AspNet-Version

(you may need to stop and start the web app to get it to pick up the applicaitonhost.config changes)
