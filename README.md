#Environment configs for Sitecore XP

##Warnings
1. This repository contains experimental config overrides. No guarantees that it works with your Sitecore instance.
Please use with caution.

##Repo structure
There is a subfolder for each role (CD or dev, for example).
You can find an auto include config there.

##Known Issues
Because of the getTranslation pipeline `patch:delete`, you will be seeing some errors in the logs:
`ERROR Cannot find translation pipeline with name 'getTranslation'.`
