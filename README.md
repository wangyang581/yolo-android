## Basic environment

python == 3.10.14

cuda == 12.0

torch == 2.1.1+cu121

torchaudio == 2.1.1+cu121

torchvision == 0.16.1+cu121

ultralytics  == 8.2.101

tf_keras  == 2.17.0

tflite-support == 0.4.4

tifffile ==  2024.7.24

## Folder contents

The assets folder contains tflite files converted using the YOLOV8 project and corresponding tag txt files

The result folder contains the inference results of the same image using the same model on different platforms. The result_comuter is the result of using YOLOV8 to load best_float32.tflite inference cls_person_2. jpg on the computer
Result_phone.jpg is the result of inferring cls_person_2. jpg on a computer or Android phone

The release folder contains the apk installation package built using the best_float32.tflite model

The weights folder contains YOLOV8 trained PT files and converted files in other formats
