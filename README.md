# p2 Repository for Eclipse CheckStyle v8.12.0

[Eclipse CheckStyle][eclipse-cs] used to host its p2 repos on [Bintray](https://bintray.com/), but that service [is not available anymore][bintray-eol].

The project has now moved to a new URL, <http://checkstyle.org/eclipse-cs-update-site/>, but that repo only contains recent versions (starting from v8.41). See [the GitHub Issue][gh-issue] for more details.

For projects which are stuck on older versions, there is no simple recourse.
In our case, [Eclipse Sirius][sirius] is still using a CheckStyle configuration from the very old CheckStyle 8.12, hence this project to make the corresponding p2 repo for that specific version available more easily (until we migrate to a more recent version).

[eclipse-cs]: https://checkstyle.org/eclipse-cs/
[bintray-eol]: https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/
[gh-issue]: https://github.com/checkstyle/eclipse-cs/issues/279
[sirius]: https://www.eclipse.org/sirius
