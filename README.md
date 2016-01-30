# 9API

### Resource URL
- http://quit0.eu/9api/section/page

## Parameters

Parameter                 | Description
------------------------- | -----------
**section** *required* | Section of the page (hot,fresh,funny, etc.)
**id** optional | pageID where to get the data from.
# Example request

- http://quit0.eu/9api/funny

## Result
```
{
    "nextPageUrl":"a8M377e%2CaBY071O%2Ca8M3x83&c=10"
    {
        "posts":[
            {
                "isVideo":"true",
                "title":"Best gif I saw in my life",
                "pageLink":"\/gag\/aW6YXPK?sc=funny",
            "voting":
            {
                "like":"http:\/\/9gag.com\/vote\/like\/id\/aW6YXPK?sc=funny",
                "unlike":"http:\/\/9gag.com\/vote\/unlike\/id\/aW6YXPK?sc=funny",
                "dislike":"http:\/\/9gag.com\/vote\/dislike\/id\/aW6YXPK?sc=funny"
            },
            "media":
            {
                "image":
                    {
                        "src":"http:\/\/img-9gag-fun.9cache.com\/photo\/aW6YXPK_460s.jpg",
                        "alt":"Best gif I saw in my life"},
                "video":
                {
                    "mp4":"http:\/\/img-9gag-fun.9cache.com\/photo\/aW6YXPK_460sv.mp4",
                    "webm":"http:\/\/img-9gag-fun.9cache.com\/photo\/aW6YXPK_460svwm.webm"}
                },
                "comments":"37",
                "loveCount":"1,491"
            }
}
```
## Get section list
To get all the section from 9GAG use:
- api/section/list/true
