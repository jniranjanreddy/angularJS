Installing AngularJS.
## https://www.kevinboosten.dev/how-to-use-angular-environment-files-in-your-azure-devops-multi-stage-yml-release-pipeline
## https://www.youtube.com/watch?v=9b9pLgaSQuI

## AD authentication - https://www.youtube.com/watch?v=vjpKYSmvRKQ&t=695s
```
curl -sL https://rpm.nodesource.com/setup_12.x | sudo -E bash -
sudo yum install nodejs
node --version
npm --version
npm install -g @angular/cli
ng new hello-angular
cd hello-angular
ng serve --host 192.168.9.100 --port 4200

```
## creating projects..
```
ng new hotelinventoryapp --createApplication=false

ng new hotelinventoryapp
```







```
[root@minikube01 ~]# npm install -g @angular/cli
npm WARN deprecated request@2.88.2: request has been deprecated, see https://github.com/request/request/issues/3142
npm WARN deprecated har-validator@5.1.5: this library is no longer supported
npm WARN deprecated uuid@3.4.0: Please upgrade  to version 7 or higher.  Older versions may use Math.random() in certain circumstances, which is known to be problematic.  See https://v8.dev/blog/math-random for details.
/usr/bin/ng -> /usr/lib/node_modules/@angular/cli/bin/ng

> @angular/cli@12.2.10 postinstall /usr/lib/node_modules/@angular/cli
> node ./bin/postinstall/script.js

? Would you like to share anonymous usage data with the Angular Team at Google under
Google’s Privacy Policy at https://policies.google.com/privacy? For more details and
how to change this setting, see https://angular.io/analytics. Yes
+ @angular/cli@12.2.10
added 236 packages from 183 contributors in 60.594s
[root@minikube01 ~]# ng --version

     _                      _                 ____ _     ___
    / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
   / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
  / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
 /_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
                |___/


Angular CLI: 12.2.10
Node: 14.18.1
Package Manager: npm 6.14.15
OS: linux x64

Angular:
...

Package                      Version
------------------------------------------------------
@angular-devkit/architect    0.1202.10 (cli-only)
@angular-devkit/core         12.2.10 (cli-only)
@angular-devkit/schematics   12.2.10 (cli-only)
@schematics/angular          12.2.10 (cli-only)

```
```
[root@minikube01 ~]# ng new hello-angular
? Would you like to add Angular routing? No
? Which stylesheet format would you like to use? CSS
✔ Packages installed successfully.
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
    Successfully initialized git.
Nothing to be done.
```
```

[root@minikube01 hello-angular]# ng serve --host 192.168.9.100 --port 4200
Warning: This is a simple server for use in testing or debugging Angular applications
locally. It hasn't been reviewed for security issues.

Binding this server to an open connection can result in compromising your application or
computer. Using a different host than the one passed to the "--host" flag might result in
websocket connection issues. You might need to use "--disable-host-check" if that's the
case.
⠋ Generating browser application bundles (phase: setup)...Compiling @angular/core : es2015 as esm2015
Compiling @angular/common : es2015 as esm2015
Compiling @angular/platform-browser : es2015 as esm2015
Compiling @angular/platform-browser-dynamic : es2015 as esm2015
✔ Browser application bundle generation complete.

Initial Chunk Files | Names         |      Size
vendor.js           | vendor        |   2.09 MB
polyfills.js        | polyfills     | 128.51 kB
main.js             | main          |  54.67 kB
runtime.js          | runtime       |   6.63 kB
styles.css          | styles        | 736 bytes

                    | Initial Total |   2.27 MB

Build at: 2021-10-18T13:30:05.512Z - Hash: 80d5e6c8940cf14122ed - Time: 48832ms

** Angular Live Development Server is listening on 192.168.9.100:4200, open your browser on http://192.168.9.100:4200/ **


✔ Compiled successfully.
✔ Browser application bundle generation complete.

5 unchanged chunks

Build at: 2021-10-18T13:30:09.282Z - Hash: a58064426aa184f6ab73 - Time: 2807ms

✔ Compiled successfully.
```
## Modules
```
Karma - Karma is a JavaScript test runner that is used to test Angular applications
Jasmine - Jasmine is a free as well as an open-source Behavior Driven Development (BDD) framework that tests JavaScript code and also goes well with Karma

```
