# sample-embedded-project
This is a sample embedded project created for study purposes

# Layers
- openembedded-core (https://github.com/openembedded/openembedded-core.git)

# Utilities
- bitbake (https://github.com/openembedded/bitbake.git)
- ossystems-yocto-base-scripts (https://github.com/OSSystemsEmbeddedLinux/ossystems-yocto-base-scripts.git)

# Getting Started
- Clone this repository
- Enter in project directory 
- Execute commands above: 

```
git submodule update --init
source setup-environment build
bitbake core-image-minimal
```
