# https://github.com/immunefi-team/Web3-Security-Library/tree/main/Tools#visualization-tools
## npm installs on my kali:
```bash
sudo npm install -g {PACKAGE_NAME} --unsafe-perm=true --allow-root
# surya example
# sudo npm install -g surya --unsafe-perm=true --allow-root
```

## surya
- https://github.com/ConsenSys/surya
- NO NEED TO INSTALL SINCE `SOLIDITY VISUAL DEVELOPER` VSCODE EXTENTION FORKS THIS

## SOL2UML
- https://github.com/naddison36/sol2uml


## solgraph
- https://github.com/raineorshine/solgraph
- simple and minimal
- better than solidity metrics call graph
- interactive
```bash
solgraph /path/to/file.sol > previewMe.dot
```
then 
```
xdg-open previewMe.dot
```
