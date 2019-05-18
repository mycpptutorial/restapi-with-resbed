# the minimum version of CMake required
cmake_minimum_required(VERSION 2.8)

# required modules for our task
include(CheckIncludeFile)
include(CheckIncludeFileCXX)
include(CheckIncludeFiles)

# we add the files in the include
# directory to be included while
# compiling
# all the source code
include_directories(/Users/nkabiliravi/git/restbed/distribution/include/)


set(RESBED_LIBS /Users/nkabiliravi/git/restbed/build/CMakeFiles/restbed-static.dir/source/corvusoft/restbed/)
set(RESBED_IMPL_LIBS /Users/nkabiliravi/git/restbed/build/CMakeFiles/restbed-static.dir/source/corvusoft/restbed/detail)

# we add the
# sub-directories that
# we want CMake to
# scan
#add_subdirectory(include)
add_subdirectory(src)
