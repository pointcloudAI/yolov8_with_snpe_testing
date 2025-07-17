# yolov8_with_snpe_testing

# mixed_precision
Using encoding_format.encodings from [Model-Accuracy-Mixed-Precision](https://github.com/quic/qidk/blob/master/Model-Enablement/Model-Accuracy-Mixed-Precision/Accuracy_Analyzer_YoloV8.ipynb) 

# mixed_precision_v2
Using encoding_format.encodings by new value from python code which value from without_mixed_precision_int8/yolov8s_quantized.dlc 

# Error code

mixed_precision and mixed_precision_v2 run with --usr_dsp will get below error message:

` error_code=1002; error_message=Layer parameter value is invalid. No backend could validate Op=/model.22/Sigmoid Type=ElementWiseNeuron error code=3110; error_component=Model Validation; line_no=156; 
`    