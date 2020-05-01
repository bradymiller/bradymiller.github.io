---
layout: default
---
## TODO lists

### STAT
1. Patch 2 (when release, remove the mysql8 version limits at top of download page)(will need new packages since mysql 8 bug effects install)(patch and docker done; next need to release the rebuilt packages)
1. MU3 re-analysis
1. Release 5.0.2 xampp package (ensure add `Options -Indexes` to the apache config)
1. Release 5.0.2 deb package (the popups and php edit is not working); ensure the mysqli.allow_local_infile setting works as expected in the ubuntu package.

### Expedited
1. Change docker farm to mariadb 10.4
1. sherwin's sql inject thing fix
1. request donations for mu3
1. oe-blue-button-generate
1. couchdb ssl
1. MIPS research
1. MU3 research

### Under Consideration
1. (note weird placement of whitelisting which may break dicom stuff if it's turned on)
1. snomed rf2 (main done but still may need to support in ccda stuff; https://github.com/openemr/openemr/blob/master/interface/modules/zend_modules/module/Carecoordination/src/Carecoordination/Model/EncounterccdadispatchTable.php#L2316-L2333)

### Scheduled items to do
1. When Alpine 3.12 is released (these changes are now working in the Edge docker), make the following changes that were made in this Edge docker commit (this is because alpine edge/3.12 upgraded to py3-pip): https://github.com/openemr/openemr-devops/commit/6dd334c4f21be5c0af71a227100564319028baf9
1. AWS has set up reserved instances of ec2/rds stuff to decrease costs (done; keeping reg db on demand since will hopefully go away in a couple months)

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
1. When release 5.0.3, the demo farm password reset will need a mode 3 since salts are now gone (and need to also update the last_update_password entry to NOW())
