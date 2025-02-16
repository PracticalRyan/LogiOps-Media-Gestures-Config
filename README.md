# LogiOps configuration with media gestures
A configuration file to illustrate how to create media gestures in LogiOps.
Tested on Fedora Linux 41, LogiOps v0.3.5
This configuration file was made using the information from the  [LogiOps Documentation](https://github.com/PixlOne/logiops/wiki/Configuration), [Input Events Codes](https://github.com/torvalds/linux/blob/master/include/uapi/linux/input-event-codes.h) additional sources

# Installation & Setup
1. **Install LogiOps** (For Fedora or RHEL, it's as simple as `sudo dnf install logiops`, Ubuntu can install using `apt`)
2. Place the logid.cfg file in the `/etc` directory, or modify the contents of `/etc/logid.cfg` so that it matches the file in the repo.
3. run `logid -v` to check if there are any errors. Depending on the permission level you may need to use `sudo`.
4. Done! You can use `sudo systemctl enable logid` to run the program on startup.
