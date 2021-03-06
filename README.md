# integration-data-copy

This is a utility that copies data from production into the integration system. The app is live at [http://familysearch.github.io/integration-data-copy](http://familysearch.github.io/integration-data-copy)

Basic instructions on use are:

* Authenticate to production and integration by clicking on each "Sign In" button
* Enter a starting PID from production
* Select the types of people you want to have copied from production to integration.
* Specify the number of people to copy
* Click the "Copy" button

**Note:** The utility will copy only deceased people from the authenticated user’s ancestry with a max limit of 100 persons per copy. Memories, sources and other artifacts are not copied.

At the bottom of the page you can watch the status and progress in real time as each person is copied over. Green represents success and red represents a failure. You can browse existing bugs and report addition bugs in the issues of this project.
