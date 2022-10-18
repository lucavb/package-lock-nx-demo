# package-lock-nx-demo
A demo project to show case the problem nx has with package-lock@v3

# Steps to reproduce

* Run `npm i`
* Make sure that the `package-lock.json` file is version 3
* Run `npx nx build my-nest-app`
* See the error ` NX   Cannot convert undefined or null to object` 
