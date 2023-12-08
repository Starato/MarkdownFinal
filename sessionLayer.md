# **Session Layer**

Summary: Maintains connection and responsible for controlling ports and sessions

The session layer creates communication channels aka sessions, between devices. Opening sessions and making sure they stay open and working correctly while information is being transferred and closing it when it ends is the job of this layer. This layer also sets up checkpoints throughout the transfer so that if the session is interrrupted, the device can resume data transfer from the last checkpoint.

![Session Layer](https://mplsnet.files.wordpress.com/2014/07/49-transport-layer-services2.jpg)
