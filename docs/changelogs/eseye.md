![SeAT](https://i.imgur.com/aPPOxSK.png)

# services change logs
Generated with: `git log --pretty=format:"%h%>(12)%ad %<(7)%aN%d %s" --date=short`

## 0.0.1
```
dcb08de  2017-01-17 Leon Jacobs (tag: 0.0.1) Set version to 0.0.1
3a95e3f  2017-01-17 Leon Jacobs Apply fixes from StyleCI (#2)
5c3fe7d  2017-01-17 Leon Jacobs Include a user-agent and small tweaks
f3d07ee  2017-01-17 Leon Jacobs Throw `RequestFailedException` for failed requests.
8fd6d3e  2017-01-16 Leon Jacobs Apply fixes from StyleCI (#1)
f5d892c  2017-01-16 Leon Jacobs Add support to set query string and body values.
656a039  2017-01-16 Leon Jacobs Refresh token generator HTML tweaks
c49c275  2017-01-16 Leon Jacobs Syntax highlight example
df1f7da  2017-01-16 Leon Jacobs Update example to a shortened version.
9a4da16  2017-01-15 Leon Jacobs Add refresh token generator helper
42c93dd  2017-01-15 Leon Jacobs Add Null and Redis Cache drivers
e35a336  2017-01-15 Leon Jacobs Add caching and a FileCache driver
1cdabd7  2017-01-15 Leon Jacobs Add more logging and improve some existing logging
52df33c  2017-01-15 Leon Jacobs Update example to show how to loop over data.
984c825  2017-01-15 Leon Jacobs Make access token optional
3537bd5  2017-01-14 Leon Jacobs Use singleton pattern for library configuration and add Logging
ab7ed76  2017-01-14 Leon Jacobs Return correct boolean value to say is valid
fa609ab  2017-01-14 Leon Jacobs Abstract the ArrayAccess implementations for Containers
6a88bc8  2017-01-14 Leon Jacobs Update readme
d854df8  2017-01-14 Leon Jacobs Update Example to show how to access fetched data
fdf1fd8  2017-01-14 Leon Jacobs Rename `fetch` to `invoke`
190a1cf  2017-01-14 Leon Jacobs Extend `ArrayObject` instead of `ArrayAccess` for `EsiResponse`
c6e5fab  2017-01-13 Leon Jacobs Add StyleCI configuration
59bc055  2017-01-13 Leon Jacobs Start work in having a predictable `EsiResponse` container.
2640c22  2017-01-13 Leon Jacobs First commit
4839df5  2017-01-13 Leon Jacobs Initial commit
```
## 0.0.2
```
db47273  2017-01-17 Leon Jacobs (tag: 0.0.2) Update package name and version bump
```
## 0.0.3
```
ed95d4e  2017-01-17 Leon Jacobs (tag: 0.0.3) Vendor the tokengenerator bin and version bump
```
## 0.0.4
```
15874a8  2017-01-22 Leon Jacobs (tag: 0.0.4) Version Bump
e7719d0  2017-01-20 Leon Jacobs Disable camelCase checks
e3b008e  2017-01-20 Leon Jacobs Add codeclimate configuration
d2a2860  2017-01-19 Leon Jacobs Add more tests
c348c4d  2017-01-19 Leon Jacobs Exclude interfaces and tests from coverage reports
086cba4  2017-01-18 Leon Jacobs Add test coverage badge
63cbb3e  2017-01-18 Leon Jacobs Add whitelist to specify which directory to include in a coverage report
2a607aa  2017-01-18 Leon Jacobs Update code coverage runner and add badges
d5d3c6e  2017-01-18 Leon Jacobs Add test coverage reporting support
bcc6edf  2017-01-18 Leon Jacobs Add Travis configuration
97e0d94  2017-01-18 Leon Jacobs 👟 Add Tests!
7320f1d  2017-01-18 Leon Jacobs Update readme to show class instantiation
d998b39  2017-01-18 Leon Jacobs Allow for public calls to be made with an `EsiAuthentication` instance
de4586d  2017-01-18 Leon Jacobs Update readme
d74060a  2017-01-17 Leon Jacobs Typo fixes
434f2b4  2017-01-17 Leon Jacobs Update readme
fe3d7c5  2017-01-17 Leon Jacobs Update link to deleting third party apps.
3d68052  2017-01-17 Leon Jacobs Resolve the symlinks in a path too
```
## 0.0.5
```
dd5d694  2017-01-27 Leon Jacobs (tag: 0.0.5) Version Bump
f3cb63f  2017-01-27 Leon Jacobs Only cache results that have not already expired.
ba2c5b2  2017-01-27 Leon Jacobs Fix filecache forget() method bug found in eveseat/eseye#3
4c56d96  2017-01-27 Maikel van der Knaap / Jarno Midumulf Ignore errors when unlinking
```
## 0.0.6
```
9444a30  2017-01-28 Leon Jacobs (tag: 0.0.6) Version Bump
a3268b4  2017-01-28 Leon Jacobs Fix failing test
20aea22  2017-01-28 Leon Jacobs Apply fixes from StyleCI (#5)
f43a74b  2017-01-28 Leon Jacobs Move the Fetcher to an interface and implement a GuzzleFetcher
f03313c  2017-01-28 Leon Jacobs Add more tests!
befac9f  2017-01-28 Leon Jacobs Add ability to set the fetcher
a8bdd11  2017-01-28 Leon Jacobs Update test to init a new Fetcher for scopes testing
d238c74  2017-01-28 Leon Jacobs Mke it possible to get the original exception when a request fails
488efe5  2017-01-28 Leon Jacobs Add test for the Eseye fetcher, mokcing ESI interfacing
0200f2f  2017-01-28 Leon Jacobs Allow Client and Authentication to be set later
9f0333d  2017-01-28 Leon Jacobs Fix setting additional headers in requests
25a980e  2017-01-28 Leon Jacobs Improve error logging for ESI errors
3557313  2017-01-27 Leon Jacobs Add test for refresh_token stripping
```
## 0.0.7
```
9557c6c  2017-05-07 Leon Jacobs (tag: 0.0.7) Version Bump
d64b39d  2017-05-07 Leon Jacobs Return the context after setVersion
72535ab  2017-05-07 Leon Jacobs Update example with setVersion()
c60682f  2017-04-01 Leon Jacobs FIx styleci issues
98c5d0f  2017-04-01 Leon Jacobs Add ability to set version of ESI to use.
```
## 0.0.8
```
dd1b19f  2017-07-09 Leon Jacobs (tag: 0.0.8) Keep guzzle at 6.2.* for now and version bump
```
## 0.0.9
```
6f05b40  2017-07-10 Leon Jacobs (tag: 0.0.9) Revert dd1b19fdc and fix calls to GuzzleHttp\Psr7\Request
```
## 0.0.10
```
1dafe7e  2017-09-20 Leon Jacobs (tag: 0.0.10) Version Bump
ea40481  2017-09-20 Leon Jacobs Apply fixes from StyleCI.
6afa018  2017-09-20 Leon Jacobs Styling fixes.
2c47254  2017-09-20 HgAlexx Few changes adding Memcache(d) support (#10)
```
## 0.0.11
```
dba3c35  2017-12-30 Leon Jacobs (tag: 0.0.11) Version bump to 0.0.11. 🎉
c6268b1  2017-12-30 Leon Jacobs Add `page()` helper to specify the page to retrieve.
35553bd  2017-12-30 Leon Jacobs Add response headers to an EsiResponse object.
9d9c7d3  2017-12-29 Leon Jacobs Update request logger to include current error limit.
39709ca  2017-12-29 Leon Jacobs Use helper method to update authentication info.
d4f0e71  2017-12-29 Leon Jacobs Add test for the EsiResponse `raw` property.
7db6c4a  2017-12-29 Leon Jacobs Test on PHP 7.1 & PHP 7.2 too.
8aa5053  2017-12-29 Leon Jacobs Fix memcache test with new EsiResponse signature.
c1067fb  2017-12-29 Leon Jacobs Fix tests to match new EsiResponse signature.
9ea3157  2017-12-29 Leon Jacobs Make it possible to get raw responses from ESI.
26720da  2017-12-28 Leon Jacobs Perform cleanups of request elements after an invoke().
d5eeedf  2017-12-28 Leon Jacobs Add getAuthenticationScopes() to the FetcherInterface.
6ca37ee  2017-12-28 Leon Jacobs Use carbon lte() method for time comparison
59bbb34  2017-12-28 Leon Jacobs Make it possible to cache HTTP GET and POST request responses.
fe41321  2017-12-28 Leon Jacobs Setup a logger for Eseye::class on init.
02f69ef  2017-12-23 Loïc LEUILLIOT add missing getter for cache_path (#17)
c0d015c  2017-12-23 Leon Jacobs Docblock updates.
7aab880  2017-12-23 Leon Jacobs Update endpoints & permissions.
b744e69  2017-12-20 Leon Jacobs Update return type to self.
6c6fa67  2017-12-20 Leon Jacobs Update possible scopes for the token generator helper.
```
## 0.0.12
```
1425e70  2018-04-15 Leon Jacobs (tag: 0.0.12) Version 0.0.12 🎉
ac4bf9c  2018-03-31 Leon Jacobs Apply fixes from StyleCI (#29)
8f8f083  2018-03-17 Leon Jacobs Fix various typos and return types.
1165942  2018-01-21 Leon Jacobs Apply fixes from StyleCI (#27)
c2a2d87  2018-01-21 Leon Jacobs Add tests and minor rename of cached load helpers.
7baf14d  2018-01-21 Michael Cooke Add loaded_from_cache flag to EsiResponse (#26)
d831310  2018-01-20 Leon Jacobs Bump required PHP version to 7.1.
79d3276  2018-01-20 Leon Jacobs Stop testing on PHP 7.0. Only 7.1+ is important now.
dde5969  2018-01-20 Leon Jacobs Add missing dockblock.
f00f305  2018-01-20 Leon Jacobs Remove .DS_store from .gitignore.
e9e1763  2018-01-20 Michael Cooke Add setRefreshToken() methods to Eseye and EsiAuthentication (#25)
48eda27  2018-01-20 Michael Cooke Fix typo (#24)
b530929  2018-01-06 Leon Jacobs Disable POST caching pending a better solution.
f87f0e9  2018-01-05 Leon Jacobs Minor style updates.
cb8cc2f  2018-01-05 Michael Cooke Include array handling in setQueryString() (#23)
9ce7bc6  2018-01-04 Leon Jacobs Add missing handling of `GuzzleHttp\Exception\ServerException`.
029f105  2018-01-03 Leon Jacobs Remove configurable default return value.
8888e16  2018-01-03 Leon Jacobs Add an optional() helper for response keys that might not exist.
```
## 1.0.0
```
5c3af0b  2018-04-29 Leon Jacobs (tag: 1.0.0) Version 1.0.0 🎉
dd14c7f  2018-04-29 Leon Jacobs Apply fixes from StyleCI (#32)
1377046  2018-04-29 Leon Jacobs Minor sorting/style fix.
8070a42  2018-04-29 Leon Jacobs Fix various annotator problems.
c0e1e5d  2018-04-17 Leon Jacobs Apply fixes from StyleCI (#31)
```
## 1.1.0
```
5761b6e  2018-05-06 Leon Jacobs (tag: 1.1.0) Version 1.1.0 🎉
ba3f5aa  2018-05-06 Michael Cooke Update ESI domain name (#28)
216483d  2018-05-06 Leon Jacobs Add more debug logging points for cached loads and failed responses.
b0006c3  2018-05-06 Leon Jacobs Include and make a rotating handler the default.
```
## 1.1.1
```
8a25b51  2018-05-06 Leon Jacobs (tag: 1.1.1) Version 1.1.1 🎉
4df88ce  2018-05-06 Leon Jacobs Fix FileLogger test.
663d250  2018-05-06 Leon Jacobs Normalize logfile paths.
```
## 1.1.2
```
b47549a  2018-05-06 Leon Jacobs (tag: 1.1.2) Version 1.1.2 🎉
a611ffa  2018-05-06 Leon Jacobs Fix rotating file logger and add tests.
```
## 1.1.3
```
e507480  2018-05-09 Leon Jacobs (tag: 1.1.3) Version 1.1.3 🎉
2d1fe4f  2018-05-09 Loïc LEUILLIOT address issue related to body stream which avoid error to be forwarded to the container (#35)
```
## 1.1.4
```
c90ed69  2018-05-12 Leon Jacobs (tag: 1.1.4) Version 1.1.4 🎉
d8b3616  2018-05-12 Ben     Update FileCache.php (#36)
```
## 1.1.5
```
e157ec0  2018-05-27 Leon Jacobs (tag: 1.1.5) v1.1.5 🎉
26308d5  2018-05-27 Leon Jacobs Bump the default request timeout to 30 seconds.
```
## 1.1.6
```
cae2782  2018-06-30 Leon Jacobs (tag: 1.1.6) v1.1.6
edaf443  2018-06-30 Leon Jacobs Remove checkers for deprecated outposts updater.
```
## 1.1.7
```
065d8b2  2019-03-30 Loïc LEUILLIOT (tag: 1.1.7) v1.1.7
05653e2  2019-03-30 Loïc Leuilliot feat(cache): Add ETag support into the cache engine (#34)
076dc3d  2019-02-18 Leon Jacobs Apply fixes from StyleCI (#45)
3fc6cb9  2018-12-06 Loïc Leuilliot feat(core): Allow Eseye to exploit mocked API (#42)
9fba47e  2018-10-28 Loïc Leuilliot fix(routes checker): Add corporation contact labels endpoint (#41)
```
## 1.1.8
```
55a90cc  2019-04-22 Loïc Leuilliot (tag: 1.1.8) feat(core): Allow Eseye to use alternative SSO endpoint (#47)
a9a0a6d  2019-04-22 stcktrce Bump carbon version to 2.16 (#48)
```
## 2.0.0
```
1e10355  2019-12-23 Loïc LEUILLIOT (tag: 2.0.0) build(core): version bump
64e29d0  2019-12-23 Loïc LEUILLIOT ci(deps): remove php 7.1 and introduce php 7.3
4e73c0f  2019-12-23 Loïc LEUILLIOT fix(deps): bump minimum required php version to 7.2
9f5d2fb  2019-12-23 Loïc LEUILLIOT tests: switch test data-source to singularity
c46e81a  2019-12-23 Loïc LEUILLIOT tests: fix class imports
56e18d9  2019-12-23 Loïc LEUILLIOT test: use level string instead class constants
c0723e9  2019-12-23 Loïc LEUILLIOT chore(typo): fix a typo in test method
d48f0a1  2019-12-23 Loïc LEUILLIOT ci(styleci): fix settings due to new controls
98f14bb  2019-12-23 Loïc LEUILLIOT feat(deps): replace carbon and monolog with v2
96e42ea  2019-12-10 Loïc LEUILLIOT fix(deps): upgrade monolog implementation
```
## 2.1.0
```
94dbc95  2020-03-17 Loïc Leuilliot (tag: 2.1.0) ci(styleci): update config for preset changes
7a8aa8a  2020-03-01 Ben Thompson fix(exception): catch ClientException and re-throw RequestFailedException instead for token update.
a24a21a  2020-02-18 Loïc LEUILLIOT tests(jwk): update tests according to JWK changes
0dc20ea  2020-02-17 Loïc LEUILLIOT feat(jwk): implement JWK validation
bd7b8b7  2020-02-17 Loïc LEUILLIOT style(ci): apply styleCI change request
18c50ed  2020-02-17 Loïc LEUILLIOT fix(deps): include openssl, gmp, json & mbstring
1117fdc  2020-01-12 Loïc LEUILLIOT fix(auth): ensure token are properly refreshed
7f6b88a  2020-01-05 Loïc LEUILLIOT feat(auth): switch to oauth v2 endpoints (JWT support)
```