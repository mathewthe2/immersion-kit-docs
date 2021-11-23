# Search

Search for example sentences.

## Endpoint

`https://api.immersionkit.com/look_up_dictionary`

## Query Parameters:

Key | Type | Explanation | Default Value | Example | Notes | 
--- | --- | --- | --- | --- | --- |
keyword | string | search  |  | genki | Only first 50 characters are analyzed |
category | string | media options: *anime*, *drama*, *games*, *literature* | anime | drama | |
sort | string | options to sort: *shortness*, *longness* |  | shortness | |
tags[] | array | tagging filtering |  | Action,Studio+Ghibli | |
min_length | integer | filter results by minimum characters |  | 10 | |
max_length | integer | filter results by maximum characters |  | 50 | |
jlpt | integer | filter results by JLPT level |  | 2 | Union selection applied when used together with WaniKani filter |
wk | integer | filter results by WaniKani level |  | 31 | Union selection applied when used together with JLPT filter |

## Example Query
`HTTP GET https://api.immersionkit.com/look_up_dictionary?keyword=俺`