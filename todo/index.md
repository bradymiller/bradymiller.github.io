---
layout: default
---
## TODO lists

### STAT
1. Change docker examples and docker farm to mariadb 10.4
1. Release 5.0.2 xampp package (ensure add `Options -Indexes` to the apache config)
1. 5.0.2 release security specific blog
1. 5.0.2 release PR
1. Release 5.0.2 deb package (the popups and php edit is not working); ensure the mysqli.allow_local_infile setting works as expected in the ubuntu package.
1. sherwin's sql inject thing fix

### Expedited
1. request donations for mu3
1. oe-blue-button-generate
1. couchdb ssl
1. phpunit
1. MIPS research
1. MU3 research

### Under Consideration
1. use better random password generation for portal
1. encrypt stored API tokens
1. (note weird placement of whitelisting which may break dicom stuff if it's turned on)
1. snomed rf2 (main done but still may need to support in ccda stuff; https://github.com/openemr/openemr/blob/master/interface/modules/zend_modules/module/Carecoordination/src/Carecoordination/Model/EncounterccdadispatchTable.php#L2316-L2333)

### Scheduled items to do
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
1. For next ubuntu package, don't secure files needed for install if auto-configuration was not done.(low priority)
