---
title: "S3 Datasource using entire bucket instead of limiting to path"
url: "https://discuss.roboflow.com/t/s3-datasource-using-entire-bucket-instead-of-limiting-to-path/12472#post_3"
date: "2026-09-10"
author: "@Addison_Grant Addison Grant"
feed_url: "https://discuss.roboflow.com/posts.rss"
---
japrescott: If you want to remove the images from your asset library/from robfolow which you don’t want, you can enable “Remove orphaned sources”. On the next run, it will remove these images and only keep the images which match your glob pattern. I assumed it would glob under the given bucket path instead of using the entire bucket with the way I input the bucket path.
