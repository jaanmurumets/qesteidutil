# ID-card utility

 * License: LGPL 2.1
 * &copy; Estonian Information System Authority

## Building
[![Build Status](https://travis-ci.org/open-eid/qesteidutil.svg?branch=master)](https://travis-ci.org/open-eid/qesteidutil)
[![Coverity Scan Build Status](https://scan.coverity.com/projects/737/badge.svg)](https://scan.coverity.com/projects/737)

### Ubuntu

1. Install dependencies

        sudo apt-get install cmake qttools5-dev qttools5-dev-tools libpcsclite-dev libssl-dev

2. Fetch the source

        git clone --recursive https://github.com/open-eid/qesteidutil
        cd qesteidutil

3. Configure

        mkdir build
        cd build
        cmake ..

4. Build

        make

5. Install

        sudo make install

6. Execute

        /usr/local/bin/qesteidutil
        
### OSX

1. Install dependencies from [http://www.cmake.org](http://www.cmake.org) and [http://qt-project.org](http://qt-project.org)


2. Fetch the source

        git clone --recursive https://github.com/open-eid/qesteidutil
        cd qesteidutil

3. Configure

        mkdir build
        cd build
        cmake -DQTSDK="~/Qt/5.3/clang_64" ..

4. Build

        make

5. Install

        sudo make install

6. Execute

        open /usr/local/bin/qesteidutil.app

## Support
Official builds are provided through official distribution point [installer.id.ee](https://installer.id.ee). If you want support, you need to be using official builds.

Source code is provided on "as is" terms with no warranty (see license for more information). Do not file Github issues with generic support requests.
