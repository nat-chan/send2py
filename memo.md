#screen-sixelをインストール
```bash
sudo apt install -y libncurses5-dev #絶対必要
git clone http://bitbucket.org/arakiken/screen/get/sixel.tar.gz
tar xzvf sixel.tar.gz
cd arakiken-screen-f6d67e586a3e
./configure
make
sudo make install
```
#mltermをインストール
```bash
sudo apt install -y xdev-org #xlib.hがないとき
wget http://sourceforge.net/projects/mlterm/files/01release/mlterm-3.7.2/mlterm-3.7.2.tar.gz
tar xzvf mlterm-3.7.2.tar.gz
cd mlterm-3.7.2
./configure
make
sudo make install
```
#libsixelをインストール
```bash
git clone https://github.com/saitoha/libsixel.git
cd libsixel
./configure --enable-colors256
make
sudo make install
```
