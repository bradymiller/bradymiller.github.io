---
layout: default
---
## TODO lists

### Expedited
* MU2(WCAG report and ensure get ZH code)
* Emails(pr. boot/menu)
* Calls(s. billing, FHIR)

### OpenEMR Code Reviews
1. Matrix groups.(ongoing review)
1. Sherwin bug fix.
1. Matrix price history.
1. MD support class for select list.(M to review)
1. MDSupport tabs improvement.(made a demo and waiting for Ra input)
1. MD Support encounter form order display.
1. Visolve html escape avoid in options list.(not on github, need to look through it)
1. MD Support extend zero time.
1. Sherwin labs form.
1. Ra. security fix.
1. Visolve add rows lists and default on for the active box.
1. Visolve import lists.
1. MD Support ignoreauth on labs thing.
1. Visolve 1500 pdf settings.(reviewed; good feature and I will integrate it, if necessary)
1. Matrix Zend patient validation module.(already committed into codebase; need to get the modify demographics 'edit' zend module popup to work smoothly and remove the 'closeBeforeOpening=1')
1. Kevin M. EDI module.(already committed into codebase, but need to go through each script and incorporate html escaping)
1. MD Support PrevSetting.(already committed into codebase, but awaiting fix by MD Support)
1. Ray site id bug fix.(awaiting Ray's testing)
1. Matrix minor fixes.(awaiting Ray's testing)
1. Ray encounter provider selector.(reviewed; awaiting next revision)
1. Sherwin update ROS form.(reviewed; awaiting next revision)
1. Rishabh drag/drop tabs.(reviewed; awaiting next revision)
1. Visolve address book.(reviewed; awaiting next revision)
1. Terry annotate form.(reviewed; awaiting next revision)
1. Sherwin WENO Rx.(reviewed; awaiting next revision) 
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
1. Continue security fixes.
1. Fix most recent Certified Contributor entry and V entry.
1. Website google analytics on main page (already in wiki).
1. Migrate website to server(likely aws) that can support SSL(either in aws if use load balancer or vie 'Let's Encrypt' service); also migrating automated server scripts.
1. Fix demo farm to not start apache until the entire install is done.(note no longer need to start apache earlier since the appliance serving the development translations is not pulling the translations from itself anymore)
1. Upgrade demo farm from Ubuntu 12.04 to 14.04/16.04.
1. Upgrade wiki (mediawiki) to most recent version.

### OEMR Organization
1. Set up OEMR secrets (via M. email)
1. Revocation (turned in by Treasurer; awaiting reply).
1. Taxes (2015 turned in by Treasurer, although likely not needed until revocation complete).
1. Confirm registered agent and USPS address change.
1. Confirm up to date on North Carolina non profit status.
1. New OEMR logo(have budget of $100).
1. Budget.
1. Fund-raising(options are donations grants, crowd-sourcing etc; d/w L regarding crowd-sourcing and many more).
1. Discuss with board regarding settings aside funds for under-represented clinics and other charitable organizations.

### MU2
1. Complete the items flagged by the "Technical Review" and then get that Full Certification.

### MU3
1. Complete wiki planning page.
1. Current budget is about 31 developer months plus $22,000 testing fee.
1. Look into prioritizing CQM since may be required for 2017 reporting??

### OpenEMR Next Release
1. Plan release after get Complete MU2 Certification
1. Need to rebuild development ubuntu package since removed the /library/freeb directory.
1. In documentation for when upgrading to 5.0.0 or greater from a version less than 5.0.0, warn that it can take anywhere from 3 minutes to several hours (and will see a whitescreen until is is completed).
1. New ubuntu dependencies: none for now
1. For next ubuntu package, don't secure files needed for install if auto-configuration was not done.(low priority)
