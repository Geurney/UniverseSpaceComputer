# CS290B Java-Cluster Course Project

Universe Space Computer system is the scale up of Space-Computer model. In our design, the system has the following two hierarchies. Universe - Space, Space - Computer. The Universe manages Spaces in a similar way as the Space manages Computers using Remote Proxy Design Pattern. By implementing coarse and fine Tasks achieve work balance among Spaces. And by implementing checkpoint at Universe and Task Tracking at Space, we achieve fault-tolerance.
