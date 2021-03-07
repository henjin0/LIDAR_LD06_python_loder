# LIDAR_LD06_python_loder
LDROBOT社から提供されているLidarのLD06(LDS06)をpythonから使えるようにしてみました。このサンプルコードは取得した点群をリアルタイムにmatplotlibにて表示します。

# つかいかた
1. このリポジトリをcloneし、main.pyのSerial(port='/dev/tty.usbserial-0001'...を自身のポートに変更する。
2. venv環境などで`pip install -r requirements.txt`を実行し、モジュールをインストールする。
3. `python main.py`を実行する。
4. 終了するときにはEキーを押してください。

# LD06(LDS06)について
- LD06(LDS06)入手先 https://www.inno-maker.com/product/lidar-ld06/
- (データシート、SDKなど) http://wiki.inno-maker.com/display/HOMEPAGE/LD06

# ライセンス
Please see [LICENSE](https://github.com/henjin0/LIDAR_LD06_python_loder/blob/main/LICENSE).
