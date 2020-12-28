# Home Service Robot
Have you ever dreamed of a robot bringing your morning coffee ☕ to your bedroom without you havig to leave the site?

In this project, I´m building a robot which uses SLAM to move objects from one place of the house to another.

To speed up the process of building the robot, I am using a robot simulator called [Gazebo](http://gazebosim.org/)

## Try it yourself
1. Clone this repository:
- Using SSH:
```git clone git@github.com:aaronespasa/home-service-robot.git```
- Using HTTPS:
```https://github.com/aaronespasa/home-service-robot.git```
2. Install the required dependencies (Ubuntu commands):

Install **Gazebo**:

```$ sudo sh -c 'echo "deb http://packages.osrfoundation.org/gazebo/ubuntu-stable `lsb_release -cs` main" > /etc/apt/sources.list.d/gazebo-stable.list'```

```$ wget https://packages.osrfoundation.org/gazebo.key -O - | sudo apt-key add -```

```$ sudo apt-get update```

```$ sudo apt-get install gazebo11 && sudo apt-get install libgazebo11-dev```

Install the C++ compiler (**g++**):
```$ sudo apt-get install g++```

3. (Optional) If you want to make changes:

Install **CMake**:

```$ sudo apt-get install cmake```

Create a folder called **build** inside of the main folder of the repository you cloned: `mkdir build`.

Navigate to that folder: `cd ./build`.

And run the following commands:

```$ cmake ../```

```$ make```

4. Now, you can execute the program by going to the world folder and running:
```$ gazebo myworld```

## Components
### World
### Models
### Plugins


#### Made with ❤️ by Aarón Espasandín
