Since July 2025, the DEDuino Connector app has been crashing on startup. I looked into the issue and found that the app tries to check for updates when it starts. Because the update URL is no longer available, it crashes. As a quick fix, I simply changed the URL to 127.0.0.1, which was enough to get the app running again.

I’ve also included a precompiled EXE file in the ZIP archive. You need all files inside the folder tor run the app! 

Works fine with Falcon BMS 4.38
