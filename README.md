# Example MBED

Clonning the repository
```
mbed import git@github.com:alexandcote/mbed-example.git
```

Compile the project
```
cd mbed-example
mbed compile -m LPC1768 -t GCC_ARM
```

Run the script to copy the binary file on the MBED
```
./mbed_copy BUILD/LPC1768/GCC_ARM/mbed-example.bin /Volumes/MBED
```
