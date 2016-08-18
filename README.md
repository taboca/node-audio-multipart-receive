### Node

```sh
npm install
node index.js
```

And visit <http://localhost:3000/>.


## History of changes 

### Specific to my system, my fixes for Mac OS X (nvm was lost)

* Somehow after installing some bach_profile changes, I lost nvm 
* Had to fix based in https://github.com/creationix/nvm/issues/758 tips, specifically
* created a .bashrc
```
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh" # This loads nvm
```

And called it from .bash_profile
```
source ~/.bashrc
```
 
