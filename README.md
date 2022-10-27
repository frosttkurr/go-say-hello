# Learn how to make modules with different kind of version

**1. Do not forget to use this line of code**
```
go mod init <module_repository_url>
```
Example:
```
go mod init github.com/frosttkurr/go-say-hello
```
**2. Before you want to commit the modules to GitHub, make sure use tag**
```
git tag <version_number>
git push origin <version_number>
```
Example: 
```
git tag v1.0.0
git push origin v1.0.0
```
**3. You can increase version number if there's an upgrade**
Example:
```
v1.0.1 # if it's minor upgrade
v2.0.0 # if it's major upgrade
```
***And don't forget to update the modules name too***

Example:
```
module github.com/frosttkurr/go-say-hello/v2 # for version >= v2.0.0
```
