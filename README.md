# obe-build-environment
Building the OBE environment from KL repos. The build script clones tip for
all of the major repos required and builds OBE in a self-contained
'target-root' directory, along with avconf/ffmpeg and any other project
dependencies.

Tested on CentOS 7.2.1511 only.

Manually, make sure you yum install any packages described at the start of the build script.
