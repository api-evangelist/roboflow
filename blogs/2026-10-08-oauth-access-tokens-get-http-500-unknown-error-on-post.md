---
title: "OAuth access tokens get HTTP 500 \"Unknown error\" on POST /dataset/{project}/upload"
url: "https://discuss.roboflow.com/t/oauth-access-tokens-get-http-500-unknown-error-on-post-dataset-project-upload/12552#post_1"
date: "2026-10-08"
author: "@pnewell4 Patrick Newell"
feed_url: "https://discuss.roboflow.com/posts.rss"
---
I’m building a native iOS app that authenticates with Roboflow OAuth (PKCE public client, rfoa_ access tokens). Reads, model downloads, and /{workspace}/{project}/upload/zip all accept the token, but the single-image upload endpoint crashes: curl -X POST -H 'Authorization: Bearer rfoa_x' https://api.roboflow.com/dataset/p/upload returns HTTP 500 {"error":"Unknown error"} for any rfoa_ token (valid or fake), whatever the body: base64, multipart, or image= URL. The same token passed as ?api_key= does the same thing.
