---
title: "Corrupted SAM3 model package: missing sam_configuration.json"
url: "https://discuss.roboflow.com/t/corrupted-sam3-model-package-missing-sam-configuration-json/12367#post_2"
date: "2026-07-21"
author: "@Grzegorz Grzegorz"
feed_url: "https://discuss.roboflow.com/posts.rss"
---
Hi @wrayjacksonr , Can you check your dataset masks? I suspect you have some box-only annotations in your dataset - this would explain why training job failed Thanks! Grzegorz
