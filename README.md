## Auto-version xcode projects by git tag/commit

This simply pacakges the very useful shell script by Gabriel Rinaldi, posted at http://gabrielrinaldi.me/ios-app-versioning-with-git-tag/

To use:
1. `yarn add @rh389/rn-xcode-git-version`
2. Add the script `../node_modules/@rh389/rn-xcode-git-version/version.sh` as a build phase to your xcode project

### Options

Name | Type | Description
-----|------|-------------
`-b`| number | Optional, default=0. Increase the calculated `CFBundleVersion` (based on number of commits on this tree) by the given number. Useful when continuing a build sequence from a new repository.
