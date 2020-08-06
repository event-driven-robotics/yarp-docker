# yarp-docker
Dockerfile development with YARP

Builds on the official Ubuntu Bionic Docker environment.

The code directory can be found in the container at `/usr/local/src`. Here you can find all the repositories which are already cloned with specific versions, known to be compatible with each other, built in the `build` directory available inside each repo, and installed system-wise.

The repositories being cloned are: 
* https://github.com/robotology/yarp.git
* https://github.com/robotology/ycm.git

Please refer to the [documentation](http://www.yarp.it/) of YARP for more details on usage.
