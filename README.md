# Program-assignment-1

Each directory contains four files:

xxx.mp4:    mp4 video with ground-truth (red) and predicted (blue, by "some" algorithm) bounding boxes overlay. IoU is displayed at the upper-left corner.

frames.tar: archive of all images in the video, image names start from 0 (0.jpg, 1.jpg, etc.)

jhead.txt:  contains a single line like this "Resolution   : 480 x 360", where 480 is the width and 360 is the height of the video frames
            NOTE: this information is also there when you read any images with OpenCV and check the image dimension
            
xxx.txt:    The ground-truth bounding box information, with as many lines as the number of images in frames.tar.
