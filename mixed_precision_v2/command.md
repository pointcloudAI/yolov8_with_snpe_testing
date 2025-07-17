1.
~~~snpe-onnx-to-dlc --input_network yolov8s.onnx --output_path mixed_precision_dlc/yolov8_mixed_precision_v2.dlc --quantization_overrides encoding_format.encodings
~~~
2. 
~~~
snpe-dlc-quantize --input_dlc yolov8_mixed_precision_v2.dlc --override_params --output_dlc yolov8_mixed_precision_Q_v2.dlc --input_list quantization_input_list.txt --enable_htp
~~~