# PJC Website Builder

Hi, welcome to the PJC website builder.

The aim here is to keep things:
* small   - so that understanding how it all works doesn't take forever
* simple  - so that you don't need to know too much to be productive
* safe    - so you can make a local copy of the site, play with it, and try things out without fear of breaking the live site
* shared  - so many people can take on different aspects of site and content maintenance


# Getting Started
To to install and build the site you'll need just two apps:
1. `git` will be used to synchronise the files between GitHub and yor machine
2. `bun` which is a JavaScript engine that will do the building work 
3. Clone a copy of the site
4. Install the dependencies


## Installing `Git`
Detailed instructions on various ways of installing `git`
https://git-scm.com/book/en/v2/Getting-Started-Installing-Git


## Installing `Bun`
Instructions on how to install `bun` 
https://bun.sh/docs/installation


## Cloning the site
The site is shared through GitHub at: https://github.com/Portsmouth-Joggers/webtest

If you're using the GitHub Desktop App you should be able to clone it here: x-github-client://openRepo/https://github.com/Portsmouth-Joggers/webtest

If you're using command line then navigate to a folder where you'd like to add the clone and type:
```shell
git clone https://github.com/Portsmouth-Joggers/webtest.git
```

## Installing Dependencies
The site is built using a tool called `nuekit`.  All the necessary prep-work for this should be done when you type∏
```shell
bun install
```

After this you should have everything ready to build and serve a copy of the site locally




# Edit, Build & Serve

1. Change to the website folder and start the server:
```shell
cd webtest
bun start
```
2. Visit http://localhost:8080/ in a browser.
3. Edit files in the `src` folder
4. Reload the page to see the changes.


