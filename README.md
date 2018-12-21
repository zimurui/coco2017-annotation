# coco2017-annotation
COCO2017 annotations
I parsed the coco2017 train datset, and find that there are 117266 images with bounding box.
the format of annotation.txt is:
  filename1 x1min,y1min,x1max,y1max,cls1_id x2min,y2min,x2max,y2max,cls2_id ....
  filename2 .......
  
  the xmin,ymin,xmax,ymax is absolute coordinate in original image
  the cls_id is between 0 and 79, corresponding to the cls.txt
