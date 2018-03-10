---
layout: default
---
## TODO lists

### Expedited
* sql-upgrade fix.(in codebase. test extensively:b05e2c979eb482ebafda555e8b5fdb591cce7a5e )

### OpenEMR Code Reviews
1. Ranganath modern styling.
1. Sherwin WYSIWYG editor for dictation form.
1. venambati statement combined pdf fix.
1. Roberto rf2 snomed.
1. Alfonso shell scripts (email)
1. Alfonso demographics (email).
1. Visolve gender stuff.
1. Sherwin max pid thing.(R plans to confirm the original bug first before bringing into codebase)
1. Rishabh tabs improvements.(M reviewing)
1. Stephen osx support.
1. MD Support service providers improvements.(R to review)
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
1. Sherwin portal invoice.(work in progress; may not pursue because of the new portal)
1. Matrix sort pubpid.(awaiting reply to my question)
1. Arnab and Jerry xmlformgen pdf fix.(work in progress)
1. Robert timeline.(work in progress)
1. Robert default encounter category.(work in progress)
1. Venkat billing fix.(reviewed; awaiting next revision)
1. Robert user ui improvements.(reviewed; awaiting next revision)
1. Robert central ui improvements.(reviewed; awaiting next revision)
1. Robert Amendments.(reviewed; awaiting next revision)
1. Robert demographics ui improve.(reviewed; awaiting next revision)
1. A1Gard procedure activity.(reviewed; awaiting next revision)
1. Ray encounter provider selector.(reviewed; awaiting next revision)
1. Sherwin update ROS form.(reviewed; awaiting next revision)
1. Visolve address book.(reviewed; awaiting next revision)
1. Terry annotate form.(reviewed; awaiting next revision)
1. Scott html2pdf removal.(images not working on testing; awaiting a response)
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
1. Need to add --link to the rsync command for demo scripts; note demos may of died after doing this, so need to do trial first)
1. For packages also need to figure out if need to deal with links in composer bin (like the --link issue in demos)
1. For composer, research if will need to use --copy-links rather than --link to ensure vendor/bin softlinks work on windows(copy-links copies the actual file rathe than the link to the file)(also need to ensure --link doesn't break anything since it may of broken the demo scripts).
1. Upgrade wiki (mediawiki) to most recent version.

### OEMR Organization
1. Add MACRA,MU,MIPS,PQRS to Education.
1. Join OSI.
1. Set up OEMR secrets (via M. email)
1. New OEMR logo(have budget of $100).
1. Budget.
1. Fund-raising(options are donations grants, crowd-sourcing etc; d/w L regarding crowd-sourcing and many more).

### OpenEMR Next Release
1. Issue - (for development and 5.0.1 ubuntu package also may need to add --link to the rsync command; ensure --link doesn't break anything since it may of broken the demo scripts)
1. New ubuntu dependencies(for 5.0.1): php-ldap (this is already in the development package (version 7) for testing). Also may likely need nodejs (currently testing). ENSURED REMOVED php-mcrypt from PHP7 packages!
1. Ensure php-openssl working in ubuntu packages, all dockers (official dockers (except 5.0.0), all alpines in docker farm and ensure works out of box in ubuntus, especially 18.04), and in xampp package.(test log encryption and doc encryption to ensure it's working on all platforms)
1. Removed ubuntu perl dependencies, so will need to build a new version development ubuntu package at some point. In this package could also stream line the clone with the `--depth 1` setting.
1. New ubuntu and xampp php settings to change to(for 5.0.1): max_input_time = -1 , memory_limit = 512M
1. For next ubuntu package, don't secure files needed for install if auto-configuration was not done.(low priority)
