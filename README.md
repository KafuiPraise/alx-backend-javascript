Last login: Wed Jan 24 03:36:32 on console

The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
Matildas-MacBook-Pro:~ matilda$ vagrant up
==> vagrant: A new version of Vagrant is available: 2.4.1 (installed version: 2.4.0)!
==> vagrant: To upgrade visit: https://www.vagrantup.com/downloads.html

Bringing machine 'default' up with 'virtualbox' provider...
==> default: Checking if box 'ubuntu/focal64' version '20230731.0.0' is up to date...
==> default: Resuming suspended VM...
==> default: Booting VM...
==> default: Waiting for machine to boot. This may take a few minutes...
    default: SSH address: 127.0.0.1:2222
    default: SSH username: vagrant
    default: SSH auth method: private key
==> default: Machine booted and ready!
==> default: Machine already provisioned. Run `vagrant provision` or use the `--provision`
==> default: flag to force provisioning. Provisioners marked to run always will still run.
Matildas-MacBook-Pro:~ matilda$ ssh vagrant
ssh: Could not resolve hostname vagrant: nodename nor servname provided, or not known
Matildas-MacBook-Pro:~ matilda$ vagrant ssh
Welcome to Ubuntu 20.04.6 LTS (GNU/Linux 5.4.0-169-generic x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

  System information as of Mon Feb  5 14:46:49 UTC 2024

  System load:  0.0               Processes:               116
  Usage of /:   7.6% of 38.70GB   Users logged in:         0
  Memory usage: 21%               IPv4 address for enp0s3: 10.0.2.15
  Swap usage:   0%


Expanded Security Maintenance for Applications is not enabled.

29 updates can be applied immediately.
6 of these updates are standard security updates.
To see these additional updates run: apt list --upgradable

Enable ESM Apps to receive additional future security updates.
See https://ubuntu.com/esm or run: sudo pro status


The list of available updates is more than a week old.
To check for new updates run: sudo apt update
New release '22.04.3 LTS' available.
Run 'do-release-upgrade' to upgrade to it.


Last login: Wed Jan 17 13:45:34 2024 from 10.0.2.2
vagrant@ubuntu-focal:~$ ls
ALX_Projects     alx-system_engineering-devops  matilda_keys.pub  web_02
AfriSky-Weather  matilda_keys                   web_01            web_03
vagrant@ubuntu-focal:~$ curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
vagrant@ubuntu-focal:~$ sudo bash nodesource_setup.sh

================================================================================
================================================================================

                              DEPRECATION WARNING                            

  Node.js 12.x is no longer actively supported!

  You will not receive security or critical stability updates for this version.

  You should migrate to a supported version of Node.js as soon as possible.
  Use the installation script that corresponds to the version of Node.js you
  wish to install. e.g.

   * https://deb.nodesource.com/setup_16.x — Node.js 16 "Gallium"
   * https://deb.nodesource.com/setup_18.x — Node.js 18 LTS "Hydrogen" (recommended)
   * https://deb.nodesource.com/setup_19.x — Node.js 19 "Nineteen"
   * https://deb.nodesource.com/setup_20.x — Node.js 20 "Iron" (current)

  Please see https://github.com/nodejs/Release for details about which
  version may be appropriate for you.

  The NodeSource Node.js distributions repository contains
  information both about supported versions of Node.js and supported Linux
  distributions. To learn more about usage, see the repository:
    https://github.com/nodesource/distributions

================================================================================
================================================================================

Continuing in 20 seconds ...


================================================================================
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
================================================================================

                           SCRIPT DEPRECATION WARNING                    

  
  This script, located at https://deb.nodesource.com/setup_X, used to
  install Node.js is deprecated now and will eventually be made inactive.

  Please visit the NodeSource distributions Github and follow the
  instructions to migrate your repo.
  https://github.com/nodesource/distributions

  The NodeSource Node.js Linux distributions GitHub repository contains
  information about which versions of Node.js and which Linux distributions
  are supported and how to install it.
  https://github.com/nodesource/distributions


                          SCRIPT DEPRECATION WARNING

================================================================================
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
================================================================================

TO AVOID THIS WAIT MIGRATE THE SCRIPT
Continuing in 60 seconds (press Ctrl-C to abort) ...


## Installing the NodeSource Node.js 12.x repo...


## Populating apt-get cache...

+ apt-get update
Get:1 http://security.ubuntu.com/ubuntu focal-security InRelease [114 kB]
Hit:2 http://archive.ubuntu.com/ubuntu focal InRelease
Get:3 http://archive.ubuntu.com/ubuntu focal-updates InRelease [114 kB]
Get:4 http://security.ubuntu.com/ubuntu focal-security/main amd64 Packages [2679 kB]
Hit:5 http://archive.ubuntu.com/ubuntu focal-backports InRelease  
Get:6 http://archive.ubuntu.com/ubuntu focal-updates/main amd64 Packages [3058 kB]
Get:7 http://security.ubuntu.com/ubuntu focal-security/main Translation-en [410 kB]
Get:8 http://security.ubuntu.com/ubuntu focal-security/restricted amd64 Packages [2508 kB]    
Get:9 http://security.ubuntu.com/ubuntu focal-security/restricted Translation-en [349 kB]                  
Get:10 http://security.ubuntu.com/ubuntu focal-security/universe amd64 Packages [935 kB]                   
Get:11 http://archive.ubuntu.com/ubuntu focal-updates/main Translation-en [493 kB]                         
Get:12 http://security.ubuntu.com/ubuntu focal-security/universe Translation-en [197 kB]                   
Get:13 http://security.ubuntu.com/ubuntu focal-security/multiverse amd64 Packages [23.9 kB]                
Get:14 http://archive.ubuntu.com/ubuntu focal-updates/restricted amd64 Packages [2619 kB]                  
Get:15 http://archive.ubuntu.com/ubuntu focal-updates/restricted Translation-en [365 kB]                   
Get:16 http://archive.ubuntu.com/ubuntu focal-updates/universe amd64 Packages [1162 kB]                    
Get:17 http://archive.ubuntu.com/ubuntu focal-updates/universe Translation-en [279 kB]                     
Get:18 http://archive.ubuntu.com/ubuntu focal-updates/multiverse amd64 Packages [26.1 kB]                  
Fetched 15.3 MB in 19s (816 kB/s)                                                                          
Reading package lists... Done

## Confirming "focal" is supported...

+ curl -sLf -o /dev/null 'https://deb.nodesource.com/node_12.x/dists/focal/Release'

## Adding the NodeSource signing key to your keyring...

+ curl -s https://deb.nodesource.com/gpgkey/nodesource.gpg.key | gpg --dearmor | tee /usr/share/keyrings/nodesource.gpg >/dev/null

## Creating apt sources list file for the NodeSource Node.js 12.x repo...

+ echo 'deb [signed-by=/usr/share/keyrings/nodesource.gpg] https://deb.nodesource.com/node_12.x focal main' > /etc/apt/sources.list.d/nodesource.list
+ echo 'deb-src [signed-by=/usr/share/keyrings/nodesource.gpg] https://deb.nodesource.com/node_12.x focal main' >> /etc/apt/sources.list.d/nodesource.list

## Running `apt-get update` for you...

+ apt-get update
Get:1 https://deb.nodesource.com/node_12.x focal InRelease [4583 B]
Hit:2 http://archive.ubuntu.com/ubuntu focal InRelease                    
Hit:3 http://security.ubuntu.com/ubuntu focal-security InRelease    
Hit:4 http://archive.ubuntu.com/ubuntu focal-updates InRelease      
Get:5 https://deb.nodesource.com/node_12.x focal/main amd64 Packages [774 B]
Hit:6 http://archive.ubuntu.com/ubuntu focal-backports InRelease
Fetched 5357 B in 1s (4609 B/s)
Reading package lists... Done

## Run `sudo apt-get install -y nodejs` to install Node.js 12.x and npm
## You may also need development tools to build native addons:
     sudo apt-get install gcc g++ make
## To install the Yarn package manager, run:
     curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | gpg --dearmor | sudo tee /usr/share/keyrings/yarnkey.gpg >/dev/null
     echo "deb [signed-by=/usr/share/keyrings/yarnkey.gpg] https://dl.yarnpkg.com/debian stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
     sudo apt-get update && sudo apt-get install yarn


vagrant@ubuntu-focal:~$ sudo apt-get install -y nodejs
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following NEW packages will be installed:
  nodejs
0 upgraded, 1 newly installed, 0 to remove and 57 not upgraded.
Need to get 18.1 MB of archives.
After this operation, 93.5 MB of additional disk space will be used.
Get:1 https://deb.nodesource.com/node_12.x focal/main amd64 nodejs amd64 12.22.12-deb-1nodesource1 [18.1 MB]
Fetched 18.1 MB in 18s (980 kB/s)                                                                          
Selecting previously unselected package nodejs.
(Reading database ... 94737 files and directories currently installed.)
Preparing to unpack .../nodejs_12.22.12-deb-1nodesource1_amd64.deb ...
Unpacking nodejs (12.22.12-deb-1nodesource1) ...
Setting up nodejs (12.22.12-deb-1nodesource1) ...
Processing triggers for man-db (2.9.1-1) ...
vagrant@ubuntu-focal:~$ nodejs -v

Command 'nodejs' not found, but can be installed with:

apt install nodejs
Please ask your administrator.

vagrant@ubuntu-focal:~$ apt install nodejs
E: Could not open lock file /var/lib/dpkg/lock-frontend - open (13: Permission denied)
E: Unable to acquire the dpkg frontend lock (/var/lib/dpkg/lock-frontend), are you root?
vagrant@ubuntu-focal:~$ npm -v
6.14.16
vagrant@ubuntu-focal:~$ git clone https://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github.com/KafuiPraise/alx-backend-javascript.git
Cloning into 'alx-backend-javascript'...
^[[D^[[Dfatal: unable to access 'https://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github.com/KafuiPraise/alx-backend-javascript.git/': Could not resolve host: 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github.com
vagrant@ubuntu-focal:~$ git clone https://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@github.com/KafuiPraise/alx-backend-javascript.git
Cloning into 'alx-backend-javascript'...
warning: You appear to have cloned an empty repository.
vagrant@ubuntu-focal:~$ ce alx-backend-javascript/
ce: command not found
vagrant@ubuntu-focal:~$ cd alx-backend-javascript/
vagrant@ubuntu-focal:~/alx-backend-javascript$ npm install.

Usage: npm <command>

where <command> is one of:
    access, adduser, audit, bin, bugs, c, cache, ci, cit,
    clean-install, clean-install-test, completion, config,
    create, ddp, dedupe, deprecate, dist-tag, docs, doctor,
    edit, explore, fund, get, help, help-search, hook, i, init,
    install, install-ci-test, install-test, it, link, list, ln,
    login, logout, ls, org, outdated, owner, pack, ping, prefix,
    profile, prune, publish, rb, rebuild, repo, restart, root,
    run, run-script, s, se, search, set, shrinkwrap, star,
    stars, start, stop, t, team, test, token, tst, un,
    uninstall, unpublish, unstar, up, update, v, version, view,
    whoami

npm <command> -h  quick help on <command>
npm -l            display full usage info
npm help <term>   search for help on <term>
npm help npm      involved overview

Specify configs in the ini-formatted file:
    /home/vagrant/.npmrc
or on the command line via: npm <command> --key value
Config info can be viewed via: npm help config

npm@6.14.16 /usr/lib/node_modules/npm

Did you mean one of these?
    install
    uninstall
    unstar
vagrant@ubuntu-focal:~/alx-backend-javascript$ npm install
npm WARN saveError ENOENT: no such file or directory, open '/home/vagrant/alx-backend-javascript/package.json'
npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN enoent ENOENT: no such file or directory, open '/home/vagrant/alx-backend-javascript/package.json'
npm WARN alx-backend-javascript No description
npm WARN alx-backend-javascript No repository field.
npm WARN alx-backend-javascript No README data
npm WARN alx-backend-javascript No license field.

up to date in 0.817s
found 0 vulnerabilities

vagrant@ubuntu-focal:~/alx-backend-javascript$ vi README
vagrant@ubuntu-focal:~/alx-backend-javascript$ vi README.md
vagrant@ubuntu-focal:~/alx-backend-javascript$ touch package.json babel.config.js .eslintrc.js
vagrant@ubuntu-focal:~/alx-backend-javascript$ ls
README.md  babel.config.js  package-lock.json  package.json
vagrant@ubuntu-focal:~/alx-backend-javascript$ vi babel.config.js 
vagrant@ubuntu-focal:~/alx-backend-javascript$ vi package.json 
vagrant@ubuntu-focal:~/alx-backend-javascript$ vi .eslintrc.js
vagrant@ubuntu-focal:~/alx-backend-javascript$ ls
README.md  babel.config.js  package-lock.json  package.json
vagrant@ubuntu-focal:~/alx-backend-javascript$ vi package-lock.json 
vagrant@ubuntu-focal:~/alx-backend-javascript$ npm install
npm WARN deprecated fsevents@1.2.13: The v1 package contains DANGEROUS / INSECURE binaries. Upgrade to safe fsevents v2
npm WARN deprecated sane@4.1.0: some dependency vulnerabilities fixed, support for node < 10 dropped, and newer ECMAScript syntax/features added
npm WARN deprecated abab@2.0.6: Use your platform's native atob() and btoa() methods instead
npm WARN deprecated domexception@1.0.1: Use your platform's native DOMException instead
npm WARN deprecated w3c-hr-time@1.0.2: Use your platform's native performance.now() and performance.timeOrigin.
npm WARN deprecated request-promise-native@1.0.9: request-promise-native has been deprecated because it extends the now deprecated request package, see https://github.com/request/request/issues/3142
npm WARN deprecated request@2.88.2: request has been deprecated, see https://github.com/request/request/issues/3142
npm WARN deprecated left-pad@1.3.0: use String.prototype.padStart()
npm WARN deprecated source-map-resolve@0.5.3: See https://github.com/lydell/source-map-resolve#deprecated
npm WARN deprecated har-validator@5.1.5: this library is no longer supported
npm WARN deprecated uuid@3.4.0: Please upgrade  to version 7 or higher.  Older versions may use Math.random() in certain circumstances, which is known to be problematic.  See https://v8.dev/blog/math-random for details.
npm WARN deprecated resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated
npm WARN deprecated source-map-url@0.4.1: See https://github.com/lydell/source-map-url#deprecated
npm WARN deprecated urix@0.1.0: Please see https://github.com/lydell/urix#deprecated

> core-js@3.35.1 postinstall /home/vagrant/alx-backend-javascript/node_modules/core-js
> node -e "try{require('./postinstall')}catch(e){}"

Thank you for using core-js ( https://github.com/zloirock/core-js ) for polyfilling JavaScript standard library!

The project needs your help! Please consider supporting core-js:
> https://opencollective.com/core-js 
> https://patreon.com/zloirock 
> https://boosty.to/zloirock 
> bitcoin: bc1qlea7544qtsmj2rayg0lthvza9fau63ux0fstcz 

I highly recommend reading this: https://github.com/zloirock/core-js/blob/master/docs/2023-02-14-so-whats-next.md 

npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@^1.2.7 (node_modules/jest-haste-map/node_modules/fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"linux","arch":"x64"})
npm WARN alx-backend-javascript No repository field.
npm WARN alx-backend-javascript No license field.

added 738 packages from 425 contributors and audited 739 packages in 72.548s

83 packages are looking for funding
  run `npm fund` for details

found 18 moderate severity vulnerabilities
  run `npm audit fix` to fix them, or `npm audit` for details
vagrant@ubuntu-focal:~/alx-backend-javascript$ npm installnpm install

Usage: npm <command>

where <command> is one of:
    access, adduser, audit, bin, bugs, c, cache, ci, cit,
    clean-install, clean-install-test, completion, config,
    create, ddp, dedupe, deprecate, dist-tag, docs, doctor,
    edit, explore, fund, get, help, help-search, hook, i, init,
    install, install-ci-test, install-test, it, link, list, ln,
    login, logout, ls, org, outdated, owner, pack, ping, prefix,
    profile, prune, publish, rb, rebuild, repo, restart, root,
    run, run-script, s, se, search, set, shrinkwrap, star,
    stars, start, stop, t, team, test, token, tst, un,
    uninstall, unpublish, unstar, up, update, v, version, view,
    whoami

npm <command> -h  quick help on <command>
npm -l            display full usage info
npm help <term>   search for help on <term>
npm help npm      involved overview

Specify configs in the ini-formatted file:
    /home/vagrant/.npmrc
or on the command line via: npm <command> --key value
Config info can be viewed via: npm help config

npm@6.14.16 /usr/lib/node_modules/npm

Did you mean one of these?
    install
    install-test
    uninstall
vagrant@ubuntu-focal:~/alx-backend-javascript$ npm audit fix
npm WARN alx-backend-javascript No repository field.
npm WARN alx-backend-javascript No license field.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.13 (node_modules/fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"linux","arch":"x64"})

up to date in 6.174s

83 packages are looking for funding
  run `npm fund` for details

fixed 0 of 18 vulnerabilities in 739 scanned packages
  5 vulnerabilities required manual review and could not be updated
  2 package updates for 13 vulnerabilities involved breaking changes
  (use `npm audit fix --force` to install breaking changes; or refer to `npm audit` for steps to fix these manually)
vagrant@ubuntu-focal:~/alx-backend-javascript$ npm audit fix --force
npm WARN using --force I sure hope you know what you are doing.
npm WARN eslint-plugin-jest@27.6.3 requires a peer of eslint@^7.0.0 || ^8.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN tsutils@3.21.0 requires a peer of typescript@>=2.8.0 || >= 3.2.0-dev || >= 3.3.0-dev || >= 3.4.0-dev || >= 3.5.0-dev || >= 3.6.0-dev || >= 3.6.0-beta || >= 3.7.0-dev || >= 3.7.0-beta but none is installed. You must install peer dependencies yourself.
npm WARN alx-backend-javascript No repository field.
npm WARN alx-backend-javascript No license field.

+ eslint-plugin-jest@27.6.3
+ jest@29.7.0
added 233 packages from 98 contributors, removed 231 packages and updated 84 packages in 60.392s

104 packages are looking for funding
  run `npm fund` for details

fixed 13 of 18 vulnerabilities in 739 scanned packages
  5 vulnerabilities required manual review and could not be updated
  2 package updates for 13 vulnerabilities involved breaking changes
  (installed due to `--force` option)
vagrant@ubuntu-focal:~/alx-backend-javascript$ ls
README.md  babel.config.js  node_modules  package-lock.json  package.json
vagrant@ubuntu-focal:~/alx-backend-javascript$ sudo vi package.json 
vagrant@ubuntu-focal:~/alx-backend-javascript$ NODE -V
NODE: command not found
vagrant@ubuntu-focal:~/alx-backend-javascript$ node -v
v12.22.12
vagrant@ubuntu-focal:~/alx-backend-javascript$ mkdir 0x00-ES6_basic 
vagrant@ubuntu-focal:~/alx-backend-javascript$ cd 0x00-ES6_basic/
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ touch 0-constants.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ touch 0-constants.js 1-block-scoped.js 2-arrow.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ touch 0-constants.js 1-block-scoped.js 2-arrow.js 3-default-parameter.js 4-rest-parameter.js 5-spread-operator.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ touch 0-constants.js 1-block-scoped.js 2-arrow.js 3-default-parameter.js 4-rest-parameter.js 5-spread-operator.js 6-string-interpolation.js 7-getBudgetObject.js 8-getBudgetCurrentYear.js 9-getFullBudget.js 10-loops.js 11-createEmployeesObject.js 12-createReportObject.js 100-createIteratorObject.js 101-iterateThroughObject.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ touch 0-constants.js 1-block-scoped.js 2-arrow.js 3-default-parameter.js 4-rest-parameter.js 5-spread-operator.js 6-string-interpolation.js 7-vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ ls
0-constants.js     10-loops.js                  101-iterateThroughObject.js  12-createReportObject.js  3-default-parameter.js  5-spread-operator.js       7-getBudgetObject.js       9-getFullBudget.jsjs 7-1-block-scoped.js  100-createIteratorObject.js  11-createEmployeesObject.js  2-arrow.js                4-rest-parameter.js     6-string-interpolation.js  8-getBudgetCurrentYear.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 0-constants.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 1-block-scoped.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 2-arrow.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 3-default-parameter.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 4-rest-parameter.js export default function returnHowManyArguments(...theArgs) {
-bash: syntax error near unexpected token `('
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$   return theArgs.length;
-bash: return: theArgs.length: numeric argument required
-bash: return: can only `return' from a function or sourced script
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 4-rest-parameter.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 5-spread-operator.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 4-rest-parameter.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 5-spread-operator.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 6-string-interpolation.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 7-getBudgetObject.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 8-getBudgetCurrentYear.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 9-getFullBudget.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 10-loops.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 100-createIteratorObject.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 11-createEmployeesObject.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 101-iterateThroughObject.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ ls
0-constants.js               11-createEmployeesObject.js  5-spread-operator.js
1-block-scoped.js            12-createReportObject.js     6-string-interpolation.js
10-loops.js                  2-arrow.js                   7-getBudgetObject.js
100-createIteratorObject.js  3-default-parameter.js       8-getBudgetCurrentYear.js
101-iterateThroughObject.js  4-rest-parameter.js          9-getFullBudget.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ git add .
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ git commit -m 'All Task'
[master (root-commit) 1694e03] All Task
 15 files changed, 112 insertions(+)
 create mode 100644 0x00-ES6_basic/0-constants.js
 create mode 100644 0x00-ES6_basic/1-block-scoped.js
 create mode 100644 0x00-ES6_basic/10-loops.js
 create mode 100644 0x00-ES6_basic/100-createIteratorObject.js
 create mode 100644 0x00-ES6_basic/101-iterateThroughObject.js
 create mode 100644 0x00-ES6_basic/11-createEmployeesObject.js
 create mode 100644 0x00-ES6_basic/12-createReportObject.js
 create mode 100644 0x00-ES6_basic/2-arrow.js
 create mode 100644 0x00-ES6_basic/3-default-parameter.js
 create mode 100644 0x00-ES6_basic/4-rest-parameter.js
 create mode 100644 0x00-ES6_basic/5-spread-operator.js
 create mode 100644 0x00-ES6_basic/6-string-interpolation.js
 create mode 100644 0x00-ES6_basic/7-getBudgetObject.js
 create mode 100644 0x00-ES6_basic/8-getBudgetCurrentYear.js
 create mode 100644 0x00-ES6_basic/9-getFullBudget.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ git push
Enumerating objects: 18, done.
Counting objects: 100% (18/18), done.
Delta compression using up to 2 threads
Compressing objects: 100% (16/16), done.
Writing objects: 100% (18/18), 2.74 KiB | 1.37 MiB/s, done.
Total 18 (delta 0), reused 0 (delta 0)
To https://github.com/KafuiPraise/alx-backend-javascript.git
 * [new branch]      master -> master
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 0-constants.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ chmod 0-constants.js 
chmod: missing operand after ‘0-constants.js’
Try 'chmod --help' for more information.
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ chmod +x 0-constants.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ ls
0-constants.js               11-createEmployeesObject.js  5-spread-operator.js
1-block-scoped.js            12-createReportObject.js     6-string-interpolation.js
10-loops.js                  2-arrow.js                   7-getBudgetObject.js
100-createIteratorObject.js  3-default-parameter.js       8-getBudgetCurrentYear.js
101-iterateThroughObject.js  4-rest-parameter.js          9-getFullBudget.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ chmod +x 100-createIteratorObject.js  101-iterateThroughObject.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ ls
0-constants.js               11-createEmployeesObject.js  5-spread-operator.js
1-block-scoped.js            12-createReportObject.js     6-string-interpolation.js
10-loops.js                  2-arrow.js                   7-getBudgetObject.js
100-createIteratorObject.js  3-default-parameter.js       8-getBudgetCurrentYear.js
101-iterateThroughObject.js  4-rest-parameter.js          9-getFullBudget.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ git add .
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ git commit -m 'All Task'
[master bef53bf] All Task
 3 files changed, 0 insertions(+), 0 deletions(-)
 mode change 100644 => 100755 0x00-ES6_basic/0-constants.js
 mode change 100644 => 100755 0x00-ES6_basic/100-createIteratorObject.js
 mode change 100644 => 100755 0x00-ES6_basic/101-iterateThroughObject.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 295 bytes | 295.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/KafuiPraise/alx-backend-javascript.git
   1694e03..bef53bf  master -> master
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 12-createReportObject.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 12-createReportObject.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ ls
0-constants.js               11-createEmployeesObject.js  5-spread-operator.js
1-block-scoped.js            12-createReportObject.js     6-string-interpolation.js
10-loops.js                  2-arrow.js                   7-getBudgetObject.js
100-createIteratorObject.js  3-default-parameter.js       8-getBudgetCurrentYear.js
101-iterateThroughObject.js  4-rest-parameter.js          9-getFullBudget.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ chmod -x 100-createIteratorObject.js 101-iterateThroughObject.js 0-constants.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ ls
0-constants.js               11-createEmployeesObject.js  5-spread-operator.js
1-block-scoped.js            12-createReportObject.js     6-string-interpolation.js
10-loops.js                  2-arrow.js                   7-getBudgetObject.js
100-createIteratorObject.js  3-default-parameter.js       8-getBudgetCurrentYear.js
101-iterateThroughObject.js  4-rest-parameter.js          9-getFullBudget.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi 0-constants.js 
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi README.md
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi README.md
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ git add .
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ git commit -m 'All Task'
[master ae06f81] All Task
 5 files changed, 34 insertions(+)
 mode change 100755 => 100644 0x00-ES6_basic/0-constants.js
 mode change 100755 => 100644 0x00-ES6_basic/100-createIteratorObject.js
 mode change 100755 => 100644 0x00-ES6_basic/101-iterateThroughObject.js
 create mode 100644 0x00-ES6_basic/README.md
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ git push
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 905 bytes | 129.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/KafuiPraise/alx-backend-javascript.git
   bef53bf..ae06f81  master -> master
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ ls
0-constants.js               12-createReportObject.js   7-getBudgetObject.js
1-block-scoped.js            2-arrow.js                 8-getBudgetCurrentYear.js
10-loops.js                  3-default-parameter.js     9-getFullBudget.js
100-createIteratorObject.js  4-rest-parameter.js        README.md
101-iterateThroughObject.js  5-spread-operator.js
11-createEmployeesObject.js  6-string-interpolation.js
vagrant@ubuntu-focal:~/alx-backend-javascript/0x00-ES6_basic$ vi README.md 

## ES6 Basics

This project introduces learners to modern JasvaScript essentials.

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- What ES6 is
- New features introduced in ES6
- The difference between a constant and a variable
- Block-scoped variables
- Arrow functions and function parameters default to them
- Rest and spread function parameters
- String templating in ES6
- Object creation and their properties in ES6
- Iterators and for-of loops

## Installations
Install NodeJS 12.x
- nodejs -v
- npm -v

Install Jest, Babel and ESList by using the supplied `package.json` and run `npm install`.
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
~                                                                                          
"README.md" 24L, 686C                                                    1,3           All

