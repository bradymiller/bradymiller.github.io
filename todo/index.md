---
layout: default
---
## TODO lists

### Expedited
1. Release 5.0.1.3 packages (docker(DONE), tar, zip, ubuntu, xampp, appliance, express/standard aws marketplace)
1. Ensure 5.0.1 to 5.0.2 docker upgrade works with the new apache uid 1000 fix
1. swarms away (nginx*3 and php-fpm*3)
1. Add hylafax docker
1. snomed rf2
1. CAMOS escaping bugs
1. couchdb ssl
1. apache 2.2 updates
1. phpunit
1. MIPS research
1. MU3 research


### OpenEMR Code Reviews
* [Pull Requests](https://github.com/openemr/openemr/pulls)

### OpenEMR Issues
* [High Priority](https://github.com/openemr/openemr/milestone/2)
* [Normal Priority](https://github.com/openemr/openemr/milestone/4)
* [Very Low Priority](https://github.com/openemr/openemr/milestone/5)

### OpenEMR Project Admin
1. Upgrade wiki (mediawiki) to most recent version.(R working on)

### OEMR Organization
1. Restructuring

### OpenEMR Next Release
1. Removed ubuntu perl dependencies, so will need to build a new version development ubuntu package at some point. In this package could also stream line the clone with the `--depth 1` setting.
1. For next ubuntu package, don't secure files needed for install if auto-configuration was not done.(low priority)
