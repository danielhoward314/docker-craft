Here is a basic setup that leverages Docker containers to create a dev environment for Craft 3 CMS.

Steps to get started:
  1. clone the repo
  2. cd into root directory
  3. run `docker compose up` and wait while docker downloads all the dependencies

If you get an error about port being allocated try the following:
  1. find and kill any active processes on the port listed in the error
  2. a MySQL process may be running at machine startup by default on Mac
  go to System Preferences, search for mysql, press the Stop MySQL Server button
