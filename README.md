# COMP2211 Toolchain

A Docker image containing the toolchain to cross-compile and run Xv6 for the RISC architecture

# Build
docker build . -t toolchain

# Example Usage
docker run -d -it toolchain

Then attach a shell and either mount your source code from the host machine, or clone the source directly into the container.
