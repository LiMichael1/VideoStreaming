# VideoStreaming
Members:  
Dave Patsy  
Michael Li  
  
First, start the server with the command  
    "python Server.py 1024"  
where server_port is the port your server listens to for incoming RTSP connections. The standard RTSP
port is 554, but you will need to choose a port number greater than 1024.  
  
Then, start the client with the command  
    "python ClientLauncher.py 127.0.0.1 1024 1025 movie.Mjpeg"  
where server_host is the name of the machine where the server is running, server_port is the port where
the server is listening on, RTP_port is the port where the RTP packets are received, and video_file is the
name of the video file you want to request (we have provided one example file movie.Mjpeg). The file
format is described in Appendix section.

