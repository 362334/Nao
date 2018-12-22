# Nao机器人程序

黄杆识别演示地址:https://www.bilibili.com/video/av36980274

#### Nao高尔夫最后一关.py
Nao机器人高尔夫击球程序第三关，注意修改木杆的长度和mark的半径。

#### SVM物体识别.py
SVM图片识别程序，使用的是OpenCV中自带的机器学习功能。  

#### 多进程的红球识别功能.py  
多进程可能大量缩短程序的执行的时间，但是，可能造成机器人不稳定，注意，此处使用的是多进程，而不是多线程，因为Nao有两个CPU，所以多进程的速度比多线程更快。  

#### 机器人倒地处理程序.py
它会不断的去检测Nao机器是否摔倒，然后去停止Nao机器人的Python脚本。当Nao机器人站起来以后，但又可以使脚本继续运行。  

#### 黄杆识别.py
主要运用的是OpenCV，之所以使用的是旋转矩形，是因为，Nao机器的头部旋转，可能会导致画面倾斜，而旋转矩形可以处理这个问题。

#### License  
> Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0 Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

#### 前方高能  

![](https://github.com/bitbitluo/Nao/blob/master/img/naos.jpg)

