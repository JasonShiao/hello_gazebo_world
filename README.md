# Hello Gazebo world

Udacity VM Setup
```
sudo apt-get update && sudo apt-get upgrade -y 
```

Launch Gazebo
```
gazebo

# which is equivalent to
#gzserver
# then
#gzclient
```

Build plugin
```
# only once
cmake -B build -S .
# rebuild
cmake --build build
```

