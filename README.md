# ImageClassification
# Equipment Requirements
* Jetson Nano 2GB
* Python 3.6.9
* Jetcam
* PyTorch 1.8.0 or 1.9.0
* CUDA 10.2
* Torchvision
* JetPack 4.6
# References
* [Getting Started with AI on Jetson Nano](https://ithelp.ithome.com.tw/m/articles/10297084)
* [chu24/Jetson-Nano-2G](https://github.com/chu24/Jetson-Nano-2G)
* [DLI(Deep Learning Institute)](https://courses.nvidia.com/courses/course-v1:DLI+S-RX-02+V2/)
# Pre-Processing
1. Install the corresponding kit
  ```
  sudo apt-get install nvidia-container-toolkit nvidia-container-runtime nvidia-container-csv-*
  ```
2. Reinstall the specified version of docker
   ```
   wget https://launchpad.net/ubuntu/+source/docker.io/20.10.2-0ubuntu1~18.04.2/+build/21335731/+files/docker.io_20.10.2-0ubuntu1~18.04.2_arm64.deb
   sudo dpkg -i docker.io_20.10.2-0ubuntu1~18.04.2_arm64.deb
   rm docker.io_20.10.2-0ubuntu1~18.04.2_arm64.deb
   sudo apt-get install containerd
   ```
