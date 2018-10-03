# Flask实现视频流媒体

[*参考1*](https://github.com/Mjrovai/Video-Streaming-with-Flask/tree/master/camWebServer)
[*参考2*](https://github.com/miguelgrinberg/flask-video-streaming)

在win10和树莓派3B+上测试通过，win10测试python3，树莓派测试python2。
摄像头使用USB摄像头。

## 项目结构

* app.py
* base_camera.py
* camera_opencv.py
* static
  * style.css
  * logo.png
* templates
  * index.html 

## 安装依赖库

```python
# via pip
sudo pip(2) install flask
```

## 运行

```python
python app.py
```

## 运行效果（树莓派）

![](https://github.com/Mjrovai/Video-Streaming-with-Flask/tree/master/camWebServer/result/1.jpg)

