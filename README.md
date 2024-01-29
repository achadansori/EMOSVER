./darknet detector demo data/obj.data yolov4-tiny-custom.cfg yolov4-tiny-custom_last.weights -c 0

 ./darknet detector demo data/obj.data yolov4-tiny-custom.cfg yolov4-tiny-custom_last.weights "v4l2src ! video/x-raw, framerate=30/1, width=640, height=360 ! videoconvert ! appsink" -ext_output

https://github.com/jkjung-avt/tensorrt_demos?tab=readme-ov-file#yolov4
