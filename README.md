# obe-build-environment
Building the OBE environment from KL repos. The build script clones tip for
all of the major repos required and builds OBE in a self-contained
'target-root' directory, along with avconf/ffmpeg and any other project
dependencies.

Tested on CentOS 7.2.1511 only.

Manually, make sure you yum install any packages described at the start of the build script,
see build.sh yum commands.

# Any dependencies are automatically downloaded during the build process.
$ git clone https://github.com/stoth68000/obe-build-environment build
$ cd build
$ ./build.sh experimental
$ ./target-root/usr/local/bin/obecli 

Open Broadcast Encoder command line interface.
Including Kernel Labs fixups.
Version 1.3

obecli> quit

