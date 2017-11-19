Kod a girince (`racecar-ws` klasöründe):
```bash
source devel/setup.bash
```
Racecar ndoe larını çalıştırmak için:
```bash
roslaunch racecar teleop.launch
```
Tek başına sweep i çalıştırmak için:
```bash
roslaunch sweep_node sweep_minified.launch
```
OpenCV veya bangbang node unu çalıştırmak için:
```bash
rosrun openCV opencv.py
rosrun bangbang bangbang
```
Kod u değiştirdikten sonra tekrar build etmek için:
```bash
catkin_make
# veya 
catkin_make --pkg <paket ismi>
```
