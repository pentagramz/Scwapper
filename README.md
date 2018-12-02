# Scwapper

Scwapper - the iOS screens swapper.

This tool aids with black-box iOS applications security assesments and enables you to:
1. Enumerate the running application's view controllers, and
2. Load a desired view controller.

Scwapper works with applications using storyboards and it's stregth is based on grouping the view controllers according to storyboards to provide a context for each of the displayed view controllers.

This is helpful for:

Recon,
Bypassing client-side restrictions,
Bypassing JB detection screens,
Finding hidden screens and components.

Prerequisites: Jailbroken iPhone, Cycript

Usage: scwapper_script.sh app_process

Scwapper should be run from the application's directory in the device. Thus, it is recommended to copy scwapper to a /bin directory and run it from the app's directory. Please also consider file permissions in the case of any errors.
