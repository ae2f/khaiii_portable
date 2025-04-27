# Update
- Docker dedication has removed.
- Locale dedication has removed.
- Hunter package manager has removed.

# What you need
> Since docker has removed, you need to install some of the 3rd-party dependency manually.  
> This is the list of them for you.

- cmake, and compiler (gcc, clang, ...), and linker (make, ninja, ...)

# Dependent 3rd party libraries
## Will automatical be installed
> Will automatically be imported if possible.  
> is tested on Arch Linux.  
> For renewing them you will need to delete the cache by removing the build directory, whereever you've set. (Normally it's `out` or `build` or `Build`-like)  
- Threads
- cxxopts
- fmt

## Libraries which Manual Handling required
> In cmake, some libraries are not allowing in-source builds.  
> You will install them manually.
- Eigen3
- Boost
- GTest

## Not sure currently
> You probably have to install them.  

- nlohmann_json
- spdlog