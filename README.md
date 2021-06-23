Cài đặt các thư viện cần thiết ở file requirements.txt
## Huấn luyện mô hình 

Sử dụng file train.py để huấn luyện mô hình. Truyền vào các tham số đã được tạo cờ (flag) như data, batchsize, numofepochs, optimizer,vvvv...
Ví dụ file runtrain.sh

## Kiểm tra mô hình

Sử dụng file test.py để kiểm tra mAP trên tập dữ liệu kiểm tra
Ví dụ file runtest.sh

## Mô hình đã huấn luyện

Mô hình yolov3-spp đã huấn luyện nằm trong folder runs/train/exp7. Bao gồm file tensorboard để xem đồ thị huấn luyện và checkpoint nằm trong folder weights.
Mô hình yolov3 đã huấn luyện nằm trong folder runs/train/exp8.

## Phát hiện trên ảnh/video thực tế 

Sử dụng file detect.py để phát hiện trên hình ảnh và video thực tế.



## Citation

[![DOI](https://zenodo.org/badge/146165888.svg)](https://zenodo.org/badge/latestdoi/146165888)


## About Author

Ultralytics is a U.S.-based particle physics and AI startup with over 6 years of expertise supporting government, academic and business clients. We offer a wide range of vision AI services, spanning from simple expert advice up to delivery of fully customized, end-to-end production solutions, including:
- **Cloud-based AI** systems operating on **hundreds of HD video streams in realtime.**
- **Edge AI** integrated into custom iOS and Android apps for realtime **30 FPS video inference.**
- **Custom data training**, hyperparameter evolution, and model exportation to any destination.