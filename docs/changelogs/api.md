![SeAT](https://i.imgur.com/aPPOxSK.png)

# api change logs
Generated with: `git log --pretty=format:"%h%>(12)%ad %<(7)%aN%d %s" --date=short`

### 1.0.0
```
03064d4  2015-11-30 Leon Jacobs (tag: 1.0.0) Add admin views, complete middleware and add menu.
c11ca2e  2015-11-30 Leon Jacobs Add Corporation API Endpoints
122f2da  2015-11-30 Leon Jacobs Add Character API Endpoints
dda7cbb  2015-11-30 Leon Jacobs Add endpoint to validate credentials
014502b  2015-11-30 Leon Jacobs Add roles and permissions query endpoint
4e88616  2015-11-30 Leon Jacobs Add endpoints to get Role information
4516aaa  2015-11-29 Leon Jacobs Add CRUD for User management
2d129ea  2015-11-29 Leon Jacobs Update links to eveseat/api
2c2cef3  2015-11-29 Leon Jacobs Fix typo
5620aa2  2015-11-29 Leon Jacobs Update README
6905c26  2015-11-29 Leon Jacobs Compelte the EVE API Key API
32d17cf  2015-11-29 Leon Jacobs First preperations for the SeAT API
57f8c6d  2015-11-28 Leon Jacobs first commit
```
### 1.0.1
```
cc4ea85  2015-12-01 Leon Jacobs (tag: 1.0.1) Version Bump
16c3896  2015-12-01 Leon Jacobs Dont use a sub-menu
88348cb  2015-12-01 Leon Jacobs Cleanup Middleware and add Request Path logging
```
### 1.0.2
```
de62767  2015-12-04 Leon Jacobs (tag: 1.0.2) Update README.md
```
### 1.0.3
```
dee0f28  2015-12-16 Leon Jacobs (tag: 1.0.3) Version Bump
76647e9  2015-12-16 Leon Jacobs Add localization support
```
### 1.0.4
```
3b80952  2015-12-20 Leon Jacobs (tag: 1.0.4) Version Bump
55269b9  2015-12-20 Leon Jacobs Add char & corp Bookmarks endpoints
b65799f  2015-12-20 Leon Jacobs Add Character Channels endpoint
```
### 1.0.5
```
220b7bb  2015-12-24 Leon Jacobs (tag: 1.0.5) Version Bump
86c4602  2015-12-24 Leon Jacobs Specify versions with ~
```
### 1.0.6
```
a949267  2015-12-26 Leon Jacobs (tag: 1.0.6) Version Bump
8f5c35f  2015-12-26 Leon Jacobs Allow for API Keys to be transferred to a different User
c712823  2015-12-26 Leon Jacobs Add starbase and assets-by-location endpoints
```
### 1.0.7
```
6ca59b0  2015-12-27 Leon Jacobs (tag: 1.0.7) Version Bump
603cb76  2015-12-27 Leon Jacobs Add ability to get a specific starbases info
```
### 1.0.8
```
2409d0c  2015-12-28 Leon Jacobs (tag: 1.0.8) Version Bump
ad8351a  2015-12-28 Leon Jacobs Add Corp Pocos Endpoint
```
### 1.0.9
```
22f8b34  2016-01-26 Leon Jacobs (tag: 1.0.9) Version Bump
f6bfc7e  2016-01-26 Leon Jacobs Update copyright
7f24bf8  2016-01-06 Leon Jacobs Code style fixes
```
### 1.0.10
```
3faff1e  2016-04-29 Leon Jacobs (tag: 1.0.10) Version Bump
99871c9  2016-04-29 Leon Jacobs Rename repository method that was incorrectly called
131a3b8  2016-04-29 Leon Jacobs Add /api/v1/corporation/all endpoint
be8e6aa  2016-04-29 Leon Jacobs Include key info and characters.
```
### 1.0.11
```
d35e7ef  2016-06-26 Leon Jacobs (tag: 1.0.11) Version Bump
60475a4  2016-06-26 Leon Jacobs Add /api/v1/corporation/assets-contents/{corp_id} endpoint
530703c  2016-06-26 Leon Jacobs Add missing PPHDoc comment for argument
```
### 1.0.12
```
fbf3e88  2016-07-10 Leon Jacobs (tag: 1.0.12) Version Bump
e8f1882  2016-07-10 Leon Jacobs Fix eveseat/seat#115 by adding new endpoints for role management
729971f  2016-07-10 Leon Jacobs Convert from a resource to controller route for roles
d2ff1df  2016-06-28 Leon Jacobs Merge pull request #1 from nizzan/patch-1
dc80447  2016-06-28 nizzan  Typo on API Token generation
```
### 1.0.13
```
b55b1aa  2016-07-23 Leon Jacobs (tag: 1.0.13) Version Bump
8b80e11  2016-07-18 Leon Jacobs Paginate the token logs
```
### 2.0.0-alpha1
```
2d66b64  2016-11-26 Leon Jacobs (tag: 2.0.0-alpha1) Update composer for 2.0 packages and version 2.0.0-alpha1
92a189e  2016-11-26 Leon Jacobs (tag: 2.0.0-dev) Bump to 2.0.0-dev
2485046  2016-11-19 Leon Jacobs Remove unused precedence rule
80c3d0e  2016-11-05 Leon Jacobs Code formatting fixes
6d28aff  2016-11-05 Leon Jacobs Extend new core controllers instead of base in App namespace
4f74325  2016-10-25 Leon Jacobs Update to make use of new corp repository classes
39237e8  2016-10-25 Leon Jacobs Update to use new classes from the the repository
db6db82  2016-10-23 Leon Jacobs Fix middleware to include new `web` middleware.
ba92bd6  2016-10-23 Leon Jacobs Update PHP & Laravel dependencies
dc8136f  2016-10-23 Leon Jacobs Update Form Request validation to use new base class
7ebe1db  2016-10-23 Leon Jacobs Convert `Route::controller` methods to explicit routes
```
### 2.0.0-alpha2
```
cd107a5  2016-11-26 Leon Jacobs (tag: 2.0.0-alpha2) Drop minimum stability, add prefer-stable and bump to 2.0.0-alpha2.
```
### 2.0.0-dev
```

```
### 2.0.0
```
a1ef4d3  2016-12-08 Leon Jacobs (tag: 2.0.0) Version Bump! 2.0.0! ⚡️
cd107a5  2016-11-26 Leon Jacobs (tag: 2.0.0-alpha2) Drop minimum stability, add prefer-stable and bump to 2.0.0-alpha2.
2d66b64  2016-11-26 Leon Jacobs (tag: 2.0.0-alpha1) Update composer for 2.0 packages and version 2.0.0-alpha1
```
### 2.0.1
```
9a5b152  2016-12-10 Leon Jacobs (tag: 2.0.1) Version Bump
d457eeb  2016-12-10 Leon Jacobs Fix namespace for Validator
```
### 2.0.2
```
5a115a0  2016-12-11 Leon Jacobs (tag: 2.0.2) Version Bump
ca57ce6  2016-12-11 Leon Jacobs Set a user_id if one is not given.
```
### 2.0.3
```
3b90fea  2016-12-13 Leon Jacobs (tag: 2.0.3) Version Bump
8cd58b1  2016-12-12 Leon Jacobs Fix eveseat/seat#156 by adding the optional starbase_id param.
```
### 2.0.4
```
6fb753f  2016-12-28 Leon Jacobs (tag: 2.0.4) Version Bump
619d48d  2016-12-26 Leon Jacobs Update internal menu name
```
### 2.0.5
```
7b91b04  2017-01-12 Leon Jacobs (tag: 2.0.5) Version Bump
8c3004d  2017-01-04 Leon Jacobs Update styleci config
44dbb59  2017-01-02 Leon Jacobs Add StyleCI badge.
b11d5c5  2017-01-02 Leon Jacobs Apply fixes from StyleCI (#2)
7f7674d  2017-01-02 Leon Jacobs Add StyleCI configuration
```
### 2.0.6
```
24ec51c  2017-01-22 Leon Jacobs (tag: 2.0.6) Version Bump
56c550e  2017-01-22 Leon Jacobs Apply fixes from StyleCI (#3)
5d0b17f  2017-01-22 Leon Jacobs Add groups/ and groups/{id} endpoints.
1ee8e81  2017-01-20 Leon Jacobs Add codeclimate configuration
```
### 2.0.7
```
18a75cc  2017-01-31 Leon Jacobs (tag: 2.0.7) Version Bump
2716318  2017-01-31 Loïc LEUILLIOT fix middleware flow for bouncer null exception (#4)
```
### 2.0.8
```
88a519c  2017-04-17 Leon Jacobs (tag: 2.0.8) Version Bump
85f2c98  2017-04-17 Leon Jacobs Apply fixes from StyleCI (#7)
f345da5  2017-04-17 Leon Jacobs Small cleanup
645a369  2017-04-17 Loïc LEUILLIOT Keys duplication (#6)
1b16132  2017-03-29 NoMercy82 Updating routes.php to include member tracking url (#5)
```
### 2.0.9
```
36c8592  2017-08-12 Leon Jacobs (tag: 2.0.9) Version Bump
8c6e4e3  2017-08-12 Leon Jacobs Style fixes.
91c33bf  2017-08-12 Loïc LEUILLIOT Update role (#8)
38d0fc8  2017-08-12 Loïc LEUILLIOT fix api log issue (#10)
```
### 2.0.10
```
a36841b  2017-10-25 Leon Jacobs (tag: 2.0.10) Version Bump.
7293928  2017-10-25 Loïc LEUILLIOT security hotfix related to API log which add missing method column (#12)
```
### 3.0.0-beta1
```
2d32c6e  2018-04-29 Leon Jacobs (tag: 3.0.0-beta1) Package upgarde and v3.0.0-beta1.
3d941cb  2018-04-29 Leon Jacobs Apply fixes from StyleCI (#15)
bbe233c  2018-04-29 Leon Jacobs Indentation fixes.
a773f77  2018-04-17 Leon Jacobs Apply fixes from StyleCI (#14)
d98f460  2017-09-18 Leon Jacobs Update middleware registers for Laravel 5.5.
```
### 3.0.0-beta2
```
6dbd039  2018-04-29 Leon Jacobs (tag: 3.0.0-beta2) v3.0.0-beta2
```
### 3.0.0-beta3
```
1fc7fc3  2018-05-02 Leon Jacobs (tag: 3.0.0-beta3) v3.0.0-beta3
4fda254  2018-05-02 Leon Jacobs Remove old API controllers.
6f7952c  2018-05-02 Leon Jacobs Complete v2 character level API endpoints.
eac5238  2018-05-01 Leon Jacobs Migrate and document more endpoints.
321666b  2018-05-01 Leon Jacobs Start the v2, swaggified API.
30117e0  2018-05-01 Leon Jacobs Remove unused trait.
```
### 3.0.0-beta4
```
73c4945  2018-05-05 Leon Jacobs (tag: 3.0.0-beta4) v3.0.0-beta4
bd36017  2018-05-05 Leon Jacobs Compelte API migration to v2 & Swagger.
482d09a  2018-05-04 Leon Jacobs Start adding user management v2 endpoints.
ebaeaed  2018-05-03 Leon Jacobs Add v2 Corporation API endpoints and remove v1 endpoints.
```
### 3.0.0-beta5
```
689a886  2018-05-08 Leon Jacobs (tag: 3.0.0-beta5) v3.0.0-beta5
35012f3  2018-05-08 Leon Jacobs Fix method name.
e8c7137  2018-05-08 Loïc LEUILLIOT Fix grouprelationship (#17)
57b2b86  2018-05-05 Leon Jacobs Add link to API documentation.
9d24246  2018-05-05 Leon Jacobs Apply fixes from StyleCI (#16)
```
### 3.0.0
```
a592a59  2018-06-16 Leon Jacobs (tag: 3.0.0) v3.0.0 🎉
31f88e0  2018-06-16 Leon Jacobs Style fix.
81bf6d3  2018-06-16 Leon Jacobs Add ability to populate and retreive refresh tokens.
0f75f3f  2018-06-16 Leon Jacobs Fix class order.
99e5376  2018-06-16 Leon Jacobs Move validation classes namespace.
cbabab1  2018-06-16 Leon Jacobs Remove old validation rules.
be53e61  2018-06-16 Leon Jacobs Expose user token via API
```
### 3.0.1
```
9c531be  2018-07-29 Leon Jacobs (tag: 3.0.1) v3.0.1
6ba9e60  2018-07-29 Loïc LEUILLIOT fix issue which was preventing to use swagger UI to test endpoints (#22)
f4f6657  2018-07-29 Loïc LEUILLIOT improve api logging by appending request method. Use swagger color chart (#23)
6b3ecdd  2018-07-29 Loïc LEUILLIOT Improve api docs (#21)
e82a756  2018-07-29 Leon Jacobs Formatting fixes.
f44c675  2018-07-29 Loïc LEUILLIOT add group control logic in order to deny addition to admin group (#20)
292acd5  2018-07-29 Loïc LEUILLIOT Generate API based on multiple paths (allow api documentation for plugins) (#19)
```
### 3.0.2
```
cbfcf00  2018-08-20 Leon Jacobs (tag: 3.0.2) v3.0.2
1961df9  2018-08-17 Loïc Leuilliot feat(character): Provide skillpoints and unallocated skillpoints into character sheet endpoint (#25)
fcafab2  2018-08-17 Loïc Leuilliot feat(users): Add pagination to users list (#24)
```
### 3.0.3
```
ee60536  2018-08-20 Leon Jacobs (tag: 3.0.3) v3.0.3
3230d41  2018-08-20 Leon Jacobs Temporarily pin zircote/swagger-php.
```
### 3.0.4
```
9351a4f  2018-09-09 Leon Jacobs (tag: 3.0.4) v3.0.4
3ec50da  2018-09-09 Leon Jacobs Drop the Swagger version number.
4bf5ab7  2018-09-09 Leon Jacobs Pin swagger-php more gnerically.
```
### 3.0.5
```
fbb608a  2018-12-08 Loïc LEUILLIOT (tag: 3.0.5) build(core): v3.0.5
06fd5b3  2018-12-06 Herpaderp Aldent [feat](core): Use new migration mechanic
55b372d  2018-10-09 Herpaderp Aldent [feat](api) Add main_character_id to group-list
```
### 3.0.6
```
626b74c  2019-01-13 Loïc LEUILLIOT (tag: 3.0.6) build(core): v3.0.6
9ecdad9  2019-01-07 Loïc Leuilliot feat(roles): Allow roles name to be changed (#28)
2a38099  2019-01-07 Loïc Leuilliot feat(versions): Implement new version management for API package (#29)
```
### 3.0.7
```
acd162a  2019-06-03 Loïc LEUILLIOT (tag: 3.0.7) build(core): v3.0.7
885ab4d  2019-06-03 Loïc Leuilliot fix(api): remove the type attribute on body POST and switched it in schema (#33)
9b93eaf  2019-02-18 Leon Jacobs Apply fixes from StyleCI (#32)
```
### 3.0.8
```
e88df37  2019-08-03 Loïc LEUILLIOT (tag: 3.0.8) build(core): v3.0.8
71d86ce  2019-08-03 Seb Ferraro feat(api): add main_character_id to User (#35)
4b653bc  2019-06-07 Loïc Leuilliot feat(api): enforce JSON format for API requests (#34)
```
### 4.0.0-rc1
```
ec82196  2019-10-22 Loïc Leuilliot (tag: 4.0.0-rc1) refactor(core): move AbstractSeatPlugin from services to seat package (#37)
a89a079  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade tokens logs layout
61e42cc  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade tokens list layout
6939cc2  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade to font-awesome 5
686c8d3  2019-10-10 Loïc LEUILLIOT fix(deps): update resources directory structure according L5.7
115168b  2019-10-10 Loïc LEUILLIOT fix(deps): replace str_ and arr_ helpers by their Classes
670e756  2019-10-10 Loïc LEUILLIOT fix(deps): dev must be use as a suffix instead prefix
6858b8f  2019-10-10 Loïc LEUILLIOT chore(deps): downgrade stability to dev version
c790198  2019-10-10 Loïc LEUILLIOT chore(deps): update dependencies to Laravel 6.x
```
### 4.0.0-rc2
```
32bf7af  2019-11-16 Loïc LEUILLIOT (tag: 4.0.0-rc2) fix(deps): update php minimum version to 7.3
b9a3bbf  2019-11-16 Loïc LEUILLIOT ci(styleci): remove length_ordered_imports from disabled rules
f8e9e1f  2019-11-16 Loïc LEUILLIOT refactor(acl): drop Group class and use an unique user bucket
```
### 4.0.0-rc3
```
516634a  2020-03-23 Loïc Leuilliot (tag: 4.0.0-rc3) refactor: use array of path to register api doc
5de3c69  2020-03-23 Loïc LEUILLIOT refactor(api): use api doc provider method
6523aab  2020-03-23 Loïc LEUILLIOT style(api): apply some StyleCI change requests
faac995  2020-03-23 Loïc LEUILLIOT feat(api): implement squads routes
7a68024  2020-03-23 Loïc LEUILLIOT refactor(api): upgrade users category
8972efb  2020-03-23 Loïc LEUILLIOT refactor(api): upgrade roles category
fed22d6  2020-03-22 Loïc LEUILLIOT refactor(api): switch logs to data-table factory
5758e77  2020-03-22 Loïc LEUILLIOT style: remove stale code
af292f5  2020-03-22 Loïc LEUILLIOT fix(api): ensure method is properly logged
aa3adc7  2020-03-22 Loïc LEUILLIOT feat(api): upgrade doc to OAS3
915cf8a  2020-03-17 Loïc Leuilliot ci(styleci): update config for preset changes
```