Download raylib and set makefile cflag and ldflags  
You can use suitable raylib lib for your system  

<img width="520" height="520" alt="图片" src="https://github.com/user-attachments/assets/4ed11961-4e5a-4881-abdd-36f33d18934c" />


Default debug build and run
>make run  
make run ARGS="input.txt --verbose"

Build tests only
>make test  
make test MODE=release

Compile + run tests
>make test-run  
make test-run ARGS="--verbose"

Shortcut for release build
>make release  
make run MODE=release  
make test-run MODE=release

Custom main is foo.qk
>make run MAIN=foo 

