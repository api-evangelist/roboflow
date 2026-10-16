---
title: "Low latency video streaming for real time computer vision"
url: "https://discuss.roboflow.com/t/low-latency-video-streaming-for-real-time-computer-vision/12542#post_3"
date: "2026-10-06"
author: "@llwyd"
feed_url: "https://discuss.roboflow.com/posts.rss"
---
I’ve played around with Luxonis’ OAK cameras for real time streaming (stream can be displayed in a browser too with WebRTC) and they have some examples of integrating with roboflow workflows . You can do inference right on the camera, and now that doing local inference costs no credits it may be more economically viable if you chose to use the local roboflow inference server. I didn’t use their inference server because I needed total offline access.
