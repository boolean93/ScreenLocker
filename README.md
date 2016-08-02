# ScreenLocker
A Screen Locker for macOS using Private API

# How to build
clang -F /System/Library/PrivateFrameworks -framework login -o lockscreen main.c

# How to use
Copy the output file to `~/bin`, and have fun.