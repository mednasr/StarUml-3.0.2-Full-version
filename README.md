# StarUml-3.0.2-Full-version 
Get starUml full version

**StarUML 3.0.2** 
**Windows 10** 


- 1- install staruml. : [staruml](http://staruml.io/)
- 2- install node.js  : [node.js](https://nodejs.org/en/download/)
- 3- go to C:\Program Files\StarUML\resources
- 4- open CMD As admin
- 5- execute 

`npm install -g asar`
`asar extract app.asar app`


- 6- an app file is going to be created in resources folder 
- 7-   go to app\src\engine\license-manager.js
- 8- update file with Notepad

  
  
```
  checkLicenseValidity () {
    this.validate().then(() => {
      setStatus(this, true)
    }, () => {
      setStatus(this, true)
    })
  }
```
 

-   9- go back to CMD and execute 

  `asar pack app app.asar`
  
  
  
  
  its done enjoy
