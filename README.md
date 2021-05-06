# mecanumrover

mecanumroverは四輪のメカナムホイールを搭載した全方位移動台車ロボットです。

ROSでのプログラム開発が行えるため、様々な環境・用途で使用されています。

# 実行環境

| Linux Ubuntu 16.04 LTS |                   gcc 5.4.0                    |

| Linux Ubuntu 18.04 LTS |                   gcc 5.4.0                    |

シミュレーション環境　Gazebo9

32 ビット OS での動作確認はしていないので、必要な場合はご自分で試してください。

# 実行方法

```
roslaunch mecanumrover_samples vmecanumrover_withworld.launch
```

![mecanumrover2](https://user-images.githubusercontent.com/65348333/117230128-52d4d600-ae57-11eb-85f4-c55f9f389149.png)

![mecanumrover](https://user-images.githubusercontent.com/65348333/117230046-20c37400-ae57-11eb-996b-1f62b4b67648.png)




# 使用するための事前パッケージインストール一覧(ディストリビューションがmelodicの場合)
・sudo apt install ros-melodic-gmapping

・sudo apt install ros-melodic-map-server

・sudo apt install ros-melodic-amcl

・sudo apt install ros-melodic-move-base

・sudo apt install ros-melodic-gazebo-ros

・sudo apt install ros-melodic-gazebo-ros-control 

・sudo apt install ros-melodic-ros-control

・sudo apt install ros-melodic-ros-controllers

・sudo apt-get install ros-medic-move-base-msgs

・sudo apt-get install ros-meldic-navigation
