# compile-python
This is a repo for compiling and installing python from scratch.


## Compile Python and Create VirtualEnv with it

'sudo apt-get install build-essential gdb lcov libbz2-dev libffi-dev libgdbm-dev liblzma-dev libncurses5-dev libreadline-dev libsqlite3-dev lzma lzma-dev tk-dev uuid-dev zlib1g-dev'

'wget https://www.python.org/ftp/python/3.10.13/Python-3.10.13.tgz'

'tar zxvf Python-3.10.13.tgz'

./configure --enable-optimization

make -j 16

sudo make altinstall