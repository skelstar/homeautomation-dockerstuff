## Setup
- Use DietPi: https://dietpi.com/docs/install/

**NOTE: for when you're plugged into the ethernet port on the router**

- Mac address: `B8:27:EB:53:DC:E0` (found automatically on startup)
- Booted...
- Installed:
  - Git
  - Docker
  - `dietpi-launcher` to add drives
  - Added usb with launcher (named "cruzer")
  - (In `cruzer`) `git clone https://github.com/skelstar/homeautomation-dockerstuff.git`
 
## Issues
### Node-red
> Error: EACCES: permission denied, copyfile '/usr/src/node-red/node_modules/node-red/settings.js' -> '/data/settings.js'
-  https://github.com/node-red/node-red-docker/issues/221#issuecomment-1565956535


## When disk space full because of `/overlay2` folders being full 
- run commands in this img
- ![image](https://github.com/skelstar/homeautomation-dockerstuff/assets/16521921/3089056b-1e5d-4459-9a9e-57809b7e2c1e)
