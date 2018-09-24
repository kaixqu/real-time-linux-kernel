# real-time linux kernel

This work is done at the TREC lab under the supervision of Prof. Alexander Leonessa

Basically, it is about make linux kernel real-time. This is a requirement if you want to have real-time applications, e.g., ROS2, ROS+Orocos, ihmc ROBOTICS, XBotCore.

## How to use these files.

1. Read "Real-time implementation for humanoid robots.pdf" first. There are some concepts about real-time for everyone, and some linux concepts mainly focused on ME students. You can skip the part you already know.

When you are going to install real-time linux kernel, go to [installation_guide](https://github.com/qkx515/real-time-linux-kernel/tree/master/installation_guide) folder.

2. 
    -> install *lowlatency kernel*

    -> install *rt         kenel*
    
    -> you really don't need to install *xenomai kernel*. But, still, you can do that if you want.
    
    After successfully installed a real-time kernel, you can test their performance. 

3. Move to the **test_files** folder and please read **README.md**

