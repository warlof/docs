![SeAT](https://i.imgur.com/aPPOxSK.png)

# web change logs
Generated with: `git log --pretty=format:"%h%>(12)%ad %<(7)%aN%d %s" --date=short`

### 1.0-pre-alpha
```
6332cd7  2015-11-27 Leon Jacobs (tag: 1.0-pre-alpha) Update README
a48340a  2015-11-27 Leon Jacobs Login using names instead of emails
2dfdc27  2015-11-27 Leon Jacobs Add ability to view corp wallet transactions
06c4741  2015-11-27 Leon Jacobs Add ability to view corp wallet journals
97547a7  2015-11-27 Leon Jacobs Add ability to view corp standings
1a825e0  2015-11-27 Leon Jacobs Add ability to view corp market orders
bab5d6a  2015-11-27 Leon Jacobs Add ability to view corp killmails
26923cc  2015-11-27 Leon Jacobs Add ability to view corporation industry jobs
fc43803  2015-11-27 Leon Jacobs Add ability to view corporation contracts
a386881  2015-11-27 Leon Jacobs Add ability to view corp contacts
110b142  2015-11-27 Leon Jacobs Add ability to view corporation assets
2b9dd85  2015-11-27 Leon Jacobs Add ability to view corp summary
0bf5bdc  2015-11-26 Leon Jacobs First work on corporation views.
5114d4f  2015-11-26 Leon Jacobs Resolve a trait method conflict
5eaffdc  2015-11-21 Leon Jacobs Add ability to mass import keys via CSV files
17feb08  2015-11-21 Leon Jacobs Add ability to view character standings
797c9f0  2015-11-21 Leon Jacobs Add ability to view character research info
771ee34  2015-11-21 Leon Jacobs Add ability to view character PI
0fcb7de  2015-11-21 Leon Jacobs Add ability to view character market orders
a6b7ac6  2015-11-20 Leon Jacobs Add ability to view character industry
c020c36  2015-11-20 Leon Jacobs Small UI refactor to make it cleaner
0d5e18a  2015-11-20 Leon Jacobs Add character contract view
f36e34b  2015-11-20 Leon Jacobs Add ability to view character killmails
45e8dd5  2015-11-20 Leon Jacobs Link to character details
08d1d48  2015-10-30 Leon Jacobs Add character contacts view
dc3a396  2015-10-30 Leon Jacobs Add character calendar view
085368f  2015-10-30 Leon Jacobs Add character notifications view
04ca0ee  2015-10-30 Leon Jacobs Add filter rules.
ccc5ad2  2015-10-30 Leon Jacobs Add Character Assets View
c748d29  2015-10-29 Leon Jacobs Add table-responsive
9aaa7ae  2015-10-29 Leon Jacobs Add Character Mail View
f046272  2015-10-29 Leon Jacobs Add Character Wallet Transaction View
1ae69e0  2015-10-29 Leon Jacobs Add Character Wallet Journal View
814a95d  2015-10-29 Leon Jacobs Rename method from EveRepository
5d9cfc1  2015-10-28 Leon Jacobs Add Implants, Jump Fatigue and Clone info
ac83d39  2015-10-28 Leon Jacobs Minor formatting changes
3631b89  2015-10-28 Leon Jacobs Re-arrange character details layout
e23a153  2015-10-27 Leon Jacobs Add more character sheet info and shuffle a few things around
c414bb2  2015-10-27 Leon Jacobs Create a base view for character detail views
d3fc448  2015-10-27 Leon Jacobs Add Character Skills view
51caf72  2015-10-09 Leon Jacobs Add Security logging and viewing abilities
7debd56  2015-10-09 Leon Jacobs Start the Character Viewer
5bfbed0  2015-10-09 Leon Jacobs Small responsive fixes
4cf03ed  2015-10-08 Leon Jacobs Add All Characters View
51ccf46  2015-10-08 Leon Jacobs Add hasAny()
12e05de  2015-10-07 Leon Jacobs Split permissions into categories
50a68ab  2015-10-06 Leon Jacobs Add a view into the Job Queue as well as some management
0da342b  2015-10-06 Leon Jacobs Add live queue status updates
b9df4c4  2015-10-06 Leon Jacobs Fix cases where keys with missing info would throw errors
9faffab  2015-10-06 Leon Jacobs Remove usage of the Redirect Facade
2250508  2015-10-05 Leon Jacobs Add ability to manually start a job update
3e34b3e  2015-10-05 Leon Jacobs Add key detail viewer and introduce the keybouncer
85bf567  2015-10-05 Leon Jacobs Add ability ti list and delete API keys
2fe3d76  2015-10-04 Leon Jacobs Add lazy image loading support
ee21c49  2015-10-04 Leon Jacobs Style fixes
1de991a  2015-10-04 Leon Jacobs Add ability to add new Api Keys
358ba7f  2015-10-04 Leon Jacobs Make sidebar permissions aware
41190e6  2015-10-02 Leon Jacobs Introduce the Bouncer and hes Clipboard 🚪
c2edc6b  2015-10-02 Leon Jacobs Use auth() helper instead of Auth Facade
2a864dc  2015-10-02 Leon Jacobs Fix some inconsistency with edit/updater user lang
e473bba  2015-10-02 Leon Jacobs Swap input for has to read better
5e65509  2015-10-02 Leon Jacobs Allow for users to be quick added
89ca4e1  2015-10-02 Leon Jacobs Allow for the account status to be filled
05e6019  2015-10-02 Leon Jacobs Resize grid to match other configuration views
fdeb2cc  2015-10-02 Leon Jacobs Rename menu entry to match page title
7a03e34  2015-10-02 Leon Jacobs Complete the impersonation feature
6195979  2015-10-02 Leon Jacobs Add ability to delete users
0675ef9  2015-10-02 Leon Jacobs Cleanup when a user is deleted
4c58659  2015-10-02 Leon Jacobs Allow for users to be modified
a3f1882  2015-10-01 Leon Jacobs Add a basic summary of user roles and affiliations
f03f872  2015-09-30 Leon Jacobs Localize flash messages on perm/role changes
679b020  2015-09-30 Leon Jacobs Fix typo in affiliation form request validator
2e656a8  2015-09-30 Leon Jacobs First iteration of Acl methods and web structuring.
e8c4343  2015-09-29 Leon Jacobs Highlight submenu items based on URL match
b6cd2b9  2015-09-29 Leon Jacobs Have the sidebar honor the Locale
1f91ef0  2015-09-29 Leon Jacobs Add view composer to build the sidebar menu
3425769  2015-09-28 Leon Jacobs Add a User view composer
3e72326  2015-09-28 Leon Jacobs Restructure Service Provider
4aa96f5  2015-09-27 Leon Jacobs Fix duplicate 'reset' translation key
1160deb  2015-09-27 Leon Jacobs Use class property
22c7747  2015-09-27 Leon Jacobs Add password reset functionality
9377f67  2015-09-27 Leon Jacobs Add README
f16a71d  2015-09-27 Leon Jacobs Start web interface
3f15794  2015-09-24 Leon Jacobs Initial commit
```
### 1.0.0
```
e885f07  2015-11-28 Leon Jacobs (tag: 1.0.0) Style fixes and version Bump
fddc5ba  2015-11-28 Leon Jacobs Add SeAT Settings Page with registration toggle
30b2b9c  2015-11-28 Leon Jacobs Add more settings options
bb6e8ed  2015-11-28 Leon Jacobs Add ability to change SeAT theme.
8dbb713  2015-11-28 Leon Jacobs Read skin ccs filename from settings()
67d823c  2015-11-28 Leon Jacobs Read some values from settings
91872a1  2015-11-27 Leon Jacobs Remove unused HTML and fix brand route
3ec66f3  2015-11-27 Leon Jacobs Reduce icon size and add corp icons
e78c62f  2015-11-27 Leon Jacobs Add more complete corp security views
13f6c9d  2015-11-27 Leon Jacobs Add ability to view corp member tracking
```
### 1.0.1
```
4598815  2015-12-01 Leon Jacobs (tag: 1.0.1) Version Bump
2c683ba  2015-12-01 Leon Jacobs Dont force a package to have a sub-menu
6c13e32  2015-12-01 Leon Jacobs Resolve menu routes in the sidebar view.
e8f3237  2015-11-30 Leon Jacobs Add api version display
0f6d4ec  2015-11-30 Leon Jacobs First pass in allowing packages to add menu items
fe117ce  2015-11-30 Leon Jacobs Add hasRole() method
be056a9  2015-11-30 Leon Jacobs Fix #2
```
### 1.0.2
```
7fcac57  2015-12-02 Leon Jacobs (tag: 1.0.2) Version Bump
020c885  2015-12-02 Leon Jacobs Add notifications version
f9fdaf6  2015-12-02 Leon Jacobs Dont force packages to set a permission
5d1bb8c  2015-12-02 Leon Jacobs Add email notifications setting and new email templates
4bade0d  2015-12-02 Leon Jacobs Auto update copyright year
9eba303  2015-12-02 Leon Jacobs Add WebUI to manage schedules
```
### 1.0.3
```
bc8e6eb  2015-12-04 Leon Jacobs (tag: 1.0.3) Start something for a dashboard
0238e32  2015-12-04 Leon Jacobs Update README.md
73d415d  2015-12-04 Leon Jacobs Add optional Google Two-Factor TOTP support.
84723ff  2015-12-03 Leon Jacobs Merge pull request #3 from Cynabal/patch-1
2d98ead  2015-12-03 Cynabal Update add.blade.php
```
### 1.0.4
```
4aab9b8  2015-12-05 Leon Jacobs (tag: 1.0.4) Version Bump
```
### 1.0.5
```
df6ddae  2015-12-13 Leon Jacobs (tag: 1.0.5) Version Bump
14bc397  2015-12-13 Leon Jacobs Add ability to set an admin contact
5e6498b  2015-12-12 Leon Jacobs Add links to external services
f819124  2015-12-12 Leon Jacobs Show output of jobs
070c232  2015-12-12 Leon Jacobs Show eveapi errors status
80775e2  2015-12-11 Leon Jacobs Allows superusers to transfer keys to other owners
```
### 1.0.6
```
2042098  2015-12-16 Leon Jacobs (tag: 1.0.6) Version Bump
83a7ea8  2015-12-16 Leon Jacobs Add Afrikaans language support
0039045  2015-12-16 Leon Jacobs Add ability to select a preferred language
30a71e6  2015-12-16 Leon Jacobs Update langauge strings
2956a15  2015-12-15 Leon Jacobs Resolve contract issuerID's to names
36ea925  2015-12-15 Leon Jacobs Apply number() to a few values
40e5c24  2015-12-15 Leon Jacobs Add ability to view profile login/logout history
a8e93d7  2015-12-15 Leon Jacobs Add for user password resets
81682c4  2015-12-15 Leon Jacobs Add recipient info into the mail timeline
cc141c8  2015-12-15 Leon Jacobs Add id-to-name helper
6999007  2015-12-15 Leon Jacobs Add X-CSRF Token for ajax calls
6915fec  2015-12-15 Leon Jacobs Add the mail timeline view
5ade565  2015-12-14 Leon Jacobs Add ability to view character email
```
### 1.0.7
```
660b6fa  2015-12-17 Leon Jacobs (tag: 1.0.7) Version Bump
b65aa7e  2015-12-17 Leon Jacobs Remove URI scheme
639b3fb  2015-12-17 Leon Jacobs Add missing language definition for view
```
### 1.0.8
```
0ece0ce  2015-12-17 Leon Jacobs (tag: 1.0.8) Version Bump
616067c  2015-12-17 Leon Jacobs Check if we have data before attempting to display
99c14a3  2015-12-17 Leon Jacobs Fix eveseat/seat#10
```
### 1.0.9
```
9e4cd79  2015-12-17 Leon Jacobs (tag: 1.0.9) Add account info check and Version Bump
bfaabe2  2015-12-17 Leon Jacobs Merge pull request #4 from freedenizen/master
d802b98  2015-12-17 Asher Schaffer add updated_at timestamps to Character and Corporation Sheet summary
```
### 1.0.10
```
5aebf1e  2015-12-18 Leon Jacobs (tag: 1.0.10) Allow French to be chosen and Version Bump
dae1719  2015-12-18 Leon Jacobs Merge pull request #5 from warlof/french
6e827ae  2015-12-17 elfaus  Translate SeAT in french according to 1.0.9
```
### 1.0.11
```
ca67d0a  2015-12-20 Leon Jacobs (tag: 1.0.11) Version Bump
78da260  2015-12-20 Leon Jacobs Add ability to view corporation bookmarks
eda1260  2015-12-19 Leon Jacobs Add ability to view character bookmarks
8e1285e  2015-12-18 Leon Jacobs Add ability to view character channels
```
### 1.0.12
```
7bdbf10  2015-12-24 Leon Jacobs (tag: 1.0.12) Version Bump
6c365ad  2015-12-24 Leon Jacobs Specify versions with ~
3f604e2  2015-12-24 Leon Jacobs Merge pull request #11 from warlof/french
c1f4657  2015-12-24 elfaus  add new translations according to recent commits (for 1.0.12)
ed485b3  2015-12-24 Leon Jacobs Move strontium usage to its own string for easier translation
64a6f86  2015-12-24 Leon Jacobs Take into account bonusses silo/coupling array capacities
488fd3b  2015-12-24 Leon Jacobs Merge pull request #8 from warlof/unknown-item
cd66a8a  2015-12-24 Leon Jacobs Add Starbase details views
f9dc521  2015-12-24 elfaus  fix issue #9
9f74d1c  2015-12-24 Leon Jacobs Add more details about starbases
7e67371  2015-12-23 Leon Jacobs First pass at adding starbase views
9496188  2015-12-21 Leon Jacobs Merge pull request #6 from warlof/french
2491e69  2015-12-21 elfaus  Translate SeAT in french according to 1.0.11
f5fa4e3  2015-12-21 Leon Jacobs Show timestampts and paginate wallet info
c6b4311  2015-12-21 Leon Jacobs Fix eveseat/seat#15
```
### 1.0.13
```
936e8b8  2015-12-24 Leon Jacobs (tag: 1.0.13) Fix a assets check, add missing string and Version Bump
```
### 1.0.14
```
3f8587c  2015-12-26 Leon Jacobs (tag: 1.0.14) Version Bump
14d87b4  2015-12-26 Leon Jacobs Merge pull request #13 from warlof/ticket5
d412b7e  2015-12-26 Leon Jacobs Excluse Towers themselves from module views
98a8e19  2015-12-26 Leon Jacobs Use a macro for progressbar generation
c0e9ce3  2015-12-26 Leon Jacobs Remove unused variables
22932b4  2015-12-26 Leon Jacobs Refactor Starbase views mostly for performance reasons
0cefaac  2015-12-25 elfaus  fix issue #5 about labels display on neutral and negative standing
```
### 1.0.15
```
bbede7b  2015-12-27 Leon Jacobs (tag: 1.0.15) Version Bump
63f308a  2015-12-27 Leon Jacobs Load starbase modules via Ajax calls
c0f48df  2015-12-27 Leon Jacobs Display page render time
```
### 1.0.16
```
075784c  2015-12-28 Leon Jacobs (tag: 1.0.16) Version Bump
b688c4f  2015-12-28 Leon Jacobs Add planet type icons
54ccdec  2015-12-28 Leon Jacobs Add corporation Pocos view
```
### 1.0.17
```
ec9d5c8  2015-12-29 Leon Jacobs (tag: 1.0.17) Version Bump
aaaac36  2015-12-29 Leon Jacobs Fix eveseat/seat#29
6de7e1e  2015-12-29 Leon Jacobs Add Datatables for tables.
```
### 1.0.18
```
69239bf  2016-01-03 Leon Jacobs (tag: 1.0.18) Version Bump
33470ce  2016-01-03 Leon Jacobs Allow packages to hook into corporation menus
24c9f1d  2016-01-03 Leon Jacobs Only attempt to read package menus if they are defined
3b7ecad  2016-01-03 Leon Jacobs Allow packages to hook into character menus
bac4a6e  2015-12-29 Leon Jacobs Add Datatables to starbase summary
```
### 1.0.19
```
f212c78  2016-01-26 Leon Jacobs (tag: 1.0.19) Version Bump
d5376f9  2016-01-26 Leon Jacobs Update Copyright
39c8243  2016-01-26 Leon Jacobs Subclass the bouncers
afb0be5  2016-01-26 Leon Jacobs Add a People Groups feature
17c4f3e  2016-01-11 Leon Jacobs Set queue status update time via configuration
5d30ff0  2016-01-08 Leon Jacobs Fix eveseat/seat#48 by adding data-order attributes
530c268  2016-01-07 Leon Jacobs Add a check for loaded modules and php version
c84baaa  2016-01-07 Leon Jacobs Merge pull request #18 from warlof/ticket38
e4e1fd0  2016-01-07 Leon Jacobs Merge pull request #20 from warlof/ticket43
94e470d  2016-01-05 elfaus  Fix wishlist #38 eveseat/seat#38
21a3bb3  2016-01-06 elfaus  Fix issue eveseat/seat issues#43 - Update calc formula - Adding ceil in order to get round item unit (ccp like)
274409b  2016-01-06 Leon Jacobs Use league/csv to parse CSV's instead of the homebrew
741755d  2016-01-06 Leon Jacobs Remove unnecessary re-fetch of model data
b7ff1a2  2016-01-06 Leon Jacobs Fix eveseat/seat#39 by changing ownership of an existing key.
8fcc13e  2016-01-06 Leon Jacobs Remove footer. Datatables will count the keys
b357826  2016-01-06 Leon Jacobs Code formatting fixes
d5f58de  2016-01-06 Leon Jacobs Merge pull request #19 from Cynabal/master
7a78e2f  2016-01-06 Leon Jacobs Merge pull request #17 from warlof/french
9d2ab0f  2016-01-05 Cynabal Update seat.php
86da25f  2016-01-05 elfaus  New translation according to v1.0.18
```
### 1.0.20
```
e2056a1  2016-01-26 Leon Jacobs (tag: 1.0.20) Version Bump
92986b7  2016-01-26 Leon Jacobs Remove pcntl requirement
ad5f515  2016-01-26 Leon Jacobs Merge pull request #21 from warlof/french
642a832  2016-01-26 elfaus  New french translation according to 1.0.19
```
### 1.0.21
```
70783d8  2016-02-02 Leon Jacobs (tag: 1.0.21) Version Bump
c9188b7  2016-02-02 Leon Jacobs Fix eveseat/seat#60 by using `firstOrNew` instead of create
98b9679  2016-01-27 Leon Jacobs Fix eveseat/seat#51 by always showing the pagination
```
### 1.0.22
```
cc8019a  2016-02-09 Leon Jacobs (tag: 1.0.22) Version Bump
0f02f88  2016-02-09 Leon Jacobs Fix eveseat/seat#59 by adding a unique validation constraint
c69fa2f  2016-02-09 Leon Jacobs Add button to easily re-enable keys
```
### 1.0.23
```
954c178  2016-03-01 Leon Jacobs (tag: 1.0.23) Version Bump
498b868  2016-02-29 Leon Jacobs Fix eveseat/seat#70 by ignoring the current users email in the constraint
8422602  2016-02-29 Leon Jacobs Fix eveseat/seat#57 by adding missing language strings
```
### 1.0.24
```
c20194b  2016-04-14 Leon Jacobs (tag: 1.0.24) Version Bump
eac101f  2016-04-13 Leon Jacobs CS Fixes
f6e3186  2016-04-13 Leon Jacobs Small refactoring and CS fixes
9997914  2016-04-13 dysath  Adding Corporation Wallet Ledger (#23)
```
### 1.0.25
```
168bb3e  2016-04-29 Leon Jacobs (tag: 1.0.25) Version Bump
aee17af  2016-04-29 Leon Jacobs Add ability to force a minimum API access mask.
5101767  2016-04-29 Leon Jacobs Start adding search functionality
b8ac4fb  2016-04-29 Leon Jacobs Remove accountid as it is not useful data
8604036  2016-04-29 Leon Jacobs Fix eveseat/seat#81 by validating for numeric instead of integers
e1cd641  2016-04-29 Leon Jacobs Fix eveseat/seat#78 by adding a link to view one mail only
60727e4  2016-04-29 Leon Jacobs Warn if the default admin contact is still set. Ref eveseat/seat#77
a5d1f8f  2016-04-28 Leon Jacobs Fix eveseat/seat#65 by setting the key_id in the model
9884772  2016-04-26 Loïc LEUILLIOT fix reinforcement time using API stateTimeStamp (#24)
```
### 1.0.26
```
981ccc4  2016-05-14 Leon Jacobs (tag: 1.0.26) Version Bump
0796b2c  2016-05-13 Leon Jacobs Allow SSO to be enabled/disabled via the web interface.
7a605be  2016-05-13 Leon Jacobs Give accounts a temp email address and flag Sso created accounts
6efc9bf  2016-05-13 Leon Jacobs Add first support for the EVE Online SSO
```
### 1.0.27
```
7689032  2016-05-30 Leon Jacobs (tag: 1.0.27) Version Bump
c036c44  2016-05-30 Leon Jacobs Update Provider with new method name.
```
### 1.0.28
```
4e5225e  2016-06-26 Leon Jacobs (tag: 1.0.28) Version Bump
5b2443b  2016-06-26 Leon Jacobs FIx indentation
f9b6ee8  2016-06-26 James Browning Added total values to the Bounty Prizes and PI monthly ledgers. (#25)
21fc0d9  2016-06-26 Leon Jacobs Remove logic that is now in the service repository.
```
### 1.0.29
```
bc76609  2016-07-10 Leon Jacobs (tag: 1.0.29) Version Bump
12a1229  2016-07-10 Leon Jacobs Resolve names of affiliations.
e1c82e3  2016-07-10 Leon Jacobs Paginate character contracts and all killmails
91a5e98  2016-07-10 Leon Jacobs Fix eveseat/seat#111 by paginating the results
3ac3699  2016-07-10 Leon Jacobs Fix eveseat/seat#121 by adding a button to re-enable all keys
a6a8897  2016-07-08 Leon Jacobs Add warning about a autogenerated email from sso
c66c68e  2016-07-08 Leon Jacobs Fix spacing
4aa702d  2016-07-08 Leon Jacobs Small codestyle related fixes
1cca04d  2016-07-08 Loïc LEUILLIOT Provide a way for user to change their email address (#27)
e27d545  2016-06-28 Martin Morling Adjusted setting (#26)
```
### 1.0.30
```
bc1f5ac  2016-07-23 Leon Jacobs (tag: 1.0.30) Version Bump
33b0e03  2016-07-23 Loïc LEUILLIOT Update full api mask (#31)
ec19039  2016-07-23 Leon Jacobs Add link to analytics doc
ccd332d  2016-07-23 Leon Jacobs Add ability to disable tracking completely.
c7372e9  2016-07-22 Loïc LEUILLIOT Add corporation titles to character sheet
b527652  2016-07-22 Loïc LEUILLIOT Add contact tracking links into character and corporation contact list (#30)
```
### 1.0.31
```
9fdea41  2016-10-14 Leon Jacobs (tag: 1.0.31) Version Bump
8d1f8fd  2016-10-14 Leon Jacobs Formatting and style fixes
360e76c  2016-10-14 Loïc LEUILLIOT add SDE version into both footer and settings page (#39)
1db0265  2016-10-13 Leon Jacobs Add alliance name filter to character list
770044c  2016-10-13 Loïc LEUILLIOT Fix permission issues (#38)
7c935df  2016-10-13 Loïc LEUILLIOT add alliance icon and name into character list. fixes eveseat/seat#134
2ad376f  2016-09-06 David Wright Rename EveonlineProvider.php to EveOnlineProvider.php (#36)
edb6543  2016-08-25 Leon Jacobs Fix formatting
584c9e6  2016-08-25 Loïc LEUILLIOT Add collateral amount into contract list (#33)
433f10a  2016-08-25 Leon Jacobs Fix formatting and restore min_access_mask language string
60b7cd6  2016-08-25 Loïc LEUILLIOT Create a new minimum required mask dedicated for corporation (#34)
22c4209  2016-08-25 Loïc LEUILLIOT Add paid-until in Key Details view (depends on PR paid-until branch from eveseat/eveapi) (#32)
```
### 2.0.0-alpha1
```
dd76e24  2016-11-26 Leon Jacobs (tag: 2.0.0-alpha1) Update composer for 2.0 packages and version 2.0.0-alpha1
a408ddf  2016-11-25 Leon Jacobs Add a character wallet spend graph.
ff13f32  2016-11-25 Leon Jacobs Introduce ChartJS and add more dashboard elements.
21067c6  2016-11-22 Leon Jacobs Allow packages to set a permission required for a menu item.
b82aa7d  2016-11-21 Leon Jacobs Use select2 for character selection
db20434  2016-11-21 Leon Jacobs Set main character ID & name on SSO login
7c4868f  2016-11-21 Leon Jacobs Allow for sub menus to be pluralized
685b96d  2016-11-20 Leon Jacobs Add localization for email verification.
5ea1f72  2016-11-20 Leon Jacobs Remove unessesary file
85ad7de  2016-11-20 Leon Jacobs Add email verification to account creation.
6cc2854  2016-11-20 Leon Jacobs Update EVE API status to match new style.
32641e0  2016-11-20 Leon Jacobs Move supervisor status to a panel.
99ae5b6  2016-11-20 Leon Jacobs Prepare status response from a collection instead of a raw array.
241c9a9  2016-11-20 Leon Jacobs Use process group name from config file.
70bb0ff  2016-11-20 Leon Jacobs Bind 'supervisor' as a singleton into the IoC to remove code clutter.
5b88e1b  2016-11-20 Leon Jacobs Move supervisor config ot its own file.
c40bf89  2016-11-20 Leon Jacobs Move available languages to its own config
d3879ac  2016-11-19 Loïc LEUILLIOT Improve queue dashboard by adding supervisor information (#43)
f09384a  2016-11-19 Leon Jacobs Add ability to edit existing notes.
4c30a48  2016-11-19 Leon Jacobs Remove character specific notes model and use services model note trait.
56f316c  2016-11-18 Leon Jacobs First iteration adding notes to the intel section
cf30e2f  2016-11-17 Leon Jacobs Remove intel journal detail
f1f4a17  2016-11-17 Leon Jacobs Allow standings profiles to be built by importing char/corp contacts 👍
0f6c11c  2016-11-17 Leon Jacobs Inject the affected id from the request.
40f2b65  2016-11-17 Leon Jacobs Allow for a standings profile to be deleted.
aed53aa  2016-11-16 Leon Jacobs Move People Groups to the Tools section
a50a741  2016-11-16 Leon Jacobs Remove ajax responses and return json for datatables.
5d55b47  2016-11-16 Leon Jacobs Move the last summaries to datatables
e8813d7  2016-11-16 Leon Jacobs Convert top transactions to datatables view
9b6f2b8  2016-11-16 Leon Jacobs Fix alliance name images
6bb770f  2016-11-15 Leon Jacobs Load mail interactions using datatables.
8712398  2016-11-13 Leon Jacobs Fix typo from `read` to `ready`.
441a612  2016-11-13 Leon Jacobs Sort the character list correctly
debd68e  2016-11-13 Leon Jacobs Do not include the old filter config file
6146dca  2016-11-13 Leon Jacobs Remove state config file of the old `Filterable` trait
5445360  2016-11-13 Leon Jacobs Convert character tables to datatables.
abb48be  2016-11-13 Leon Jacobs Fix Mail menu entry name
94a6c32  2016-11-13 Leon Jacobs Correctly sort by default
f485c03  2016-11-13 Leon Jacobs Include external providers in a seperate method.
fdfd922  2016-11-13 Leon Jacobs Fix indenting
4bae275  2016-11-13 Loïc LEUILLIOT Hide registration link if registration is disabled (#46)
7a0cfcb  2016-11-12 Leon Jacobs Fix searching on corporation killboard
4c04af9  2016-11-11 Leon Jacobs Indenting fixes
a5125e3  2016-11-11 Loïc LEUILLIOT Add two low fuel warning on starbase list (#45)
de8b88c  2016-11-11 Leon Jacobs Convert Corporation tables to data tables.
34c6bc9  2016-11-11 Leon Jacobs Sort Datatables columns by default on fist column
d13c96f  2016-11-11 Leon Jacobs Allow for name resolution to be called by function
f9b0962  2016-11-11 Leon Jacobs Covert Corporation View to use Datatables
e7bd080  2016-11-11 Leon Jacobs Make datatables responsive by default
09714e0  2016-11-11 Leon Jacobs Use the new data tables helper to make search & sorting work
a5e8cbe  2016-11-11 Leon Jacobs Add a JS version of the `human_readable` helper
51340f8  2016-11-11 Leon Jacobs Add javascript using `push` & format fixes
bcc35e0  2016-11-11 Loïc LEUILLIOT Redesign queue dashboard to use a dynamic table (#41)
142bb8a  2016-11-11 Leon Jacobs Add scripts using a `stack` instead of `section`.
a99aeb6  2016-11-10 Leon Jacobs Add yajra/laravel-datatables and convert api key list to datatables
e7d8e07  2016-11-09 Leon Jacobs Start the intel journal detail view.
6dd6312  2016-11-08 Leon Jacobs First rough commit of character intel module! 👾
d7aa864  2016-11-07 Leon Jacobs Formatting fixes
3369f0b  2016-11-06 Leon Jacobs Add ability to mark label as a plural
6dcb3de  2016-11-06 Loïc LEUILLIOT refactoring a bit menu composer in order to define a menu composer type and use config file instead hard coded entry (#44)
ea656b5  2016-11-05 Leon Jacobs Code formatting fixes.
869e26c  2016-11-05 Leon Jacobs Explode the Corporation\ViewController into seperate controllers
e19b350  2016-11-05 Leon Jacobs Paginate market orders
0933c79  2016-11-05 Leon Jacobs Explode Character\ViewController into better managed controllers
b5e6f9f  2016-11-05 Leon Jacobs Extend new core controllers instead of base in App namespace
1890f8a  2016-11-04 Leon Jacobs Redirect to the newly created role
e38c7ba  2016-11-04 Leon Jacobs Add ability to wildcard corporation and character access
5d8ccca  2016-11-04 Leon Jacobs Simply validation using form array validation.
231ea86  2016-11-04 Leon Jacobs Remove `insteadof` as repository refactor removed the need for this
ce1bd67  2016-11-04 Leon Jacobs Change Action to route home
f6fb5f9  2016-11-04 Leon Jacobs Fix translation strings
27bd2c2  2016-11-04 Leon Jacobs Implement Inverse access checking
48160d5  2016-11-03 Leon Jacobs Rename Pillow to AccessManager and add typing
7042418  2016-11-03 Leon Jacobs Fix translation key
896592c  2016-11-03 Leon Jacobs Add support for storing inverse permissions
86ade0b  2016-11-01 Leon Jacobs Add the AuthorizationController and fix the KeyBouncer
d8a412f  2016-10-31 Leon Jacobs Update bouncers to return a redirect instead of view
2d73c70  2016-10-29 Leon Jacobs Update to match new class names in eveapi repo
249c5af  2016-10-28 Leon Jacobs Fix language string
038ba4d  2016-10-25 Leon Jacobs Update to make use of new Corp repository classes
fb129f9  2016-10-25 Leon Jacobs Update to make use of new Character repository classes
799fdee  2016-10-24 Leon Jacobs Update distrib JS/CSS
74752d2  2016-10-23 Leon Jacobs Upgrade to AdminLTE 2.3.7
735279c  2016-10-23 Leon Jacobs Remove usages of `collect()`. All queries return a collection by default
ee461fb  2016-10-23 Leon Jacobs Upgrade `pragmarx/google2fa` & `league/csv` dependencies
e414ecb  2016-10-23 Leon Jacobs Updpate Form Request validation to extend new base class
fe0606d  2016-10-22 Leon Jacobs Show icon of actual ship instead of a generic one
e4821ca  2016-10-18 Loïc LEUILLIOT fix paid-until issue in detail api key view due to possible missing status (#40)
2bef52c  2016-10-17 Leon Jacobs Move logout to a POST method as the new Laravel default
abea1b1  2016-10-17 Leon Jacobs Rename `lists()` to `pluck()`
c215f78  2016-10-15 Leon Jacobs Update Authentication Scaffolding for Laravel 5.3
97fdc4d  2016-10-15 Leon Jacobs Add Notifiable trait introduced in L5.3
6366ccc  2016-10-15 Leon Jacobs Update Events to use new Class based events for L5.3
c45ac15  2016-10-15 Leon Jacobs Update composer to require PHP7 and Laravel 5.3
```
### 2.0.0-alpha2
```
680e4a3  2016-11-26 Leon Jacobs (tag: 2.0.0-alpha2) Drop minimum stability, add prefer-stable and bump to 2.0.0-alpha2.
```
### 2.0.0
```
e648d7e  2016-12-08 Leon Jacobs (tag: 2.0.0) Version Bump! 2.0.0! ⚡️
690f1be  2016-12-08 Leon Jacobs Format and style fixes.
f7ad9a6  2016-12-08 Loïc LEUILLIOT add disable key function (#50)
48069d6  2016-11-30 Leon Jacobs Add a check for cases where api keys may have `null` constraints.
82f1bbb  2016-11-30 Leon Jacobs Move the Validation namespace to Seat\Web\Http\Validation.
55436eb  2016-11-30 Leon Jacobs Allow constraints to be set on specific API keys.
1ab8153  2016-11-29 Leon Jacobs Add message that all workers will run without a constraint set.
d2faf43  2016-11-29 Leon Jacobs First iteration of adding worker constraints.
893f9a9  2016-11-29 Leon Jacobs Formatting and style fixes.
946578d  2016-11-29 Leon Jacobs Change method visibility to private.
f65286c  2016-11-29 Leon Jacobs Small refactoring and code cleanup for the SSO upgrade option.
8583a5c  2016-11-29 Loïc LEUILLIOT fix multiple user creation when user is already owning an account and authenticate with SSO (#49)
c2d4cc7  2016-11-28 Leon Jacobs Correctly sort first search results.
0da3bf0  2016-11-28 Leon Jacobs Add character skills and assets search.
fa2a4fd  2016-11-28 Leon Jacobs Remove return type as there is more than one
8892a83  2016-11-28 Leon Jacobs Show security logs using datatables.
bc2b8f2  2016-11-28 Leon Jacobs Convert Search results to use Datatables.
e259c38  2016-11-27 Leon Jacobs Add skills graphs to character skills view.
26bbed0  2016-11-27 Leon Jacobs Move character skills graphing routes the the CharacterController.
29f8614  2016-11-27 Loïc LEUILLIOT add skills related chart (#48)
```
### 2.0.1
```
00536d7  2016-12-10 Leon Jacobs (tag: 2.0.1) Version Bump
41cc905  2016-12-10 Leon Jacobs Remove trailing brace
b8ed06b  2016-12-10 Leon Jacobs Only display graphs when there is data.
14c547e  2016-12-10 Leon Jacobs Small layout refactor and removal of self account deletion.
d07639f  2016-12-10 Leon Jacobs Log impersonation events.
158b141  2016-12-10 Leon Jacobs Improve impersonation by adding an easy revert option.
5f8ea64  2016-12-10 Leon Jacobs Allow sorting by key status and show disabled reason in details.
986541c  2016-12-10 Leon Jacobs Fix global worker constraints view.
536880c  2016-12-10 Leon Jacobs Update datatables version constraint as newer versions are broken.
edb4f27  2016-12-09 Leon Jacobs Fix eveseat/seat#152 by instantiating with `moment.utc`.
```
### 2.0.2
```
e7590c3  2016-12-10 Leon Jacobs (tag: 2.0.2) Version Bump
7d00d54  2016-12-10 Leon Jacobs Limit keys returned based on permissions
```
### 2.0.3
```
e960118  2016-12-11 Leon Jacobs (tag: 2.0.3) Version Bump
d30202a  2016-12-11 Leon Jacobs Update view to check new key status field
3f826f8  2016-12-11 Leon Jacobs Add option to disable email activation requirement.
a388a5d  2016-12-11 Leon Jacobs Use `setting()` helper instead of static Class method
55cfca3  2016-12-11 Loïc LEUILLIOT fixing possible issue with Supervisor Monitor setting (#51)
```
### 2.0.4
```
3d2f6b3  2016-12-12 Leon Jacobs (tag: 2.0.4) Version Bump
00c3bf2  2016-12-12 Leon Jacobs Grant first time SSO login opportinity to set an email.
aa62453  2016-12-12 Leon Jacobs Return a response instead of a just a view.
```
### 2.0.5
```
ed9901b  2016-12-13 Leon Jacobs (tag: 2.0.5) Version Bump
617670b  2016-12-13 Leon Jacobs Finally, add the favico.
a9f3aa4  2016-12-13 Leon Jacobs Help prevent users from accidently disabling themselves.
786a4ed  2016-12-13 Leon Jacobs Fix eveseat/seat#158 by checking if Email Activation is required.
```
### 2.0.6
```
a00f236  2016-12-15 Leon Jacobs (tag: 2.0.6) Version Bump
4637e88  2016-12-15 Leon Jacobs Style fixes
829b93b  2016-12-15 Loïc LEUILLIOT fix issue related to permission when an object owner get all permission, including system permission. (#54)
e31f19e  2016-12-15 Leon Jacobs Apply threaded view to mail timeline
9532c87  2016-12-15 Leon Jacobs Code style and formatting fixes.
8b640ba  2016-12-15 Loïc LEUILLIOT Key list search (#56)
df176ba  2016-12-14 Leon Jacobs Add a threaded view to the mail read view.
06fe0ac  2016-12-14 Loïc LEUILLIOT fixing issue introduce on #52 (#55)
799a7b9  2016-12-14 Loïc LEUILLIOT add the ability to search on keyID field from ApiKey (#52)
```
### 2.0.7
```
63adffb  2016-12-16 Leon Jacobs (tag: 2.0.7) Version Bump
d4c6988  2016-12-16 Leon Jacobs Mail characterName clickable.
92bf30b  2016-12-16 Leon Jacobs Make mail view as threads configurable.
915eb64  2016-12-16 Leon Jacobs Ensure require_activation is validated.
40b1263  2016-12-16 Leon Jacobs Allow jobs to be manually killed/removed.
c26f501  2016-12-15 Leon Jacobs Fix typo
99c5c3f  2016-12-15 Leon Jacobs Fix typo
```
### 2.0.8
```
b7ecacd  2016-12-21 Leon Jacobs (tag: 2.0.8) Version Bump
4b7a4af  2016-12-21 Leon Jacobs Give manually submitted update jobs some priority
8740878  2016-12-21 Leon Jacobs Fix bug where new keys wont show in API key list
6d28de8  2016-12-21 Leon Jacobs Fix comment
3ebcf67  2016-12-21 Loïc LEUILLIOT update permission system in order to have a faster discover (#57)
5881ab5  2016-12-21 Leon Jacobs Show if the joblog is disabled.
22cb093  2016-12-21 Leon Jacobs Fix language string
6a01a76  2016-12-21 Leon Jacobs Fix column names
3bca775  2016-12-21 Leon Jacobs Add ability to view joblogs.
02bc02c  2016-12-19 Leon Jacobs Add bz2 as an extention requirement
```
### 2.0.9
```
ba7118d  2016-12-28 Leon Jacobs (tag: 2.0.9) Version Bump
507caf2  2016-12-28 Leon Jacobs Show corporation assets contents
6929851  2016-12-28 Leon Jacobs Update message about job that git pushed to the queue
ec1b412  2016-12-28 Leon Jacobs Hide update button if key is not enabled
d08077f  2016-12-28 Leon Jacobs Check that key info exists before attempting to set it
4ea98ac  2016-12-27 Leon Jacobs Dont consider affiliations for menu item check
e3740e9  2016-12-27 Leon Jacobs Add filter to clean out null menu entries.
30f5826  2016-12-26 Leon Jacobs Update sidebar menu loader to sort menu items alphabetically.
5d1d860  2016-12-26 Leon Jacobs Add corporation contracts view
11e3cb0  2016-12-26 Leon Jacobs Add contract items view for characters
fa511ba  2016-12-26 Leon Jacobs Code style tweaks and color tweaks for asset contents view.
eb4c37b  2016-12-26 freedenizen Web portion of character nested asset view (#58)
```
### 2.0.10
```
46d14d9  2017-01-01 Leon Jacobs (tag: 2.0.10) Version Bump
32be7a5  2017-01-01 Leon Jacobs Rename configuration to settings.
```
### 2.0.11
```
0b890f6  2017-01-12 Leon Jacobs (tag: 2.0.11) Version Bump
aa88df0  2017-01-12 Leon Jacobs Fix eveseat/seat#173 by adding a unique constriant to emails
183389f  2017-01-12 freedenizen Characterassets update (#60)
a3c4d52  2017-01-06 Leon Jacobs Update ms to s
aab1aae  2017-01-04 Leon Jacobs Improve readability
0e92e5e  2017-01-04 Leon Jacobs Update styleci config
45dd47f  2017-01-04 Leon Jacobs Fix eveseat/seat#171 by using `Laravel\Socialite\Two\InvalidStateException`
cf5c8e0  2017-01-02 Leon Jacobs Apply fixes from StyleCI (#59)
5ad0d85  2017-01-02 Leon Jacobs Add StyleCI configuration & badge
ae5b3b2  2017-01-01 Leon Jacobs Style fixes
```
### 2.0.12
```
052ab31  2017-01-22 Leon Jacobs (tag: 2.0.12) Version Bump
b3c3cf3  2017-01-22 Leon Jacobs Apply fixes from StyleCI (#62)
be689d2  2017-01-22 Leon Jacobs Load assets contents using ajax requests
666d353  2017-01-22 Leon Jacobs Include the original title and sent date when parsed headers arent ok
5692799  2017-01-22 Leon Jacobs Improve 'inverse' tag on permissions and affiliations
ab28861  2017-01-22 Leon Jacobs Fix eveseat/seat#181 by ensuring that permission inverses are checked
c3fa810  2017-01-22 Loïc LEUILLIOT Fix ACL issue on menu display if menu is requiring permission affiliation (#61)
b669fbb  2017-01-20 Leon Jacobs Add codeclimate configuration
```
### 2.0.13
```
6adfb30  2017-02-19 Leon Jacobs (tag: 2.0.13) Version Bump
a179b5e  2017-02-19 BenH    improved lisibility on the skill sheet of a character (#69)
fe3fac6  2017-02-19 Leon Jacobs Show status of job logging
76f4e27  2017-02-19 Leon Jacobs Add space
a95747d  2017-02-19 Loïc LEUILLIOT Use font-awesome package instead raw import in order to get always last provided icons (#68)
d7bd1fd  2017-02-10 Loïc LEUILLIOT Add a third menu level into sidebar (#66)
b1b685c  2017-02-10 BenH    Improved Tools>People Groups layout (#65)
deaec02  2017-02-02 Leon Jacobs Add comments
4f5af78  2017-02-02 BenHUET Allow to add custom content from a child template to <head> (#64)
```
### 2.0.14
```
0f9e10d  2017-04-17 Leon Jacobs (tag: 2.0.14) Version Bump
dd9fddd  2017-04-17 Leon Jacobs Apply fixes from StyleCI (#78)
c90f111  2017-04-17 Leon Jacobs Simplify the character_id and corporation_id lookups.
763684a  2017-04-17 Loïc LEUILLIOT fix acl minor issue related to job dashboard access from header buttons (#77)
6916be3  2017-04-17 Leon Jacobs Remove wildcard checks as this is done with `hasSuperUser`.
36247bf  2017-02-19 moe-alabel Modified cron statements to proper format. Changed from 6 positions to 5 (#70)
```
### 2.0.15
```
c6ee343  2017-07-02 Leon Jacobs (tag: 2.0.15) Version Bump
758cb4c  2017-07-02 Viola   add language Chinese (#79)
c66c132  2017-06-30 Loïc LEUILLIOT the current delete statement is not firing the delete event from eloquent (#81)
```
### 2.0.16
```
66edf32  2017-08-12 Leon Jacobs (tag: 2.0.16) Version bump
fe45072  2017-08-12 Loïc LEUILLIOT add status filters on industry tables for both character and corporation (#82)
68e3c93  2017-08-12 Leon Jacobs Style fixes.
6879b29  2017-08-12 Loïc LEUILLIOT allow SeAT owner to overload theme using two custom css file (#84)
eb367cf  2017-08-12 Loïc LEUILLIOT pugx service is dead, replace all badge by shields.io (#85)
f116ff1  2017-08-12 Leon Jacobs Style fixes.
2391377  2017-08-12 Loïc LEUILLIOT hide enable/disable account status if the instance is not requiring mail activation (#83)
d1b1527  2017-08-12 Loïc LEUILLIOT improve tables usability by adding paginate on both header and footer as well as filter feature (#80)
```
### 2.0.17
```
0450d6c  2017-08-12 Leon Jacobs (tag: 2.0.17) Version bump
ac49aa9  2017-08-12 Loïc LEUILLIOT fix merge issue due to conflicting dom property between indie filter PR and paginate duplication PR (#86)
```
### 2.0.18
```
036bce9  2017-09-17 Leon Jacobs (tag: 2.0.18) Version bump
4ab49a2  2017-09-17 Loïc LEUILLIOT fix hasrole method by calling magic property instead method. (#90)
6183416  2017-09-16 Loïc LEUILLIOT add documentation link to supervisor integration (#89)
```
### 2.0.19
```
7ea9e99  2017-10-25 Leon Jacobs (tag: 2.0.19) Version Bump.
58a04ad  2017-10-25 Leon Jacobs Apply fixes from StyleCI (#94)
1abb402  2017-10-25 Leon Jacobs Fix 'disabled account' behaviour.
9aaa93d  2017-10-25 Leon Jacobs Revert "security hotfix which is providing a control on disabled account (#92)" (#93)
7c72e63  2017-10-25 Loïc LEUILLIOT security hotfix which is providing a control on disabled account (#92)
8a1e143  2017-10-25 Leon Jacobs Formatting fixes.
262cf96  2017-10-25 Loïc LEUILLIOT security hotfix : add missing ACL from people and group feature (#91)
```
### 3.0.0-beta1
```
cfb1fda  2018-04-29 Leon Jacobs (tag: 3.0.0-beta1) Package upgrade, autodiscovery and v3.0.0-beta1 tag.
507485a  2018-04-29 Leon Jacobs Remove legacy accessmask setting
7eb435e  2018-04-29 Leon Jacobs Apply fixes from StyleCI (#140)
2d411a9  2018-04-29 Leon Jacobs Indentation fixes.
53d56c9  2018-04-29 Leon Jacobs Minor JavaScript, spelling and other annotation fixes.
26fad1b  2018-04-29 Loïc LEUILLIOT state field has been dropped from endpoint (#139)
05070a2  2018-04-29 Leon Jacobs Formatting and style fixes.
6c5afaf  2018-04-29 Loïc LEUILLIOT integration eveseat-mining-ledger (#137)
a6bc5b0  2018-04-29 Leon Jacobs Fix corp wallet journal tooltips and job counter ajax.
7584cdb  2018-04-29 Leon Jacobs Fix type_id reference for nested assets content images.
b5bdd3b  2018-04-29 Leon Jacobs Resolve asset hangar division names.
aa9b15f  2018-04-28 Leon Jacobs Update Corporation assets view.
a832b61  2018-04-28 Leon Jacobs Fix dashboard to once again show server status.
ee64a59  2018-04-28 Leon Jacobs Provide visual aids for accounts with invalid tokens.
5db105d  2018-04-28 Leon Jacobs Fix tooltips for killmails.
b872439  2018-04-28 Leon Jacobs Fix tooltips.
5db2b9d  2018-04-28 Leon Jacobs Add link to EVEO third party apps list.
800a376  2018-04-28 Leon Jacobs Prevent accidental removal of roles from yourself.
8ce2ffb  2018-04-28 Loïc LEUILLIOT pruning chat channel system according to CCP state (#138)
a645387  2018-04-28 Loïc LEUILLIOT upgrade corporation contact in order to implement labels (#136)
26cf741  2018-04-25 Loïc LEUILLIOT only grant access to a corporation with wildcard permission if corporation match ! (#135)
9c8da61  2018-04-24 Leon Jacobs Mark new accounts as active by default.
175954d  2018-04-24 Leon Jacobs Only process corporation roles if they exist.
8201497  2018-04-22 Leon Jacobs Grant the `corporation.summary` role with all ingame roles.
ef07072  2018-04-22 Leon Jacobs Grant SeAT roles based on in-game roles.
84bdd59  2018-04-22 Leon Jacobs Improve validation.
9062385  2018-04-22 Leon Jacobs Restore ability to toggle account status.
5e621f2  2018-04-22 Leon Jacobs Fix online players graph.
8bdc529  2018-04-22 Leon Jacobs Fix impersonation session data handling.
6623b0a  2018-04-22 Leon Jacobs Apply vendor published overrides for proxies.
cf506c1  2018-04-18 Leon Jacobs Update standings builder with Laravel 5.5 validation rule changes.
fb09828  2018-04-18 Loïc LEUILLIOT update setting validation and drop xAPI related fields (#133)
a3c40de  2018-04-18 Loïc LEUILLIOT update intel layouts for ESI (#132)
fd3a3e2  2018-04-17 Leon Jacobs Apply fixes from StyleCI (#130)
5e22915  2018-04-17 Leon Jacobs Fix profile controller view in case no scopes are available.
7a3b0cb  2018-04-17 Loïc LEUILLIOT fix burger menu issue related to adminLTE upgrade (#129)
664b441  2018-04-17 Loïc LEUILLIOT upgrade standing builder to ESI (#124)
3434323  2018-04-17 Loïc LEUILLIOT improve vanilla ACL in order to allow corporation affiliation on char (#122)
0d08acc  2018-04-16 Loïc LEUILLIOT allow route bridging between linked characters (#123)
00374a6  2018-04-15 Leon Jacobs Remove the user quick add feature.
e29f8f0  2018-04-15 Leon Jacobs Refactor Register event to instead dispatch update on every login.
9cf7d84  2018-04-15 Herpaderp Aldent  Pull data for newly created users (#128)
7abbe2b  2018-04-15 Herpaderp Aldent Align assets representation to ingame experience (#127)
a8938a9  2018-04-15 Loïc LEUILLIOT fix employment history sort (#126)
0bd0eeb  2018-04-15 Loïc LEUILLIOT Issue254 (#125)
6a16212  2018-04-08 Loïc LEUILLIOT fix a typo issue which avoid summary to load on character views (#121)
b314d17  2018-04-08 Loïc LEUILLIOT cascading email update over all linked account (#120)
5960947  2018-04-08 Loïc LEUILLIOT Prune worker constraint and update adminLTE (#119)
8c49d03  2018-04-02 Leon Jacobs Remove people groups. This will be replaced later.
df48765  2018-04-01 Leon Jacobs Use current user context when getting other users in the group.
a607545  2018-04-01 Loïc LEUILLIOT don't use lazy load which is not loading images (#118)
634c831  2018-03-31 Leon Jacobs Fix up Corporation security views with new ESI models.
2893e42  2018-03-31 Leon Jacobs Mograte market view to ESI model data.
e44aae3  2018-03-31 Leon Jacobs Update corporation contacts with ESI data.
d113819  2018-03-31 Leon Jacobs Update validation to pass for a space character since TrimStrings.
36cd185  2018-03-31 Leon Jacobs Add associatedCharacterIds helper.
5c391c3  2018-03-31 Leon Jacobs Update mail timeline with new ESI fields.
1156e79  2018-03-31 Leon Jacobs Remove email warning.
4e1d77c  2018-03-31 Leon Jacobs Fix up Access Control CRUD to match 3.x models.
420ed20  2018-03-31 Leon Jacobs Fix up div allignment for inverse checkbox.
6866c58  2018-03-31 Leon Jacobs Allow inverse to not be required.
df72a5a  2018-03-18 Leon Jacobs Add link to third party app management page.
ba4cda7  2018-03-18 Leon Jacobs Add ability for a user to see granted scopes.
fb82eae  2018-03-18 Leon Jacobs Remove unused settings.
0fc3554  2018-03-18 Leon Jacobs Make Sso scopes configurable to admins.
9a27d76  2018-03-18 Loïc LEUILLIOT Corporation 3.x (#117)
802adf0  2018-03-02 Loïc LEUILLIOT Corporation 3.x (#115)
ed5608e  2018-02-18 Leon Jacobs Remove supervisor dependency as we are now using Horizon.
bb7e416  2018-02-18 Loïc LEUILLIOT upgrade character contracts to ESI models (#114)
96621b3  2018-02-17 Leon Jacobs Fix typo.
7f4223f  2018-02-17 Leon Jacobs Resolve names for wallet journals and transactions.
7898a95  2018-02-17 Leon Jacobs Prevent random crap in the UI from changing to #System.
1f40593  2018-02-17 Leon Jacobs Update access checker to get characters from character_groups.
34fd4dc  2018-02-17 Leon Jacobs Flatten array of ids to resolve.
4bc5670  2018-02-17 Leon Jacobs Remove the count() and process ids that remain.
538b99d  2018-02-17 Leon Jacobs Refactor and modernize the name resolution helper.
78cd00c  2018-02-17 Leon Jacobs Fix character list view and minor refactorings.
f7c5998  2018-02-17 Leon Jacobs Fix group -> user relationship.
52f980a  2018-02-17 Loïc LEUILLIOT Migrate Character view to match new ESI models. (#113)
0094101  2018-02-04 Leon Jacobs Formatting and security fixes.
cda9b54  2018-02-04 Loïc LEUILLIOT Provide a nice character switcher for user (#97)
0f6a54d  2018-02-03 Leon Jacobs Simplify group syncing when linking characters.
5e7f3fd  2018-02-03 Leon Jacobs Add a property alias for character_id on a User.
b20f1d8  2018-02-03 Leon Jacobs Handle character logins that have a changed character_owner_hash.
1173954  2018-02-03 Leon Jacobs Remove MFA requirement from SeAT. SSO provides this for EVE.
4d9d008  2018-02-03 Leon Jacobs Add ability to see and link new characters.
5487630  2018-02-03 Leon Jacobs Fix profile view and remove password reset feature.
d7549fe  2018-02-03 Leon Jacobs Fix group inheritence for existing sessions.
6e89bc2  2018-02-03 Leon Jacobs Do *not* make id fillable.
26b78fe  2018-02-03 Leon Jacobs [wip] SSO login flow updates for character linking.
0d88bc0  2018-01-23 Leon Jacobs Include recent error count in queue summaries.
4576bbd  2018-01-14 Leon Jacobs Replace queue dashboard with Horizon.
2c75661  2018-01-14 Leon Jacobs Remove references and logic to XML API keys.
174f70f  2017-12-28 Leon Jacobs Record access tokens and expiry on SSO login.
1519a4a  2017-12-23 Leon Jacobs [WIP] Update SSO login to populate refresh tokens and scopes.
ca565d5  2017-12-21 Leon Jacobs [WIP] Minor login page tweaks for SSO button.
d47aa0b  2017-12-21 Leon Jacobs [WIP] Migrate web package to be SSO logins only.
23231a0  2017-09-18 Leon Jacobs Update middleware registers for Laravel 5.5.
b460d6c  2017-09-17 Leon Jacobs Backport path from eveseat/web#90
```
### 3.0.0-beta2
```
5dc4a28  2018-04-29 Leon Jacobs (tag: 3.0.0-beta2) v3.0.0-beta2
```
### 3.0.0-beta3
```
4087e7e  2018-04-29 Leon Jacobs (tag: 3.0.0-beta3) 3.0.0-beta3
4ba46d2  2018-04-29 Leon Jacobs Add missing SecLog import.
```
### 3.0.0-beta4
```
9527b02  2018-05-02 Leon Jacobs (tag: 3.0.0-beta4) v3.0.0-beta4
7f2bb25  2018-05-02 Loïc LEUILLIOT fix character route including initial route parameters (#142)
efdb989  2018-05-02 Leon Jacobs Formatting fixes.
9972fd0  2018-05-02 Herpaderp Aldent Extend PI View with Extractors (#141)
8a2767d  2018-05-01 Leon Jacobs Fix tax rate and membercount display.
653e05d  2018-05-01 Leon Jacobs Update corporation information on login too.
cad5173  2018-05-01 Leon Jacobs Remove API and Import routes.
c4681fb  2018-04-29 Leon Jacobs Make section linking to third party app access more visible.
```
### 3.0.0-beta5
```
270bcf3  2018-05-07 Loïc LEUILLIOT (tag: 3.0.0-beta5) Loadbalancing help (#149)
94f43d7  2018-05-07 Leon Jacobs v3.0.0-beta5
57e65d3  2018-05-07 Leon Jacobs Minor styling fixes.
d0fe1f1  2018-05-07 Loïc LEUILLIOT Aclchecker fix (#148)
f7b3e33  2018-05-07 Leon Jacobs Removei temporary trusted proxy override.
7302a19  2018-05-07 Leon Jacobs Fix wallet filtering.
2cec3e4  2018-05-07 Leon Jacobs Fix character_id reference.
8dc06cc  2018-05-07 Loïc LEUILLIOT Corp taxes (#146)
26e61f6  2018-05-06 Leon Jacobs Apply fixes from StyleCI (#145)
9570831  2018-05-06 Leon Jacobs Update ACL manager to be groups aware.
73df305  2018-05-06 Leon Jacobs Update fillable array for groups.
8d7cfa6  2018-05-06 Leon Jacobs Remove unused imports.
52bd000  2018-05-06 Leon Jacobs Refactor User <-> Group relationships.
c1c86fa  2018-05-06 Leon Jacobs Check that a user is logged in first.
e18a487  2018-05-06 Leon Jacobs Warn if SSO has not been configured yet.
5791051  2018-05-06 Leon Jacobs Remove unused registration logic.
cc39700  2018-05-05 Leon Jacobs Improve user cleanup on delete.
7b44abf  2018-05-03 Loïc LEUILLIOT address eveseat/seat#277 (#144)
```
### 3.0.0-beta6
```
1948ff1  2018-05-07 Leon Jacobs (tag: 3.0.0-beta6) v3.0.0-beta6
```
### 3.0.0-beta7
```
a1ac94d  2018-05-08 Leon Jacobs (tag: 3.0.0-beta7) v3.0.0-beta7
28b0bab  2018-05-08 Loïc LEUILLIOT fix summary group display and rollback to repository instead model (#152)
523632c  2018-05-08 Loïc LEUILLIOT fix route and user/group relationships on user layouts (#151)
c67e679  2018-05-08 Loïc LEUILLIOT Fix layouts (#150)
```
### 3.0.0-beta8
```
4e1f48b  2018-05-10 Leon Jacobs (tag: 3.0.0-beta8) v3.0.0-beta8
d3ebc52  2018-05-10 Loïc LEUILLIOT more fix on user layout related to group relationship (#157)
70310b2  2018-05-10 Loïc LEUILLIOT fix skill queue refresh according to finished date instead of queue position (#156)
a1d3e2f  2018-05-10 Loïc LEUILLIOT fix group attached tokens (#154)
333c195  2018-05-10 Loïc LEUILLIOT do not display skills charts for admin user (#153)
```
### 3.0.0-beta9
```
d84d83b  2018-05-11 Leon Jacobs (tag: 3.0.0-beta9) v3.0.0-beta9
996a83e  2018-05-11 Loïc LEUILLIOT Fix corpacl issue (#158)
d1abdc5  2018-05-11 Loïc LEUILLIOT fix doc link to the new amazing documentation ♥ (#155)
```
### 3.0.0-beta10
```
45e77ce  2018-05-16 Leon Jacobs (tag: 3.0.0-beta10) v3.0.0-beta10
f7b88fe  2018-05-16 Leon Jacobs [WIP] Allow jobs to be manually and contextually dispatched.
bb05dd6  2018-05-15 Leon Jacobs Dispatch update jobs with high priority on login.
491cdcb  2018-05-15 Leon Jacobs Add ability to configure worker count with the web UI.
cdc5b71  2018-05-15 Ben     Fix for offline POS (#161)
9189b1a  2018-05-15 Leon Jacobs Remove some defunct services.
8a34135  2018-05-15 Leon Jacobs Fix starbase views when tower has no fuel.
08b7251  2018-05-15 Leon Jacobs Handle message bodies that may not yet have downloaded.
20d2893  2018-05-15 Leon Jacobs Fix stortium checks if no strontium is present.
0dfe14d  2018-05-15 Leon Jacobs Fix type lookups in case its unknown from the SDE.
402f007  2018-05-15 Argon Inkura fix: Roleconfiguration template tried to access removed property (#159)
118b44c  2018-05-14 Leon Jacobs Fix indentation.
b3ced55  2018-05-14 Loïc LEUILLIOT filtering displayed skills and wallet information according to permission on character sheet layout (#160)
```
### 3.0.0-beta11
```
5be4077  2018-05-16 Leon Jacobs (tag: 3.0.0-beta11) v3.0.0-beta11
f55e850  2018-05-16 Leon Jacobs Handle a case where worker counts cant be set without the DB.
```
### 3.0.0-beta12
```
fb93023  2018-05-18 Leon Jacobs (tag: 3.0.0-beta12) v3.0.0-beta12
6e4887b  2018-05-17 Jake Z  Update links for eveboard to eveskillboard (#165)
cdfbccf  2018-05-17 Ben     Update log.blade.php (#164)
4cbd395  2018-05-17 Argon Inkura fix: The characters ship will now get displayed properly. (#163)
f68bb58  2018-05-17 Argon Inkura eveseat/seat#310: Fixes broken login via admin link (#162)
```
### 3.0.0-beta13
```
b97ddbf  2018-05-19 Leon Jacobs (tag: 3.0.0-beta13) v3.0.0-beta13
3d7f305  2018-05-19 Leon Jacobs Make user listing table responsive.
015fcc6  2018-05-18 Leon Jacobs Reshuffle the dashboard widgets.
910e4d9  2018-05-18 Leon Jacobs Link the email attribute to the User model.
106cd46  2018-05-18 Leon Jacobs Replace character switcher with modal to handle large groups.
f0899dc  2018-05-18 Leon Jacobs Apply fixes from StyleCI (#167)
880eaa7  2018-05-18 Leon Jacobs Move main char and email to a setting for a group.
07a18b4  2018-05-18 Alex Skobelev updated missing fields in web app manifest (#166)
```
### 3.0.0-beta14
```
b925e7f  2018-05-20 Leon Jacobs (tag: 3.0.0-beta14) v3.0.0-beta14
3c43088  2018-05-20 Loïc LEUILLIOT remove ability to bind admin user to EVE (#170)
abbc9e9  2018-05-20 Loïc LEUILLIOT provide extra helper attribute to Group (#169)
632493b  2018-05-19 Loïc LEUILLIOT fix sorting on user table for refresh token and last login columns (#168)
```
### 3.0.0-beta15
```
ba1abce  2018-05-20 Leon Jacobs (tag: 3.0.0-beta15) v3.0.0-beta15
6c0e93f  2018-05-20 Leon Jacobs Allow for user group reassignment.
843a941  2018-05-20 Leon Jacobs Add character attributes.
6f6d340  2018-05-20 Leon Jacobs Add corporation structures view.
3392e1a  2018-05-20 Leon Jacobs Specify the horizon job timeout.
```
### 3.0.0-beta16
```
cc500cc  2018-05-21 Leon Jacobs (tag: 3.0.0-beta16) v3.0.0-beta16
a76eca1  2018-05-21 Herpaderp Aldent Return MainCharacter of Group (#171)
```
### 3.0.0-beta17
```
5ae4303  2018-05-24 Leon Jacobs (tag: 3.0.0-beta17) v3.0.0-beta17
e371c6d  2018-05-24 Leon Jacobs Fix settings relationship.
```
### 3.0.0-beta18
```
eab5e0d  2018-05-27 Leon Jacobs (tag: 3.0.0-beta18) v3.0.0-beta18
70d8269  2018-05-27 Leon Jacobs Apply fixes from StyleCI (#175)
61e9e4e  2018-05-27 Leon Jacobs Add ability to delete characters & corporations via the Web UI.
2623e24  2018-05-27 Leon Jacobs Update wording.
34c3ab0  2018-05-27 Leon Jacobs Add stale data cleanup setting for maintenance job.
593e74e  2018-05-27 Leon Jacobs Apply fixes from StyleCI (#174)
767cb57  2018-05-27 Leon Jacobs Expose ESI status to the WEB UI.
b45daae  2018-05-26 Loïc LEUILLIOT append counter on tracking footer (#173)
```
### 3.0.0-beta19
```
a06d226  2018-05-28 Leon Jacobs (tag: 3.0.0-beta19) v3.0.0-beta19
795a49a  2018-05-28 Leon Jacobs Handle an empty ESI statys gracefully.
```
### 3.0.0-beta20
```
f6cd5aa  2018-05-30 Leon Jacobs (tag: 3.0.0-beta20) v3.0.0-beta20
4091f3f  2018-05-29 Leon Jacobs Add view to see character fittings.
816dfa9  2018-05-29 Leon Jacobs Cleanup orphan groups when deleting / re-assigning users.
```
### 3.0.0-beta21
```
0957696  2018-06-13 Leon Jacobs (tag: 3.0.0-beta21) v3.0.0-beta21
b4a90be  2018-06-13 Leon Jacobs Remove debug code.
736e9bd  2018-06-13 Leon Jacobs Update user list to show groups.
810cabc  2018-06-09 Leon Jacobs Update token deletes as it now has soft deletes.
85bfd44  2018-06-09 JiaYing Chen Update chinese language file (#180)
25aff8d  2018-06-09 Loïc LEUILLIOT fix column name according to ESI design (#179)
```
### 3.0.0-beta22
```
de1c76f  2018-06-14 Leon Jacobs (tag: 3.0.0-beta22) v3.0.0-beta22
2f95358  2018-06-14 Leon Jacobs Include user count.
2dfe458  2018-06-14 Leon Jacobs Refactor user / group listing, again.
0171c24  2018-06-14 Leon Jacobs Remove unused variable and add refactor warning.
30f722b  2018-06-14 Loïc LEUILLIOT Fix user layout (#181)
```
### 3.0.0
```
13f20a7  2018-06-16 Leon Jacobs (tag: 3.0.0) v3.0.0 🎉
6e1b466  2018-06-16 Leon Jacobs Show email address in user list.
13d8183  2018-06-16 Loïc LEUILLIOT fix skill training human conversion (#183)
27d29a4  2018-06-16 Leon Jacobs Fix character standings view.
11e5ff2  2018-06-16 Leon Jacobs Paginate standings view.
cdbf668  2018-06-16 Leon Jacobs Remove mcrypt dependency for PHP 7.2 support.
736375d  2018-06-16 Leon Jacobs Add more character manual update dispatchers.
23ec965  2018-06-16 Leon Jacobs Remove old supervisor integration config.
7a64386  2018-06-16 Leon Jacobs Rename key to token.
bb5dacc  2018-06-16 Loïc LEUILLIOT fix starbase layout (progress and offline timer) (#182)
```
### 3.0.1
```
713f8e3  2018-06-17 Leon Jacobs (tag: 3.0.1) v3.0.1
ec4f257  2018-06-17 Loïc LEUILLIOT Fix starbase stats (#184)
```
### 3.0.2
```
448d81b  2018-06-24 Leon Jacobs (tag: 3.0.2) v3.0.2
3e7c945  2018-06-24 Loïc LEUILLIOT reinsert button for edit/delete/impersonate function (#186)
0d6132e  2018-06-24 Loïc LEUILLIOT improve id to name resolver in order to support resolving in link (#185)
```
### 3.0.3
```
ce01e3d  2018-06-30 Leon Jacobs (tag: 3.0.3) v3.0.3
0185d53  2018-06-30 Leon Jacobs Temporarily remove the location_id column.
dbdb06b  2018-06-30 Leon Jacobs Include the reason if available in wallet journal.
ac70a1e  2018-06-30 Leon Jacobs Workaround for corporation name resolution bugs.
f639634  2018-06-30 Leon Jacobs Remove empty groups when linking existing characters.
2d997d6  2018-06-30 Herpaderp Aldent Move action buttons to the right (#187)
b602265  2018-06-30 Leon Jacobs Fix number formatting with spaces.
e97f66a  2018-06-30 Herpaderp Aldent Add overview box with total mined isk (#189)
eff0739  2018-06-30 Herpaderp Aldent respect number format from user settings (#191)
2f033cc  2018-06-30 mmolitor87 Update ScheduleController.php (#190)
```
### 3.0.4
```
1aa780a  2018-07-12 Leon Jacobs (tag: 3.0.4) v3.0.4
5b819ed  2018-07-13 Loïc LEUILLIOT [Critical Hotfix] login flow issues (#195)
```
### 3.0.5
```
859c36f  2018-07-29 Leon Jacobs (tag: 3.0.5) v3.0.5
f1c01ba  2018-07-29 Loïc LEUILLIOT fix(corporation structures): Fix table sort on offline column (#198)
33cd56a  2018-07-29 Loïc LEUILLIOT Generate complete documentation for user category (HTTP/200) (#196)
9c8793c  2018-07-29 Loïc LEUILLIOT fix extractor progress-bar in character PI layout (#192)
```
### 3.0.6
```
a9a26d8  2018-08-20 Leon Jacobs (tag: 3.0.6) v3.0.6
6e7f008  2018-08-20 Loïc Leuilliot fix(industry jobs): Fix datatable search (#204)
af93484  2018-08-17 Leon Jacobs Refactor a switch for a simple ternary operator.
f9a8625  2018-08-17 Herpaderp Aldent Add tab for users with `character.list` permission (#207)
1702f5c  2018-08-17 Herpaderp Aldent Add token status linked characters (#205)
6b9c67e  2018-08-17 Loïc Leuilliot fix(industry jobs): Fix location field (#203)
2899e90  2018-08-17 Loïc Leuilliot feat(industry jobs): Add end column to industry jobs table (#202)
82954c2  2018-08-17 Loïc Leuilliot fix(corporation tracking): fix last location column (#201)
8dd5d2a  2018-08-17 Loïc Leuilliot fix(jump clones): Display name of player structure (#200)
399b8c8  2018-08-17 Loïc Leuilliot feat(contacts): Bump corporation and character contact endpoint to v2 (#199)
```
### 3.0.7
```
8f49b5d  2018-09-09 Leon Jacobs (tag: 3.0.7) v3.0.7
3916281  2018-09-09 Loïc Leuilliot fix(corporation): Fix number sort on bounty ledger (#211)
52a7d2d  2018-09-09 Loïc Leuilliot fix(character): Address an issue related to filter on industry page (#210)
```
### 3.0.8
```
66ba408  2018-09-09 Leon Jacobs (tag: 3.0.8) v3.0.8
0a9ef8c  2018-09-09 Herpaderp Aldent fix(characters list): Make all character related to authenticated user visible
```
### 3.0.9
```
44d4ff5  2018-10-04 Leon Jacobs (tag: 3.0.9) v3.0.9
b5b0279  2018-09-21 ASTairov fix(language): Add missing translation constants
5e35fe7  2018-09-17 ASTairov feat(language): Add russian support
91f2cdb  2018-09-16 Alex Skobelev feat(ui): Add ability to load content into right control sidebar
848c442  2018-09-16 Herpaderp Aldent feat(prices): Lock mining values
535575c  2018-09-09 Herpaderp Aldent Fix no_corporation_titles translation (#215)
```
### 3.0.10
```
e396edd  2018-12-08 Loïc LEUILLIOT (tag: 3.0.10) build(core): v3.0.10
4a31104  2018-12-08 Loïc LEUILLIOT fix(corporation): Update corporation killmails according to partials update
3d6dcfe  2018-12-08 Loïc LEUILLIOT fix(corporation): Update corporation journal according to partials update
768540f  2018-12-08 Loïc LEUILLIOT fix(corporation): Update corporation market according to partials updates
c7b1687  2018-12-08 Loïc LEUILLIOT fix(character): Fix attributes null exceptions
0487d5c  2018-12-08 Loïc LEUILLIOT fix(character): Fix a null exception which may occures when the character information wasn't already pulled
60348e8  2018-12-08 Loïc LEUILLIOT fix(transactions): Fix Sold transaction styling
4002c08  2018-12-08 Herpaderp Aldent [feat](mails): Mailtimeline Improvement: only link existing characters and corporations (#243)
7864e9c  2018-12-08 Herpaderp Aldent [feat](market): Update market tab and refactor partials (#240)
4a92912  2018-12-08 Herpaderp Aldent [feat](characters): Make the list sorteable by name and turn into async
0cecc79  2018-12-08 Herpaderp Aldent [feat](transactions): Move to asynchronous loading
7ff4220  2018-12-08 Herpaderp Aldent [feat](mails): Move to asynchronous loading
83e0e99  2018-12-08 Herpaderp Aldent [feat](wallets): Move to asynchronous loading
aea1dce  2018-12-07 Herpaderp Aldent [feat](killmails): Move to asynchronous loading
a1274fa  2018-12-06 Loïc LEUILLIOT style(users): Code format
c47244f  2018-12-06 Herpaderp Aldent [feat](users): Move to asynchronous loading
a42805f  2018-12-06 Loïc LEUILLIOT style(core): Code format
aa1f785  2018-12-06 Herpaderp Aldent [feat](core): Resolve ids universe names (#236)
eba65dd  2018-12-06 Herpaderp Aldent [feat](core): Use new migration mechanic
1f59798  2018-12-06 Loïc LEUILLIOT style(contract): Code format
accd83e  2018-12-06 Herpaderp Aldent [feat](contracts): Move to asynchronous loading
890b7a6  2018-12-06 Loïc Leuilliot feat(core): Provide events when a role is attached or detached from a group (#228)
b84f4b9  2018-12-06 Loïc LEUILLIOT style(assets): Code format
86b8dd9  2018-12-06 Herpaderp Aldent [feat](assets): Move to asynchronous loading
379bd57  2018-12-06 Herpaderp Aldent [feat](contacts): Move to asynchronous loading
1d67235  2018-11-18 Herpaderp Aldent [feat](dependencies): Update DataTables Dependencies for new DataTables Version (#221)
01631c5  2018-11-17 ASTairov [fix](assets): Add missing EVE Logo
945dc95  2018-11-17 Herpaderp Aldent [feat](profile): Provide a link to characters
5bcb533  2018-11-18 Ben Thompson [fix](mining-ledger): fix ErrorException for undefined variable character_id
554fe56  2018-11-03 Loïc Leuilliot (ASTairov/master) fix(settings): Fix GA tracking explanation dead link (#226)
794edd4  2018-10-28 Loïc Leuilliot fix(mining ledger): Fix loading time issue due to prices eager-load (#225)
fb36916  2018-10-28 Loïc LEUILLIOT style(resolver): rename methods from resolveEntityIDsFromSeat to resolverInternalEntityIDs
ba8a4ff  2018-10-28 Herpaderp Aldent feat(resolver): Improve resolver using local database information
4115a79  2018-10-09 Herpaderp Aldent [fix](characters) Avoid the group table from characters list to throw an exception on Admin user
80729f2  2018-10-09 Herpaderp Aldent [feat](api) Add main_character_id to group-list
250db17  2018-10-09 Herpaderp Aldent [feat](corporation) Include main character into Corporation Mining Ledger
3166690  2018-10-06 Herpaderp Aldent [feat](corporation) Include main character into MemberTracking
```
### 3.0.11
```
679d370  2018-12-10 Loïc LEUILLIOT (tag: 3.0.11) build(core): v3.0.11
c841fbf  2018-12-10 Herpaderp Aldent [fix](killmails): Change `is_nan` to `is_null` (#244)
```
### 3.0.12
```
9572e51  2018-12-22 Loïc LEUILLIOT (tag: 3.0.12) build(core): v3.0.12
46bf66b  2018-12-22 Herpaderp Aldent [fix](contract): fix contract details for linked characters (#255)
24214a9  2018-12-22 Loïc Leuilliot fix(users): Reduce user coupling and avoid null exception (#251)
c7cbc12  2018-12-22 Herpaderp Aldent [fix](ACL): inverse character permission on yourself denys access to own data (#253)
3d862ff  2018-12-16 Herpaderp Aldent [fix](users) Delay search to query less (#248)
a6c9e0b  2018-12-16 Herpaderp Aldent [fix](core): Number precision fix (#247)
```
### 3.0.13
```
d0164a6  2018-12-30 Loïc LEUILLIOT (tag: 3.0.13) build(core): v3.0.13
b93fb70  2018-12-30 Herpaderp Aldent Fix corporation contracts and add loading spinner (#263)
```
### 3.0.14
```
adef9f2  2019-01-13 Loïc LEUILLIOT (tag: 3.0.14) build(core): v3.0.14
8613202  2019-01-13 Herpaderp Aldent Issue 453 searchblade improvements (#270)
e54d8c2  2019-01-13 Loïc LEUILLIOT fix(extractions): Add breadcrumb into the layout
b69a99b  2019-01-13 Herpaderp Aldent Add ability to filter users for valid or invalid refresh_tokens. (#271)
f76440a  2019-01-12 Loïc Leuilliot feat(extractions): Design an UI to retrieve pending and active moon-mining extractions (#262)
4cdd48e  2019-01-07 Herpaderp Aldent feat(character): Move intel to asynchronous requests and improve UI
55c004d  2019-01-07 Loïc Leuilliot feat(header): Add a caret near profile user drop-down (#259)
05215fb  2019-01-07 Loïc Leuilliot feat(character): Add the character name into page title
aa70113  2019-01-07 Loïc Leuilliot * feat(versions): Switch package versions display to generic list
39ceb29  2019-01-06 Herpaderp Aldent Refactor view: (#268)
b3617bb  2019-01-06 Herpaderp Aldent Refactor corporation journal to work as in game. (#267)
2010dca  2019-01-06 Loïc LEUILLIOT Merge branch '3.0.x'
87164cf  2019-01-06 Herpaderp Aldent Some refactoring in the service and view to be consistant with character. (#266)
6329a86  2019-01-06 Herpaderp Aldent [fix](resolver): Contract filter method. Used previously the wrong attribute. (#269)
c986a69  2019-01-06 Loïc Leuilliot feat(mining): Reduce numbers precisions (#260)
80c0544  2019-01-06 Herpaderp Aldent Corporation tracking (#250)
e805d03  2019-01-06 Loïc Leuilliot Queue balancing (#246)
```
### 3.0.15
```
84f860b  2019-02-24 Loïc LEUILLIOT (tag: 3.0.15) build(core): v3.0.15
111ebae  2019-02-24 Loïc Leuilliot fix(corporation): Fix Planetary Interaction Ledger (#287)
c4d2065  2019-02-15 Herpaderp Aldent Fix character contracts (#279)
0b6a7b0  2019-02-15 Herpaderp Aldent Used wrong attribute for filterColumn (#277)
d6ba26d  2019-02-15 Herpaderp Aldent Fix issue 512 related to corp tracking (#276)
5ea5da0  2019-02-15 Herpaderp Aldent Fix corp killmails table header missarrangement (#275)
ecfd279  2019-01-20 Loïc Leuilliot fix(contracts): Remove non-existing variable from contract index (#272)
```
### 3.0.16
```
630c3b6  2019-03-23 Loïc LEUILLIOT (tag: 3.0.16) build(core): v3.0.16
04d1664  2019-03-23 Loïc LEUILLIOT style(wallet): Apply styleCI complaints
0693b04  2019-03-23 Loïc LEUILLIOT fix(mining): Add missing quantity when computing total price
4501f26  2019-03-23 Herpaderp Aldent feat(mining): Switch mining ledger to async loading (#289)
aa69768  2019-03-23 Herpaderp Aldent refactor(contracts): Updated contract filters (#278)
22f6826  2019-03-23 Loïc LEUILLIOT fix(sheet): Fix character location null exception
e943e62  2019-03-12 Matthew Yu trans(chinese): Improve translation (#292)
94de5e0  2019-03-09 Herpaderp Aldent feat(tracking): Allow location to be searchable into corporation tracking (#291)
8f47de1  2019-03-09 Herpaderp Aldent feat(sheet): Add Solar System to the character sheet (#290)
78ca6a4  2019-03-09 Loïc LEUILLIOT Merge branch '3.0.x'
fc9034f  2019-02-24 Loïc LEUILLIOT build(core): v3.0.15
1c89e56  2019-02-24 Loïc Leuilliot fix(corporation): Fix Planetary Interaction Ledger (#287)
1b24d45  2019-02-15 Herpaderp Aldent fix(contracts): Fix character filter column (#279)
7b7ae51  2019-02-15 Herpaderp Aldent fix(search): Use proper attribute for filterColumn (#277)
01b668f  2019-02-15 Herpaderp Aldent fix(tracking): Exclude non-members characters (#276)
cc73336  2019-02-15 Herpaderp Aldent fix(killmails): Fix corp killmails table header miss-arrangement (#275)
ee87361  2019-01-20 Loïc Leuilliot fix(contracts): Remove non-existing variable from contract index (#272)
7d3ec2f  2019-02-19 Herpaderp Aldent feat(settings): Add loading spinner to changelog (#274)
6f09605  2019-02-19 Herpaderp Aldent feat(users): Add warning about outdated information (#273)
0a4b687  2019-02-19 Loïc Leuilliot feat(universe): Bump universe resolver to v3 which include factions (#280)
830e97b  2019-02-18 Leon Jacobs style(core): Update licence headers (#285)
4e92fb2  2019-02-15 Loïc Leuilliot 3.0.x (#284)
f036723  2019-02-15 Loïc Leuilliot 3.0.x (#283)
077df2a  2019-01-13 Loïc LEUILLIOT build(core): v3.0.14
8936de2  2019-01-13 Herpaderp Aldent feat(search): Improve search-blades (#270)
1043b4e  2019-01-13 Loïc LEUILLIOT fix(extractions): Add breadcrumb into the layout
1176047  2019-01-13 Herpaderp Aldent feat(users): Add ability to filter users for valid or invalid tokens. (#271)
7c0f855  2019-01-12 Loïc Leuilliot feat(extractions): Design an UI to retrieve pending and active moon-mining extractions (#262)
6ae50e0  2019-01-07 Herpaderp Aldent feat(character): Move intel to asynchronous requests and improve UI
92fd6fe  2019-01-07 Loïc Leuilliot feat(header): Add a caret near profile user drop-down (#259)
381318a  2019-01-07 Loïc Leuilliot feat(character): Add the character name into page title
257d81c  2019-01-07 Loïc Leuilliot feat(versions): Switch package versions display to generic list
14774bf  2019-01-06 Herpaderp Aldent fix(market): Allow table to be searchable (#268)
e18c88d  2019-01-06 Herpaderp Aldent refactor(wallets): Alter corporation blade to work as in game (#267)
534aa91  2019-01-06 Loïc LEUILLIOT Merge branch '3.0.x'
251ce81  2019-01-06 Herpaderp Aldent fix(resolver): Contract filter method used previously the wrong attribute (#269)
07cea51  2019-01-06 Herpaderp Aldent refactor(killmails): Improve consistency between corp. and char. (#266)
f2412ae  2019-01-06 Loïc Leuilliot feat(mining): Reduce numbers precisions (#260)
3246545  2019-01-06 Herpaderp Aldent feat(tracking): Move corporation tracking table rendering to server
d05d0cc  2019-01-06 Loïc Leuilliot feat(jobs): Introduce queue balancing (#246)
d4ca256  2018-12-30 Loïc LEUILLIOT build(core): v3.0.13
16727b8  2018-12-30 Herpaderp Aldent fix(contracts): Fix corporation contracts and add loading spinner (#263)
43ac47d  2018-12-22 Loïc LEUILLIOT build(core): v3.0.12
7a60d33  2018-12-22 Herpaderp Aldent fix(contract): fix contract details for linked characters (#255)
2f92d9f  2018-12-22 Loïc Leuilliot fix(users): Reduce user coupling and avoid null exception (#251)
b5a7638  2018-12-22 Herpaderp Aldent fix(ACL): avoid to loose access on your owned data due to inverse (#253)
ed9c7f2  2018-12-16 Herpaderp Aldent fix(users): Delay search to query less (#248)
```
### 3.0.17
```
e2fed96  2019-03-28 Loïc Leuilliot (tag: 3.0.17) build(core): v3.0.17
9f5c123  2019-03-28 Loïc Leuilliot fix(mining): remove unset variable from main view (#293)
```
### 3.0.18
```
3973009  2019-05-05 Loïc LEUILLIOT (tag: 3.0.18) build(core): v3.0.18
697bf16  2019-05-05 Loïc Leuilliot fix(character): avoid some null exception related to ship and location (#301)
2cee954  2019-05-04 Loïc Leuilliot fix(user): ensure the email address is properly updated (#300)
14262a3  2019-04-01 Loïc Leuilliot fix(ACL): Avoid null exception on Horizon access check (#295)
```
### 3.0.19
```
3be5e4d  2019-05-12 Loïc LEUILLIOT (tag: 3.0.19) build(core): v3.0.19
33a90df  2019-05-11 Loïc Leuilliot fix(standings): address an issue related to character contact pull (#303)
ecd7f1a  2019-05-11 Jabasukuriputo Wang feat(lookup): use fastlookup as search engine for roles and standings builder
```
### 3.0.20
```
1f01a19  2019-05-20 Loïc LEUILLIOT (tag: 3.0.20) build(core): v3.0.20
e21361a  2019-05-19 Loïc Leuilliot fix(config): put environment variables into config file (#304)
```
### 3.0.21
```
ebb8a63  2019-06-10 Loïc LEUILLIOT (tag: 3.0.21) build(core): v3.0.21
c2a567d  2019-06-10 Loïc Leuilliot feat(license): add CCP copyright in dedicated license page (#308)
ba7a945  2019-06-04 Justin Mercer fix(datatables): avoid errors on null values (#305)
9493903  2019-05-28 Jabasukuriputo Wang fix(tracking): ensure name and last location are properly filtered
```
### 3.0.22
```
94950b2  2019-08-03 Loïc LEUILLIOT (tag: 3.0.22) build(core): v3.0.22
a0a6dd4  2019-08-03 Seb Ferraro feat(api): add main_character_id to User (#309)
0500d11  2019-08-03 Loïc Leuilliot fix(extractions): ensure integrity of moon content (#310)
```
### 3.0.23
```
79ad973  2019-08-13 Loïc LEUILLIOT (tag: 3.0.23) build(core): v3.0.23
ca2de88  2019-08-09 Loïc Leuilliot refactor(titles): use relationship instead atomic table (#311)
```
### 3.0.24
```
670c5be  2019-08-25 Loïc LEUILLIOT (tag: 3.0.24) build(core): v3.0.24
a7b50b8  2019-08-24 Loïc Leuilliot fix(auth): ensure requested scopes are properly provided (#312)
```
### 3.0.25
```
900de53  2019-10-04 Loïc LEUILLIOT (tag: 3.0.25) build(core): v3.0.25
b75574c  2019-10-04 Loïc Leuilliot fix(titles): reduce abnormal loop on corp titles page (#314)
```
### 3.0.26
```
c1e6b84  2019-11-11 Loïc LEUILLIOT (tag: 3.0.26) build(core): v3.0.26
95afd33  2019-11-11 Loïc LEUILLIOT ci(styleci): remove length_ordered_imports
2ab125d  2019-11-11 Loïc LEUILLIOT fix(versions): exclude unstable versions from checker
```
### 3.0.27
```
abb320d  2019-11-20 Loïc LEUILLIOT (tag: 3.0.27) build(core): v3.0.27
e6510ec  2019-11-20 Loïc LEUILLIOT fix(acl): remove corp journal and corp transactions from Jun. Accountant
1ff8f99  2019-11-19 Loïc LEUILLIOT fix(orders): address a typo on the corporation market table
8ad8b0c  2019-11-11 Loïc LEUILLIOT ci(styleci): remove rules from preset
```
### 3.0.28
```
0e02fa3  2020-02-07 Loïc LEUILLIOT (tag: 3.0.28) build(core): v3.0.28
e1d95db  2020-02-07 Loïc LEUILLIOT fix(cve): this address an issue on affiliations permissions merge
```
### 4.0.0-rc1
```
de8f37f  2019-10-31 Loïc LEUILLIOT (tag: 4.0.0-rc1) refactor(mails): reduce duplicated entries on mails module
8595fd9  2019-10-30 Loïc LEUILLIOT style(styleci): apply requested changes
f1ab313  2019-10-30 Loïc LEUILLIOT fix(layouts): apply BS4 to intel summary
b6f5a43  2019-10-30 Loïc LEUILLIOT feat(acl): queue_manager is now required to see queue status
014af25  2019-10-29 Loïc LEUILLIOT fix(layouts): apply BS4 to intel standings compare
aa58b6a  2019-10-29 Loïc LEUILLIOT fix(layouts): apply BS4 to intel menu
85539a9  2019-10-29 Loïc LEUILLIOT feat: ensure number are properly rendered with separator
3c8f852  2019-10-29 Loïc LEUILLIOT feat(structures): add more information on structure modal
34b88f3  2019-10-29 Loïc LEUILLIOT refactor(notes): fix character note layout and improve blades structure
455b538  2019-10-29 Loïc LEUILLIOT fix(ui): ensure card header is properly rendered with title and buttons
fe54b23  2019-10-28 Loïc LEUILLIOT feat(search): update search views to BS4
b55e2c1  2019-10-28 Loïc LEUILLIOT fix(acl): avoid null exception if character not found
24f59e3  2019-10-28 Loïc LEUILLIOT test(acl): add missing global scope to superuser permission
ebd5d53  2019-10-27 Loïc LEUILLIOT refactor(tables): use generic filters system
dfcd64a  2019-10-27 Loïc LEUILLIOT feat(contracts): add filters for type and status
83be1b0  2019-10-27 Loïc LEUILLIOT refactor(tables): remove un-required LoC in favor of relationship
f39bf82  2019-10-27 Loïc LEUILLIOT fix(prices): ensure we're using average_price everywhere
039d0cd  2019-10-26 Loïc LEUILLIOT refactor: remove unrequired call and reduce variables name
3891cc0  2019-10-26 Loïc LEUILLIOT fix(layouts): apply BS4 changes to mini-app and ensure css is imported
58e6d87  2019-10-24 Loïc LEUILLIOT test(acl): update testGetPermissionsFromCorporationRoles permissions
fc36f00  2019-10-24 Loïc LEUILLIOT test(acl): update orchestra structure dependency
a1ebb27  2019-10-24 Loïc LEUILLIOT ci(travis): add prompt answer to php-redis extension
0fae4a8  2019-10-24 Loïc LEUILLIOT refactor(styleci): apply requested changes
1dd4c2a  2019-10-24 Loïc LEUILLIOT fix(acl): list permission attached to an user using new filters
23c5367  2019-10-24 Loïc LEUILLIOT fix(users): return character based on user if none exists
b5bb004  2019-10-24 Loïc LEUILLIOT fix(acl): redirect once role has been dropped from user
ded7dfc  2019-10-24 Loïc LEUILLIOT fix(acl): remove affiliations from relationships replaced by filters
0d27bd3  2019-10-24 Loïc LEUILLIOT fix(acl): ensure corp filter targeting char perm is properly applied
26b8f40  2019-10-24 Loïc LEUILLIOT fix(acl): add global scope on superuser permission
17f1dee  2019-10-24 Loïc LEUILLIOT refactor(standings): use generic blade for all standing render
2cd04a3  2019-10-24 Loïc LEUILLIOT fix(users): ensure list is properly render even if no main has been set
1c5aee4  2019-10-24 Loïc LEUILLIOT feat(acl): restrict standing builder access
842cd67  2019-10-23 Loïc LEUILLIOT refactor(fittings): replace tables by dl lists to display meta info
6a7e374  2019-10-23 Loïc LEUILLIOT feat(structures): add fittings modals and export button
42a2003  2019-10-23 Loïc LEUILLIOT fix(fittings): fix columns width to render tables uniformly
6b9210e  2019-10-23 Loïc LEUILLIOT fix(fittings): use button instead of a tag
084b3a7  2019-10-22 Loïc LEUILLIOT fix(ledger): use proper party to render corp wallet ledger
8eb7c40  2019-10-22 Loïc LEUILLIOT fix(ui): disable token warning for admin user
2b83b1a  2019-10-22 Loïc LEUILLIOT feat(ui): remove profile block for admin user
da114a9  2019-10-22 Loïc LEUILLIOT fix(acl): add missing blueprints permissions
74c3281  2019-10-21 Loïc LEUILLIOT feat(corporation): add new categories to wallet ledger
3372506  2019-10-21 Loïc LEUILLIOT fix(fittings): ensure html encapsulated inside Ship desc. is rendered
e3c7906  2019-10-21 Loïc LEUILLIOT refactor(entities): use Universe Entity model to render char/corp/ally
6cbc36d  2019-10-22 Loïc Leuilliot feat(list): sort characters and corporation in ascending order (#325)
f73b213  2019-10-22 Loïc Leuilliot feat(character): add number of toons on character summary (#324)
c5d47bc  2019-10-22 Loïc Leuilliot feat(skills): add a button to export skills with Pyfa format (#323)
9a84622  2019-10-22 Loïc Leuilliot feat(market): add filters options on characters & corporation market (#322)
c12a650  2019-10-22 Loïc Leuilliot feat(industry): improve filterability of industry tables (#321)
85878c2  2019-10-22 Loïc Leuilliot feat(blueprints): re-introduced blueprints view which has been removed (#320)
636cc43  2019-10-22 Loïc Leuilliot feat(acl): implement new UI
d152cca  2019-10-17 Loïc Leuilliot Merge pull request #317 from warlof/4.0.x
f9d0963  2019-10-17 Loïc Leuilliot Merge branch '4.0.x' into 4.0.x
cfb2775  2019-10-17 Loïc LEUILLIOT style(styleci): apply request changes
1eac33c  2019-10-17 Loïc LEUILLIOT refactor(ui): remove un-required float on card tools
7fad413  2019-10-17 Loïc LEUILLIOT feat(ui): improve forms design
9436c15  2019-10-17 Loïc LEUILLIOT refactor(ui): remove unused views
7f04aa3  2019-10-17 Loïc LEUILLIOT feat(deps): upgrade profile card
5963ef3  2019-10-17 Loïc LEUILLIOT feat(deps): upgrade standing builder card
c00ca77  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade standing builder layout
d6498c6  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade about layout
9e754d2  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade security logs layout
07563b9  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade settings card layout
22ef460  2019-10-16 Loïc LEUILLIOT feat(deps): replace help-block which has been removed
f9bcd03  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade sso card
aa4f366  2019-10-16 Loïc LEUILLIOT refactor(ui): update some tags according to AdminLTE3
9e6dc84  2019-10-16 Loïc LEUILLIOT fix(ui): ensure card is covering select2 completely
9de2254  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade select2
8547605  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade schedule list
e9032de  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade users card
596d97f  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade users list
7fcf2d1  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade access card
7b1a589  2019-10-16 Loïc LEUILLIOT fix(deps): replace btn-xs by btn-sm since xs is non longer available
d96b7c0  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade access list
8aad656  2019-10-16 Loïc LEUILLIOT feat(deps): switch the icons stylesheet to config
fc73fd3  2019-10-16 Loïc LEUILLIOT fix(deps): use new offset helper
860daf8  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade mail timeline
543c4d8  2019-10-16 Loïc LEUILLIOT feat(deps): replace pull helper by new float helper
2813b3f  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade corporations assets
f513716  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade corporations bookmarks
0460c03  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade corporations contacts
8431178  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade corporations contracts
1e67886  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade corporations extractions
bb30d72  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade corporations industry
c46a106  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade corporations killmails
5197f47  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade corporations planetary interaction ledger
3d42e9d  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade corporations bounty prizes ledger
0008033  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade corporations ledger sub-menu
24cec16  2019-10-16 Loïc LEUILLIOT fix(ui): replace raw style by padding helper on corp wallet sub-menu
b8f78d4  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade corporations wallet ledger summary
20439d9  2019-10-16 Loïc LEUILLIOT feat(deps): upgrade corporations market
218474d  2019-10-16 Loïc LEUILLIOT feat(ui): add mining details modal on both corporation and character
8122158  2019-10-15 Loïc LEUILLIOT fix(deps): use proper map mark icon for font-awesome 5
4cd2c37  2019-10-15 Loïc LEUILLIOT fix(deps): restore timeline on character mining ledger
f64a871  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations mining-ledger
89eb4e9  2019-10-15 Loïc LEUILLIOT fix(deps): replace data-widget call for tooltip by data-toggle
f870fa6  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations customs-offices
17d8b6b  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations logs
2035b2f  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations titles
51fa6f4  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations security menu
fd8df74  2019-10-15 Loïc LEUILLIOT refactor(entity): entity model can be used with char & corp rendering
a79ca7e  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations roles
e27beca  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations standings
d613738  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations starbases
65841aa  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations structures
f29941a  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations wallet sub-menu
861a0dc  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations journals
9984d9c  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations transactions
5f70cd9  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations tracking
c6ed474  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations menu
b7a046d  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations sidebar
ee22da6  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations summary
fbed121  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade corporations list
9339978  2019-10-15 Loïc LEUILLIOT style(styleci): apply requested changes
c0bd889  2019-10-15 Loïc LEUILLIOT style(styleci): apply requested changes
e8b7be3  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character assets
00fbcf0  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character bookmarks
ed27e44  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character calendar
e48f20f  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character contacts
c323c17  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character contracts
a15f58a  2019-10-15 Loïc LEUILLIOT fix(contracts): show contract title instead test lorem ipsum string
c285196  2019-10-15 Loïc LEUILLIOT fix(deps): remove deprecated class from headings and improve style
4a737ea  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character fittings
39132a5  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character industry
1936edf  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character killmails
fecc2cb  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character mails
5d1eb68  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character market
c391125  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character mining
f069e14  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character notifications
fe1b771  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character planetary interaction
7474c32  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character research
a5a1948  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character wallet navigation
4666ff5  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character wallet transactions
58799a6  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character wallet journal
afd1997  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character standings
3fe8013  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character skills
b8feb07  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character sheet
a211196  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character menu
2cf0343  2019-10-15 Loïc LEUILLIOT feat(deps): upgrade character summary
69506a4  2019-10-11 Loïc LEUILLIOT fix(deps): update data-tables dependency and pull it from packagist
82850cb  2019-10-10 Loïc LEUILLIOT feat(deps): upgrade dashboard
1a93bfc  2019-10-10 Loïc LEUILLIOT feat(deps): bump AdminLTE to v3 and FontAwesome to v5
6f86473  2019-10-10 Loïc LEUILLIOT feat(config): switch worker config to configuration file
2e9b7b3  2019-10-10 Loïc LEUILLIOT fix(deps): move Eve Online OAuth to its own socialite package
74adf8e  2019-10-10 Loïc LEUILLIOT fix(deps): update resources directory structure according L5.7
9974e17  2019-10-10 Loïc LEUILLIOT fix(deps): switch font-awesome import path from v4 to v5
7a02cc4  2019-10-10 Loïc LEUILLIOT fix(deps): replace str_ and arr_ helpers by their Classes
1114fde  2019-10-10 Loïc LEUILLIOT fix(deps): dev must be use as a suffix instead prefix
494d8a0  2019-10-10 Loïc LEUILLIOT chore(deps): downgrade stability to dev version
8a8ac1c  2019-10-10 Loïc LEUILLIOT chore(deps): update dependencies to Laravel 6.x
dbd311a  2019-10-10 Loïc Leuilliot (wfjsw/master, seat/master, darkflamed/master, master) fix(ACL): use keys returned from ACL mapping in order to apply DT scope (#316)
c67c36d  2019-10-10 Loïc Leuilliot fix(deps): add missing yajra datatable service dependency (#315)
c986c5e  2019-10-10 Loïc LEUILLIOT fix(deps): dev must be use as a suffix instead prefix
7846d12  2019-10-10 Loïc LEUILLIOT chore(deps): downgrade stability to dev version
c20f440  2019-10-10 Loïc LEUILLIOT chore(deps): update dependencies to Laravel 6.x
7ebc8b2  2019-10-06 Loïc Leuilliot refactor(datatable): increase Yajra/Datatable usage (#313)
```
### 4.0.0-rc2
```
7e2f070  2019-11-16 Loïc LEUILLIOT (tag: 4.0.0-rc2) ci(travis): require php 7.3 for build
2c450e4  2019-11-16 Loïc LEUILLIOT fix(deps): ensure php_version view is properly rendered on check
e6501dc  2019-11-16 Loïc LEUILLIOT fix(deps): update php minimum version to 7.3
fd965fa  2019-11-16 Loïc LEUILLIOT test(acl): remove group from tests
e6ba402  2019-11-16 Loïc LEUILLIOT fix(acl): remove groups call from remaining controllers
fb285dc  2019-11-16 Loïc LEUILLIOT style: apply syleci change requests
134edce  2019-11-16 Loïc LEUILLIOT refactor(acl): drop Group class and use an unique user bucket
c4e062e  2019-11-11 Loïc LEUILLIOT style: apply styleci changes request
a00b34d  2019-11-11 Loïc LEUILLIOT fix(ui): apply small change on UI layouts
3d75fe7  2019-11-11 Loïc LEUILLIOT ci(styleci): remove rules from preset
037a2c1  2019-11-11 Loïc LEUILLIOT ci(styleci): remove length_ordered_imports
3989d5b  2019-11-11 Loïc LEUILLIOT fix(versions): exclude unstable versions from checker
458b14d  2019-11-11 Loïc LEUILLIOT feat(moons): add moons reporter
54e38c9  2019-11-11 Loïc LEUILLIOT feat(ui): use new EVE images server signatures
4263cad  2019-11-11 Loïc LEUILLIOT fix(acl): avoid null exception on empty permission titles dataset
```
### 4.0.0-rc3
```
766653e  2019-12-22 Loïc LEUILLIOT (tag: 4.0.0-rc3) style: address some issues triggered by styleci
69d018e  2019-12-22 Loïc LEUILLIOT feat(squads): add creation form
3d9cabe  2019-12-22 Loïc LEUILLIOT fix(filters): avoid null exception due to empty filter source
3ef0a6b  2019-12-22 Loïc LEUILLIOT style: fix indent issue on main layout
54bd08a  2019-12-22 Loïc LEUILLIOT refactor(role): add more constraint on logo during role edition
849b175  2019-12-22 Loïc LEUILLIOT feat(role): allow role logo to be removed
e69fb6f  2019-12-22 Loïc LEUILLIOT refactor(role): replace logo button by a modern preview mechanics
d199eca  2019-12-21 Loïc LEUILLIOT style: address some issues triggered by styleci
32ca5a0  2019-12-21 Loïc LEUILLIOT feat(squads): allow user roles to be auto updated
bb1a18e  2019-12-21 Loïc LEUILLIOT refactor: drop has filter check from filter trait
f898253  2019-12-21 Loïc LEUILLIOT fix(acl): avoid null exception when corporation is missing
a1f01ee  2019-12-21 Loïc LEUILLIOT feat(squads): add roles relation to squads
d660c62  2019-12-21 Loïc LEUILLIOT feat(squads): make squads to be droppable
837370c  2019-12-21 Loïc LEUILLIOT fix(squads): add squad type into columns sorting queries
e6b0b8e  2019-12-21 Loïc LEUILLIOT fix(squads): add relations between squads tables
d408555  2019-12-21 Loïc LEUILLIOT feat(squads): add squad type (auto, hidden, manual)
494c9ad  2019-12-21 Loïc LEUILLIOT fix(squads): add margin after members/candidates/moderator
23b3cd7  2019-12-21 Loïc LEUILLIOT feat(squads): complete filters component
60e759d  2019-12-20 Loïc LEUILLIOT fix(squads): address issue on filter check when there were ruleset
9e122fc  2019-12-18 Loïc LEUILLIOT feat(squads): implement magic filter query builder
584de74  2019-12-17 Loïc LEUILLIOT feat(squads): start to implement magic filter component
b1a1e8f  2019-12-15 Loïc LEUILLIOT feat(squads): implement a new intermediate layer between user and ACL called Squads
1e9270d  2019-12-15 Loïc LEUILLIOT fix(ui): ensure plural parameter is properly handled on sidebar building
3694efe  2019-12-12 Loïc LEUILLIOT fix: adapt role members lookup to use compact alt. characters
6779161  2019-12-10 Loïc LEUILLIOT fix: ensure affiliation call is properly made
677b3f1  2019-12-10 Loïc LEUILLIOT fix: use 4.0.x dev branch of eseye
ad4c6a8  2019-12-10 Loïc LEUILLIOT fix: drop users and tokens related to admin only if account exists
c1a0905  2019-11-28 Loïc LEUILLIOT feat(esi): use affiliation to retrieve character corporations & alliance
c65c62c  2019-11-28 Loïc LEUILLIOT docs: fix documentation blocs
11a7b5a  2019-11-19 Loïc LEUILLIOT fix(images): use reaction render instead default
```
### 4.0.0-rc4
```
b06ad4d  2020-01-02 Loïc LEUILLIOT (tag: 4.0.0-rc4) refactor(squads): use ajax to update members and roles table
f2634d5  2020-01-01 Loïc LEUILLIOT style: apply styleci changes
2dfd191  2020-01-01 Loïc LEUILLIOT feat(squads): add ways to manage members & roles
a0c750f  2020-01-01 Loïc LEUILLIOT feat(squads): show squad application date/time
d937b7b  2020-01-01 Loïc LEUILLIOT fix(squads): restrict delete function to superuser
99a924f  2020-01-01 Loïc LEUILLIOT style: apply styleci changes
67dbd7e  2020-01-01 Loïc LEUILLIOT fix(squads): add a check to determine if we have an authenticated user
dca1674  2019-12-29 Loïc LEUILLIOT feat(squads): implement moderator functions (add/removal)
301e00f  2019-12-29 Loïc LEUILLIOT refactor(squads): split squads applications methods from main squad methods
26b11a2  2019-12-29 Loïc LEUILLIOT refactor(squads): add some effect on list
0b41427  2019-12-29 Loïc LEUILLIOT refactor(squads): improve squad card layout
4a71915  2019-12-23 wfjsw   fix(langs): fix langcode for Chinese (Simp.)
d700b8c  2019-12-29 Loïc LEUILLIOT feat(squads): implement create and delete buttons
98def84  2019-12-28 Loïc LEUILLIOT feat(squads): add filters to squad list
6efef09  2019-12-28 Loïc LEUILLIOT refactor(squads): improve list layout with dynamic search
46f30c3  2019-12-24 Loïc LEUILLIOT fix(squads): add missing unsigned flag on squad_id
3147895  2019-12-23 Loïc LEUILLIOT test(acl): fix tests according to affiliation change
0e087d4  2019-12-23 Loïc LEUILLIOT fix(acl): use affiliation to character entity during check
594b70b  2019-12-23 Loïc LEUILLIOT fix(deps): bump to eseye 2.0
```
### 4.0.0-rc5
```
6ffd664  2020-01-14 Peter Pfeufer (tag: 4.0.0-rc5) [translation] wallet to german (part 2)
2eb079d  2020-02-09 Loïc LEUILLIOT fix(acl): avoid key collision
8674251  2020-02-09 Ben Thompson (fix) the throw Exception in this migration check refers to a undefined property as the name column is not selected.
5e9794a  2020-02-09 Ben Thompson (fix) update Login event to accomodate changes in Console package.
2d6a012  2020-02-02 Loïc LEUILLIOT refactor(auth): enqueue corporations jobs if unknown
bb8b21f  2020-02-02 Loïc LEUILLIOT fix(scopes): add source user in routes since authenticated user may differ
32ebe25  2020-02-02 Loïc LEUILLIOT fix: set user as auto-incremented
f1de62e  2020-01-19 Loïc LEUILLIOT fix(squads): remove default value for filters json field
41e51bd  2020-01-19 Loïc LEUILLIOT fix(mails): remove timestamps from search query and use default sender search
66071e3  2020-01-11 Peter Pfeufer Update .gitignore
8da1b2b  2020-01-11 Peter Pfeufer [fix] better wording and typo
7c40569  2020-01-11 Peter Pfeufer [fix] better wording for global_standing_builder_label
9a6961f  2020-01-11 Peter Pfeufer [fix] typo
54142d9  2020-01-11 Peter Pfeufer [translation] wallet to german
be96c20  2020-01-11 Peter Pfeufer [translation] squads to german
e66c439  2020-01-11 Peter Pfeufer [translation] research to german
26cce1a  2020-01-11 Peter Pfeufer [translation] permissions to german
2d7320e  2020-01-11 Peter Pfeufer [fix] typo in english translations
7aec6ca  2020-01-11 Peter Pfeufer [translation] notifications to german
4b9d347  2020-01-11 Peter Pfeufer [translation] moons to german
f59510f  2020-01-11 Peter Pfeufer [translation] mining to german
93c9a7e  2020-01-11 Peter Pfeufer [fix] using the same that was used in the already translated file
de52e2e  2020-01-11 Peter Pfeufer [translation] market to german
148340f  2020-01-11 Peter Pfeufer [translation] mail to german
a85dbbe  2020-01-11 Peter Pfeufer [translation] kills to german
7ef0cf3  2020-01-11 Peter Pfeufer [translation] industry to german
ba8fe10  2020-01-11 Peter Pfeufer [fix] typo
b929cd7  2020-01-11 Peter Pfeufer [translation] fittings to german
58e8d59  2020-01-11 Peter Pfeufer [translation] custom offices to german
c170281  2020-01-11 Peter Pfeufer [translation] contracts to german
0b1c44e  2020-01-11 Peter Pfeufer [translation] calendar to german
ea835f5  2020-01-11 Peter Pfeufer [translation] bookmarks to german
1bfcaf9  2020-01-11 Peter Pfeufer [update] .gitignore to accomodate neatbeans project settings
2b90bd9  2020-01-12 Loïc LEUILLIOT fix(contracts): show acceptor only if exists
c81695e  2020-01-12 Loïc LEUILLIOT feat(killmails): add factions to victim and killer columns
487c2c7  2020-01-12 Loïc LEUILLIOT fix(intel): remove unused jobs dispatch from intel controller
8224d98  2020-01-11 Loïc LEUILLIOT fix(ui): remove skins css import
58bd278  2020-01-11 Loïc LEUILLIOT fix(squads): return proper view on index
dbaaffd  2020-01-11 Loïc LEUILLIOT style: apply styleci change requests
ba97b49  2020-01-11 Loïc LEUILLIOT fix: ensure users table start to increment at 2
0f6aec0  2020-01-11 Loïc LEUILLIOT refactor: adapt package according to eveapi changes
bcd2bd7  2020-01-05 Loïc LEUILLIOT style: add margin upper each skills group card
ea28ce2  2020-01-08 autophob chore(acl): improve captions related to permissions (#349)
af0d0af  2020-01-04 Loïc LEUILLIOT style: reordering dependencies in composer
37c796c  2020-01-04 Loïc LEUILLIOT fix(squads): use proper index route when redirecting user
e87f8f0  2020-01-04 Loïc LEUILLIOT fix: make active field fillable
7cfcd38  2020-01-04 Loïc LEUILLIOT feat(auth): switch to oauth v2 endpoints
3fa83a8  2020-01-04 Loïc LEUILLIOT refactor(auth): switch socialite extension to services package
```
### 4.0.0-rc6
```
0da9c90  2020-03-26 Loïc LEUILLIOT (tag: 4.0.0-rc6) fix(ui): ensure tab structure is properly built
4d888d3  2020-03-26 Loïc LEUILLIOT fix(ui): improve changelog button render
24cd199  2020-03-23 Loïc LEUILLIOT refactor(api): move user OAS to UserResource
2d769f1  2020-03-23 Loïc LEUILLIOT fix(ui): address a small bug in role UI
7b080dd  2020-03-22 Loïc LEUILLIOT feat(api): upgrade API doc to OAS3
75c09a9  2020-03-22 Loïc LEUILLIOT fix: ensure scopes don't conflict with search
bce139d  2020-03-22 Loïc LEUILLIOT refactor: remove auth mail controller reference
b42b62a  2020-03-22 Loïc LEUILLIOT feat(squads): improve logging
c866db3  2020-03-21 Loïc LEUILLIOT fix(squads): ensure squad moderator are able to manage members
9699a03  2020-03-21 Loïc LEUILLIOT fix(squads): log bounced access
ec92bdb  2020-03-21 Loïc LEUILLIOT fix(squads): hide kick button from non admin/moderators
dc9247d  2020-03-21 Loïc Leuilliot feat(squads): add guardians front of routes (#396)
974a894  2020-03-21 Loïc LEUILLIOT refactor(moons): avoid selection to determine which moon can be display
634ced2  2020-03-21 John L. Carveth feat(moons): add granular permissions and render scanned moon only (#393)
c94f832  2020-03-21 Loïc LEUILLIOT style: apply styleci changes requests
729ed90  2020-03-21 Loïc LEUILLIOT style: fix a typo in class name
b72e0db  2020-03-21 Loïc LEUILLIOT refactor(squads): replace moderated field in table with a relation attribute
d7c3862  2020-03-21 Loïc LEUILLIOT feat(squads): allow candidate to cancel their application
f656cec  2020-03-21 Loïc LEUILLIOT fix(squads): replace squad_id unique index with user and squad
6f2d6ff  2020-03-21 Loïc LEUILLIOT refactor: move compact character view to global partials
6128fc8  2020-03-19 Justin Mercer fix(configuration):  Fix User Management characters display and sort (#384)
aab8b1d  2020-03-17 Loïc Leuilliot ci(styleci): update config for preset changes
c797bd8  2020-03-17 Loïc Leuilliot ci(styleci): update config for preset changes
8509e14  2020-03-17 Loïc Leuilliot ci(styleci): update config for preset changes
3684eff  2020-03-16 Loïc Leuilliot ci(styleci): update config for preset changes
f367541  2020-03-15 Ben Thompson refactor(intel): updated to reflect changes to Intel repository in services package (#392)
cd67fda  2020-03-09 Jabasukuriputo Wang ui(sheet): make skill list compact and fit (#390)
313b187  2020-03-06 C Edwards feat(squads): add validation to ensure message set (#389)
08311c0  2020-03-06 C Edwards fix(squads): address typo on applications routes (#388)
b6bf19e  2020-03-01 Loïc LEUILLIOT fix(acl): make role description optional and ensure multiple users can be added at time
44c1b22  2020-03-01 Loïc LEUILLIOT refactor(acl): remove permissions and role permissions from v3
9f6e832  2020-03-01 Loïc LEUILLIOT fix(ui): make sure mining modal is showing metadata table properly
d929ac8  2020-03-01 Loïc LEUILLIOT fix: ensure upgrade compatibility between v3 and v4
64aca03  2020-03-01 Loïc LEUILLIOT fix(squads): update members when filters or type is altered
92a82da  2020-03-01 Loïc LEUILLIOT refactor: add system and standard scope to users model
051bcc2  2020-02-29 Loïc LEUILLIOT feat(moons): add small stats in footer
caed739  2020-02-29 Loïc LEUILLIOT fix(killmails): use proper field to filter corporation killmails
966891c  2020-02-26 Ben Thompson fix(membertracking): Using updated model relations, refactored to fix sorting and add ship column
7736940  2020-02-24 Loïc LEUILLIOT fix(squads): add missing update form
4eb8ea6  2020-02-16 Loïc LEUILLIOT fix(squads): ensure filters are properly casts
6cb27bd  2020-02-23 Justin Mercer fix(profile): Main Character select option from id to character_id
8536957  2020-02-19 Ben Thompson fix(ledger): too few arguments passed to controller functions
4d4dd02  2020-02-19 Ben Thompson fix(notifications): fix datatables error on character notifications from issue passing notification text from array to string
a30b40d  2020-02-19 Ben Thompson  fix: AccessCheck affiliation lookup, missing cron validator when adding schedules. (#380)
348ee5c  2020-02-16 Ben Thompson fix(search): Fixes to Datatables errors on Search pages
da3afe2  2020-02-15 Justin Mercer fix(character): Change to character initialization instead of else
3598455  2020-02-14 Justin Mercer fix(character): Allow character tabs to be viewed without needing a refresh token
7fe3234  2020-02-14 Justin Mercer fix(corporation): Datatables corporation mining ledger needs to look at affiliations for corporation_id of character
6799b19  2020-02-14 Justin Mercer fix(characters): Add affiliation to data name to match query so that we don't get a query error
```