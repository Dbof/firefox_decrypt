#### Changelog

##### 0.5.2
- non-interative mode (`-n/--no-interactive`, `-l/--list`, `-c/--choice`)

##### 0.5.1
- Testsuite is now in place

##### 0.5
- Fix encoding/decoding problems in python 2 - #5
- Exporting passwords to *pass* now includes the login name
- Exported password identifiers no longer include login names unless multiple
  credentials exist for the same address.

##### 0.4.2
- If profile_path provided doesn't contain profiles.ini assume it is an actual profile

##### 0.4.1
- If only a single profile is found do not prompt user for profile
- Document that the tool also works for Thunderbird profiles

##### 0.4
- Add option to export passwords to *pass* from http://passwordstore.org

##### 0.3
- Polyglot Python 2 and 3. Python 3 now supported.
- Improved debugging information with -v or -vv

##### 0.2
- Added support for logins.json. New format since Firefox 32.

##### 0.1
- Initial version supporting Firefox 3.5 and up.
