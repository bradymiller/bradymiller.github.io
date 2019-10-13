---
layout: default
---
## TODO lists

### STAT
1. Release patch 1 (md5sum:f026ff19ac682dae4c5ff85c1dda9f5b) (branch test PASSED and patch PASSED) and new docker/zip(md5sum: aee25be40d8a4cfdf866ef8d3dac676c)/tar(md5sum: a238f73ce95307a3fda854a0f34352d2)(PENDING testing) packages (when done, then change docker examples back to mariadb)
1. 5.0.2 release security specific blog
1. 5.0.2 release PR
1. Release 5.0.2 deb package (the popups and php edit is not working)
1. Release 5.0.2 xampp package
1. Ensure the mysqli.allow_local_infile setting works as expected in the ubuntu package (see 1 above).
1. sherwin's sql inject thing fix

### Expedited
1. (note weird placement of whitelisting which may break dicom stuff if it's turned on)
1. snomed rf2 (main done but still may need to support in ccda stuff; https://github.com/openemr/openemr/blob/master/interface/modules/zend_modules/module/Carecoordination/src/Carecoordination/Model/EncounterccdadispatchTable.php#L2316-L2333)
1. request donations for mu3
1. oe-blue-button-generate
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
1. For next xampp package, add `Options -Indexes` to the apache config
1. For next ubuntu package, don't secure files needed for install if auto-configuration was not done.(low priority)
