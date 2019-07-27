---
layout: default
---
## TODO lists

### STAT
1. Prep for 5.0.2 release (next up: ubuntu package add php.ini change)
1. (note weird placement of whitelisting which will break all dicom stuff if it's turned on)
1. snomed rf2 (main done but still need to support in ccda stuff; https://github.com/openemr/openemr/blob/master/interface/modules/zend_modules/module/Carecoordination/src/Carecoordination/Model/EncounterccdadispatchTable.php#L2316-L2333)
1. Audit API code couple times to ensure secure (0/3 done so far)
1. Audit calendar code couple times to ensure secure (0/2 done so far)
1. Audit auth/sessions/cookie code couple times to ensure secure (0/2 done so far)
1. Do more testing of the 5.0.2 docker and when upgrade docker from 5.0.1.

### Expedited
1. request donations for mu3
1. oe-blue-button-generate
1. CSRF implementation ongoing
1. Blog post for google cloud launcher
1. couchdb ssl
1. phpunit
1. MIPS research
1. MU3 research

### Scheduled items to do
1. After release 5.0.2, change docker farm mariadb version to 10.4
1. Whenever update or build the docker, check if need to increment the `git clone https://github.com/letsencrypt/letsencrypt` branch that is collected. 

### OpenEMR Code Reviews
* [Pull Requests](https://github.com/openemr/openemr/pulls)

### OpenEMR Issues
* [High Priority Codebase](https://github.com/openemr/openemr/milestone/4)
* [High Priority Devops](https://github.com/openemr/openemr-devops/milestone/1)
* [Normal Priority](https://github.com/openemr/openemr/milestone/5)
* [Low Priority](https://github.com/openemr/openemr/milestone/6)

### OpenEMR Project Admin
1. Upgrade wiki (mediawiki) to most recent version.(R working on)

### OpenEMR Foundation
1. Setting up the plumbing

### OpenEMR Next Release
1. Add `mysqli.allow_local_infile = On` setting to php.ini for 5.0.2 ubuntu package and xampp package
1. For next xampp package, add `Options -Indexes` to the apache config
1. For next ubuntu package, don't secure files needed for install if auto-configuration was not done.(low priority)
