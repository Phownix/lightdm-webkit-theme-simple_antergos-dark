# lightdm-webkit-theme-antergos
### THIS REPO IS A MIRROR
#### Theme code is now maintained as part of [lightdm-webkit2-greeter](http://github.com/antergos/lightdm-webkit2-greeter).
#### This repo is maintained as a mirror of the theme's code for easy cloning/forking.

### Overview

This is the default theme included with [lightdm-webkit2-greeter](http://github.com/Antergos/lightdm-webkit2-greeter). If you are using the Webkit2 greeter, you already have this theme.

### Screenshots
<center>
<img src="img/screenshot1.png" alt="screenshot1" />
</center>

### Prerequisites
* lightdm-webkit2-greeter

### Installation
This theme is included with `lightdm-webkit2-greeter` which is installed by default for Antergos users. Non-Antergos users should see [lightdm-webkit2-greeter](https://github.com/Antergos/lightdm-webkit2-greeter/) for installation details.

### User Icons Management

To change users icons:

* Create a resource named with the user's login in `/var/lib/AccountsService/icons/`
* Edit `/var/lib/AccountsService/users/<userLogin>` and add a property `Icon` targeting the icon resource you just created.

## Theme JavaScript API:
The greeter exposes a JavaScript API to themes which they must use to interact with the greeter (in order to facilitate the user login process). For more details, check out the [API Documentation](https://doclets.io/Antergos/lightdm-webkit2-greeter/master). 


## Translations
Translations are managed through [Transifex](http://transifex.com).

