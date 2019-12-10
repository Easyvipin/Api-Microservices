# Managing Packages with Npm
> What is a Package.json?
Package is centerliaze file of Node.js Project,which contain all the information about your project,including Name,Author,Dependancies structured by "key" : "value" pairs.

> Main keys in Package.json file
1. description
`"description":"This is a npm Package" `
2. keyword
`"keyword":"["effcient","reliable"] " `
3. license
`"license":"MIT"`
4. dependencies
`"dependencies":{
"package":"1.0.0"
}`
### version of Package ( Semantic Versioning)
 `1.0.1 `
 1. Major (1) This increment when there's a API change.
 2. Minor (0) This increment when a functionality is added at backward.
 1. Patch (1) This increment when a bug is fixed.
 
 > Whenever we run a project ,npm package check the dependencies and install the latest version of dependencies.

