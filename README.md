# TikTok's Research API (Google Colab)

This code queries video data with TikTok's Research API. To use this code, you must first apply and be approved for [TikTok's Research API](https://developers.tiktok.com/products/research-api/). Please note, you will need a Client Key and Client Secret to run this script.

## Query Video Data
Script: query_video_data

This script queries all videos with a given hashtag in a specified timeframe and writes the data to a CSV file. The data includes all fields offered by TikTok: creation date, username, region code, video ID, hashtags, video description, music ID, like count, comment count, share count, view count, effect ID, and video length. Please refer to TikTok's Research API documentation on [querying videos](https://developers.tiktok.com/doc/research-api-specs-query-videos/) for more information.

To run the script, insert your CLIENT KEY and CLIENT SECRET in the get_access_token function on Lines 37 and 38, respectively.
