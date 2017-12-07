This is repository from Alexey branch. Adding test dir functions for massive detection <br>
**the current commands for darknet testing a single image is **<br>
darknet.exe detector test     _data _cfg _weights images.JPEG

**I create similar function and commonds for darknet testing images in one directory. And write detection bounding box to txt file**<br>
darknet.exe detector test_dir _data _cfg _weights input_dir  output_dir   detecion_txt_path

 
