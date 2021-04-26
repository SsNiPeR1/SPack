################################
[Documentation for SPack]
SPack is fully free, open-source project that aims to provide some packages to end users.
To install SPack, run "./install", then all needed files will be installed and you can run all packaging tools.
To create own package, run "createimg". You need to supply some package, for example, my command looks like "createimg helloworld.sh".
This will create a "program.mnt" package.
You can rename that package as you want, with extension too.
To install a package, run "installimg" There is 3 arguments:
							<image filename> program.mnt or something
							<executable name> this is how you will run that package
							<-l> IMPORTANT: this is OPTIONAL!! This installs the package in current working directory.
You can always remove packages with "sudo rm -rf /usr/bin/<packagename you supplied in <executable name>>"
