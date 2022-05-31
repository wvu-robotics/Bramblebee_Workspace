# smartag_datacollection

**WIP**

#3# Description and goals
  Collect farm and plant data using a Clearpath Robotics Husky base from various farms in and around West Virginia.
  
## Installation
  1. Clone the workspace into your src folder and run catkin_make:
  ```
  git clone https://github.com/adsarver/smartag_datacollection
  catkin_make
  ```

## How to run
  1. Navigate to the workspace src folder and run the launch_nobag.sh:
  ```
  cd ~/${YOUR_CATKIN_WS}/src
  ./launch_nobag.sh
  ```
2. In Rviz, click *Add*, go to the *By topic* tab, add *map*
3. Repeat for adding Point_Cloud2
4. Start data collection:
  ```
  ./launch_bag.sh
  ```
