![SeAT](https://i.imgur.com/aPPOxSK.png)

# services change logs
Generated with: `git log --pretty=format:"%h%>(12)%ad %<(7)%aN%d %s" --date=short`

### 1.0-pre-alpha
```
93958d6  2015-11-27 Leon Jacobs (tag: 1.0-pre-alpha) Update README
666036a  2015-11-27 Leon Jacobs Add method to get corp wallet transactions
bcb36f7  2015-11-27 Leon Jacobs Fix filter rule reference
5e579ec  2015-11-27 Leon Jacobs Add methods to get standings and wallet journal
91163b3  2015-11-27 Leon Jacobs Fix a join
bab5d59  2015-11-27 Leon Jacobs Add method to get corp market orders
6b2734d  2015-11-27 Leon Jacobs Add method to get corp killmails
513c1e5  2015-11-27 Leon Jacobs Add method to get corp industry jobs
eb0b9d7  2015-11-27 Leon Jacobs Add method to get corp contracts
3b2e7eb  2015-11-27 Leon Jacobs Add methods to get corp contacts & labels
057e1d4  2015-11-27 Leon Jacobs Add method to get corp assets
907870a  2015-11-27 Leon Jacobs Add methods for corp summary pages
c4a4977  2015-11-27 Leon Jacobs Small refactor to remove attributes instead of making them blank
0b1ee7a  2015-11-27 Leon Jacobs Add method to cleanup CCP produced HTML
11e55c6  2015-11-26 Leon Jacobs Add method to list corporations
3a76e64  2015-11-26 Leon Jacobs Fix typo
02eea36  2015-11-26 Leon Jacobs Add ability to just dump query and continue load
c71ca03  2015-11-21 Leon Jacobs Add method to get character standings
be1c6db  2015-11-21 Leon Jacobs Add method to get character research info
7d0105c  2015-11-21 Leon Jacobs Add method to get character pi
6ea00fb  2015-11-21 Leon Jacobs Add methods to get character market orders
18e3580  2015-11-20 Leon Jacobs Add method comments
4daabd8  2015-11-20 Leon Jacobs Add method to get character industry
196e968  2015-11-20 Leon Jacobs Add method to get contract information
3ad8de1  2015-11-20 Leon Jacobs Add method to get killmails
2c5ca99  2015-11-20 Leon Jacobs Lock type image to max 32/64px
0071fa7  2015-11-20 Leon Jacobs Add character contact lists and calendar repositories
11ebe15  2015-10-30 Leon Jacobs Add character notifications repo
52807cf  2015-10-30 Leon Jacobs Add the Notification Types Seeder
6560b34  2015-10-30 Leon Jacobs Add rules to ensure columns can not be tampered with
bb32b1b  2015-10-30 Leon Jacobs Add Character Assets services
cc493be  2015-10-30 Leon Jacobs Style fixes
0e56275  2015-10-30 Leon Jacobs Add Mail Service for Characters
6fa7631  2015-10-29 Leon Jacobs Add Character Wallet Transactions Service
bd1b364  2015-10-29 Leon Jacobs Add Wallet Journal Services
22d7e6f  2015-10-29 Leon Jacobs Add option to auto-detect image types
f899060  2015-10-29 Leon Jacobs Rename method from Character->Eve
d3f6fb7  2015-10-28 Leon Jacobs Add more methods for character information
46910d1  2015-10-28 Leon Jacobs Fix a table ambiguity problem for characterID
33463b9  2015-10-27 Leon Jacobs Add more repository methods
f75cd7c  2015-10-27 Leon Jacobs Add Services for Character Skills
d35099a  2015-10-09 Leon Jacobs Add security repository
9bcb126  2015-10-09 Leon Jacobs Add more methods for character info
71e3864  2015-10-09 Leon Jacobs Add a number formatter
55a29d2  2015-10-08 Leon Jacobs Add repositories to get character information
04df3b9  2015-10-08 Leon Jacobs Add a query builder filterable helper
0fdea02  2015-10-08 Leon Jacobs Add SQL debug helper
6e32c77  2015-10-06 Leon Jacobs Add Respository to support the Queue
54cda05  2015-10-04 Leon Jacobs Set extention correctly based on image type
4172206  2015-10-04 Leon Jacobs Add a service to prepare lazy loaded <img> tags
89dfbb2  2015-10-01 Leon Jacobs Add user modifiction services
30bdace  2015-09-30 Leon Jacobs Add repositories used in eveseat/web acl
a8ff125  2015-09-28 Leon Jacobs Update to match eveseat/eveapi Model refactor
4a69ce0  2015-09-24 Leon Jacobs Add Config file
ea84fb0  2015-09-24 Leon Jacobs Add Queue Data Source
2f60e1d  2015-09-24 Leon Jacobs Add EveApiKeyData service
467fb42  2015-09-24 Leon Jacobs Update badges
5779eff  2015-09-24 Leon Jacobs Prepare repository for packagist
a46f437  2015-09-24 Leon Jacobs Initial commit
```
### 1.0.0
```
300cdde  2015-11-28 Leon Jacobs (tag: 1.0.0) Update required eveseat package version
526493c  2015-11-28 Leon Jacobs Style Fixes and Version Bump
9ded93d  2015-11-28 Leon Jacobs Add registration options
e5348f0  2015-11-28 Leon Jacobs Update to support new settings features
f601b60  2015-11-28 Leon Jacobs Move options scope to public
dcbd238  2015-11-28 Leon Jacobs Add a setting() helper and provide some defaults
82115c2  2015-11-28 Leon Jacobs Add a settings service
c72cd8a  2015-11-27 Leon Jacobs Add methods to query corp security info
5371848  2015-11-27 Leon Jacobs Add method to get corp member tracking
```
### 1.0.1
```
f32b199  2015-12-02 Leon Jacobs (tag: 1.0.1) Version Bump
9a2fe0f  2015-12-02 Leon Jacobs Allow to get/set settings for another user by id
71504e9  2015-12-02 Leon Jacobs Add default for email notifications
8109b5c  2015-12-02 Leon Jacobs Add service for database stored schedules
d4afc21  2015-12-01 Leon Jacobs Ensure we pass integers to the helper
```
### 1.0.2
```
717f9fb  2015-12-04 Leon Jacobs (tag: 1.0.2) Add server status method
f2172dc  2015-12-04 Leon Jacobs Update README.md
8b65137  2015-12-04 Leon Jacobs Add default MFA setting
```
### 1.0.3
```
e1c75bb  2015-12-05 Leon Jacobs (tag: 1.0.3) Version Bump
```
### 1.0.4
```
d087604  2015-12-13 Leon Jacobs (tag: 1.0.4) Version Bump
d3d6bd0  2015-12-13 Leon Jacobs Add an admin contact setting
a5b4135  2015-12-12 Leon Jacobs Order jobs by date
```
### 1.0.5
```
af4abdc  2015-12-16 Leon Jacobs (tag: 1.0.5) Version Bump
cda2f34  2015-12-16 Leon Jacobs Default to english language
ea02832  2015-12-15 Leon Jacobs Add method to get mail timeline
28b0933  2015-12-15 Leon Jacobs Suppress errors incase the html is invalid
012e0e6  2015-12-14 Leon Jacobs Add method to get an email for a character
```
### 1.0.6
```
aa17e7d  2015-12-17 Leon Jacobs (tag: 1.0.6) Version Bump
691dc5c  2015-12-17 Leon Jacobs Prevent dupe or corp chars from showing
1b93322  2015-12-17 Leon Jacobs Prevent duplicate entries in corp member tracking
```
### 1.0.7
```
5734db7  2015-12-20 Leon Jacobs (tag: 1.0.7) Version Bump
e221f72  2015-12-20 Leon Jacobs Add method to get corp bookmarks
30699d3  2015-12-20 Leon Jacobs Add method to get character bookmarks
afd7cba  2015-12-18 Leon Jacobs Add method to get character chat channels
6ca677b  2015-12-17 Leon Jacobs Second attempt at fixing eveseat/seat#7
```
### 1.0.10
```
e985e13  2015-12-24 Leon Jacobs (tag: 1.0.10) Version Bump
9e75900  2015-12-24 Leon Jacobs Revert version setting via ~
cd3878c  2015-12-24 Leon Jacobs (tag: 1.0.9) Version Bump
a0c30a9  2015-12-24 Leon Jacobs Version Set via ^
ebd21c7  2015-12-24 Leon Jacobs (tag: 1.0.8) Version Bump
e7a055d  2015-12-24 Leon Jacobs Set composer versions using ~
08a50d8  2015-12-24 Leon Jacobs Determine capacity bonus with tower
aa51300  2015-12-24 Leon Jacobs Temporarily ignore nested groups
5ff8e0a  2015-12-23 Leon Jacobs Add methods to get starbase related data
63e9be9  2015-12-21 Leon Jacobs Return paginated results
```
### 1.0.8
```

```
### 1.0.9
```
cd3878c  2015-12-24 Leon Jacobs (tag: 1.0.9) Version Bump
a0c30a9  2015-12-24 Leon Jacobs Version Set via ^
```
### 1.0.11
```
bb1cd45  2015-12-27 Leon Jacobs (tag: 1.0.11) Version Bump
0d139b2  2015-12-27 Leon Jacobs Allow starbase details to be loaded by starbase_id
e985e13  2015-12-24 Leon Jacobs (tag: 1.0.10) Version Bump
9e75900  2015-12-24 Leon Jacobs Revert version setting via ~
```
### 1.0.12
```
c3d9aaf  2015-12-28 Leon Jacobs (tag: 1.0.12) Version Bump
bee194f  2015-12-28 Leon Jacobs Add method to get corporation customs offices
```
### 1.0.13
```
e33ed92  2015-12-29 Leon Jacobs (tag: 1.0.13) Version Bump
582d719  2015-12-29 Leon Jacobs Fix eveseat/seat#28
```
### 1.0.14
```
e4d521b  2016-01-26 Leon Jacobs (tag: 1.0.14) Version Bump
96c9fb5  2016-01-26 Leon Jacobs Update copyright
c9cd51c  2016-01-26 Leon Jacobs Ensure that people.view role is enforced
2f1e9e3  2016-01-26 Leon Jacobs Add methods for People groups
f7bb649  2016-01-06 Leon Jacobs Handle some unicode characters for cases like eveseat/seat#13
0ad1ffa  2016-01-06 Leon Jacobs Code style fix
```
### 1.0.15
```
570bbd0  2016-04-14 Leon Jacobs (tag: 1.0.15) Version Bump
630b8af  2016-04-13 Leon Jacobs Remove unused pagination and CS fixes
cbc4206  2016-04-13 dysath  Services for Corporation Ledger queries. (#5)
b87d364  2016-01-27 Leon Jacobs Order jobs by creation date
```
### 1.0.16
```
439fbac  2016-04-29 Leon Jacobs (tag: 1.0.16) Version Bump
ea240c7  2016-04-29 Leon Jacobs Add defaults for minimum access mask checking settings
d7b7eaf  2016-04-29 Leon Jacobs Add the search service
ce085f7  2016-04-29 Leon Jacobs Fix eveseat/seat#93 by filtering corporation_account_balances too
0c03b8e  2016-04-29 Leon Jacobs Modify timeline method to retrive one specific message
```
### 1.0.17
```
e35f552  2016-05-14 Leon Jacobs (tag: 1.0.17) Version Bump
10c4a86  2016-05-13 Leon Jacobs Set default values for 'allow_sso'
```
### 1.0.18
```
b3d538d  2016-06-26 Leon Jacobs (tag: 1.0.18) Version Bump
305a3ab  2016-06-26 Leon Jacobs Sort killmails by newest first.
2edf0fd  2016-06-26 Leon Jacobs Add module info if a single starbases' info is called
```
### 1.0.19
```
b2b9995  2016-07-10 Leon Jacobs (tag: 1.0.19) Version Bump
744e982  2016-07-10 Leon Jacobs Paginate Killmails
5711563  2016-07-10 Leon Jacobs Paginate contracts. Part of the fix for eveseat/seat#111
```
### 1.0.20
```
cfcefda  2016-07-23 Leon Jacobs (tag: 1.0.20) Version Bump
7fa3040  2016-07-23 Leon Jacobs Add missing import of CharacterSheetCorporationTitles
b4a8080  2016-07-23 Leon Jacobs Set available options and defaults for usage tracking
b2765c6  2016-07-23 Leon Jacobs Add analytics Jobs using Google Analytics measurement protocol.
9d23cb6  2016-07-22 Loïc LEUILLIOT * Add corporation titles to character sheet (#7)
26c1673  2016-07-19 Leon Jacobs Fix eveseat/seat#112 by using an advanced where to group the filter
58cfc96  2016-07-18 Leon Jacobs Add the `seat:queue:clear-expired` scheduled command
```
### 1.0.21
```
0ad3ccf  2016-07-23 Leon Jacobs (tag: 1.0.21) Version Bump
```
### 1.0.22
```
a0a0c75  2016-07-27 Leon Jacobs (tag: 1.0.22) Version Bump
02ad71e  2016-07-27 Leon Jacobs Seed the expired job time to run every 6 hours
```
### 1.0.23
```
49bc082  2016-10-14 Leon Jacobs (tag: 1.0.23) Version Bump
a199fa9  2016-10-13 Leon Jacobs Add getCharacterAlliances method
dfaa83a  2016-08-25 Leon Jacobs Add char and corp minimum mask defaults
4739b90  2016-08-25 Leon Jacobs Add a default for the `installed_sde` setting
```
### 2.0.0-alpha1
```
95f0453  2016-11-26 Leon Jacobs (tag: 2.0.0-alpha1) Update composer for 2.0 packages and version 2.0.0-alpha1
3367168  2016-11-25 Leon Jacobs Add more data sources for the dashboard.
0da12f3  2016-11-25 Leon Jacobs Allow specifying which tags to exclude when cleaning html.
e87cb20  2016-11-25 Leon Jacobs Fix member tracking counts by using a leftJoin.
f70db5f  2016-11-25 Leon Jacobs Dont override existing schedules when seeding the database.
2cbaf0f  2016-11-20 Leon Jacobs Allow carbon helper to be called without an argument.
41a9b07  2016-11-19 Leon Jacobs Add `updateNote` method.
a1c72d6  2016-11-19 Leon Jacobs Add Trait that allows adding notes to any model.
dc81167  2016-11-17 Leon Jacobs Return an unresolved query for datatables to work with.
e3437ca  2016-11-17 Leon Jacobs Join invTypes to get the contact type
d804d7e  2016-11-16 Leon Jacobs Return raw query builder objects for use with datatables
3b1cc16  2016-11-15 Leon Jacobs Prevent overriding existing functions.
eca05dd  2016-11-15 Leon Jacobs Alloe setting settings values using the helper.
c62da72  2016-11-13 Leon Jacobs Remove stale usages of the old `Filterable` trait.
68e28c9  2016-11-13 Leon Jacobs Allow for repo queries to return unresolved.
5ae8c91  2016-11-11 Leon Jacobs Add flag to return unresolved queries for datatables.
bdb2ba0  2016-11-08 Leon Jacobs Add Intel repository
f65548e  2016-11-05 Leon Jacobs Code formatting fixes
6ccfb97  2016-11-05 Leon Jacobs Paginate market orders
720e5cb  2016-11-04 Leon Jacobs Use logger() helper
1ad9cfb  2016-11-04 Leon Jacobs Remove `array_flatten()` as collections are returned
d8ddbb0  2016-11-04 Leon Jacobs Fix column ambiguity
d1d46cf  2016-10-30 Leon Jacobs Remove return type as it can be null
d13d650  2016-10-25 Leon Jacobs Refactor Corporation repo to use structured classes
ab9f039  2016-10-25 Leon Jacobs Refactor the Character repository to use seperate classes
3f7a1f9  2016-10-23 Leon Jacobs Return a single value instead of array
6b0aa6c  2016-10-23 Leon Jacobs Remove usage of `collect()`. Collections are returned by default
7784321  2016-10-23 Leon Jacobs Update PHP & Laravel dependencies
1de059b  2016-10-23 Leon Jacobs Log queries based on the value of `DB_DEBUG`
c5ac762  2016-10-21 Leon Jacobs Revert groupBy changes introduced in 982b8661
ee0ff98  2016-10-21 Leon Jacobs Upgrade to coduo/php-humanizer 2.0
869f330  2016-10-21 Leon Jacobs Fix namespace change for humanizer 2.0
982b866  2016-10-21 Leon Jacobs Fix strict mode groupBy constraints
3f1f2c5  2016-10-21 Leon Jacobs Make the query debugger listen on the DB facade directly.
0ff8a45  2016-10-17 Leon Jacobs Fix Job to match L5.3 changes
ac59839  2016-10-17 Leon Jacobs Rename lists() to pluck()
5dc3ac7  2016-10-15 Leon Jacobs Get the value with `value()` instead of `pluck()`
```
### 2.0.0-alpha2
```
69ad918  2016-11-26 Leon Jacobs (tag: 2.0.0-alpha2) Drop minimum stability, add prefer-stable and bump to 2.0.0-alpha2.
```
### 2.0.0
```
b3fdb7a  2016-12-08 Leon Jacobs (tag: 2.0.0) Version Bump! 2.0.0! ⚡️
cdde3d0  2016-12-08 Leon Jacobs Format and style fixes.
95eee16  2016-11-30 Leon Jacobs Allow longer values in the global settings.
b64e55b  2016-11-29 Leon Jacobs Add default for api_constraint
77822f5  2016-11-29 Leon Jacobs Formatting and style fixes.
ae73811  2016-11-28 Leon Jacobs Add methods for searching.
dcc872f  2016-11-28 Leon Jacobs Return a unresolved query.
ac10ed1  2016-11-28 Leon Jacobs Rename getAllCharactersWithAffiliations method.
0277069  2016-11-27 Leon Jacobs Move character skills graph info from the Stats to Character repo.
7a2ca83  2016-11-27 Loïc LEUILLIOT add skills related chart (#10)
5f2f09f  2016-11-26 AsherST Fix where clause for PI (#11)
```
### 2.0.1
```
e51c35d  2016-12-11 Leon Jacobs (tag: 2.0.1) Version Bump
2209e71  2016-12-11 Leon Jacobs Remove return type as it can be null too
eb58671  2016-12-11 Leon Jacobs Fix member tracking query to return correct key statuses.
22f1d42  2016-12-11 Leon Jacobs Add default value for require_activation
```
### 2.0.2
```
de658a8  2016-12-15 Leon Jacobs (tag: 2.0.2) Version Bump
aaec7d7  2016-12-15 Leon Jacobs Formatting fixes.
0bde264  2016-12-15 Loïc LEUILLIOT implement a custom method dedicated to search for ApiKey (#12)
8203f69  2016-12-14 Leon Jacobs Add function to parse evemail threads.
```
### 2.0.3
```
33be7aa  2016-12-16 Leon Jacobs (tag: 2.0.3) Version Bump
17fcaec  2016-12-16 Leon Jacobs Add new mail_threads option
d966f59  2016-12-16 Leon Jacobs Add method to remove job tracking items
```
### 2.0.4
```
9e68e86  2016-12-22 Leon Jacobs (tag: 2.0.4) Version Bump
9041297  2016-12-22 Leon Jacobs Dont prefix cache keys with the session_id
```
### 2.0.5
```
fc82256  2016-12-22 Leon Jacobs (tag: 2.0.5) Version Bump
1a56751  2016-12-22 Leon Jacobs Only prefix user keys with the session_id
```
### 2.0.6
```
318fc64  2016-12-28 Leon Jacobs (tag: 2.0.6) Version Bump
637e566  2016-12-26 Leon Jacobs Add methods to get contract items
bc09a37  2016-12-26 Leon Jacobs Formatting and code style fixes
84dfae6  2016-12-26 freedenizen Add assetContents collection for Character Assets view (#14)
2efc1ff  2016-12-26 Loïc LEUILLIOT including level in skill coverage chart (#13)
```
### 2.0.7
```
462fd5c  2017-01-12 Leon Jacobs (tag: 2.0.7) Version Bump
0be2e39  2017-01-12 freedenizen Character assets (#16)
44c6db5  2017-01-04 Leon Jacobs Update styleci config
e36d874  2017-01-02 Leon Jacobs Apply fixes from StyleCI (#15)
2ecf750  2017-01-02 Leon Jacobs Add StyleCI configuration & badge
4a232d1  2017-01-01 Leon Jacobs Style fixes
```
### 2.0.8
```
f0074be  2017-01-22 Leon Jacobs (tag: 2.0.8) Version Bump
9144305  2017-01-22 Leon Jacobs Apply fixes from StyleCI (#17)
f29b680  2017-01-22 Leon Jacobs Add `childContentCount` field for assets
42adef9  2017-01-20 Leon Jacobs Add codeclimate configuration
```
### 2.0.9
```
1095543  2017-04-17 Leon Jacobs (tag: 2.0.9) Version Bump
dc46c73  2017-02-19 moe-alabel Modified cron statements to proper format. Changed from 6 positions to 5 (#18)
```
### 2.0.10
```
3feccc6  2017-07-02 Leon Jacobs (tag: 2.0.10) Version Bump
eb02e76  2017-07-02 Loïc LEUILLIOT avoid null exception on assetlist_locations for starbases trait (#22)
4358497  2017-07-02 BenH    Added support for the 'Render' type (#23)
```
### 2.0.11
```
4658230  2017-08-12 Leon Jacobs (tag: 2.0.11) Version Bump
d1bc5b3  2017-08-12 Leon Jacobs Remove an unused variable and style fixes.
654e4da  2017-08-12 Loïc LEUILLIOT add ACL filters on dashboard stats (#25)
a65f4a4  2017-08-12 Leon Jacobs Style fixes
f4e1c22  2017-08-12 Loïc LEUILLIOT optimise top mail query by dropping join table and exploit getAffiliationMap in order to retrieve the user character IDs (#24)
```
### 2.0.12
```
01a90cc  2017-10-25 Leon Jacobs (tag: 2.0.12) Version Bump.
294f2cb  2017-10-25 Leon Jacobs Update account status correctly.
```
### 2.0.13
```
86c8bcc  2018-03-17 Loïc LEUILLIOT (tag: 2.0.13) hotfix - add missing ESS amount to the corporation bounty ledger (#38)
```
### 3.0.0-beta1
```
128de35  2018-04-29 Leon Jacobs (tag: 3.0.0-beta1) Upgrade packages and version 3.0.0-beta1
d5abfed  2018-04-29 Leon Jacobs Apply fixes from StyleCI (#48)
a24eeb1  2018-04-29 Leon Jacobs Indentation fixes.
ce16ce3  2018-04-29 Leon Jacobs Fix annotator warnings.
0583f55  2018-04-29 Leon Jacobs Formatting and style fixes.
73c92bc  2018-04-29 Loïc LEUILLIOT moving queries to service package (#47)
8002684  2018-04-29 Leon Jacobs Fix docstring.
538c27e  2018-04-28 Leon Jacobs Update corporation asset repository.
9ec579d  2018-04-28 Leon Jacobs Use associatedCharacterIds() helper.
47ec800  2018-04-28 Leon Jacobs Include refresh tokens.
a39ce84  2018-04-28 Loïc LEUILLIOT pruning chat channel system according to CCP state (#46)
3dcf979  2018-04-28 Loïc LEUILLIOT upgrade corporation contact in order to implement labels (#45)
e7fbe1f  2018-04-18 Loïc LEUILLIOT update intel for ESI models (#44)
f8b1ea5  2018-04-17 Leon Jacobs Apply fixes from StyleCI (#42)
b44c87f  2018-04-17 Herpaderp Aldent Add PI as default SSO scope (#41)
c191653  2018-04-15 Leon Jacobs Update code formatting.
31a5376  2018-04-15 Loïc LEUILLIOT Issue254 (#40)
2c805ce  2018-04-02 Leon Jacobs Update scheduler with ESI jobs.
282d343  2018-04-02 Leon Jacobs Remove people repository.
60b05cd  2018-04-02 Leon Jacobs Include Horizon metrics jobs.
657ab92  2018-03-31 Leon Jacobs Update Security trait for ESI models.
33b8e39  2018-03-31 Leon Jacobs Update services for mail and corp contacts.
2fce3fb  2018-03-18 Leon Jacobs Remove unused defaults.
0ea54f4  2018-03-18 Leon Jacobs Add sso_scopes global configuration.
6c6de4f  2018-03-18 Leon Jacobs Json encode/decode settings by default.
cfd2ebe  2018-03-18 Leon Jacobs Remove keys eager loading.
e483d9a  2018-03-18 Leon Jacobs Remove nested Trait usage from Corporation repository.
b1092ec  2018-03-18 Leon Jacobs Minor formatting fixes.
adee5b0  2018-03-18 Loïc LEUILLIOT Corporation 3.x (#39)
a5df115  2018-03-02 Loïc LEUILLIOT Corporation 3.x (#36)
0eb76a2  2018-02-17 Leon Jacobs Fix character list query to allow super admins to see all.
410ea9b  2018-02-17 Leon Jacobs Remove unnecessary return.
17eb41c  2018-02-17 Leon Jacobs Fix query debugger trying to __toString() invalid values.
d7ccf47  2018-02-17 Leon Jacobs Update getAllCharactersWithAffiliations to no longer want keys.
7e253a6  2018-02-17 Leon Jacobs Minor style fixes.
7142106  2018-02-17 Loïc LEUILLIOT Update of character service according to new ESI models (#35)
555c6f8  2018-02-03 Leon Jacobs Update methods for profile view.
b51b709  2018-01-14 Leon Jacobs Remove old repositories.
6681ca3  2018-01-14 Leon Jacobs [WIP] Update repositores for ESI migration.
```
### 3.0.0-beta2
```
9bf27d0  2018-04-29 Leon Jacobs (tag: 3.0.0-beta2) v3.0.0-beta2
```
### 3.0.0-beta3
```
57067dd  2018-04-29 Leon Jacobs (tag: 3.0.0-beta3) v3.0.0-beta3
323a07c  2018-04-29 Leon Jacobs Add missing returns.
```
### 3.0.0-beta4
```
7c065ad  2018-05-02 Leon Jacobs (tag: 3.0.0-beta4) v3.0.0-beta4
643288d  2018-05-02 Leon Jacobs Rename numberToRomanRepresentation to number_roman and style fixes.
42b9605  2018-05-02 Herpaderp Aldent Enabler: Extend PI View with Extractors (#49)
c3b4010  2018-04-29 Leon Jacobs Fix return type for getCharacterJournalStandingsWithProfile.
a910847  2018-04-29 Leon Jacobs Remove method return type.
```
### 3.0.0-beta5
```
280a14a  2018-05-07 Leon Jacobs (tag: 3.0.0-beta5) v3.0.0-beta5
883fedc  2018-05-07 Leon Jacobs Give Analytics job just one try.
bb74a44  2018-05-06 Leon Jacobs Add groups method.
d188fdd  2018-05-06 Leon Jacobs Fix methods after user <-> group association changes.
```
### 3.0.0-beta6
```
7b01ae6  2018-05-08 Leon Jacobs (tag: 3.0.0-beta6) v3.0.0-beta6
7bb0f78  2018-05-08 Loïc LEUILLIOT fix route and user/group relationships on user layouts (#51)
701267f  2018-05-08 Loïc LEUILLIOT faction are provided by ccp on their cdn on alliance route - except drifter :/ (#50)
```
### 3.0.0-beta7
```
0d3b09c  2018-05-16 Leon Jacobs (tag: 3.0.0-beta7) v3.0.0-beta7
e9b7c4c  2018-05-15 Leon Jacobs Add the default for number of workers.
a7e3c26  2018-05-15 Leon Jacobs Only show unique emails in the timeline.
```
### 3.0.0-beta8
```
dcd4b69  2018-05-19 Leon Jacobs (tag: 3.0.0-beta8) v3.0.0-beta8
99a5162  2018-05-18 Leon Jacobs Fix settings cache prefixes to be tied to group ids.
e62d320  2018-05-18 Leon Jacobs Apply fixes from StyleCI (#53)
f0d195d  2018-05-18 Leon Jacobs Show stats for all users in group.
d4bc7a9  2018-05-18 Leon Jacobs Apply settings to a group rather than a specific user.
```
### 3.0.0-beta9
```
4482cf3  2018-05-20 Leon Jacobs (tag: 3.0.0-beta9) v3.0.0-beta9
671844f  2018-05-20 Leon Jacobs Update repository.
d9be804  2018-05-20 Leon Jacobs Style fix.
63dc301  2018-05-20 Leon Jacobs Add structures repository.
7e4a27b  2018-05-20 Leon Jacobs Add `alerts:run` to the schedule.
```
### 3.0.0-beta10
```
2b7d6b2  2018-05-23 Leon Jacobs (tag: 3.0.0-beta10) v3.0.0-beta10
0aeb7f3  2018-05-23 Leon Jacobs Fix setting set/get affected group id calculation.
9d506e2  2018-05-23 Loïc LEUILLIOT fix minor ACL issue related to corporation listing (#54)
```
### 3.0.0-beta11
```
2624b5b  2018-05-24 Leon Jacobs (tag: 3.0.0-beta11) v3.0.0-beta11
911ac7a  2018-05-24 Leon Jacobs Fix settings relationship.
```
### 3.0.0-beta12
```
95df998  2018-05-27 Leon Jacobs (tag: 3.0.0-beta12) v3.0.0-beta12
dc175a1  2018-05-27 Leon Jacobs Add missing .
fb4f0e1  2018-05-27 Leon Jacobs Add maintenance job and schedule.
f25b81b  2018-05-27 Leon Jacobs Add cleanup_data option.
9ba63a3  2018-05-27 Leon Jacobs Add esi status job schedule and repository.
```
### 3.0.0-beta13
```
dab8f58  2018-05-30 Leon Jacobs (tag: 3.0.0-beta13) v3.0.0-beta13
494fb0c  2018-05-29 Leon Jacobs Remove extra newline.
db33d22  2018-05-29 Leon Jacobs Add character fittings repository.
bebea11  2018-05-29 Leon Jacobs Drop the default # of workers to spawn.
```
### 3.0.0-beta14
```
4a5e2b6  2018-06-13 Leon Jacobs (tag: 3.0.0-beta14) v3.0.0-beta14
cc5c160  2018-06-13 Leon Jacobs Cleanup empty groups.
2ea8bcb  2018-06-09 Leon Jacobs Add a daily queue restart job to help with some leaks.
b4bd180  2018-06-09 Loïc LEUILLIOT fix search issue due to user/group refactoring (#56)
2633f6d  2018-06-09 Loïc LEUILLIOT Fix update sde schedule command (#55)
```
### 3.0.0
```
33d0d7d  2018-06-16 Leon Jacobs (tag: 3.0.0) v3.0.0 🎉
f506590  2018-06-16 Leon Jacobs Remove unused class.
1af5a97  2018-06-16 Leon Jacobs Update repository to paginate standings.
```
### 3.0.1
```
2b00724  2018-06-30 Leon Jacobs (tag: 3.0.1) v3.0.1
d980b88  2018-06-30 Leon Jacobs Remove outposts scope.
ced5016  2018-06-30 Leon Jacobs Add missing comment.
2da79d6  2018-06-30 Herpaderp Aldent CharacterMiningTotal ISK (#58)
4de3c9a  2018-06-30 Loïc LEUILLIOT fix PI extractors query (#57)
```
### 3.0.2
```
aa57926  2018-08-20 Leon Jacobs (tag: 3.0.2) v3.0.2
4d1fc62  2018-08-17 Loïc Leuilliot fix(search): Add missing character affiliation filters on mail search (#61)
deb1c96  2018-08-17 Loïc Leuilliot fix(industry jobs): Fix location field (#60)
fd85db8  2018-08-17 Loïc Leuilliot fix(corporation assets): Fix asset top level listing (#59)
```
### 3.0.3
```
6155fd9  2018-10-04 Leon Jacobs (tag: 3.0.3) v3.0.3
6868841  2018-09-16 Herpaderp Aldent feat(prices): Lock mining values
```
### 3.0.4
```
3335171  2018-12-08 Loïc LEUILLIOT (tag: 3.0.4) build(core): v3.0.4
cad123e  2018-12-08 Loïc LEUILLIOT fix(corporation): Update corporation killmails according to partials update
2a71dc3  2018-12-08 Loïc LEUILLIOT fix(corporation): Update corporation journal according to partials update
6fef491  2018-12-08 Herpaderp Aldent [feat](market): Update market tab and refactor partials (#74)
ffba218  2018-12-08 Herpaderp Aldent [feat](mails): Add sender to relation eager load
4bb2032  2018-12-08 Herpaderp Aldent [feat](transactions): Move character transactions to async loading
979d245  2018-12-06 Herpaderp Aldent [feat](core): Use new migration mechanic
6b8417f  2018-12-06 Herpaderp Aldent [feat](killmails): Use ORM relationship in order to avoid raw JOIN
9f78d66  2018-12-06 Herpaderp Aldent [feat](wallet): Use ORM relationship to link parties
e913402  2018-12-06 Herpaderp Aldent [feat](contracts): Move to asynchronous loading
26817c9  2018-12-06 Herpaderp Aldent [feat](contacts): Move to asynchronous loading
ad8cc1e  2018-12-06 Herpaderp Aldent [feat](assets): Move to asynchronous loading
22d7612  2018-12-06 Herpaderp Aldent [feat](users): Move to asynchronous loading
817483c  2018-10-28 Loïc Leuilliot fix(mining ledger): Fix loading time issue due to prices eager-load (#65)
77b52bb  2018-10-09 Herpaderp Aldent [fix](prices) Fix historical price table field size
```
### 3.0.5
```
3646324  2019-01-13 Loïc LEUILLIOT (tag: 3.0.5) build(core): v3.0.5
0fc1e61  2019-01-12 Herpaderp Aldent some minor refactoring and testing of https://github.com/eveseat/seat/issues/453 (#84)
435d3bb  2019-01-12 Loïc Leuilliot feat(extractions): Provide data related to corporation extraction (#85)
f57f641  2019-01-07 Herpaderp Aldent feat(character): Move intel to asynchronous requests and improve UI
e05b114  2019-01-07 Loïc Leuilliot feat(versions): Switch package versions display to generic list
226b1c5  2019-01-06 Herpaderp Aldent Refactor view: (#83)
b00244b  2019-01-06 Herpaderp Aldent Refactor corporation journal to work as in game. (#82)
216e8af  2019-01-06 Herpaderp Aldent Some refactoring in the service and view to be consistant with character. (#81)
697b5a3  2019-01-06 Herpaderp Aldent Corporation tracking (#78)
1ff335a  2018-12-15 Loïc Leuilliot fix(dashboard): Avoid eager load usage on mining stats leading to timeout (#68)
```
### 3.0.6
```
8956254  2019-03-23 Loïc LEUILLIOT (tag: 3.0.6) build(core): v3.0.6
f259657  2019-03-23 Herpaderp Aldent feat(datatables): Add a generic filter for universe names (#86)
96f04d1  2019-03-10 Herpaderp Aldent feat(mining): Switch table to server-side rendering (#89)
09c462c  2019-03-10 Peter Petermann fix(search): Correct asset search query to use proper array (#90)
64d579e  2019-02-18 Leon Jacobs Apply fixes from StyleCI (#88)
```
### 3.0.7
```
7207b51  2019-05-15 Loïc LEUILLIOT (tag: 3.0.7) build(core): v3.0.7
2654b97  2019-05-15 Loïc Leuilliot fix(industry): improve performance related to industry jobs rendering (#93)
5ceaae5  2019-05-11 Loïc Leuilliot fix(standings): allow standings filter to be nullable (#92)
```
### 3.0.8
```
c017887  2019-05-20 Loïc LEUILLIOT (tag: 3.0.8) build(core): v3.0.8
28db4de  2019-05-20 Loïc Leuilliot fix(plugin): return the proper github page (#94)
```
### 3.0.9
```
f4aff88  2019-08-13 Loïc LEUILLIOT (tag: 3.0.9) build(core): v3.0.9
b63e362  2019-08-09 Loïc Leuilliot refactor(titles): use relationship instead atomic table (#96)
29d76cc  2019-06-14 Loïc Leuilliot feat(core): freeze helper plugin methods (#95)
```
### 3.0.10
```
2419632  2019-10-04 Loïc LEUILLIOT (tag: 3.0.10) build(core): v3.0.10
f3b5e3f  2019-10-04 Loïc Leuilliot fix(titles): reduce abnormal loop on corp titles page (#99)
b075df2  2019-08-24 Loïc Leuilliot fix(image): address a logic issue related to invType maximum size (#97)
```
### 3.0.11
```
27b3323  2019-10-28 Loïc LEUILLIOT (tag: 3.0.11, seat/3.0.x, 3.0.x) build(core): v3.0.11
57bf9ad  2019-10-28 Loïc LEUILLIOT fix(image): lock retina size to 64px for invType
```
### 4.0.0-rc1
```
0f1ddab  2019-10-31 Loïc LEUILLIOT (tag: 4.0.0-rc1) refactor(mails): reduce duplicated entries on mails module
ed2c7cc  2019-10-30 Loïc LEUILLIOT fix(intel): ensure fields returned by top queries are properly grouped
5cc8dd7  2019-10-29 Loïc LEUILLIOT fix(image): use proper DNS to call eve image server
86c81fb  2019-10-28 Loïc LEUILLIOT fix(image): lock retina size to 64px for invType
99615aa  2019-10-28 Loïc LEUILLIOT style: apply styleCI change requests
a2b1533  2019-10-28 Loïc LEUILLIOT refactor(search): simplifying search queries using eloquent
cc51f11  2019-10-28 Loïc LEUILLIOT refactor(acl): use scope to determine authorized char and corp
1eed312  2019-10-24 Loïc LEUILLIOT fix(acl): remove vanilla affiliation system
0cf63c1  2019-10-22 Loïc LEUILLIOT fix(ledger): use proper party to render corp wallet ledger
9fb5ac0  2019-10-22 Loïc Leuilliot feat(corporation): add new categories to wallet ledger (#102)
2b74476  2019-10-22 Loïc Leuilliot refactor(core): move AbstractSeatPlugin from services to seat package (#101)
29e4566  2019-10-17 Loïc Leuilliot Merge pull request #100 from warlof/4.0.x
4ff7354  2019-10-17 Loïc LEUILLIOT fix(ledger): fix group by query in order to return PI taxes
c2004dd  2019-10-16 Loïc LEUILLIOT fix(ledger): fix group by query in order to return bounties
cbed82b  2019-10-15 Loïc LEUILLIOT feat(relationship): improve performances regarding roles rendering
bd2e5c6  2019-10-10 Loïc LEUILLIOT fix(mails): fix group by query in order to return mail timeline
1e7291a  2019-10-10 Loïc LEUILLIOT fix(deps): dev must be use as a suffix instead prefix
29d95a7  2019-10-10 Loïc LEUILLIOT chore(deps): downgrade stability to dev version
b4f74b9  2019-10-10 Loïc LEUILLIOT chore(deps): update dependencies to Laravel 6.x
c83ecca  2019-10-06 Loïc Leuilliot (seat/master, master) refactor(datatable): increase Yajra/Datatables usage (#98)
```
### 4.0.0-rc2
```
aeb88e0  2019-11-16 Loïc LEUILLIOT (tag: 4.0.0-rc2) fix(deps): update php minimum version to 7.3
e27af33  2019-11-16 Loïc LEUILLIOT refactor(acl): drop Group class and use an unique user bucket
a7e1e02  2019-11-11 Loïc LEUILLIOT style: apply styleci changes request
1332a0b  2019-11-11 Loïc LEUILLIOT ci(styleci): remove rules from preset
fab14a8  2019-11-11 Loïc LEUILLIOT feat(parsers): add generic parsers to handle EVE reports
ed4ee0d  2019-11-11 Loïc LEUILLIOT feat(ui): use new EVE image server signatures
```
### 4.0.0-rc3
```
2524256  2020-02-09 Loïc LEUILLIOT (tag: 4.0.0-rc3) refactor: move schedule seeder to console
2e79c68  2020-02-06 Loïc LEUILLIOT fix(reports): allow dash character in regex group
cfc8caf  2020-01-12 Loïc LEUILLIOT refactor: update commands seeder
5605bd4  2020-01-12 Loïc LEUILLIOT fix(intel): fix mail stats query according to merge
467e6ee  2020-01-10 Loïc LEUILLIOT refactor(killmails): remove character_killmail
389cd4e  2020-01-04 Loïc LEUILLIOT feat(auth): switch SSO to v2 endpoints
```
### 4.0.0-rc4
```
d95d46f  2020-03-17 Loïc Leuilliot (tag: 4.0.0-rc4) ci(styleci): update config for preset changes
c24a5c8  2020-03-15 Loïc LEUILLIOT ci(styleci): update configuration according to laravel preset
dc73dd6  2020-03-15 Ben Thompson refactor(intel): refactor the queries for intel to remove duplicates and add missing variable from (#119)
8c29afd  2020-02-26 Ben Thompson fix(membertracking): Update Corporation Members repository to use updated model relations
d1ce6a2  2020-02-16 Ben Thompson fix(search): workaround for eloquent column name collision issue
00eaddc  2020-02-16 Ben Thompson fix(search): Update corporation and alliance relation through affiliation model
0751b0d  2020-02-14 Justin Mercer fix(repositories): Change corporation relationship to affiliation.corporation
```