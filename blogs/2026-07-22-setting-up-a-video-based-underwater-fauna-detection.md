---
title: "Setting up a video-based underwater fauna detection workflow - a few questions before I commit"
url: "https://discuss.roboflow.com/t/setting-up-a-video-based-underwater-fauna-detection-workflow-a-few-questions-before-i-commit/12384#post_2"
date: "2026-07-22"
author: "@balthasar Balthasar  Huber"
feed_url: "https://discuss.roboflow.com/posts.rss"
---
Hey Marc, this sounds like a super interesting project and a great fit. On video annotation with tracking: native video annotation with persistent track IDs is something we’re actively working on, so it’s coming up. Today labeling happens on frames, so the fastest path right now is to sample frames and auto-label them (e.g.
