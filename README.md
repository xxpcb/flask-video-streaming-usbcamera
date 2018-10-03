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

然后打开浏览器，在地址栏中输入：
```python
http://localhost:666
```


## 运行效果（树莓派）

![](https://raw.githubusercontent.com/xxpcb/flask-video-streaming-usbcamera/master/result/1.jpg)

## 帖子地址
[*【树莓派3B＋测评】搭建Flask视频流媒体Web服务器*](http://bbs.eeworld.com.cn/forum.php?mod=viewthread&tid=1006103&page=1&extra=#pid2755410)

## 演示视频
[*树莓派视频流媒体Demo*](https://v.youku.com/v_show/id_XMzg0Nzk4NzE4OA==.html?spm=a2hzp.8244740.0.0)