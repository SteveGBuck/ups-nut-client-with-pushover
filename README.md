# ups-nut-client-with-pushover
My UPS NUT client monitoring configuration with push notifications using pushover

Instructions
------------

Sign up for an account with pushover.net
Make a note of your user token.
Create an application API token and make a note of it.

Copy both files to /etc/nut.
Update upssched-cmd with your user and application tokens where noted.
Ensure upssched-cmd is executable.
Ensure permissions are correctly set on files (e.g. root:nut).
