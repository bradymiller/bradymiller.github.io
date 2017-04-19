---
layout: default
---
## TODO lists

### Expedited
* Upgrade demo farm(rollout after testing well on main devel demo)
* Security fixes (2/3 done; still graphing issue)
* new x-o package (bring in Jerry's registration bug fix, mysql settings optimize)
* minutes 3/8/17

### OpenEMR Code Reviews
1. Matrix acl groups.
1. Robert demographics ui improve.
1. Rishabh tabs improvements.
1. Sherwin WENO Rx.
1. Sherwin drag/drop docs.
1. Stephen osx support.
1. Robert auto fixed code.(work in progress; need to identify the 3rd party scripts so ignore them)
1. Victor chart doctrine (M to review)
1. Matthew facility doctrine (R and O to review).
1. Stephen sql-upgrade fix.(M to review)
1. MD Support service providers improvements.(R to review)
1. Ray menu improvements.
1. MD Support menu re-organization.
1. Sherwin labs form.
1. MD Support tabs improvement.(made a demo and waiting for Ra input)
1. MD Support encounter form order display.
1. Visolve html escape avoid in options list.(not on github, need to look through it)
1. MD Support extend zero time.
1. Ra. security fix.
1. Visolve add rows lists and default on for the active box.
1. Visolve import lists.
1. MD Support ignoreauth on labs thing.
1. Visolve 1500 pdf settings.(reviewed; good feature and I will integrate it, if necessary)
1. Matrix Zend patient validation module.(already committed into codebase; need to get the modify demographics 'edit' zend module popup to work smoothly and remove the 'closeBeforeOpening=1')
1. Kevin M. EDI module.(already committed into codebase, but need to go through each script and incorporate html escaping)
1. MD Support PrevSetting.(already committed into codebase, but awaiting fix by MD Support)
1. Ray site id bug fix.(awaiting Ray's testing)
1. Matthew and Sherwin doctrine facilities.(work in progress)
1. Sherwin portal invoice.(work in progress; may not pursue because of the new portal)
1. Matrix sort pubpid.(awaiting reply to my question)
1. Arnab and Jerry xmlformgen pdf fix.(work in progress)
1. Robert procedure order form to bootstrap.(reviewed; awaiting next revision)
1. Roberto rf2 snomed.(reviewed; awaiting next revision)
1. A1Gard procedure activity.(reviewed; awaiting next revision)
1. Ray encounter provider selector.(reviewed; awaiting next revision)
1. Sherwin update ROS form.(reviewed; awaiting next revision)
1. Visolve address book.(reviewed; awaiting next revision)
1. Terry annotate form.(reviewed; awaiting next revision)
1. Scott html2pdf removal.(images not working on testing; awaiting a response)
1. MD Support lef_nav arrow to hide/show.(reviewed; awaiting next revision and response from MD Support)
1. Scott js and css organization.(reviewed; awaiting response from Scott)
1. Craig Codes gui update.(Rod reviewed; awaiting response from Craig)
1. Scott path uppercase cleanup.
1. Terry duplicate appt bug fix (plan to help integrate this fix if have time).
1. MD Support onsite patient portal signon update.
1. Visolve multi-provider bug fix.
1. MD Support PE form.
1. Art x10 4010 smackdown.
1. Sherwin auto save (pending issues by Brady and MD Support).
1. Sherwin prior auth form (pending issue by Rod).

### OpenEMR Project Admin
1. Upgrade demo farm from Ubuntu 12.04 to 14.04/16.04. (rollout after testing well on main development demo)
1. remove need for demo ports via reverse proxy
1. Need to add --link to the rsync command for demo scripts; note demos may of died after doing this, so need to do trial first)
1. For packages also need to figure out if need to deal with links in composer bin (like the --link issue in demos)
1. Continue security fixes.
1. Fix most recent Certified Contributor entry and V entry.
1. Website google analytics on main page (already in wiki).
1. Migrate website to server(likely aws) that can support SSL(either in aws if use load balancer or vie 'Let's Encrypt' service); also migrating automated server scripts.
1. For composer, research if will need to use --copy-links rather than --link to ensure vendor/bin softlinks work on windows(copy-links copies the actual file rathe than the link to the file)(also need to ensure --link doesn't break anything since it may of broken the demo scripts).
1. Fix demo farm to not start apache until the entire install is done.(note no longer need to start apache earlier since the appliance serving the development translations is not pulling the translations from itself anymore)
1. Upgrade wiki (mediawiki) to most recent version.

### OEMR Organization
1. Add MACRA,MU,MIPS,PQRS to Education.
1. Join OSI.
1. Set up OEMR secrets (via M. email)
1. Find a lawyer for revocation issues
1. Revocation protest (turned in by Treasurer; has been forwarded to appeals and awaiting reply).
1. Taxes (2015 turned in by Treasurer, although likely not needed until revocation complete).
1. Confirm registered agent and USPS address change.
1. New OEMR logo(have budget of $100).
1. Budget.
1. Fund-raising(options are donations grants, crowd-sourcing etc; d/w L regarding crowd-sourcing and many more).
1. Discuss with board regarding settings aside funds for under-represented clinics and other charitable organizations.

### MU3
1. Complete wiki planning page.
1. Current budget is about 31 developer months plus $22,000 testing fee.
1. Look into prioritizing CQM since may be required for 2017 reporting??

### OpenEMR Next Release
1. Issue - (for development and 5.0.1 ubuntu package also need to add --link to the rsync command; ensure --link doesn't break anything since it may of broken the demo scripts)
1. New ubuntu dependencies(for 5.0.1): php-ldap (this is already in the development package (version 7) for testing). Also will likely need nodejs (currently testing).
1. New ubuntu and xampp php settings to change to(for 5.0.1): max_input_time = -1 , memory_limit = 512M
1. For next ubuntu package, don't secure files needed for install if auto-configuration was not done.(low priority)
