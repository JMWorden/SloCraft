# Staff Introduction
GitHub and Admin access

## Cheat Sheets
- [git](pdfs/git_cheatsheet.pdf)
- [basic linux commands](pdfs/linux_cheatsheet.pdf)
- [mark down](https://www.markdownguide.org/cheat-sheet/) (what this document is written with -- reddit uses it  too)

## Accessing server
NOTE: These instructions will change when a more permemanet user hierarchy is establishe. And when more tools are added
### SSH
`ssh <user>@158.69.52.205`
- brings you into bash shell with `sudo` access
- password shared privately
- **this can be done without requiring a password. Ask @JMWorden for help setting this up.**
### FTP
can be done with SFTP
- `sftp <user>@158.69.52.205`
### Control Panel
TBA
### SoYouStart Admin Panel
[Login portal](https://ca.api.soyoustart.com/auth/?credentialToken=2CEPJyuFL18SREqZqCOXnJKjKwIopzSz36AHZWCEnvmhGadpU9JAmYbBcxwO3HT6)
- credentials supplied privately

## Administrating server
### Updating linux!
Very important to keep software up-to-date. In Linux, this is super simple and does not require closing applications/restarting the machine.
```
sudo apt update
sudo apt upgrade
``` 
- first command pulls information from package repositories, and second command actuallly  updates the packages. This is how basically all softtware is updated

### Installing software
Almost always, this can be done using a package manager. When in doubt, google "how do I installl X on ubuntu?"
```
sudo apt install <package-name>
```

#### Installing software without the package manager
This sometimes needs to be done. **Ask @JMWorden for assistance!**