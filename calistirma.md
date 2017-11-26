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
roslaunch sweep_ros sweep_minified.launch
```
OpenCV, bangbang veya collect_data node unu çalıştırmak için:
```bash
rosrun openCV opencv.py
rosrun bangbang bangbang
rosrun deep_learning collect_data.py
```
Kod u değiştirdikten sonra tekrar build etmek için:
```bash
catkin_make
# veya 
catkin_make --pkg <paket ismi>
```
