#Create project source code
###
    git clone https://github.com/aesirteam/proxyRepeater.git
    cd ./proxyRepeater
    chmod +x genMakefiles
    ./genMakefiles mingw
    make
#Run Program
###
    ./objs/testSrslibrtmp
#Clean project
###
    make distclean
