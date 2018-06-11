# simple-cmake
dead simple cmake test

# ubuntu

### build
 
cd build

cmake ..

make

### run

./DisplayImage lena.jpg

# windows

add set("OpenCV_DIR" "%opencv%\\build\\x64\\vc14\\lib") to CMakeLists.txt

cd build

cmake -G "Visual Studio 14 2015 Win64" ..

msbuild DisplayImage.sln

cd debug

DisplayImage.exe ../lena.jpg
