# time-sort-tar
Sort data by month into tarballs using time metadata.

# Install
sudo cp time-sort-tar /usr/local/bin/

sudo chmod +x /usr/local/bin/time-sort-tar

sudo ln -sf /usr/local/bin/time-sort-tar /usr/local/bin/tst

sudo chmod +x /usr/local/bin/tst

sudo cp decade-sort /usr/local/bin/decade-sort

sudo chmod +x /usr/local/bin/decade-sort

# Usage

cd /place/to/sort

tst Nov-1999


# Sort a decade worth of stuff, from 2010 to 2020.

decade-sort




# Both time-sort-tar (tst) an decade-sort are recursive and operating in the $pwd
# so cd into the place where you need to sort down from...

cd /var/myapp/logs

tst Jun-2019

# That will get all files within /var/myapp/logs that have the "changed" file metadata from June 2019.
