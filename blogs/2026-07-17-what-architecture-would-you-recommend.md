---
title: "What architecture would you recommend?"
url: "https://discuss.roboflow.com/t/what-architecture-would-you-recommend/12376#post_2"
date: "2026-07-17"
author: "@Bar_Shimshon Bar Shimshon"
feed_url: "https://discuss.roboflow.com/posts.rss"
---
Hi Adriana, Good use case, and privacy-driven “keep everything local” requirements come up a lot with ID/document scanning. Both options you listed are viable, so it really comes down to your infrastructure and performance needs. Running in the browser: Roboflow has a JS/web inference SDK that can run models client-side, though depending on how it’s configured it may still call out to Roboflow’s cloud for inference rather than running fully offline in-browser.
