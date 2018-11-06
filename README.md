### `/bundle`
* `/bundle` is gitignored. This is because vim packages are generally already git repos, and tracking repos within repos is messy
* For this reason, favor overriding package settings outside of the package and in `/after` or some other directory under (this repo's) source control. If it is necessary to override/modify a setting in the package itself, do it on a branch other than master to isolate personal commits from the upstream
