MD5VerificationSystem By Alex Free

MD5VS makes it easy to verify the integrety of all files recursively in a specfied directory. MD5VS is very portable, it can use the BSD MD5 which comes with Mac OS X by default or the GNU MD5SUM which is on Linux and other systems, which is detected automatically.

Example:

Use the command:

./md5vs -c "/path/to/some/directoy"

This will create a file "/path/to/some/directory/md5sum.txt" which contains the md5sums of all files within "/path/to/some/directory" recursively.

Use the command:

./md5vs -v "/path/to/some/directory"

This will verify that the md5sums in all of the files within "/path/to/some/directory" recursively match what was previously recorded in the file "/path/to/some/directory/md5sum.txt" with the previous command: ./md5sum -c "/path/to/some/directory"

MD5VS is released into the public domain, see the file 'unlicense.txt'.
