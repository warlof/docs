![SeAT](https://i.imgur.com/aPPOxSK.png)

# eveapi change logs
Generated with: `git log --pretty=format:"%h%>(12)%ad %<(7)%aN%d %s" --date=short`

### 1.0-pre-alpha
```
debc408  2015-11-27 Leon Jacobs (tag: 1.0-pre-alpha) Update README
3ab3bb9  2015-11-27 Leon Jacobs Populate $fillable properties to include corpIDs
7577325  2015-11-27 Leon Jacobs Small refactor to reduce code duplication
403b894  2015-11-27 Leon Jacobs Add method to get a corporationID
f116fbe  2015-11-25 Leon Jacobs Fix up testing by allowing the access bit to be set in the constructor
18e3967  2015-11-21 Leon Jacobs Actually set the configured instance
18522f4  2015-11-21 Leon Jacobs Load access definitions directly from the config
d9c3d8f  2015-11-21 Leon Jacobs Resolve PhealNG out of the IoC
3e75254  2015-10-30 Leon Jacobs Increase field size
cc1823d  2015-10-05 Leon Jacobs Add User relationship
2c3f4a6  2015-09-27 Leon Jacobs Change Case
411e46c  2015-09-27 Leon Jacobs Refactor Models into categorized namespaces
0940ea9  2015-09-24 Leon Jacobs Make Jobs aware of the Pheal\ConnectionException
acf0a53  2015-09-24 Leon Jacobs Write a log entry if the JobTracker lookup failed
bc9b4ce  2015-09-24 Leon Jacobs Dont try and get Courier contracts items
10f496a  2015-09-24 Leon Jacobs Dont type hint the exception type, as any exception should get here.
d1d8555  2015-09-24 Leon Jacobs Cater for the strange AccountStatus call access.
318de50  2015-09-24 Leon Jacobs Rate Limit requests p/s to remain under 30 p/s
dfcd9c6  2015-09-24 Leon Jacobs Jobs can now be assigned to a queue for priority.
5b8cd0b  2015-09-24 Leon Jacobs Prevent an array_merge() attempt on NULL
31f1af0  2015-09-24 Leon Jacobs Allow for granular update worker control
ca9ff3e  2015-09-23 Leon Jacobs Collapse KillMail Attacker, Detail and Items tables.
16e75b5  2015-09-23 Leon Jacobs Split configs up and update the Service Provider
1639d2b  2015-09-23 Leon Jacobs Move load_workers to the JobTracker Trait
827f34a  2015-09-23 Leon Jacobs Small refactor to remove duplicate code starting workers.
66bb167  2015-09-23 Leon Jacobs Code Style fixes
9701167  2015-09-23 Leon Jacobs Log failed jobs to the general log.
5c76f57  2015-09-23 Leon Jacobs Fix Line Seperator to LF
e9eb32d  2015-09-23 Leon Jacobs Add sample XML
2712ac3  2015-09-23 Leon Jacobs Remove unnecessary leading \
acd5c1b  2015-09-23 Leon Jacobs Add Corporation WalletTransaction Update worker
42e8355  2015-09-22 Leon Jacobs Add more transaction uniqueness
b4b5c01  2015-09-22 Leon Jacobs Add missing accountKey arg
c27e7d3  2015-09-22 Leon Jacobs Add Corporation Wallet Journal Update worker
fa876b7  2015-09-22 Leon Jacobs Add primary key for updates
0117329  2015-09-22 Leon Jacobs Add Corporation Titles Update worker
30162a2  2015-09-22 Leon Jacobs Add StarbaseList and Detail Update workers
821b63b  2015-09-22 Leon Jacobs Add Corporation Standing Update worker
ccfa8b6  2015-09-21 Leon Jacobs Add Corporation Shareholders Update worker
6478410  2015-09-21 Leon Jacobs Add Corporation MemberSecurityLog Update worker
84cabb4  2015-09-21 Leon Jacobs Add Corporation MemberTracking Update worker
f860322  2015-09-21 Leon Jacobs Only set titles if the API response had some
eac6568  2015-09-21 Leon Jacobs Add Corporation MemberSecurity Update Worker
92cb2a0  2015-09-21 Leon Jacobs Add Corporation MemberMedals Update worker
adb06db  2015-09-21 Leon Jacobs Add Corporation Medals Update worker
799246d  2015-09-21 Leon Jacobs Add Corporation Market Order Update worker
91b9b8f  2015-09-21 Leon Jacobs Add Corporation KillMail Update worker
422cc28  2015-09-21 Leon Jacobs Add Corporation IndustryJobs Update worker
a8c58c5  2015-09-21 Leon Jacobs Add Corporation Customs Offices Update worker
2bfb7cc  2015-09-20 Leon Jacobs Add Corporation Sheet Update worker
e91a78f  2015-09-20 Leon Jacobs Add Corporation Contract/Items Update worker
c8ba721  2015-09-20 Leon Jacobs Add Corporation ContactList update worker
8042cb9  2015-09-20 Leon Jacobs Update comment
9876ed2  2015-09-19 Leon Jacobs Add Corporation Locations Update worker
4949d96  2015-09-19 Leon Jacobs Add method to find celestials closest to an x,y,z
d7f3844  2015-09-19 Leon Jacobs Add the Corporation Assets Update worker
367d83d  2015-09-18 Leon Jacobs Add Corporation Account Balance worker
85b7ed4  2015-09-18 Leon Jacobs Slightly increase possible value
a02f4f6  2015-09-18 Leon Jacobs Add helper to determine corpID for corp keys
942ee79  2015-09-18 Leon Jacobs Get a fresh instance of the model as it just updated
aaa4e2b  2015-09-18 Leon Jacobs Use relation to get type instead of a new query
0cef16e  2015-09-18 Leon Jacobs Code Style Fixes
3127104  2015-09-18 Leon Jacobs Optimize a few updater workers, fix comments and styling
ed350b6  2015-09-18 Leon Jacobs Check if api_info is available first.
3aabc11  2015-09-18 Leon Jacobs Add EVEAPI error handling
e38f15a  2015-09-18 Leon Jacobs Check if the info relation exists before using
eda56f2  2015-09-17 Leon Jacobs Add test for accessMask checking
efa6bd3  2015-09-17 Leon Jacobs Implement CanCheck to check API key accessmasks
076a608  2015-09-16 Leon Jacobs Improve readability of error output
c327e62  2015-09-16 Leon Jacobs Bump dependencies to stable versions only
d3690c0  2015-09-16 Leon Jacobs Update class comments
d377c46  2015-09-16 Leon Jacobs Move list of update classes to a config file
55c3d31  2015-09-16 Leon Jacobs Fixup tests since the phealng optimization
d0f93b4  2015-09-16 Leon Jacobs Optimize PhealNG usage.
6a0182e  2015-09-15 Leon Jacobs Add Bookmarks Update worker
5cc2f16  2015-09-14 Leon Jacobs Update Badges
72f4a40  2015-09-14 Leon Jacobs Update License
62abf5d  2015-09-14 Leon Jacobs Add Chat Channels Update worker
b1c1890  2015-09-14 Leon Jacobs Fix reference to transactions element
9d17c5e  2015-09-14 Leon Jacobs Add Utils test
effef96  2015-09-14 Leon Jacobs Update License
55a0f70  2015-09-14 Leon Jacobs Use 'hash' as primary key
9a3a1e3  2015-09-14 Leon Jacobs Add Wallet Transactions Update worker
8149688  2015-09-14 Leon Jacobs Add the Wallet Journal update worker
7fb983f  2015-09-14 Leon Jacobs Add Calendar Events Update worker
fc553d5  2015-09-14 Leon Jacobs Add Standings Update worker
b06989c  2015-09-14 Leon Jacobs Add SkillQueue Update worker
faf93b0  2015-09-14 Leon Jacobs Add SkillInTraining Update worker
4ca03ab  2015-09-14 Leon Jacobs Add Character Research Update worker
532b75b  2015-09-14 Leon Jacobs Add Character Market Orders update worker
4d2baeb  2015-09-13 Leon Jacobs Add Planetary Related Update workers
9f82357  2015-09-13 Leon Jacobs Add Character Notification Update workers
985ec34  2015-09-12 Leon Jacobs Add character mailing lists update worker
9a1da2f  2015-09-12 Leon Jacobs Add MailMessage Update worker
fdddcec  2015-09-12 Leon Jacobs Increase size of output column
81bfd5e  2015-09-11 Leon Jacobs Add supporting files for Char KillMail Updater
ea775fd  2015-09-11 Leon Jacobs Add Character KillMail Update worker
53b3b92  2015-09-11 Leon Jacobs Add CharacterInfo Update worker
259f2c6  2015-09-09 Leon Jacobs Add Industry Update worker
4cb4c79  2015-09-09 Leon Jacobs Fix a few small keying issues
75718fe  2015-09-07 Leon Jacobs Add Contract and ContractItems update workers
bb8fdbd  2015-09-07 Leon Jacobs Add Contact Notifications update worker
ae67622  2015-09-07 Leon Jacobs Add ContactList update worker
576e022  2015-09-06 Leon Jacobs Add complete CharacterUpdate worker
77ed8ca  2015-09-05 Leon Jacobs Bump default cURL timeout to 60s
6d15331  2015-09-05 Leon Jacobs Fix issue causing member corp allianceID to be 0
08ef47a  2015-09-05 Leon Jacobs Add the Character AssetsList Updater
0a0f959  2015-09-05 Leon Jacobs Add AccountBalance Update worker
5a65242  2015-09-05 Leon Jacobs Fix up the relationship keys
b12f246  2015-09-05 Leon Jacobs Add a relationship between API Keys and Characters
f20b464  2015-09-05 Leon Jacobs Prevent an errored job from being marked as Done
13ed536  2015-09-05 Leon Jacobs Add AccountStatus sample XML
b26fcf2  2015-09-05 Leon Jacobs Add AccountStatus Updater
93952a3  2015-09-05 Leon Jacobs Update Checker to queue jobs based on key type
c61dd09  2015-09-05 Leon Jacobs Style and docblock fixes
db60993  2015-09-05 Leon Jacobs Abstract some of the repeated Trait usage
7124c77  2015-09-04 Leon Jacobs Constrain the character removals to the key
b5f2f61  2015-09-04 Leon Jacobs Remove unused PhealException
b0063c7  2015-09-04 Leon Jacobs Start the Key pickup worker
3e97b6c  2015-09-04 Leon Jacobs Return the object when setting the key/vcode
99081b7  2015-09-04 Leon Jacobs Group API Tests to be easily excluded by PHPUnit
207a33d  2015-09-04 Leon Jacobs Add the Job Container to resolve Job information
598ed88  2015-09-04 Leon Jacobs Remove unused DispatchesJobs trait
93eec75  2015-09-03 Leon Jacobs Add the API CallList Updater and Test
79f4a16  2015-09-02 Leon Jacobs Add Code Climate
f881d47  2015-09-02 Leon Jacobs Update README
aafe40f  2015-09-02 Leon Jacobs Update travis-ci to include newer PHP and HHVM
d21e557  2015-09-02 Leon Jacobs Add Travis-CI config
3da6a8e  2015-09-02 Leon Jacobs Add tests for the currently implemented calls
21a3f2d  2015-08-31 Leon Jacobs CS Fixes
82c0f51  2015-08-31 Leon Jacobs Add Test to validate ServerStatus API Response
1ee3bb0  2015-08-31 Leon Jacobs Small namespace change for the test
21be320  2015-08-31 Leon Jacobs Start Testing! :)
6d0ed85  2015-08-31 Leon Jacobs Throw an exception if an api key is empty
52ad9b7  2015-08-30 Leon Jacobs Add Map Jumps Update worker
6c4bc86  2015-08-30 Leon Jacobs Add Map Kills update worker
4720ae1  2015-08-30 Leon Jacobs Fix job to actually update if something changes too
6d39cb2  2015-08-30 Leon Jacobs Update Models defining new primary keys
377428b  2015-08-30 Leon Jacobs Modify Migration Indexes
c753ad1  2015-08-30 Leon Jacobs Add Map Sovereignty Update workers
187b336  2015-08-30 Leon Jacobs Add AllianceList update
8fff877  2015-08-29 Leon Jacobs Add ConquerableStationList updater
a75c66e  2015-08-29 Leon Jacobs Add eve/errorlist API call
b02dc11  2015-08-29 Leon Jacobs Add Eve RefTypes API Call
9c61de8  2015-08-29 Leon Jacobs Move Jobs error handling to a trait
8bc8a64  2015-08-29 Leon Jacobs Implement the Job Tracker
0d0ab93  2015-08-29 Leon Jacobs Add a job manager
ca0a6d7  2015-08-29 Leon Jacobs Add generated docblocks
086ebb5  2015-08-29 Leon Jacobs Complete ServerStatus Update
8991564  2015-08-29 Leon Jacobs Start core logic and add server status checker
b6991b9  2015-08-29 Leon Jacobs Start a few things to test job workers
40d4948  2015-08-28 Leon Jacobs Start composer package
af4f12f  2015-08-28 Leon Jacobs first commit
```
### 1.0.0
```
a49216a  2015-11-28 Leon Jacobs (tag: 1.0.0) Version Bump
```
### 1.0.1
```
f4d133a  2015-12-07 Leon Jacobs (tag: 1.0.1) Version Bump
6db0044  2015-12-07 Leon Jacobs Update to Pheal2.3 and use the Guzzle fetcher
4354a90  2015-12-07 Leon Jacobs Reload the info relationship on a key to update accessMask
47ddd2b  2015-12-04 Leon Jacobs Update README.md
```
### 1.0.2
```
dc612d9  2015-12-13 Leon Jacobs (tag: 1.0.2) Version Bump
a8bcd62  2015-12-13 Leon Jacobs Compile a sane user agent for eveapi xml requests
6eced6a  2015-12-13 Leon Jacobs Change - to _
05378b6  2015-12-12 Leon Jacobs Catch the ConnectionException when checking keys
fa6bcf6  2015-12-12 Leon Jacobs Decrement the counters when checking key types
78441a9  2015-12-12 Leon Jacobs Dont increment past the limit
ff3df0a  2015-12-12 Leon Jacobs Add ability to check if the EVE XMLAPI is down.
3ec7598  2015-12-12 Leon Jacobs Add primary key
f954257  2015-12-12 Leon Jacobs Add primary key.
```
### 1.0.3
```
53c168f  2015-12-17 Leon Jacobs (tag: 1.0.3) Add check to job_ids and version bump
```
### 1.0.4
```
7be3801  2015-12-18 Leon Jacobs (tag: 1.0.4) Version Bump
6302a17  2015-12-18 Leon Jacobs Handle some HTTP response codes for expired keys
```
### 1.0.5
```
03101f9  2015-12-20 Leon Jacobs (tag: 1.0.5) Version Bump
5562f03  2015-12-20 Leon Jacobs Add corporation bookmarks updater
17c7c41  2015-12-18 Leon Jacobs Resolve the closest celestials for bookmarks
c7bef60  2015-12-18 Leon Jacobs Only resolve to items that have names
856f66f  2015-12-18 Leon Jacobs Add channel relations
```
### 1.0.6
```
74dcedb  2015-12-24 Leon Jacobs (tag: 1.0.6) Version Bump
fb2e473  2015-12-24 Leon Jacobs Set composer versions using ~
f9fdfb5  2015-12-24 Leon Jacobs Merge pull request #4 from warlof/shareholders
fd53795  2015-12-24 Leon Jacobs Keep track of the closest distance.
9840802  2015-12-24 elfaus  (origin/pr/4) Provide a fix to eveseat/seat issue #21
69e8c3b  2015-12-23 Leon Jacobs Merge pull request #3 from warlof/contactslabels
173f57c  2015-12-23 elfaus  (origin/pr/3) Provide a fix to eveseat/seat issue #5
```
### 1.0.7
```
f816c1d  2015-12-28 Leon Jacobs (tag: 1.0.7) Version Bump
dd72510  2015-12-28 Leon Jacobs Default to an Unknown system
1e41a94  2015-12-28 Leon Jacobs Default to the solarsystemid instead of null
da049c7  2015-12-28 Leon Jacobs Fix eveseat/seat#8 by checking if the body exists before insert
ff48a73  2015-12-27 Leon Jacobs Add the CustomsOfficeLocations API updater
601eb36  2015-12-24 Leon Jacobs Specify phealng version with a ~
a08e970  2015-12-24 Leon Jacobs Remove specific minor version.
a93f674  2015-12-24 Leon Jacobs Bump minimum PHP version
```
### 1.0.8
```
eac8500  2016-01-03 Leon Jacobs (tag: 1.0.8) Version Bump
83cb845  2016-01-03 Leon Jacobs Fix eveseat/seat#37
```
### 1.0.9
```
ab271fa  2016-01-26 Leon Jacobs (tag: 1.0.9) Version Bump
c285f7d  2016-01-26 Leon Jacobs Update copyright
e741457  2016-01-06 Leon Jacobs Code style fixes
```
### 1.0.10
```
3a5c6cf  2016-01-27 Leon Jacobs (tag: 1.0.10) Version Bump
6995d17  2016-01-27 Leon Jacobs Fix eveseat/seat#52 by searching by refTypeID to update
```
### 1.0.11
```
ab985bd  2016-02-09 Leon Jacobs (tag: 1.0.11) Version Bump
d4d4f50  2016-02-09 Leon Jacobs Dont disable on HTTP 403. Too many false positives.
```
### 1.0.12
```
56c8444  2016-03-01 Leon Jacobs (tag: 1.0.12) Version Bump
00d8697  2016-03-01 Leon Jacobs Catch the PhealException to handle XML parsing issues
ab00f40  2016-02-29 Leon Jacobs Temporarily fix eveseat/seat#71 by catching the PhealException
20f00e9  2016-02-29 Leon Jacobs Mark jobs as done in the case of errors.
```
### 1.0.13
```
8f8e0b1  2016-04-29 Leon Jacobs (tag: 1.0.13) Version Bump
e9db18e  2016-04-29 Leon Jacobs Add a block if an admin contact email has not been set.
459d353  2016-04-28 Leon Jacobs Add the new char/Clones and char/Skills endpoints as updaters
ccc7a08  2016-04-28 Leon Jacobs Fix XSD as 2 new endpoints have been added, bumping accessMask to long type
85b21b0  2016-04-28 Leon Jacobs Disable keys that respond with HTTP 403 in APIKeyInfo
```
### 1.0.14
```
c812028  2016-05-02 Leon Jacobs (tag: 1.0.14) Version Bump
55f1ade  2016-05-02 Leon Jacobs Fix eveseat/seat#100 by finding by primary key only.
4451000  2016-05-01 Leon Jacobs Fix eveseat/seat#99 by cleaning up after a key is deleted
```
### 1.0.15
```
c02f338  2016-07-10 Leon Jacobs (tag: 1.0.15) Version Bump
3356cd0  2016-07-09 Leon Jacobs Fix method comment
bd3e928  2016-07-09 Leon Jacobs Handle the `failed()` method on jobs by updating the `JobTracking`.
```
### 1.0.16
```
804bbdc  2016-07-23 Leon Jacobs (tag: 1.0.16) Version Bump
cfdf20c  2016-07-23 Leon Jacobs Report Exception types that have occured.
69de2a2  2016-07-18 Leon Jacobs Add timestamp to error.
87efa4b  2016-07-18 Leon Jacobs Add model for the failed_jobs table
```
### 1.0.17
```
d9af10e  2016-07-23 Leon Jacobs (tag: 1.0.17) Version Bump
1267346  2016-07-23 Leon Jacobs Remove DispatchesJobs trait and use Bus Facade
```
### 1.0.18
```
27bc174  2016-10-14 Leon Jacobs (tag: 1.0.18) Version Bump
ca27d33  2016-08-25 Leon Jacobs Fix imports, comments and codestyle
df05261  2016-08-25 johnnysplunk CharacterInfo API access mask compatability and legacy deprecation (#6)
4123994  2016-08-25 Leon Jacobs Add missing comment
d33d2cf  2016-08-25 Leon Jacobs Merge pull request #5 from warlof/paid-until
ddf666f  2016-08-04 elfaus  (origin/pr/5) adding api_key_status into apiKey relation
```
### 2.0.0-alpha1
```
53a181a  2016-11-26 Leon Jacobs (tag: 2.0.0-alpha1) Update composer for 2.0 packages and version 2.0.0-alpha1
edb45bd  2016-11-25 Leon Jacobs Add a relationship between message headers and bodies.
9983367  2016-11-25 Leon Jacobs Allow for notification on the character sheet
271aa73  2016-11-06 Leon Jacobs Fix type hint to an int instead of string
59a83e5  2016-11-06 Leon Jacobs Move the `Affiliation` updater to a character specific class.
12b0999  2016-11-06 Leon Jacobs Add CharacterAffiliation updater. This is prep for the intel module.
b68cd19  2016-11-05 Leon Jacobs Code formatting fixes
79e30bd  2016-11-04 Leon Jacobs Use logger() helper
34ac286  2016-10-29 Leon Jacobs Extract some error handling up to the base abstract class
77172ec  2016-10-29 Leon Jacobs Cleanup methods, add type hints and remove unused code
f4af243  2016-10-29 Leon Jacobs Make the integer migration a little more understandable.
66c6bba  2016-10-29 Leon Jacobs Add more contact related fields to the integer fixes
c083f61  2016-10-29 Leon Jacobs Start refactoring the job tracking and error handling from a Trait to Class
61af28c  2016-10-27 Leon Jacobs Add migration to fix text sizes
946ee47  2016-10-27 Leon Jacobs Fix labelMask integer sizes.
8699992  2016-10-26 Loïc LEUILLIOT fix migration by disabling sql modes (#7)
bcd15e0  2016-10-24 johnnysplunk Fix for RefTypesModel->refTypeName not updating properly. (#8)
dffd1c9  2016-10-23 Leon Jacobs Pass the the exception thrown into the `failed()` method.
e07f36b  2016-10-20 Leon Jacobs Fix schemas to work with MySQL in strict mode.
58da2c8  2016-10-17 Leon Jacobs Require PHP7 and Laravel 5.3
8071dce  2016-10-17 Leon Jacobs Set the primary key type
91e4b2a  2016-10-17 Leon Jacobs Fix Jobs and dispatcher to accommodate L5.3 changes
e908f11  2016-10-17 Leon Jacobs Rename `lists()` to `pluck()`
```
### 2.0.0
```
06810af  2016-12-08 Leon Jacobs (tag: 2.0.0) Version Bump! 2.0.0! ⚡️
0227052  2016-12-08 Leon Jacobs Update fields to bigInt in light of the recent CCP announcement.
6d62a2d  2016-12-08 Leon Jacobs Fix typos and remove ambogous __CLASS__ reference
3123010  2016-12-08 Leon Jacobs Lazily utf8 encode mail bodies
8496356  2016-12-08 Leon Jacobs Add doctrine/dbal as needed by some migrations.
f4ad084  2016-11-29 Leon Jacobs First iteration of adding worker constraints.
92e2d5d  2016-11-29 Leon Jacobs Improve generic error logging to be aware of the fact that no longer have context of the job_tracker.
cd7b4f8  2016-11-26 Leon Jacobs Drop minimum stability, add prefer-stable and bump to 2.0.0-alpha2.
```
### 2.0.1
```
59f7f5f  2016-12-10 Leon Jacobs (tag: 2.0.1) Version Bump
199741d  2016-12-10 Leon Jacobs Fix eveseat/seat#153 by casting the string to an int.
0ea98a4  2016-12-09 Leon Jacobs Update Travis to only allow PHP 7 now.
```
### 2.0.2
```
c11c64a  2016-12-11 Leon Jacobs (tag: 2.0.2) Version bump
c62c2ed  2016-12-11 Leon Jacobs Increase the reason field length for corp_member_medals.
```
### 2.0.3
```
b6000b7  2016-12-12 Leon Jacobs (tag: 2.0.3) Version Bump
ec9368b  2016-12-12 Leon Jacobs Fix eveseat/seat#155 by increasing column size.
```
### 2.0.4
```
40d5a34  2016-12-13 Leon Jacobs (tag: 2.0.4) Version Bump
737f28c  2016-12-13 Leon Jacobs Experimental performance patch by making the PhealFetcher a singleton.
f00190d  2016-12-12 Leon Jacobs Remove the Pheal Rate limit setting and use the defaults.
```
### 2.0.5
```
d1658a3  2016-12-21 Leon Jacobs (tag: 2.0.5) Version Bump
4072f01  2016-12-21 Leon Jacobs Update travis yaml with root package version
70b4f66  2016-12-21 Leon Jacobs Remove useless log entry
60af828  2016-12-21 Leon Jacobs Formatting & typo fixes.
8f3ce57  2016-12-21 Leon Jacobs Allow for the joblog to be disabled via a config setting.
1c8516f  2016-12-20 Leon Jacobs Fix typo
826f3cf  2016-12-20 Leon Jacobs Add update worker job logging
```
### 2.0.6
```
fe3fd7a  2016-12-22 Leon Jacobs (tag: 2.0.6) Version Bump
0f6cb57  2016-12-22 Leon Jacobs Log constraints to the joblog
```
### 2.0.7
```
7ba4970  2016-12-28 Leon Jacobs (tag: 2.0.7) Version Bump
d370866  2016-12-28 Leon Jacobs Use the same queue priority as the parent job.
260b854  2016-12-28 Leon Jacobs Update reason for disabling key.
e05a24a  2016-12-28 Leon Jacobs Add a grace error count before disabling API keys
296e24f  2016-12-28 Leon Jacobs Dont update Courier ContractsItems
2fae54f  2016-12-28 Leon Jacobs Add link to docs for more information.
```
### 2.0.8
```
aa25f97  2017-01-01 Leon Jacobs (tag: 2.0.8) Version Bump
3cad74d  2017-01-01 Leon Jacobs Fix eveseat/seat#159 by checking if the titles isset first.
```
### 2.0.9
```
73a778f  2017-01-12 Leon Jacobs (tag: 2.0.9) Version Bump
f7b9b8e  2017-01-12 freedenizen Character Assets are now pulled recursively (#12)
91508da  2017-01-12 Leon Jacobs Style fix
fb68a10  2017-01-12 Leon Jacobs Improve queue job handling.
6d945c0  2017-01-11 Leon Jacobs Remove queue tries check.
54b8297  2017-01-04 Leon Jacobs Update styleci config
7d513eb  2017-01-02 Leon Jacobs Apply fixes from StyleCI (#10)
4577068  2017-01-02 Leon Jacobs Add StyleCI configuration & badge
f1a93d2  2017-01-02 Loïc LEUILLIOT avoid primary key duplication if more than a worker is working on the same characterID (#9)
93b2124  2017-01-01 Leon Jacobs Style fixes
```
### 2.0.10
```
57cefe6  2017-02-19 Leon Jacobs (tag: 2.0.10) Version bump
f7d0f14  2017-02-19 Leon Jacobs Dont enable job logging by default
7b80128  2017-01-20 Leon Jacobs Add codeclimate configuration
```
### 2.0.11
```
dc0473a  2017-04-17 Leon Jacobs (tag: 2.0.11) Version Bump
f68007a  2017-04-17 Loïc LEUILLIOT avoid duplicate entry on character notification update (#17)
c80e611  2017-04-17 Loïc LEUILLIOT fix an issue which allow an empty response to be processed (#16)
```
### 2.0.12
```
017729d  2017-05-07 Leon Jacobs (tag: 2.0.12) Version Bump
24e19c1  2017-05-07 Leon Jacobs Remvove characterID & corporationID checks.
```
### 2.0.13
```
e763e48  2017-08-12 Leon Jacobs (tag: 2.0.13, master) Version Bump
8d0eced  2017-08-12 Leon Jacobs Style fixes.
9e36c80  2017-08-12 Loïc LEUILLIOT add industry jobs history to industry job and fix CCP shit on job status (#21)
465e6cf  2017-08-12 Loïc LEUILLIOT optimise dashboard query for top mail badge by adding an index on sentDate (#20)
```
### 2.0.14
```
8a00bfa  2017-10-25 Leon Jacobs (tag: 2.0.14) Version Bump.
e5729f6  2017-10-25 Leon Jacobs Small formatting fixes and add missing function comment.
025f51a  2017-10-25 Loïc LEUILLIOT provide hotfix for people & group when a key is deleted (#22)
```
### 3.0.0-beta1
```
228e6ce  2018-04-29 Leon Jacobs (tag: 3.0.0-beta1) Upgrade packages and version 3.0.0-beta1
857e258  2018-04-29 Leon Jacobs Remove unit testing for now.
81ac516  2018-04-29 Leon Jacobs Apply fixes from StyleCI (#73)
17131ea  2018-04-29 Leon Jacobs Indentation and sorting fixes.
0fd71c6  2018-04-29 Leon Jacobs Fix various typos and annotator warnings.
fac24cf  2018-04-29 Leon Jacobs Formatting and style fixes.
8aa74a1  2018-04-29 Loïc LEUILLIOT integrate eveseat-mining-ledger in core (#70)
144d9c5  2018-04-28 Leon Jacobs Handle invalid refresh_tokens.
46739d1  2018-04-28 Loïc LEUILLIOT Fix deprecated endpoints (#72)
1e9524c  2018-04-28 Loïc LEUILLIOT prune chat channels (#71)
b8864e6  2018-04-28 Loïc LEUILLIOT prepare job for missing corporation contact labels according to ccp-zoetrope feedback ccpgames/esi-issues#779 (#68)
40bd8df  2018-04-22 Leon Jacobs Add corporation_roles() relationship.
ccd54c5  2018-04-18 Leon Jacobs Extrax maximum cycle requests to a property.
19ad66f  2018-04-18 Leon Jacobs Refactor the corporation contract items throttler.
7a9b0c8  2018-04-18 Leon Jacobs Backoff workers if cached responses were loaded.
0cdc564  2018-04-18 Leon Jacobs Minor style and format changes.
696b982  2018-04-18 Loïc LEUILLIOT Esi intel (#67)
4a983e0  2018-04-17 Leon Jacobs Begin testing early cached backoffs for updaters.
13623b3  2018-04-17 Leon Jacobs Apply fixes from StyleCI (#66)
8f0b6a4  2018-04-16 Loïc LEUILLIOT persist unknown structure only if we don't already have it (#64)
e284415  2018-04-03 Loïc LEUILLIOT Fix roles scopes (#63)
a2e98b2  2018-04-02 Leon Jacobs Set Eseye logfie & cache path via config.
5b43af0  2018-04-02 Leon Jacobs Restore scopes needed for PI data.
2212dd5  2018-03-31 Leon Jacobs Relate refresh tokens with users.
00820e1  2018-03-30 Loïc LEUILLIOT Corporation 3.x Update Endpoints (#62)
111bc68  2018-03-18 Leon Jacobs Disable writable scopes.
d78584b  2018-03-18 Loïc LEUILLIOT Improve doc related to categoryID filter on name and location jobs (#61)
c9f564d  2018-03-17 Leon Jacobs Fix some typos.
1a5c263  2018-03-17 Leon Jacobs Minor formatting changes.
bca7f71  2018-03-17 Loïc LEUILLIOT Corporation 3.x (#60)
3fcf174  2018-03-02 Loïc LEUILLIOT fix corporation sheet with ESI upgrade (#58)
51531e2  2018-02-17 Leon Jacobs Minor refactorings.
43e5d19  2018-02-17 Loïc LEUILLIOT Add model relations, Universe related jobs and other bugfixes.
5101748  2018-02-05 Leon Jacobs Minor refactorings and introduction of IsReadOnly trait.
5491401  2018-02-05 Loïc LEUILLIOT add few model relation related to character sheet view (#44)
379fe57  2018-01-27 Leon Jacobs Minor class definition bugfixes.
dfb069c  2018-01-26 Leon Jacobs Fix SSO scope checking that require in game roles too.
582f2f4  2018-01-26 Leon Jacobs Remove hardcoded character_id.
fadef7b  2018-01-26 Leon Jacobs Add authentication check to jobs.
c047f8c  2018-01-26 Leon Jacobs Add more job scope requirements and tags fixes.
2f24143  2018-01-25 Leon Jacobs Add updaters scope definitions and other small fixes.
aaff317  2018-01-24 Leon Jacobs Remove unnecessary else.
f9f1b21  2018-01-24 Leon Jacobs Use configuration file for endpoint role requirement lookups.
2921a14  2018-01-24 Leon Jacobs Add scopes and roles checker for jobs.
2b09221  2018-01-23 Leon Jacobs Update Extraction updater to Station_Manager role.
3a3a82a  2018-01-23 Leon Jacobs Add a corporation job < - > ingame role mapping.
a1294bb  2018-01-23 Ed Stafford Replaced duplicate column with index creation. (#42)
abe7d90  2018-01-23 Leon Jacobs Add corporation members titles updater.
969c723  2018-01-22 Leon Jacobs RIP XML API. 💀
0775169  2018-01-22 Leon Jacobs Add missing docblock.
4f96333  2018-01-22 Loïc LEUILLIOT Esi calendar attendees (#41)
4a8c2c7  2018-01-22 Leon Jacobs Add foreign key constraint to alliance members and other fixes.
7d4c70a  2018-01-22 Loïc LEUILLIOT implement alliance endpoints (#40)
3be73f6  2018-01-22 Loïc LEUILLIOT Add job tags and fix tags method so we can make public call (#37)
f0a64f3  2018-01-21 Leon Jacobs Add missing docblocks and style fixes.
ba7c4a3  2018-01-21 Loïc LEUILLIOT add job for calendar attendee endpoint (#39)
42fa5fe  2018-01-21 Leon Jacobs Formatting and namespace updates.
55ddfa5  2018-01-21 Loïc LEUILLIOT Observer detail (#36)
a4f3be5  2018-01-20 Leon Jacobs Add corporation market orders updater.
b6047cf  2018-01-20 Leon Jacobs Add corporation killmails updater.
ce3fa16  2018-01-20 Leon Jacobs Add corporation mining observer udpater.
91f27fd  2018-01-20 Leon Jacobs Add corporation mining extractions updater.
5914ac1  2018-01-20 Leon Jacobs Add corporatino industry jobs updater.
9cb5f7f  2018-01-20 Leon Jacobs Fix table pluralisation and various other docblocks/syntax.
d35caf1  2018-01-20 Leon Jacobs Update license to GPL-2.0-or-later so packagist can update.
b2f7ea9  2018-01-20 Loïc LEUILLIOT add corporation member limit and wallet endpoints (#33)
ad75ff7  2018-01-20 David Davaham Fix eveseat/eveapi#232 (#34)
3bef78c  2018-01-19 Leon Jacobs Add character affiliations updater.
e75ac70  2018-01-19 Leon Jacobs Minor refactors and docblock updates.
3c86581  2018-01-19 Loïc LEUILLIOT Add more corporation endpoints (#32)
6fcfb9f  2018-01-18 Leon Jacobs Code formatting and docblock fixes.
ef8a4ac  2018-01-18 Loïc LEUILLIOT Improve corporation endpoint parity (#31)
be59da9  2018-01-17 Leon Jacobs Add missing docblocks and getCharacterId -> getCorporationId fixes.
5d3ef6c  2018-01-17 Loïc LEUILLIOT Provide support for some more root level corporation endpoints (#30)
d513281  2018-01-16 Leon Jacobs Add character contract items & bids updater and fix character udpaters.
02c53af  2018-01-16 Leon Jacobs Add corporation contacts updater.
ef9e48c  2018-01-15 Leon Jacobs Add corporation bookmarks folder updater.
9857722  2018-01-15 Leon Jacobs Add paginator and cleanups to the corporation bookmarks updater.
a3839ff  2018-01-14 Leon Jacobs Remove debugging code.
5b34fa7  2018-01-14 Leon Jacobs Remove debug code.
5a38c1f  2018-01-14 Loïc LEUILLIOT end medals implementation (#29)
7f30130  2018-01-14 Leon Jacobs Minor docblock updates.
2220ba5  2018-01-14 Loïc LEUILLIOT Complete Character PI updater (#28)
c4cbcc4  2018-01-14 Leon Jacobs Add corporation bookmarks updater.
d303570  2018-01-14 Leon Jacobs Do not pick celestials with a 0.0 position
18df457  2018-01-14 Leon Jacobs [WIP] Add corporation asset location and name endpoints.
1ba7ed1  2018-01-14 Leon Jacobs Add corporations assets updater.
bbaf673  2018-01-14 Leon Jacobs Update workers to be more Horizon friendly.
e0b76f1  2018-01-14 Leon Jacobs Remove unused, XML API related classes.
5a859b3  2018-01-13 Leon Jacobs Add character wallet transactions updater.
719cddf  2018-01-13 Leon Jacobs Add character wallet balance and journal updaters.
e5bbbe5  2018-01-13 Leon Jacobs Move character skills updater to different namespace.
d5731a8  2018-01-12 Leon Jacobs Add character skill queue updater.
5cb6bf8  2018-01-12 Leon Jacobs Add character attributes updater.
1c3673c  2018-01-12 Leon Jacobs Add server status updater.
f99b1dd  2018-01-11 Leon Jacobs Add character PI planets updater.
306aad0  2018-01-11 Leon Jacobs Add character market order updater.
7b6b0c4  2018-01-11 Leon Jacobs Add character shup updater files. 🤖
040c733  2018-01-11 Leon Jacobs Add character ship updater.
2aa07e1  2018-01-11 Leon Jacobs Add character online updater.
07fa346  2018-01-11 Leon Jacobs Remove debuggin code.
5062a21  2018-01-11 Leon Jacobs Add character location updater.
74f0f0b  2018-01-10 Leon Jacobs [WIP] Add character killmails victim and attacker updaters.
3e3f3ff  2018-01-09 Leon Jacobs [WIP] Add characters killmail updater.
7e26a10  2018-01-09 Leon Jacobs Add character mining ledger updater.
55f68b0  2018-01-09 Leon Jacobs Formatting fixes and a minor optimization for agent research updater.
ee83088  2018-01-09 Loïc LEUILLIOT Character skills and update character_id table column type (#27)
cdd0832  2018-01-08 Leon Jacobs Add indexes on industry jobs table.
69cfa89  2018-01-08 Leon Jacobs Add character industry jobs updater.
bef12c6  2018-01-07 Loïc LEUILLIOT fix fitting relation issue and add a primary key on fitting_item table (#26)
6dc3e3d  2018-01-07 Leon Jacobs Add character fittings updater.
5264648  2018-01-07 Leon Jacobs Add character contracts items updater.
96178b1  2018-01-07 Leon Jacobs Add character contract bids updater.
ade06bd  2018-01-07 Leon Jacobs Add character contracts updater.
e3d922c  2018-01-07 Leon Jacobs Add character contact labels updater.
738c814  2018-01-07 Leon Jacobs Add character contacts updater.
1de19da  2018-01-07 Leon Jacobs Add character implants updater.
5cc40a5  2018-01-07 Leon Jacobs Add character jump clone updater.
2c29a5e  2018-01-07 Leon Jacobs Add character calendar event detail updater.
0164725  2018-01-07 Leon Jacobs Add character calender events updater.
82a606b  2018-01-07 Leon Jacobs Add check if a paged response was expected but not given.
cc38477  2018-01-07 Leon Jacobs Add character bookmark folders updater.
8d12a2a  2018-01-07 Leon Jacobs [WIP] Add character bookmarks updater.
e280456  2018-01-06 Leon Jacobs Add character assets, locations and names updaters.
d3cf187  2018-01-06 Leon Jacobs Allow for jobs to set a request body.
c97d15e  2018-01-05 Leon Jacobs Add character mailing lists updater.
996232e  2018-01-05 Leon Jacobs Add character mail labels updater.
0213a1a  2018-01-05 Leon Jacobs Add character mail updaters.
f09a775  2018-01-05 Leon Jacobs Add character titles updater.
33caeeb  2018-01-05 Leon Jacobs Add character stats updater.
0a756e8  2018-01-05 Leon Jacobs Fix exception throwing for the Warning header.
6c0698c  2018-01-05 Leon Jacobs Throw exceptions if responses contain the Warning header.
1381136  2018-01-04 Leon Jacobs Add character standings updater.
d371385  2018-01-04 Leon Jacobs Add character roles updater.
f89fd32  2018-01-04 Leon Jacobs Remove older XML API helpers.
662321e  2018-01-04 Leon Jacobs Add character notifications updater.
9aa65d6  2018-01-04 Leon Jacobs Add character medals updater.
c70349d  2018-01-04 Leon Jacobs Add character jump fatigue updater.
d7ca222  2018-01-04 Leon Jacobs Add character corporation history updater.
e1226d1  2018-01-04 Leon Jacobs Throw exception if an unexpected paged response is received.
64fc698  2018-01-04 Leon Jacobs Add Character Chat Channel updater.
8ecd74a  2018-01-03 Leon Jacobs Fix typo.
4593ec8  2018-01-03 Leon Jacobs Remove old SeAT 2.x models and database migrations.
c1df71b  2018-01-03 Leon Jacobs Fix code style and add indexes.
bfaa272  2018-01-03 Leon Jacobs Add blueprints updater with paging support.
3a5dc5f  2018-01-03 Leon Jacobs Add first ESI Character Info updater.
af24fa0  2018-01-03 Leon Jacobs Fix property scopes.
1decf9a  2018-01-03 Leon Jacobs Update job class structures to use properties
9756307  2017-12-28 Leon Jacobs [WIP] First pass at adding ESI as a data source.
640427a  2017-12-23 Leon Jacobs [WIP] Add support for refresh token storage.
0ce7233  2017-10-25 Sascha Ohms fix duplicate entry erro while inserting jump clones (#23)
```
### 3.0.0-beta2
```
b324a16  2018-04-29 Leon Jacobs (tag: 3.0.0-beta2) v3.0.0-beta2
```
### 3.0.0-beta3
```
5aad9e0  2018-05-02 Leon Jacobs (tag: 3.0.0-beta3) v3.0.0-beta3
1cf129a  2018-05-02 Leon Jacobs Add relationships.
efd6474  2018-05-01 Leon Jacobs Add more relationships.
a29980a  2018-05-01 Leon Jacobs Rename trait and formatting fixes.
97117b2  2018-05-01 Loïc LEUILLIOT Prices bulkinsert (#74)
```
### 3.0.0-beta4
```
29b3f70  2018-05-05 Leon Jacobs (tag: 3.0.0-beta4) v3.0.0-beta4
deca315  2018-05-05 Loïc LEUILLIOT fix job time using bulk insert (#78)
82deca1  2018-05-04 Leon Jacobs Comments and formatting updates.
e1febf0  2018-05-04 Loïc LEUILLIOT skip NPC corporation from jobs (#77)
3bc116e  2018-05-03 Loïc LEUILLIOT Add mail relationships (#76)
aceb24f  2018-05-03 Loïc LEUILLIOT fix user relationship (#75)
b0f60fd  2018-05-03 Leon Jacobs Add relationships.
```
### 3.0.0-beta5
```
3e53350  2018-05-06 Leon Jacobs (tag: 3.0.0-beta5) v3.0.0-beta5
3694171  2018-05-06 Leon Jacobs Remove extra space.
bfa6e99  2018-05-06 Leon Jacobs Add configuration options for Eseye log levels.
d8d7b2b  2018-05-06 Loïc LEUILLIOT Longrunning jobs (#81)
69913d5  2018-05-05 Loïc LEUILLIOT Fix mining jobs detail endpoint (#80)
47978c4  2018-05-05 Leon Jacobs Apply fixes from StyleCI (#79)
```
### 3.0.0-beta6
```
a2269b4  2018-05-06 Leon Jacobs (tag: 3.0.0-beta6) v3.0.0-beta6
a3120c1  2018-05-06 Leon Jacobs Only specify the log directory.
```
### 3.0.0-beta7
```
c72beed  2018-05-07 Leon Jacobs (tag: 3.0.0-beta7) v3.0.0-beta7
087781a  2018-05-07 Leon Jacobs Report deprecations and endpoint warnings.
74e4861  2018-05-07 Leon Jacobs Restore exception analytics.
dba09c4  2018-05-07 Leon Jacobs Include 'Director' as a valid role.
67aaabf  2018-05-07 Leon Jacobs Restore cache check.
5b5518f  2018-05-07 Leon Jacobs Finally, add character bookmarks updater.
447c9c8  2018-05-07 Leon Jacobs Only persist the structure if it does not exist.
```
### 3.0.0-beta8
```
07d9491  2018-05-08 Leon Jacobs (tag: 3.0.0-beta8) v3.0.0-beta8
91baaa8  2018-05-08 Leon Jacobs Style fixes.
df1ac86  2018-05-08 Loïc LEUILLIOT Skip npc jobs (#84)
```
### 3.0.0-beta9
```
533b7da  2018-05-10 Leon Jacobs (tag: 3.0.0-beta9) v3.0.0-beta9
3999135  2018-05-10 Loïc LEUILLIOT More bulk inserted jobs (#88)
20bd291  2018-05-09 Loïc LEUILLIOT Fix nullpartyid nameresolver (#87)
a925f99  2018-05-09 Loïc LEUILLIOT Fix corpindyminingobserverdata (#86)
017baff  2018-05-09 Loïc LEUILLIOT Add missing cachecheck (#85)
```
### 3.0.0-beta10
```
f602faa  2018-05-11 Leon Jacobs (tag: 3.0.0-beta10) v3.0.0-beta10
4372f54  2018-05-11 Loïc LEUILLIOT Fix npc corp range (#89)
```
### 3.0.0-beta11
```
3546247  2018-05-14 Leon Jacobs (tag: 3.0.0-beta11) v3.0.0-beta11
0564cbc  2018-05-14 Ben     Fix Mining ObserverDetails job (#91)
24966ec  2018-05-14 Loïc LEUILLIOT Fix firstOrCreate and firstOrNew in order to avoid integrity issue (#90)
```
### 3.0.0-beta12
```
ee2afeb  2018-05-16 Leon Jacobs (tag: 3.0.0-beta12) v3.0.0-beta12
26a5b14  2018-05-15 Leon Jacobs Ensure type is set before attempting to access its name.
```
### 3.0.0-beta13
```
16147ee  2018-05-18 Leon Jacobs (tag: 3.0.0-beta13) v3.0.0-beta13
62fe633  2018-05-18 Leon Jacobs Limit the universe structures endpoint until :ccp: fixes it.
dade426  2018-05-17 Leon Jacobs Update docblocks and formatting.
6df3fff  2018-05-17 Loïc LEUILLIOT reduce alliance info job time by dispatching dedicated job for each alliance (#94)
0856a73  2018-05-17 Leon Jacobs Formatting fixes.
f467c08  2018-05-17 Argon Inkura The Ship Update Job will now fetch the characters ship type id  (#93)
436e017  2018-05-16 Loïc LEUILLIOT Exclude empty contract from contract item job (#92)
```
### 3.0.0-beta14
```
b924507  2018-05-19 Leon Jacobs (tag: 3.0.0-beta14) v3.0.0-beta14
d7d5050  2018-05-18 Loïc LEUILLIOT fix mail_labels primary key and indexes in order to avoid deadlock (#95)
```
### 3.0.0-beta15
```
75eb798  2018-05-19 Leon Jacobs (tag: 3.0.0-beta15) v3.0.0-beta15
cde417d  2018-05-19 Leon Jacobs Fix mail_label index migration.
```
### 3.0.0-beta16
```
856919f  2018-05-20 Leon Jacobs (tag: 3.0.0-beta16) v3.0.0-beta16
0039be4  2018-05-20 Leon Jacobs Add relationships.
1f7c3d8  2018-05-20 Leon Jacobs Fix style.
cbed5c8  2018-05-20 Leon Jacobs Limit the total runtime for the contract items updater.
978614e  2018-05-20 Leon Jacobs Improve query and rate limit character assets universe name lookups.
```
### 3.0.0-beta17
```
6f5a01e  2018-05-24 Leon Jacobs (tag: 3.0.0-beta17) v3.0.0-beta17
51e90e5  2018-05-24 Loïc LEUILLIOT fix job dispatcher for alliance (#96)
```
### 3.0.0-beta18
```
9857681  2018-05-27 Leon Jacobs (tag: 3.0.0-beta18) v3.0.0-beta18
c736336  2018-05-27 Leon Jacobs Remove extra newline.
9c1b7e9  2018-05-27 Leon Jacobs Add relationships for model cleanups.
c3b56f2  2018-05-27 Leon Jacobs Include an exception threshold.
a6188d0  2018-05-27 Leon Jacobs Add missing preflight checks.
d2341ec  2018-05-27 Leon Jacobs Cache ESI status.
1d45f32  2018-05-27 Leon Jacobs Apply fixes from StyleCI (#99)
99e656d  2018-05-27 Leon Jacobs Add missing newline.
833c8bb  2018-05-27 Leon Jacobs Refactor authenticated check to a generic preflight check.
d4577c1  2018-05-26 Loïc LEUILLIOT fix affiliation job (#98)
f348855  2018-05-26 Loïc LEUILLIOT ensure we really stop pulling NPC corp information (#97)
```
### 3.0.0-beta19
```
315a8d4  2018-05-27 Leon Jacobs (tag: 3.0.0-beta19) v3.0.0-beta19
f0420d2  2018-05-27 Leon Jacobs Cater for cases where a status is not yet know.
```
### 3.0.0-beta20
```
24ff52a  2018-05-28 Leon Jacobs (tag: 3.0.0-beta20) v3.0.0-beta20
ecfa73a  2018-05-28 Ben     Update CustomsOfficeLocations.php (#101)
171748c  2018-05-28 Ben     Fix https://github.com/eveseat/seat/issues/346 (#100)
```
### 3.0.0-beta21
```
cbaac66  2018-05-30 Leon Jacobs (tag: 3.0.0-beta21) v3.0.0-beta21
1065f7c  2018-05-29 Leon Jacobs Update relationships.
```
### 3.0.0-beta22
```
10ce346  2018-05-31 Leon Jacobs (tag: 3.0.0-beta22) v3.0.0-beta22
8dd1e83  2018-05-31 Leon Jacobs Rename insertOnDuplicateKey to upsert().
00f3a80  2018-05-31 Leon Jacobs Convert contracts items updater to upsert.
f440473  2018-05-31 Leon Jacobs Fix corporation contract items job throttling.
92c4955  2018-05-31 Loïc LEUILLIOT denying all pull attempt from Corp job with NPC corp (#102)
```
### 3.0.0-beta23
```
c5d7c66  2018-06-13 Leon Jacobs (tag: 3.0.0-beta23) v3.0.0-beta23
03beeda  2018-06-13 Loïc LEUILLIOT fix job tag (#105)
9aaf46a  2018-06-09 Leon Jacobs Apply fixes from StyleCI (#104)
4dcfa88  2018-06-09 Leon Jacobs Perform soft deletes on RefreshTokens.
ecc127f  2018-06-09 Loïc LEUILLIOT drop outdated skills from queue (#103)
```
### 3.0.0
```
5ec1877  2018-06-16 Leon Jacobs (tag: 3.0.0) v3.0.0 🎉
```
### 3.0.1
```
74cf25d  2018-06-24 Leon Jacobs (tag: 3.0.1) v3.0.1
ed929f6  2018-06-24 Leon Jacobs Rename references to garbage collection and fix array access.
12c20ed  2018-06-24 Loïc LEUILLIOT add garbage collector on PI job (#106)
```
### 3.0.2
```
b3b50c4  2018-06-30 Leon Jacobs (tag: 3.0.2) v3.0.2
185dbef  2018-06-30 Leon Jacobs Remove depracted outposts updater.
```
### 3.0.3
```
7b84940  2018-07-29 Leon Jacobs (tag: 3.0.3) v3.0.3
99c0e60  2018-07-29 Loïc LEUILLIOT add skill cleaner as CCP may remove some skills from the game (#109)
ace3516  2018-07-29 Loïc LEUILLIOT Improve api docs (#108)
2cb5dd6  2018-07-29 Herpaderp Aldent Enabler: Include Main Character to MemberTracking (#107)
```
### 3.0.4
```
d20bd70  2018-08-20 Leon Jacobs (tag: 3.0.4) v3.0.4
ea81668  2018-08-17 Leon Jacobs Fix typo.
a642e4e  2018-08-17 Loïc Leuilliot feat(character): Add the relation to character_info_skills (#115)
79fdf35  2018-08-17 Loïc Leuilliot fix(corporation tracking): fix last location column (#114)
1779898  2018-08-17 Loïc Leuilliot fix(jump clones): Display name of player structure (#113)
bea007b  2018-08-17 Loïc Leuilliot feat(contacts): Bump both character and corporation contacts endpoint to v2 (#112)
47eb7b9  2018-08-17 Loïc Leuilliot fix(mail): Add missing cast definition on MailHeader (#111)
e14b4c2  2018-08-17 Leon Jacobs Formatting fixes.
5cee7c3  2018-08-17 Loïc Leuilliot Fix structure resolving (#110)
```
### 3.0.5
```
ff5b558  2018-09-09 Leon Jacobs (tag: 3.0.5) v3.0.5
3b68764  2018-09-09 Loïc Leuilliot feat(mining): use ore materials to compute amount instead itself (#119)
91a526d  2018-09-09 Loïc Leuilliot fix(structure resolver): Improve queries returning structure_id (#117)
```
### 3.0.6
```
16a0f1a  2018-09-09 Leon Jacobs (tag: 3.0.6) v3.0.6
a4dc6e0  2018-09-09 Loïc Leuilliot Merge pull request #120 from warlof/structuretoarray
9566b80  2018-09-09 Loïc LEUILLIOT (warlof/structuretoarray) fix(structure): Fix ternary init to return array instead object
```
### 3.0.7
```
99e8e22  2018-10-04 Leon Jacobs (tag: 3.0.7) v3.0.7
05069c9  2018-09-16 Herpaderp Aldent feat(prices): Lock mining values
```
### 3.0.8
```
29c88ef  2018-12-03 Loïc LEUILLIOT (tag: 3.0.8) v3.0.8
44a4193  2018-12-03 Loïc Leuilliot Outdated endpoints (#131)
```
### 3.0.9
```
5c1af39  2018-12-08 Loïc LEUILLIOT (tag: 3.0.9) build(core): v3.0.9
c049949  2018-12-08 Loïc LEUILLIOT fix(corporation): Update corporation killmails according to partials update
4a9b595  2018-12-08 Loïc LEUILLIOT fix(corporation): Update corporation journal according to partials update
b2bbe72  2018-12-08 Herpaderp Aldent [feat](mails): Add sender to relation eager load
15c96a5  2018-12-08 Herpaderp Aldent [feat](wallet): Add client to eager load relationship
2d46cc3  2018-12-06 Herpaderp Aldent [feat](killmails): Use ORM relationship in order to avoid raw JOIN
fabbf44  2018-12-06 Herpaderp Aldent [feat](core): Use new migration mechanic
d964f4c  2018-12-03 Loïc LEUILLIOT Merge branch '3.0.x'
68698b3  2018-11-03 Loïc Leuilliot fix(sde): Remove typeID special attribute as it is already defined (#126)
ab76b81  2018-11-03 Loïc Leuilliot fix(jobs): Fix required role for extraction job (#125)
7fbd8b7  2018-10-28 Loïc Leuilliot fix(token management): Revoke access_token when it does not match with client app. (#124)
5e24eb7  2018-10-28 Loïc Leuilliot fix(mining ledger): Fix loading time issue due to prices eager-load (#123)
```
### 3.0.10
```
b34a2ad  2019-01-13 Loïc LEUILLIOT (tag: 3.0.10) build(core): v3.0.10
40bfb98  2019-01-07 Loïc Leuilliot * feat(sde): Increase information returned by MapDenormalize model
38c3634  2019-01-07 Loïc Leuilliot feat(versions): Implement new version management for EveAPI package (#137)
385a7a3  2019-01-06 Loïc Leuilliot fix(character): Fix a typo into the ancestry column from character entity (#141)
ab77a3f  2019-01-06 Loïc Leuilliot feat(notifications): Update notification endpoint according to latest ESI spec changes (#140)
d3da788  2019-01-06 Loïc Leuilliot fix(structures): Ensure structure data are properly persisted in database (#138)
03697c3  2018-12-11 Justin Mercer [fix](mining) Observer mining data needs last_updated as a primary key (#134)
```
### 3.0.11
```
3fb212d  2019-03-23 Loïc LEUILLIOT (tag: 3.0.11) build(core): v3.0.11
12b7f1e  2019-03-23 Loïc LEUILLIOT chore(licence): Update licence header to include 2019
76fa22a  2019-03-23 Loïc LEUILLIOT Merge branch '3.0.x'
6378d04  2019-03-23 Loïc LEUILLIOT fix(esi): Add missing migration for universe names v3
9a5d71d  2019-03-23 Loïc LEUILLIOT Merge branch '3.0.x'
59cf664  2019-03-23 Loïc Leuilliot feat(esi): Bump ESI endpoints promoted on January 2019 (#144)
514f29f  2019-03-10 Herpaderp Aldent feat(sheet): Add Solar System to the character sheet (#147)
caea62e  2019-02-19 Herpaderp Aldent Introduce public corporation history updater (#143)
102b139  2019-02-19 Herpaderp Aldent Public job character infos (#142)
7078349  2019-02-18 Leon Jacobs Apply fixes from StyleCI (#146)
3e65131  2019-02-07 Herpaderp Aldent Include mailing_list relation and remove injection (#136)
6105e1e  2019-02-07 Herpaderp Aldent Set Historical Prices for mined ore: (#127)
```
### 3.0.12
```
73e4fe4  2019-05-14 Loïc LEUILLIOT (tag: 3.0.12) build(core): v3.0.12
e48befd  2019-05-14 Loïc Leuilliot feat(esi): bump ESI endpoint promoted on May 2019 (#156)
c530582  2019-05-12 Jabasukuriputo Wang feat(relationship): add characters and alliance to corporation model (#155)
ebbbdb7  2019-04-22 Loïc Leuilliot feat(jobs): Reduce duplicated jobs (#135)
462b004  2019-04-22 Loïc Leuilliot feat(core): Allow to use alternative SSO and ESI endpoints (#151)
a84feef  2019-04-22 Loïc Leuilliot fix(jobs): Mitigate jobs issues (#149)
9457eea  2019-04-22 Loïc Leuilliot feat(assets): always store assets coordinates (#153)
```
### 3.0.13
```
3f6956d  2019-05-20 Loïc LEUILLIOT (tag: 3.0.13) build(core): v3.0.13
e866c72  2019-05-20 Jabasukuriputo Wang fix(relationship): fix a reference error (#158)
4aeb132  2019-05-19 Loïc Leuilliot fix(config): put environment variables into config file (#157)
```
### 3.0.14
```
56ed6ea  2019-06-13 Loïc LEUILLIOT (tag: 3.0.14) build(core): v3.0.14
ef77b41  2019-06-13 Loïc Leuilliot fix(jobs): reduce the token renewal flow by retrieving up-to-date token (#159)
e9e5aa6  2019-06-13 Loïc Leuilliot revert(jobs): reduce duplicated jobs (#160)
```
### 3.0.15
```
4c4cf53  2019-07-02 Loïc LEUILLIOT (tag: 3.0.15) build(core): v3.0.15
a837225  2019-07-02 Loïc LEUILLIOT feat(esi): bump character notification endpoint
```
### 3.0.16
```
dd3e5b6  2019-08-03 Loïc LEUILLIOT (tag: 3.0.16) build(core): v3.0.16
86519d6  2019-08-03 Loïc Leuilliot fix(extractions): use auto-increment primary key instead surrogate (#162)
```
### 3.0.17
```
7eb3dd1  2019-08-12 Loïc LEUILLIOT (tag: 3.0.17) build(core): v3.0.17
3715937  2019-08-09 Loïc Leuilliot refactor(titles): update character relationship to use corp titles (#164)
3857fc3  2019-08-07 Loïc Leuilliot refactor(titles): remove surrogate key by standard auto-increment key (#163)
```
### 3.0.18
```
12ba350  2019-11-26 Loïc LEUILLIOT (tag: 3.0.18) build(core): v3.0.18
3790070  2019-11-26 Loïc LEUILLIOT fix(esi): paginated endpoint may not return x-pages header
2f273e1  2019-08-12 Loïc LEUILLIOT Merge branch 'master' into 3.0.x
ef4a613  2019-08-06 Loïc LEUILLIOT refactor(titles): remove surrogate key by standard auto-increment key
```
### 4.0.0-rc1
```
04a7d38  2019-10-31 Loïc LEUILLIOT (tag: 4.0.0-rc1) refactor(mails): reduce duplicated entries on mails module
31291ef  2019-10-30 Loïc LEUILLIOT fix: ensure models without AI key are properly defined
e4426d6  2019-10-30 Loïc LEUILLIOT feat(relationship): add character and universe-name relations
1264850  2019-10-28 Loïc LEUILLIOT style: apply styleCI change requests
4e44ed3  2019-10-28 Loïc LEUILLIOT refactor(relationship): remove duplicated relation targeting dogmas
6e4eb21  2019-10-28 Loïc LEUILLIOT feat(acl): add scope to character and corporation models
4f6b5d3  2019-10-27 Loïc LEUILLIOT refactor(relationship): use universe_name instead of SDE table
04ed26f  2019-10-27 Loïc LEUILLIOT fix(relationship): dot not seed relation field using default mapping
d4f9ad9  2019-10-27 Loïc LEUILLIOT fix(mails): add unique index on mail_recipients table
a129558  2019-10-27 Loïc LEUILLIOT fix(prices): ensure we're using average_price everywhere
f91607a  2019-10-24 Loïc LEUILLIOT refactor(fittings): use collection method to build fitting format
cad4132  2019-10-23 Loïc LEUILLIOT feat(structures): add fittings relationship
0e9655b  2019-10-22 Loïc Leuilliot feat(blueprints): re-introduced blueprints view which has been removed  (#169)
23c8786  2019-10-22 Loïc Leuilliot fix(relationship): ensure default entity is properly returned (#170)
4704882  2019-10-17 Loïc Leuilliot Merge pull request #168 from warlof/4.0.x
1646f79  2019-10-17 Loïc Leuilliot Merge branch '4.0.x' into 4.0.x
2c731cf  2019-10-15 Loïc LEUILLIOT refactor(relationship): deprecating user relation from member tracking
b3fa12a  2019-10-15 Loïc LEUILLIOT feat(relationship): improve performances regarding roles rendering
bdc4a6a  2019-10-15 Loïc LEUILLIOT feat(relationship): add default relation when no related entity exists
cd10d2d  2019-10-15 Loïc LEUILLIOT fix(insurances): add missing timestamps columns
229b527  2019-10-15 Loïc LEUILLIOT fix(jobs): use proper namespace for insurances job
9a08e13  2019-10-10 Loïc LEUILLIOT feat(relationship): add default relation when no related entity exists
9e078a8  2019-10-10 Loïc LEUILLIOT feat(notifications): return default entity model if none exists
c9f4ec0  2019-10-10 Loïc LEUILLIOT fix(deps): remove Redis facade call in favor of php-redis
0ff1f14  2019-10-10 Loïc LEUILLIOT fix(deps): dev must be use as a suffix instead prefix
b9687ff  2019-10-10 Loïc LEUILLIOT chore(deps): downgrade stability to dev version
adab33d  2019-10-10 Loïc LEUILLIOT chore(deps): update dependencies to Laravel 6.x
e350107  2019-10-10 Loïc Leuilliot (seat/master, master) fix(jobs): fix namespace and class declaration (#167)
7cb821f  2019-10-10 Loïc Leuilliot fix(bookmarks): remove entity index creation which already exists (#166)
1db5d9f  2019-10-10 Loïc LEUILLIOT fix(deps): dev must be use as a suffix instead prefix
f29c8c0  2019-10-10 Loïc LEUILLIOT chore(deps): downgrade stability to dev version
4d37211  2019-10-10 Loïc LEUILLIOT chore(deps): update dependencies to Laravel 6.x
d53f6a4  2019-10-06 Loïc Leuilliot refactor(datatable): increase Yajra/Datatable usage
```
### 4.0.0-rc2
```
8db88ac  2019-11-16 Loïc LEUILLIOT (tag: 4.0.0-rc2) fix(deps): update php minimum version to 7.3
ddc55a3  2019-11-16 Loïc LEUILLIOT refactor(acl): drop Group class and use an unique user bucket
370cdd4  2019-11-11 Loïc LEUILLIOT style: apply styleci changes request
9c4770a  2019-11-11 Loïc LEUILLIOT ci(styleci): remove rules from preset
d9d5415  2019-11-11 Loïc LEUILLIOT feat(relationships): improve relations related to moons and maps
```
### 4.0.0-rc3
```
a40f381  2019-12-22 Loïc LEUILLIOT (tag: 4.0.0-rc3) docs: add deprecated tag
9629336  2019-12-21 Loïc LEUILLIOT refactor(jobs): remove mass insert from Asset, Affiliation & Skill jobs
174a4dd  2019-11-26 Loïc LEUILLIOT fix(esi): paginated endpoint may not return x-pages header
f94cdc2  2019-12-10 Loïc LEUILLIOT refactor: use affiliation
7adfbeb  2019-12-10 Loïc LEUILLIOT fix: use 4.0.x dev branch of eseye
```
### 4.0.0-rc4
```
3953246  2019-12-25 Loïc LEUILLIOT (tag: 4.0.0-rc4) fix(mig): keep mail_id index on mail_header table due to relations
bd736a4  2019-12-23 Loïc LEUILLIOT fix(deps): bump to eseye 2.0
```
### 4.0.0-rc5
```
7e1a192  2020-02-09 Loïc LEUILLIOT (tag: 4.0.0-rc5) feat(assets): bump endpoints to v4 according to ESI changes
d285d80  2020-02-09 Loïc LEUILLIOT fix: ensure enqueued skills are stored
17fb3b6  2020-02-06 Loïc LEUILLIOT style(ci): apply StyleCI changes requests
c84c86d  2020-02-06 Loïc LEUILLIOT refactor: enqueue character and corporation jobs on new token
f71772e  2020-02-06 Loïc LEUILLIOT fix(jobs): ensure distinct skill level are preserved while updating queue
36ef88e  2020-02-02 Loïc LEUILLIOT style(ci): apply StyleCI changes requests
13445f4  2020-02-02 Loïc LEUILLIOT refactor: rename type to ship to be more logic
a63e0d3  2020-02-02 Loïc LEUILLIOT refactor(surrogate): replace the surrogate pattern with a bigint key
9ab98a3  2020-02-02 Loïc LEUILLIOT refactor(contracts): avoid to dispatch useless items job
1f1b6e1  2020-01-31 Loïc LEUILLIOT feat(relationship): add affiliation relation from token
d68d4d8  2020-01-31 Loïc LEUILLIOT refactor(notifications): remove read-only from firstOrNew
571adf2  2020-01-26 Loïc LEUILLIOT refactor(notifications): parse text field
615744e  2020-01-19 Loïc LEUILLIOT fix(mails): do not use default value for labels field
b535ecd  2020-01-14 Loïc LEUILLIOT fix(jobs): address a typo in route parameter
07afe01  2020-01-14 Loïc LEUILLIOT fix(jobs): use corporation ID instead character ID
f677287  2020-01-12 Loïc LEUILLIOT fix(jobs): switch status to high priority queue
b7cdbd0  2020-01-12 Loïc LEUILLIOT fix(jobs): add missing version to structures endpoint
481a9b7  2020-01-12 Loïc LEUILLIOT style: apply requested changes made by styleci
d4ce1df  2020-01-12 Loïc LEUILLIOT refactor: remove stale methods from esi job base class
10a27d6  2020-01-12 Loïc LEUILLIOT refactor(jobs): split universe structure job
7a6170a  2020-01-12 Loïc LEUILLIOT fix(jobs): move esi rate limit counter
6582f64  2020-01-12 Loïc LEUILLIOT fix(relationship): default group on invType
18e714f  2020-01-12 Loïc LEUILLIOT feat(relationship): add faction to killmails
deb171f  2020-01-12 Loïc LEUILLIOT style: apply requested changes made by styleci
3c8b0c0  2020-01-12 Loïc LEUILLIOT refactor(jobs): move esi error handler to retrieve method
849f275  2020-01-12 Loïc LEUILLIOT refactor(jobs): non longer store stale data related to unresolved structures
7bfe08a  2020-01-12 Loïc LEUILLIOT feat(relationship): link universe name and affiliation
6bae921  2020-01-12 Loïc LEUILLIOT style: improve comments and fix some code style
a38bbec  2020-01-12 Loïc LEUILLIOT chore(deps): add missing required json extension
8b6be59  2020-01-12 Loïc LEUILLIOT feat(jobs): add a server down middleware
f84ff4e  2020-01-12 Loïc LEUILLIOT feat: add index on mail headers and affiliations
4f17252  2020-01-12 Loïc LEUILLIOT fix(jobs): ensure token is trashed when refresh has been invalidated
829e0c9  2020-01-11 Loïc LEUILLIOT refactor(jobs): replaces traits by middleware
b2977f1  2020-01-11 Loïc LEUILLIOT feat(relationship): link token and character
b7db034  2020-01-07 Loïc LEUILLIOT refactor(jobs): improve alliances jobs flexibility
7de2361  2020-01-07 Loïc LEUILLIOT refactor(jobs): improve contract jobs flexibility
5039efa  2020-01-07 Loïc LEUILLIOT refactor(jobs): merge corporation and character killmails
d0d1f7b  2020-01-07 Loïc LEUILLIOT refactor(jobs): add redis throttler over contract jobs
08c5ff6  2020-01-07 Loïc LEUILLIOT refactor(jobs): improve abstraction in job management
```
### 4.0.0-rc6
```
f562ee9  2020-03-29 Loïc LEUILLIOT (tag: 4.0.0-rc6) revert(EsiDown): Rate limit the EsiDownException job of queueing the analytics job to once every minute
6d4f9be  2020-03-23 Loïc LEUILLIOT style: fix some typo
b0e33cc  2020-03-22 Loïc LEUILLIOT feat(api): upgrade doc to OAS3
2d14c9f  2020-03-21 Loïc LEUILLIOT fix: avoid migration collision and split data migration from structure change
7903c6c  2020-03-17 Ben Thompson fix(model) fix relation from CharacterInfo to user
52850bf  2020-03-17 Loïc Leuilliot ci(styleci): update config for preset changes
b491102  2020-03-17 Loïc Leuilliot ci(styleci): update config for preset changes
cd73c38  2020-03-17 Loïc Leuilliot ci(styleci): update config for preset changes
696413b  2020-03-03 Ben Thompson fix(esi): Added another error to check for indicating invalid refresh token.
c77aa83  2020-03-03 Ben Thompson fix(kills): Update column to store unique hash.
01f03ab  2020-03-01 Loïc LEUILLIOT fix: ensure upgrade compatibility between v3 and v4
049d8cf  2020-03-01 Loïc LEUILLIOT fix: use proper field to build unique index
157c18a  2020-03-01 Ben Thompson fix(jobs): Check for the right invalid_grant error messages to disable the refresh token.
6305332  2020-02-29 Loïc LEUILLIOT style(ci): make Style CI happy
83984f5  2020-02-29 Loïc LEUILLIOT refactor: remove surrogate keys and improve DB indexing
3152a98  2020-02-29 Loïc LEUILLIOT refactor(kills): remove deprecated class
a7ff54e  2020-02-29 Loïc LEUILLIOT fix(mails): ensure last mail ID is usable
7f9ac4b  2020-02-29 Loïc LEUILLIOT refactor: remove optionals import
3e7630c  2020-02-29 Loïc LEUILLIOT refactor: remove excessive logging
8a7af30  2020-02-29 Loïc LEUILLIOT feat(moons): add indicator attribute based on relationship
cbe3953  2020-02-29 Loïc LEUILLIOT refactor(moons): add scopes related to moon rank
b334834  2020-02-27 Ben Thompson refactor(jobs): refactor UniverseNames to break up the query. Too many placeholders in the existing whereNotIn()
3a5aa4b  2020-02-26 Loïc LEUILLIOT feat(mails): interrupt process when parity has been reached
40757f6  2020-02-26 Ben Thompson fix(relations): Update relation for CorporationMemberTracking model from User to RefreshToken
4b87731  2020-02-24 Ben Thompson fix(auth): avoid null queued alliance job and set proper user relation on RefreshToken (#196)
040791b  2020-02-22 Justin Mercer fix(EsiDown): Rate limit the EsiDownException job of queueing the analytics job to once every minute
07de04f  2020-02-18 Ben Thompson feat(jobs): store updated refresh token returned by SSO when refreshing access tokens
7377372  2020-02-16 Loïc LEUILLIOT fix(affiliations): remove token parameter which is unneeded
```