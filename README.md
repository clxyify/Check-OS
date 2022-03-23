# Check-OS

Checks your **operating system** host edition.

# List
Windows 64 bit	_WIN64	Only for 64 bit Windows

Apple	__APPLE__	for all Apple OS

Apple	__MACH__	alternative to above

iOS embedded	TARGET_OS_EMBEDDED	include TargetConditionals.h

iOS stimulator	TARGET_IPHONE_SIMULATOR	include TargetConditionals.h

iPhone	TARGET_OS_IPHONE	include TargetConditionals.h

MacOS	TARGET_OS_MAC	include TargetConditionals.h

Android	__ANDROID__	subset of linux

Unix based OS	__unix__	

Linux	__linux__	subset of unix

POSIX based	_POSIX_VERSION	Windows with Cygwin

Solaris	__sun	

HP UX	__hpux	

BSD	BSD	all BSD flavors

Custom OS will not work because you need a function in your OS to be detected.
