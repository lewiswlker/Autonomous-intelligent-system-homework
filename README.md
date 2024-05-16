# teb_local_planner_tutorials

teb_local_planner codeAPI 及 参数含义 [teb_local_planner](http://wiki.ros.org/teb_local_planner) tutorials.

**Dependencies:**

- _ros-noetic_： `sudo apt install ros-noetic-desktop-full`
- _navigation stack_： `sudo apt install ros-noetic-navigation`
- _teb_local_planner_： `sudo apt install ros-noetic-teb-local-planner`

**Build:**

把 course.tar.gz 在主目录下,打开终端：

    unzip homework.zip
    cd homework/src
    catkin_init_workspace
    cd ..
    catkin_make
    gedit ~/.bashrc
    source ~/homework/devel/setup.bash

**Run:**

    roslaunch homework run.launch

**Modification:**

- 修改`src\config`中的`yaml`文件参数，改进 teb_local_planner 的效果
- 使用其他算法替换 teb_local_planner，如`dwa_local_planner`，`eband_local_planner`
