# DowngradeSSLLibCurl
While working on reverse engineering of some executables traffic which uses libCurl ( https://curl.se/libcurl/ ), 
we need to to capture the SSL Traffic. It may have extra SSL verification to bypass, 
so we can downgrade the SSL verify level of the executable by patching the executable with GHidra, Cutter or IDAPro. 
Here is the sample downgrade of related part of an executable.

How to patch with Ghidra (https://materials.rangeforce.com/tutorial/2020/04/12/Patching-Binaries/)
