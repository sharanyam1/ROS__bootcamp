# ROS__bootcamp
Repository that talks about all basic features of ROS as a part of the ROS bootcamp 

  Q1.What is ROS? Name its merits and limitations for roboticists?

Ans .    It is a META operating system which provides services like hardware abstraction, low-level device control, implementation of commonly-used functionality,message-passing between processes, and package management .

Merits of ROS :

- Allows flexibility for code written in ROS to be run in other robotics software frameworks.

- Allows you to adopt the code written by other developers for your project.

- Allows easier management of complicated multi-board robots .

- Most commercial sensors and actuators have ROS drivers.

Limitations of ROS :

- Powerful hardware required to run ROS on your robot .

- Not useful when developing novel applications where reusing of packages is not preferred , and thus requires lots of time-consuming modifications.

- Not a real-time system .

- Security issues for industrial development scenario.

Q2.Define the basic ROS terminologies.

Ans.

-   Workspace : It is the collection of different packages .

-    ROS packages : They are the main organizational software units of ROS which contains nodes ,libraries ,datasets.

-  Nodes : Nodes are the processes that perform computation. 

-  Topics :Channels through which messages are passed . It is the name given to identify the contents of the messages being passed.

-  Messages : Nodes communicate with each other by passing messages. It is just a data-structure .

-  Services : Enables request/reply interactions in distributed systems.
