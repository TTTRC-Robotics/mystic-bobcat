# mystic-bobcat
Morning Evaluation Bobcat

Welcome to the morning Module

Today we will do the morning menu as a Github repository!

First you will need to clone this repository into your workspace folder.

Second you should realise the tasks below

Third when you are finished, write a feed back on the already opened Pull Request and merge it!

Have Fun!!

# Tasks

## Explain me the bashrc

I would like you to open the open Pull Request and to explain me in you word what does the .bashrc do.

If needed you can have a look at it again
```
cat ~/.bashrc
nano ~/.bashrc
```

1. What line should you add to it to automatically be able to call the program ros2 in any terminal?
1. What can/should you do to reload the .bashrc file?

```
$ ros2
usage: ros2 [-h] [--use-python-default-buffering]
            Call `ros2 <command> -h` for more detailed
            usage. ...

ros2 is an extensible command-line tool for ROS 2.

options:
  -h, --help            show this help message and exit
  --use-python-default-buffering
                        Do not force line buffering in
                        stdout and instead use the python
                        default buffering, which might be
                        affected by PYTHONUNBUFFERED/-u
                        and depends on whatever stdout is
                        interactive or not

Commands:
  action     Various action related sub-commands
  bag        Various rosbag related sub-commands
  component  Various component related sub-commands
  daemon     Various daemon related sub-commands
  doctor     Check ROS setup and other potential issues
  interface  Show information about ROS interfaces
  launch     Run a launch file
  lifecycle  Various lifecycle related sub-commands
  multicast  Various multicast related sub-commands
  node       Various node related sub-commands
  param      Various param related sub-commands
  pkg        Various package related sub-commands
  run        Run a package specific executable
  security   Various security related sub-commands
  service    Various service related sub-commands
  topic      Various topic related sub-commands
  wtf        Use `wtf` as alias to `doctor`

  Call `ros2 <command> -h` for more detailed usage.
```

## Use the bashrc

Create an issue.

Title : Bashrc

1. make a screenshot of your terminal. 
1. Disable sexy-bash-prompt in you terminal. 
1. Reload the bashrc
1. make another screenshot of you terminal

Add all the sreenshots in the issue

## Turtlesim

Create an issue.

Title : Turtlesim

In the issue I want you to put a screenshot after each of the following task.

1. Move the turtle anywhere (The turtle should just have moved)
1. Create a turtle named bobcat
1. Move the second turtle