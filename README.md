# JP's i3 config
## Preliminary Step

*If you have already installed i3, ***and don't care about your current config***, remove the config before proceeding*
```
sudo rm -r ~/.config/i3
```

## Set up




Clone repo and change directories
```
cd ~/.config && git clone https://github.com/jamespilcher/i3 && cd i3
```
Enable executable permissions on the installer
```
sudo chmod +x installer.sh
```
Run [the installer](https://github.com/jamespilcher/i3/blob/main/installer.sh) which will install i3, any packages used by the custom scripts, and update permissions of said scripts.

```
./installer.sh
```


Log out of current session, and select "i3" as your window manager on the login screen.

That's all!
# Usage
- Configure keybindings in `config` file
- Create custom scripts in `/custom_scripts`
- After creating new scripts, run `installer.sh` to update permissions of scripts
