# Invisibility-cloak-opencv
A small and simple python program simulating invisibility cloak using OpenCV library

## To run: 

*Open terminal and run:*

```bash
git clone https://github.com/anuragjoshi3519/invisibility-cloak-opencv.git
cd invisibility-cloak-opencv
pip install -r requirements.txt
python3 invisibility.py
```
> **Note:**

> Default cloak color is red.

> After running the program you'll have to get out of frame for a couple of second (neccessary for the program to run as expected)

### with options: 
**Available options:**                   
- -c or --color    :  to set color of cloak to be used 
- --save           :  save video
- --output or -out :  specify path to directory for saving video (if --save mentioned)

```bash
python3 invisibility.py -c <color_name> --save -out path/to/directory
```
<color_name> can be chosen from 'red' , 'green' , or 'blue'

**Example:**

> Using Green color and saving to videos folder in same directory
```bash
python3 invisibility.py -c green --save
```

> Using Blue color and saving the video to 'Downloads' directory
```bash
python3 invisibility.py -c blue --save -out /home/your_user_name/Downloads
```
