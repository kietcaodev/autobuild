# autobuild
autobuild asterisk 18 * 16

sudo yum -y install wget
cd /tmp
wget https://raw.githubusercontent.com/kietcaodev/autobuild/main/build.sh
chmod +x build.sh
sh build.sh
