# platform-java-sdk

### DO NOT FORGET TO UPDATE THE LIBRARY VERSION according to SemVer strategy with every raised PR.

Version numbers take the form `X.Y.Z` and each of those fields means something well defined and specific.


- `X` is the major number.
Changes in this indicate breaking changes to the API (and/or behavior).
- `Y` is the minor number.
Changes to this number indicate that new features were added, but that no APIs are broken as a result.
- `Z` is the patch version.
Changes to this indicate that internal changes were made, but that no changes (even compatible changes) were made to the API.

More details here: [semver.org](https://semver.org/)

#### But Why?

Why bother using a semantic versioning scheme? 
What's wrong with just updating numbers arbitrarily? 
The reason is simple: Version numbers help your users understand something about the nature of the changes they can expect. 
**If you don't follow a pattern, they are left guessing. And this frustrates people.**

Following SemVer introduces rigor on two fronts:

1. It sends clear signals to users about the depth of changes they can expect in a release.
2. It sends a clear signal to your developers about what is, and what is not, allowed when it comes to changing the code.

SemVer helps us impose self-discipline, which in turn minimizes both internal and external disruption.