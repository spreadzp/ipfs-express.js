## Simple Express.js app with ipfs

### Install dependencies
You can use typical commands
```
  yarn 
or
  npm i
 ```
Or download from IPFS last  dependencies to fill node_modules folder
``` 
    npm run ipfs-to-nm 
```
for using this command need to install globally
```
    npm i ipfs-nm
```
and IPFS to see how to install for your OS, follow the link [IPFS](https://docs.ipfs.io/install/command-line/#system-requirements) 
IPFS daemon have to run in background
```
 sudo ipfs daemon &
```
## Start app
```
npm start
```

## If was changed packages in node modules during your development
Before pushing to your repository we can use the command 
```
    ipfs-nm upload
```