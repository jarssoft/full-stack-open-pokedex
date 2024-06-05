Graphical updates for old Wolfenstein 3D -game coded in C/ASM.

linting: Linting is coming from C-programming from 1978. Modern compilers includes many of lint's functions. Also because C is statically typed language there is errors in compiler time already. Any how there is the splint for find out security vulnerabilities and coding mistakes in C programcode. (https://en.wikipedia.org/wiki/Splint_(programming_tool)) GCC has analyzer itself, and it can be used with -fanalyzer flag.

testing: There is many automated test software for C. CuTest (https://cutest.sourceforge.net/) looks very simply one. Also Minunit is very easy to  use. https://jera.com/techinfo/jtns/jtn002

building: BORLAND C++ 3.0/3.1 and GCC. Borland C++ compiler comes with BC.EXE, that can compile orginal source files to DOS binary file.

Alternatives for Jenkins and Github are CruiseControl and Hudson. Both are written in Java and runs on server.

I think there is a good reason use Github Actions for C/C++ project, because it is quite common environment. There is arcticles how to setup GitHub for C++ and CMAKE, and they says the benefits for use GitHub are migration and capabilities. At otherhand if we are using old Borland compiler then there may be needs to more spesific setup.

https://www.incredibuild.com/blog/using-github-actions-with-your-c-project
