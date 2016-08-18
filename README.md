### Node

```sh
npm install
node index.js
```

## Testing

Visit <http://localhost:3000/>.

You can test using the served HTML, which is served inline from the node app. But of course, the idea is that you will be uploading data from another system, such as your Android app. 


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
 
