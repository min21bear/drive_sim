
# RO:AD 자율주행 시뮬레이션 (ros2 교육)

2025년도 국민대 대회 이전 ros2 교육과 기본기를 공부하기 위해 제작된 pkg입니다.

| os   | ros distro | simulation |
|---------|:-------:|--------:|
| ubuntu 22.04     | Humble     |gazebo11|


## install

개인 workspace/src에 `git clone` 을 사용하여 pkg를 추가 해줍니다.
```bash 
git clone
```


이후 workspace로 돌아와 `build`와 `source`를 해줍니다.
```bach
colcon build 
source install/setup.bash
```

## use guide

기본 `launch file`
```bash
ros2 launch test_sim start.launch.py
```

해당 `launch`를 한 후 발행되는 `topic`에 `msg`를 보내는 것으로 코드를 작성하시면 됩니다. 
