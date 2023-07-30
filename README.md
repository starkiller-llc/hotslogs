# Root Repo

## Clone

Clone recursively:

`git clone --recursive https://github.com/starkiller-llc/hotslogs.git`

## Build

Load `hotslogs-site/HeroesReplays.sln` in Visual Studio and build

## Run

This is a bit more involved, there are 4 parts to the site (one is just a stub), you can run them by using these batch files:
* `runang.cmd`
* `runapi.cmd`
* `rundbs.cmd`
* `runsite.cmd` (this is the stub)

`rundbs.cmd` will require a docker setup. See the docker directory readme at `hotslogs-site/docker`.

`runang.cmd` will first require `npm install` to be run inside the `hotslogs-site/Angular` directory.

## Good luck and have fun!
