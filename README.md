# Z3rodaysd
# Z3RODAY IP CAMERAS
* Author: Z3RODAY SUDAN (https://frogsd.github.io)



# terminal 

### Prerequisites

You're required to install Python 3.x

```
apt-get install python3
```

You also require to have Shodan module installed

# start tool to attack
```
sudo python3 frogcamera.py -b 2 -v  --shodan API_KEY
```
# optional

attacking IP Camera. Please use it just in educational purpose!

optional arguments:
  -h, --help            show this help message and exit
  -b {1,2}, --brand {1,2}
                        Choose the brand of IP Camera. 1 represents Netwave,2
                        represents GoAhead.
  -o OUTPUTFILE, --output OUTPUTFILE
                        Output into path you input.The default path in dir
                        /tmp
  -T TIMEOUT, --timeout TIMEOUT
                        The default timout for netwave is 300s.
  -t TASKS, --task TASKS
                        Run TASKS number of connects in parallel,default is
                        10.
  -c COUNT, --count COUNT
                        The number of ip you want to get from ZoomEye.The
                        maximum is 2000. Default is 100.
  -q, --quiet           Quiet mode.
  -v, --verbose         Show more informations.
  -i IP, --ip IP        The camera's ip and port.Example: 192.168.1.100:80
  -l INPUTFILE, --list INPUTFILE
                        The camera's ip:port address file. The file's format
                        like this 192.168.1.100:81 in a line.
  --shodan SHODAN       Your Shodan API Key.You can get help from
                        https://www.shodan.io/





### Using Shodan API

This tool requires you to own an upgraded Shodan API

You may obtain one for free in [Shodan](https://shodan.io/) if you sign up using a .edu email





* thanks for use this script 
