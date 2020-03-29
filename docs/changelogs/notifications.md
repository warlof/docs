![SeAT](https://i.imgur.com/aPPOxSK.png)

# notifications change logs
Generated with: `git log --pretty=format:"%h%>(12)%ad %<(7)%aN%d %s" --date=short`

### 1.0.0
```
15b1175  2015-12-02 Leon Jacobs (tag: 1.0.0) Add views to see notifications
fd76941  2015-12-02 Leon Jacobs Fix typo
a5f93e7  2015-12-02 Leon Jacobs Update README
c22a837  2015-12-02 Leon Jacobs First iteration of the notification package
032bebf  2015-12-01 Leon Jacobs first commit
```
### 1.0.1
```
6594754  2015-12-13 Leon Jacobs (tag: 1.0.1) Version Bump
ccf7596  2015-12-04 Leon Jacobs Update README.md
70994aa  2015-12-02 Leon Jacobs Add more complete message
```
### 1.0.2
```
aedd78a  2015-12-16 Leon Jacobs (tag: 1.0.2) Version Bump
a2e7ddf  2015-12-16 Leon Jacobs Add suport for lacalization
```
### 1.0.3
```
d47b267  2015-12-24 Leon Jacobs (tag: 1.0.3) Version Bump
e0a5b53  2015-12-24 Leon Jacobs Specify Versions with ~
```
### 1.0.4
```
c115945  2016-01-26 Leon Jacobs (tag: 1.0.4) Version Bump
7b0cd6f  2016-01-26 Leon Jacobs Update copyright
23e89b1  2016-01-06 Leon Jacobs Code style fix
```
### 2.0.0-alpha1
```
8d631d0  2016-11-26 Leon Jacobs (tag: 2.0.0-alpha1) Update composer for 2.0 packages and version 2.0.0-alpha1
9a7af30  2016-11-25 Leon Jacobs Add character mail alert.
e72475f  2016-11-25 Leon Jacobs Add new api key added alert.
5c72ad8  2016-11-25 Leon Jacobs Add member api state change alert.
177b12e  2016-11-25 Leon Jacobs Add a starbase state change alert.
d415584  2016-11-25 Leon Jacobs Give alerts pretty names.
0a6f74a  2016-11-25 Leon Jacobs Style fixes
de0b6cb  2016-11-25 Leon Jacobs Add a command handler & schedule for alerts.
b444b41  2016-11-25 Leon Jacobs Add localization strings
cd4a801  2016-11-25 Leon Jacobs Add notifications history to prevent duplicate notifications.
a37a62b  2016-11-25 Leon Jacobs Add alert for starbase fuel levels.
c75715f  2016-11-24 Leon Jacobs Apply affiliation rules to Notification Groups that have them set.
d4ade00  2016-11-24 Leon Jacobs Add Inactive Corp Member notification.
88f5d8f  2016-11-24 Leon Jacobs Only fire alerts to groups with the actual alert configured.
d2cd290  2016-11-24 Leon Jacobs Add time to player count notification
858f4e8  2016-11-24 Leon Jacobs Ensure that only a single integration of a type can be added
bd0443c  2016-11-24 Leon Jacobs Add ability to delete a notifications group.
8678921  2016-11-24 Leon Jacobs Add ability to modify notification groups.
895e510  2016-11-23 Leon Jacobs Allow for integrations to be deleted.
784f040  2016-11-23 Leon Jacobs Add a player count notification to test.
aae1201  2016-11-23 Leon Jacobs Add missing docblocks
474dd80  2016-11-23 Leon Jacobs Restore the old structure on `down()`
3ab8b06  2016-11-23 Leon Jacobs Major notifications refactor to support L5.3 features.
d1614c8  2016-11-05 Leon Jacobs Code formatting fixes
353d04c  2016-11-05 Leon Jacobs Extend new core controllers instead of base in App namespace
6caa863  2016-10-23 Leon Jacobs Update PHP & Laravel dependencies. Remove psr/log dependency.
624e13c  2016-10-23 Leon Jacobs Apply new global web middleware
```
### 2.0.0-alpha2
```
e9b2b42  2016-11-26 Leon Jacobs (tag: 2.0.0-alpha2) Drop minimum stability, add prefer-stable and bump to 2.0.0-alpha2.
```
### 2.0.0
```
125db68  2016-12-08 Leon Jacobs (tag: 2.0.0) Version Bump! 2.0.0! ⚡️
88ac259  2016-11-28 Leon Jacobs Codestyle fixes.
```
### 2.0.1
```
acdaa9d  2016-12-09 Leon Jacobs (tag: 2.0.1) Version bump
ec3a05f  2016-12-09 Leon Jacobs Add corporation killmails notification.
```
### 2.0.2
```
070c7c3  2016-12-10 Leon Jacobs (tag: 2.0.2) Version Bump
4101a77  2016-12-09 Leon Jacobs Format security status number and specify if killmail is a loss.
c7d6a05  2016-12-09 Leon Jacobs Improve performace by reducing mail scope to 1 week
0c3b224  2016-12-09 Leon Jacobs Correctly affiliate by ownerID instead of corporationID
```
### 2.0.3
```
452a409  2016-12-12 Leon Jacobs (tag: 2.0.3) Version Bump
02ce790  2016-12-12 Leon Jacobs Temporarily Disable the Member API State Alert
```
### 2.0.4
```
cfb4fdc  2016-12-15 Leon Jacobs (tag: 2.0.4) Version Bump
5e66f49  2016-12-15 Leon Jacobs Throttle notifications to prevent HTTP 429's.
cf8541b  2016-12-15 Leon Jacobs Small refactor of siphon detection `getData` method to use collections.
72f7d13  2016-12-15 Leon Jacobs Merge pull request #3 from karbowiak/master
595db6c  2016-12-14 Michael Karbowiak Remove sleep again.. replace with token bucket or something similar at a later point
af2d7c1  2016-12-14 Michael Karbowiak Fix chmod
effc7a8  2016-12-14 Michael Karbowiak Add Siphon Alerts
c9038d6  2016-12-14 Michael Karbowiak Add sleep(1) to the slack notifications, to make it sleep for a full second before sending out each message.. To stop Slack/Discord from 429'ing..
69bdf77  2016-12-14 Leon Jacobs Merge pull request #1 from warlof/typo
f0157c7  2016-12-14 elfaus  fix typo on notification message
```
### 2.0.5
```
de3ba6b  2016-12-22 Leon Jacobs (tag: 2.0.5) Version Bump
fa312ca  2016-12-22 Leon Jacobs Fix typo
f0e928b  2016-12-22 Leon Jacobs Fix email notifications for StarbaseSiphon detection
```
### 2.0.6
```
4738228  2016-12-23 Leon Jacobs (tag: 2.0.6) Version Bump
9bebd32  2016-12-22 Leon Jacobs Update siphon detection to use # of items and not volume.
```
### 2.0.7
```
b7a8ed2  2017-01-12 Leon Jacobs (tag: 2.0.7) Version Bump
b5126d3  2017-01-04 Leon Jacobs Update styleci config
b95d799  2017-01-02 Leon Jacobs Apply fixes from StyleCI (#4)
04caec8  2017-01-02 Leon Jacobs Add StyleCI badge
7f5c4a2  2017-01-02 Leon Jacobs Add StyleCI configuration
```
### 2.0.8
```
b25146f  2017-01-31 Leon Jacobs (tag: 2.0.8) Version Bump
f26e906  2017-01-31 Loïc LEUILLIOT fix middleware flow in order to avoid null exception on bouncer (#5)
bbc09a0  2017-01-20 Leon Jacobs Add codeclimate configuration
```
### 2.0.9
```
bd9bbb0  2017-05-07 Leon Jacobs (tag: 2.0.9) Version Bump
6ff4a1b  2017-05-07 Leon Jacobs Reduce one level of indentation.
ce58c03  2017-05-07 Loïc LEUILLIOT Starbase Siphon alert hotfix (#6)
```
### 2.0.10
```
8632037  2017-08-12 Leon Jacobs (tag: 2.0.10) Version Bump
5172e72  2017-08-12 Leon Jacobs Formatting, language and style fixes.
19b57dd  2017-08-12 Loïc LEUILLIOT improve slack notification for killmail (#7)
```
### 2.0.11
```
e760f9d  2017-08-12 Leon Jacobs (tag: 2.0.11) Version bump
49d515e  2017-08-12 Leon Jacobs Update wording.
cbfac3e  2017-08-12 Leon Jacobs Remove debug line.
```
### 3.0.0-beta1
```
b003788  2018-04-29 Leon Jacobs (tag: 3.0.0-beta1) Upgrade packages and version 3.0.0-beta1
75b69af  2018-04-29 Leon Jacobs Indentation and sorting fixes.
ea8775a  2018-04-22 Herpaderp Aldent Fix affiliations-panel (#9)
181e7ee  2018-04-17 Leon Jacobs Apply fixes from StyleCI (#8)
```
### 3.0.0-beta1
```
4c8186c  2018-04-29 Leon Jacobs (tag: 3.0.0-beta2) v3.0.0-beta2
```
### 3.0.0-beta1
```
6abd598  2018-05-20 Leon Jacobs (tag: 3.0.0-beta3) v3.0.0-beta3
b198e42  2018-05-20 Leon Jacobs Apply fixes from StyleCI (#11)
a2847c6  2018-05-20 Leon Jacobs Revive notifications.
```
### 3.0.0
```
756fdd8  2018-06-16 Leon Jacobs (tag: 3.0.0) v3.0.0 🎉
```
### 3.0.1
```
e460ffb  2018-07-29 Leon Jacobs (tag: 3.0.1) v3.0.1
8d03240  2018-07-29 Loïc LEUILLIOT remove eve from available notification type (#13)
6a0f85a  2018-07-29 Loïc LEUILLIOT fix new token mail notification route (#12)
```
### 3.0.2
```
d9d7cba  2018-12-08 Loïc LEUILLIOT (tag: 3.0.2) build(core): v3.0.2
5ab4330  2018-12-06 Herpaderp Aldent [feat](core): Use new migration mechanic
453d3d9  2018-11-18 Herpaderp Aldent [feat](dependencies): Update DataTables Dependencies for new DataTables Version (#16)
9488d92  2018-10-28 Loïc Leuilliot (herpaderpaldent/master) fix(token state): Remove deprecated apikey routes references (#15)
```
### 3.0.3
```
4f94377  2019-01-13 Loïc LEUILLIOT (tag: 3.0.3) build(core): v3.0.3
d265924  2019-01-07 Loïc Leuilliot feat(versions): Implement new version management for Notifications package (#18)
```
### 3.0.4
```
81525b8  2019-05-28 Loïc LEUILLIOT (tag: 3.0.4) build(core): v3.0.4
75b4d3d  2019-05-28 Loïc Leuilliot fix(notifications): address mail link construction issue (#25)
8c5f154  2019-04-22 Loïc Leuilliot fix(notifications): address zKillboard link construction issue (#24)
9d771dc  2019-04-22 Loïc Leuilliot fix(notifications): enforce corporation member tracking sorting (#23)
b088502  2019-04-22 Loïc Leuilliot fix(notifications): enforce corporation killmails sorting (#22)
39cf831  2019-02-18 Leon Jacobs Apply fixes from StyleCI (#21)
```
### 3.0.5
```
83f68a0  2019-06-13 Loïc LEUILLIOT (tag: 3.0.5) build(core): v3.0.5
3ef7fcf  2019-06-13 Loïc Leuilliot feat(notifications): add corporation character left notification support (#33)
af28ad9  2019-06-13 Loïc Leuilliot feat(notifications): add structure service offline notification support (#32)
ec39bc7  2019-06-13 Loïc Leuilliot feat(notifications): add moon mining extraction notification support (#31)
c0e28d4  2019-06-13 Loïc Leuilliot feat(notifications): add structure fuel notification support (#30)
cea5ad4  2019-06-13 Loïc Leuilliot feat(notifications): add corporation bill notification support (#29)
b249176  2019-06-13 Loïc Leuilliot feat(notifications): add sovereignty structure reinforced support (#28)
8867cf8  2019-06-13 Loïc Leuilliot feat(notifications): add sovereignty structure destroyed support (#27)
a25728c  2019-06-13 Loïc Leuilliot feat(notifications): add structure under attack support (#26)
16fc658  2019-06-01 Loïc Leuilliot fix(integrations): ensure ID to name resolver is properly call (#34)
```
### 3.0.6
```
2f4484d  2019-08-12 Loïc LEUILLIOT (tag: 3.0.6, seat/master, seat/3.0.x, master, 3.0.x) build(core): v3.0.6
bb05056  2019-08-11 Loïc Leuilliot fix(notifications): ignore alliance from dataset if allianceID is null (#37)
967614d  2019-06-30 Loïc Leuilliot fix(killmails): ensure killed entity is properly displayed (#36)
fc06c30  2019-06-30 Loïc Leuilliot feat(killmails): limit returned killmail to last 7 days (#35)
```
### 4.0.0-rc1
```
adaf173  2019-10-22 Loïc Leuilliot (tag: 4.0.0-rc1) refactor(core): move AbstractSeatPlugin from services to seat package (#39)
18f8eab  2019-10-16 Loïc LEUILLIOT fix(deps): upgrade notifications group card
5be053a  2019-10-16 Loïc LEUILLIOT fix(deps): upgrade notifications groups list
94c303e  2019-10-16 Loïc LEUILLIOT fix(deps): upgrade personal notifications
4ea8a93  2019-10-16 Loïc LEUILLIOT fix(deps): upgrade integrations slack form
c82f8db  2019-10-16 Loïc LEUILLIOT fix(deps): upgrade integrations mail form
dbc5b98  2019-10-16 Loïc LEUILLIOT fix(deps): upgrade integrations layout
eae69fa  2019-10-11 Loïc LEUILLIOT fix(deps): update font-awesome icons to v5
bcbe4b3  2019-10-10 Loïc LEUILLIOT fix(deps): update resources directory structure according L5.7
5487823  2019-10-10 Loïc LEUILLIOT fix(deps): add slack notification channel
445a0c8  2019-10-10 Loïc LEUILLIOT fix(deps): replace str_ and arr_ helpers by their Classes
4a639f3  2019-10-10 Loïc LEUILLIOT fix(deps): dev must be use as a suffix instead prefix
73372cd  2019-10-10 Loïc LEUILLIOT chore(deps): downgrade stability to dev version
84aec36  2019-10-10 Loïc LEUILLIOT chore(deps): update dependencies to Laravel 6.x
```
### 4.0.0-rc2
```
c2c3674  2019-12-01 Loïc LEUILLIOT (tag: 4.0.0-rc2) refactor(acl): move permissions to sub-directory
fafbc6e  2019-11-16 Loïc LEUILLIOT fix(deps): update php minimum version to 7.3
```
### 4.0.0-rc3
```
d77a43c  2020-02-09 Loïc LEUILLIOT (tag: 4.0.0-rc3) style: clean code
26d7f4f  2020-02-09 Loïc LEUILLIOT refactor: simplify moon notifications
06bb292  2020-02-09 Loïc LEUILLIOT refactor: remove deprecated alert command
4fb179a  2020-02-09 Loïc LEUILLIOT refactor: remove not implemented notifications
91b2b5a  2020-02-09 Loïc LEUILLIOT style(ci): apply some StyleCI change requests
17e99d1  2020-02-09 Loïc LEUILLIOT refactor: switch to datatable structure and improve alerts selection UI
aca3082  2020-02-09 Loïc LEUILLIOT refactor: remove the unused type field
1c9855c  2020-02-02 Loïc LEUILLIOT refactor(ui): replace old name by label
44a53fc  2020-02-02 Loïc LEUILLIOT refactor: complete handlers updates
4085257  2020-01-31 Loïc LEUILLIOT refactor: introduce some flavour names
4d00a74  2020-01-31 Loïc LEUILLIOT refactor: ignore notifications older than 60min
35bca77  2020-01-31 Loïc LEUILLIOT fix: use proper path to discover notification handlers
386697e  2020-01-31 Loïc LEUILLIOT refactor: add more structure notifications
498c34b  2020-01-30 Loïc LEUILLIOT refactor: add support for MoonMiningExtractionStarted
2aff975  2020-01-27 Loïc LEUILLIOT refactor: implement new notifications handlers
a874367  2020-01-26 Loïc LEUILLIOT refactor: switch character notification handler to config
70bb427  2020-01-26 Loïc LEUILLIOT refactor(killmails): use killmail detail observer
1bd7190  2020-01-26 Loïc LEUILLIOT style(ci): apply StyleCI changes requests
a59ca07  2020-01-26 Loïc LEUILLIOT refactor(notifications): exploit observer to notify
69671dc  2020-01-26 Loïc LEUILLIOT fix(deps): use Arr class instead deprecated helper
991b57e  2020-01-26 Loïc LEUILLIOT fix(ui): use web views to render entities properly
b48cb40  2020-01-26 Loïc LEUILLIOT ci(styleci): remove alpha_ordered_imports
633fe19  2020-01-26 Loïc LEUILLIOT ci(styleci): remove length_ordered_imports
```