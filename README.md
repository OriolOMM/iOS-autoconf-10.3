Compile UNIX libraries (using autoconf) for iOS 10.3

Instructions: Copy script(s) you need into the base folder of library where the "configure" script file is located.

You may need to rename destination folder and/or library name so that you can include multiple architectures in your Xcode project or create a fat binary.

Please note that dylib linking is not supported under iOS, Please build static libraries with autoconf

64-bit architectures not yet tested. You will need an iPhone 5S or newer to test 64-bit libraries.

Original scripts by sbooth


