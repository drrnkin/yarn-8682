In the yarn and npm folders, note that the package.json files are identical,
and the lock files are equivalent (locking to 4.1.3).

In the yarn folder, run "yarn" to install.
Note that 4.1.4 is retrieved instead.
(I was using the latest of 1.x, 1.22.11).

In the npm folder, run "npm install".
Note that the lock file is respected, so 4.1.3 is installed as expected.
