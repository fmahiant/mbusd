# mbusd
Tool to build mbusd following embedded-CI tuto

Build it with docker

   - mkdir mbusd/output.dir/
   - docker run -it --rm -v${PWD}:/project -w /project/mbusd/output.dir ghcr.io/fmahiant/modbus-gateway-sdk:latest "-c" "cmake -DCMAKE_BUILD_TYPE=Release -DCMAKE_TOOLCHAIN_FILE=../../arm_linux_gnueabihf-docker.cmake ../ && make "
 

Integrate docker in vscode:
