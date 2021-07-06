# youtube-comment-downloader
## Programmatic API
```
from youtube_comment_downloader import download_comments, SORT_BY_POPULAR, SORT_BY_RECENT

for comment in download_comments(youtube_id, SORT_BY_POPULAR):
    print(comment)
```
## Installation
`pip install git+https://github.com/Haroon96/youtube-comment-downloader`
