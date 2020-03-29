![SeAT](https://i.imgur.com/aPPOxSK.png)

# console change logs
Generated with: `git log --pretty=format:"%h%>(12)%ad %<(7)%aN%d %s" --date=short`

### 1.0-pre-alpha
```
fe0da9e  2015-11-27 Leon Jacobs (tag: 1.0-pre-alpha) Update README
05e59b3  2015-11-20 Leon Jacobs Add a cache clearing command
41081d9  2015-11-03 Leon Jacobs Add the UpdateSDE command
9af76fb  2015-10-02 Leon Jacobs use ::class format
7e0bae5  2015-10-02 Leon Jacobs Add seat:admin:reset command
9f4e15f  2015-09-28 Leon Jacobs Update to match eveseat/eveapi model refacto
ee48a61  2015-09-24 Leon Jacobs Add services version lookup
5d7ca5f  2015-09-24 Leon Jacobs Add a 'live' status command
bcd1feb  2015-09-24 Leon Jacobs Add command to update a single key
ee43dc5  2015-09-24 Leon Jacobs Add seat:keys:show command
f72ba13  2015-09-24 Leon Jacobs Style fix
b4bcc04  2015-09-24 Leon Jacobs Add the console.config and update version command
8fe529d  2015-09-24 Leon Jacobs Refactor updater commands to the Eve\ namespace
cc92c10  2015-09-23 Leon Jacobs Ensure only enabled keys are queued for updates
8f93faf  2015-09-23 Leon Jacobs Update to new eveapi version information location
fa5513d  2015-09-23 Leon Jacobs Queue Jobs using the UpdatePublic Job
887b89c  2015-09-16 Leon Jacobs Update readme with badges
74f82f5  2015-09-16 Leon Jacobs Prepare for packagist publish.
a782121  2015-09-04 Leon Jacobs Add the command to queue updates for API keys
14edaa8  2015-09-04 Leon Jacobs Make all commands honor the Job Container
12538ef  2015-09-03 Leon Jacobs Add command for the Api CallList update
31e0d06  2015-08-30 Leon Jacobs Add EVE Map Update command
20aa008  2015-08-29 Leon Jacobs Add eve:update-eve command
b9b7545  2015-08-29 Leon Jacobs Add the EveUpdateServerStatus command
c978b94  2015-08-29 Leon Jacobs Add the add:job command for testing
c01ddd9  2015-08-28 Leon Jacobs Start the Console package
f42ac27  2015-08-28 Leon Jacobs first commit
```
### 1.0.0
```
8cc907d  2015-11-28 Leon Jacobs (tag: 1.0.0) Update required eveseat package versions
81fde9f  2015-11-28 Leon Jacobs Version Bump
```
### 1.0.1
```
2a2a350  2015-11-30 Leon Jacobs (tag: 1.0.1) Add web and api versions
```
### 1.0.2
```
65f650d  2015-12-01 Leon Jacobs (tag: 1.0.2) Versino Bump
```
### 1.0.3
```
0f83a18  2015-12-02 Leon Jacobs (tag: 1.0.3) Version Bump
d0f6d31  2015-12-02 Leon Jacobs Display versions in a table
3d472d4  2015-12-02 Leon Jacobs Add notifications version
```
### 1.0.4
```
338a397  2015-12-04 Leon Jacobs (tag: 1.0.4) Cleanup outputs and sink to a filehandler instead.
```
### 1.0.5
```
7e1d13d  2015-12-07 Leon Jacobs (tag: 1.0.5) Version Bump
b7cac27  2015-12-07 Leon Jacobs Drop guzzle version to match that of phealng
91f2e03  2015-12-07 Leon Jacobs Cleanups
6361651  2015-12-05 Leon Jacobs Add diagnose command
123bc36  2015-12-04 Leon Jacobs Update README.md
```
### 1.0.6
```
3f541b4  2015-12-08 Leon Jacobs (tag: 1.0.6) Version Bump
a49d908  2015-12-08 Leon Jacobs Revert b7cac27ebe4a1de8
```
### 1.0.7
```
18bf548  2015-12-24 Leon Jacobs (tag: 1.0.7) Version Bump
8934a36  2015-12-24 Leon Jacobs Specify versions with ~
```
### 1.0.8
```
6a6d779  2015-12-26 Leon Jacobs (tag: 1.0.8) Version Bump
643479f  2015-12-26 Leon Jacobs Update diagnose with some more useful debug info
0132b4e  2015-12-26 Leon Jacobs Add Github version lookup
```
### 1.0.9
```
68e5638  2015-12-29 Leon Jacobs (tag: 1.0.9) Version Bump
8b3aef9  2015-12-29 Leon Jacobs Use `class` notation
```
### 1.0.10
```
8fb5ad1  2016-01-26 Leon Jacobs (tag: 1.0.10) Version Bump
3e1dca5  2016-01-26 Leon Jacobs Update copyright
d4b2b6f  2016-01-06 Leon Jacobs Code style fix
```
### 1.0.11
```
53fda6e  2016-04-29 Leon Jacobs (tag: 1.0.11) Version Bump
bb9841c  2016-04-29 Leon Jacobs Fix eveseat/seat#83 by ensuring seat:admin:reset recovers admin roles
```
### 1.0.12
```
a6e5e54  2016-05-05 Leon Jacobs (tag: 1.0.12) Version Bump
0c9f1c7  2016-05-01 Leon Jacobs Add a console command to set the admin email address
```
### 1.0.13
```
974cfad  2016-07-23 Leon Jacobs (tag: 1.0.13) Version Bump
f3f44dc  2016-07-23 Leon Jacobs Add analytics hit information.
161cdee  2016-07-22 Leon Jacobs Add ClearExpired command
a87e8d0  2016-07-18 Leon Jacobs Add `seat:queue:clear-expired` command.
```
### 1.0.14
```
57132cf  2016-07-26 Leon Jacobs (tag: 1.0.14) Version Bump
8c9abec  2016-07-26 Leon Jacobs Fix eveseat/seat#127 by removing string concatenation in Class property
```
### 1.0.15
```
43fc0b2  2016-07-26 Leon Jacobs (tag: 1.0.15) Version Bump
a1da1a0  2016-07-26 Leon Jacobs Remove string concatenation causing systax errors
```
### 1.0.16
```
c356fd3  2016-07-27 Leon Jacobs (tag: 1.0.16) Version Bump
ebbebf2  2016-07-27 Leon Jacobs Default to 6 hours to reap jobs
40707ef  2016-07-27 Leon Jacobs Add missing trait
```
### 1.0.17
```
950768a  2016-10-13 Leon Jacobs (tag: 1.0.17) Version bump
5b6c15c  2016-08-26 Leon Jacobs Escape any special characters a password.
ffc04bf  2016-08-25 Leon Jacobs Code style and language fixes
bf32149  2016-08-25 Leon Jacobs Merge pull request #1 from warlof/master
5c7f85b  2016-08-23 elfaus  add a control for SDE version in order to avoid downloading it again allow the user to force an SDE re-installation using --force argument
```
### 2.0.0-alpha1
```
81c6385  2016-11-26 Leon Jacobs (tag: 2.0.0-alpha1) Update composer for 2.0 packages and version 2.0.0-alpha1
2952e40  2016-11-05 Leon Jacobs Code formatting fixes
9d189dc  2016-11-03 Leon Jacobs Rename Pillow to AccessManager and update calls argument list
cebd0ef  2016-10-29 Leon Jacobs Update to match new class names in eveapi repo
e1a95e9  2016-10-27 Leon Jacobs Correctly identify the current user running the command.
e83fb0e  2016-10-23 Leon Jacobs Use `dispatch()` helper instead of Trait
953d790  2016-10-23 Leon Jacobs Update PHP, Laravel & Guzzle dependencies
```
### 2.0.0-alpha2
```
a01282a  2016-11-26 Leon Jacobs (tag: 2.0.0-alpha2) Drop minimum stability, add prefer-stable and bump to 2.0.0-alpha2.
```
### 2.0.0
```
6f57fa6  2016-12-08 Leon Jacobs (tag: 2.0.0) Version Bump! 2.0.0! ⚡️
05ec623  2016-11-29 Leon Jacobs Formatting and style fixes.
e5eee71  2016-11-28 Leon Jacobs Ensure the admin user is enabled when resetting the password.
```
### 2.0.1
```
352d6ae  2016-12-21 Leon Jacobs (tag: 2.0.1) Version Bump
4112603  2016-12-21 Leon Jacobs Slightly increase wait time
7cba4f1  2016-12-21 Leon Jacobs Add `seat:keys:tail` command
868adc3  2016-12-12 Leon Jacobs Make clearing the pheal cache require a flag.
```
### 2.0.2
```
9c80eee  2016-12-22 Leon Jacobs (tag: 2.0.2) Version bump
ca24d69  2016-12-22 Leon Jacobs Give the server status call priority
```
### 2.0.3
```
5e0fd35  2017-01-12 Leon Jacobs (tag: 2.0.3) Version Bump
a0dc02d  2017-01-04 Leon Jacobs Update styleci config
197d773  2017-01-02 Leon Jacobs Apply fixes from StyleCI (#2)
3774d3f  2017-01-02 Leon Jacobs Add StyleCI badge
aa138a7  2017-01-02 Leon Jacobs Add StyleCI Configuration
429b084  2017-01-01 Leon Jacobs Style fixes
```
### 2.0.4
```
8d09f93  2017-01-26 Leon Jacobs (tag: 2.0.4) Version Bump
d4d1160  2017-01-25 mrurb   Fixed UpdateSde not using port (#3)
a9a25d9  2017-01-20 Leon Jacobs Add codeclimate configuration
```
### 3.0.0-beta1
```
d9395d8  2018-04-29 Leon Jacobs (tag: 3.0.0-beta1) Upgrade packages and version 3.0.0-beta1.
ed64b5d  2018-04-29 Leon Jacobs Apply fixes from StyleCI (#19)
1a35941  2018-04-29 Leon Jacobs Indentation fixes.
38b4eba  2018-04-29 Leon Jacobs Fix namespace name to be PSR-4 complaint.
a0ecad0  2018-04-29 Leon Jacobs Fix annotator warnings.
568ce66  2018-04-29 Loïc LEUILLIOT add market prices jobs to public update command (eveseat-mining-ledger) (#17)
1a97575  2018-04-28 Loïc LEUILLIOT pruning chat channel system according to CCP state (#18)
0864380  2018-04-20 Loïc LEUILLIOT Seat3 alliance jobs (#16)
df72726  2018-04-18 Loïc LEUILLIOT queue name resolver job after affiliation one (#15)
4cca813  2018-04-17 Leon Jacobs Remove unused class.
ec5f9b3  2018-04-17 Leon Jacobs Update cache clearing command to clear Eseye caches.
b23bf8e  2018-04-17 Leon Jacobs Apply fixes from StyleCI (#14)
55240a9  2018-04-15 Leon Jacobs Remove checkForOptionalParameter() as coalesce is sufficient.
e0a4b93  2018-04-15 Herpaderp Aldent Accept character_id as parameter for esi:update:characters (#12)
40f1df9  2018-04-02 Leon Jacobs Restore the queue status command.
4042351  2018-04-02 Leon Jacobs Add eve server status command and cleanup old commands.
b9fa044  2018-04-02 Leon Jacobs Update diagnose command with Eseye Cache dir and ESI ping.
131dbe2  2018-04-01 Loïc LEUILLIOT fix removed class call and update with the kept class (#11)
448f9db  2018-02-17 Leon Jacobs Remove unnecessary constructor.
3542053  2018-02-17 Loïc LEUILLIOT Add new updaters. (#10)
fd71f56  2018-02-03 Leon Jacobs Specify an ID for the admin login generator.
79d381b  2018-01-26 Leon Jacobs Add corporation jobs dispatcher command.
1e6323b  2018-01-26 Leon Jacobs Fix EsiJobMakeCommand namespace
a7fb297  2018-01-26 Loïc LEUILLIOT Add a marvealous class builder for job (#7)
85bbebb  2018-01-14 Leon Jacobs Remove more older queue code and update queue status command.
eac414f  2018-01-14 Leon Jacobs Add ESI updater commands.
d243c7d  2018-01-14 Leon Jacobs Remove XML API updater commands
bfc84ed  2017-12-21 Leon Jacobs Add seat:admin:login command to generate admin login URLs.
```
### 3.0.0-beta2
```
633d0c9  2018-05-02 Leon Jacobs (tag: 3.0.0-beta2) v3.0.0-beta2
e2415bc  2018-05-01 Leon Jacobs Allow for a character_id to be set for corporation updates.
```
### 3.0.0-beta3
```
c3d4024  2018-05-07 Leon Jacobs (tag: 3.0.0-beta3) v3.0.0-beta3
8169d84  2018-05-07 Leon Jacobs Fix analytics.
d111531  2018-05-06 Leon Jacobs Update admin login generator command.
cc80587  2018-05-06 Leon Jacobs Update admin login generator.
d1e2a08  2018-05-04 Loïc LEUILLIOT Add sovereignty (#20)
```
### 3.0.0-beta4
```
c0b953d  2018-05-10 Leon Jacobs (tag: 3.0.0-beta4) v3.0.0-beta4
680a1b2  2018-05-10 Loïc LEUILLIOT Uniformising commands (#21)
```
### 3.0.0-beta5
```
510bb03  2018-05-16 Leon Jacobs (tag: 3.0.0-beta5) v3.0.0-beta5
d1ced67  2018-05-15 Leon Jacobs Apply fixes from StyleCI (#22)
7210750  2018-05-15 Leon Jacobs Rename method.
8601865  2018-05-15 Leon Jacobs Refactor to a command bus class.
```
### 3.0.0-beta6
```
3aec4b6  2018-05-18 Leon Jacobs (tag: 3.0.0-beta6) v3.0.0-beta6
fc7f8f3  2018-05-17 Loïc LEUILLIOT alliance info is now dispatched at end of alliance with dedicated job (#23)
```
### 3.0.0-beta7
```
3ad7ab2  2018-05-20 Leon Jacobs (tag: 3.0.0-beta7) v3.0.0-beta7
75e0e70  2018-05-20 Loïc LEUILLIOT fix admin login command related to web#15 modifications (#24)
```
### 3.0.0-beta8
```
dd94882  2018-05-24 Leon Jacobs (tag: 3.0.0-beta8) v3.0.0-beta8
9c56b7c  2018-05-24 Loïc LEUILLIOT fix diagnose command on laravel.log (#26)
f55513e  2018-05-23 Loïc LEUILLIOT add missing Pocos jobs into new corporation job dispatcher (#25)
```
### 3.0.0-beta9
```
10a1f81  2018-05-27 Leon Jacobs (tag: 3.0.0-beta9) v3.0.0-beta9
4521706  2018-05-27 Leon Jacobs Add maintenance job dispatcher.
fc1c274  2018-05-27 Leon Jacobs Apply fixes from StyleCI (#28)
96b9899  2018-05-27 Leon Jacobs Add esi status updater command.
```
### 3.0.0-beta10
```
15c1f87  2018-05-27 Leon Jacobs (tag: 3.0.0-beta10) v3.0.0-beta10
2fd4efa  2018-05-27 Leon Jacobs Add maintenence command file.
```
### 3.0.0-beta11
```
0f57e68  2018-05-31 Leon Jacobs (tag: 3.0.0-beta11) v3.0.0-beta11
901e5b2  2018-05-31 Leon Jacobs Style fixes.
efd4124  2018-05-31 Joe Jenniges Diagnose command, allow checking of redis via socket connection (#27)
c0ab432  2018-05-27 Leon Jacobs Apply fixes from StyleCI (#29)
```
### 3.0.0
```
9ec1618  2018-06-16 Leon Jacobs (tag: 3.0.0) v3.0.0 🎉
```
### 3.0.1
```
38ff110  2018-06-30 Leon Jacobs (tag: 3.0.1) v3.0.1
d0b2fc2  2018-06-30 Leon Jacobs Fix style.
2a6c726  2018-06-30 Leon Jacobs Remove deprecated outposts updater.
```
### 3.0.2
```
61a62ec  2018-08-20 Leon Jacobs (tag: 3.0.2) v3.0.2
c8bfc11  2018-08-17 Loïc Leuilliot fix(contacts): Add missing corporation contact labels job to queue candidate (#30)
```
### 3.0.3
```
6e217d3  2019-01-13 Loïc LEUILLIOT (tag: 3.0.3) build(core): v3.0.3
b97cbfe  2019-01-07 Loïc Leuilliot feat(versions): Implement new version management for Console package (#32)
```
### 3.0.4
```
38131af  2019-03-23 Loïc LEUILLIOT (tag: 3.0.4) build(core): v3.0.4
9661259  2019-02-22 Herpaderp Aldent Introduce public corporation history updater (#34)
e16de26  2019-02-19 Herpaderp Aldent Update `character_info` table for characters without `refresh_token` (#33)
5ed01a9  2019-02-18 Leon Jacobs Apply fixes from StyleCI (#36)
```
### 3.0.5
```
16a89d0  2019-05-20 Loïc LEUILLIOT (tag: 3.0.5) build(core): v3.0.5
e862254  2019-05-19 Loïc Leuilliot fix(jobs): use proper job into assets pipe in order to collect assets Locations (#37)
```
### 4.0.0-rc1
```
cea5c42  2019-10-31 Loïc LEUILLIOT (tag: 4.0.0-rc1) refactor(mails): reduce mail module complexity
fccf870  2019-10-24 Loïc LEUILLIOT fix(acl): add global scope on superuser permission
711b97a  2019-10-22 Loïc Leuilliot refactor(core): move AbstractSeatPlugin from services to seat package (#39)
48567ae  2019-10-15 Loïc LEUILLIOT fix(insurances): add missing jobs in public command
8ecaf51  2019-10-10 Loïc LEUILLIOT fix(deps): replace str_ and arr_ helpers by their Classes
46a944c  2019-10-10 Loïc LEUILLIOT fix(deps): dev must be use as a suffix instead prefix
df35614  2019-10-10 Loïc LEUILLIOT chore(deps): downgrade stability to dev version
b778aea  2019-10-10 Loïc LEUILLIOT chore(deps): update dependencies to Laravel 6.x
```
### 4.0.0-rc2
```
85177c3  2019-11-16 Loïc LEUILLIOT (tag: 4.0.0-rc2) fix(deps): update php minimum version to 7.3
26c5076  2019-11-16 Loïc LEUILLIOT ci(styleci): remove length_ordered_imports from disabled check
39e2776  2019-11-16 Loïc LEUILLIOT refactor(acl): drop Group class and use an unique user bucket
```
### 4.0.0-rc3
```
603da3f  2020-02-09 Loïc LEUILLIOT (tag: 4.0.0-rc3) refactor: move schedule seeder from services repo
0f97875  2020-02-02 Loïc LEUILLIOT style(ci): apply StyleCI changes requests
14cf332  2020-02-02 Loïc LEUILLIOT refactor(commands): use dedicated notifications command
a25acc4  2020-01-12 Loïc LEUILLIOT refactor: use new eve:update:status class namespace
bec51b0  2020-01-12 Loïc LEUILLIOT refactor(jobs): split universe structure job
bcf634a  2020-01-12 Loïc LEUILLIOT fix(contract): use proper relation between token and affiliation
60966c0  2020-01-12 Loïc LEUILLIOT refactor: improve commands consistency
6dfa398  2020-01-12 Loïc LEUILLIOT style: fix typo in documentation block
2969159  2020-01-12 Loïc LEUILLIOT refactor(jobs): dispatch analytics jobs to default queue
1580158  2020-01-12 Loïc LEUILLIOT style: simplifying dispatch typo
b9f5778  2020-01-12 Loïc LEUILLIOT fix(contracts): add missing contract_id into contract update command
7b816ce  2020-01-11 Loïc LEUILLIOT style: apply styleci change requests
53d0167  2020-01-11 Loïc LEUILLIOT feat: add new alliances, contracts and KM commands
80b76dc  2020-01-11 Loïc LEUILLIOT refactor: rewrite commands according to eveapi changes
```