# serra-de-aire.github.io
Landing page for serra de aire products showcase such as wisdom champion 
 
## How is this built? 
Static website generator framework [Hugo](https://gohugo.io/) with [Blowfish](https://blowfish.page/) theme

## How as this probably build from scratch?
### 1. Blowfish theme tutorial @ [Hugo website](https://themes.gohugo.io/themes/blowfish/#installation)
    
    npm i -g blowfish-tools
    blowfish-tools  
    blowfish-tools new mynewsite  

    OR

    git init
    git submodule add -b main https://github.com/nunocoracao/blowfish.git themes/blowfish

    OR

    hugo mod init github.com/<username>/<repo-name>

OR

### 2. [Blowfish](https://blowfish.page/) website script
    npx blowfish-tools

## Issues
**André**
1. could not load or get the git submodule to work/update
2. regenerating the site breaks changes such as hostname (eg. `npx blowfish-tools` -> Enter full configuration mode (all options) -> Site's title)