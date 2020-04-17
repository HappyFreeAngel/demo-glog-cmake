#这是个简单的验证如何在C++项目中使用谷歌glog日志框架的，最小原型验证。
项目管理采用的是CMake

前提条件:系统上已经安装了git和cmake3.0以上版本
1.先安装glog

git clone https://github.com/google/glog.git
cd glog
./autogen.sh
./configure
make
sudo make install

2.克隆本项目到本地
git clone https://github.com/HappyFreeAngel/demo-glog-cmake.git

cd demo-glog-cmake
mkdir build;cd build; cmake ..;cmake --build .;

#测试 
./demo01

