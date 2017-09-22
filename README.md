# bazel-bullet-starter
sample bullet physics project using bazel build system using linux

##SETUP
###Install Bazel,
https://docs.bazel.build/versions/master/install-ubuntu.html

###Install Bullet Physics,
 mkdir bullet-build
 cd bullet-build
 cmake ../path/to/bullet -G "Unix Makefiles" -DINSTALL_LIBS=ON 
 make -j4
 sudo make install
 
 
## RUN
bazel run //main:main
