---
title: How To Use
---

## Full example

By executing a CURL command like so:

```javascript
curl -d '{"url":"http://www.mirror.co.uk/3am/celebrity-news/daniel-craig-offered-150million-play-8771972"}' -H "x-api-key: 4pUWfv3247v19fOK7I96gDH4RhjCjoIfjg7GFASFASF" -X POST https://api.sugges.tv
```

You should be getting a response, like so:

```javascript
{
  "results": {
    "status": {
      "timems": 8,
      "rid": "4fWevpQr86dMCpMfhQ=="
    },
    "hits": {
      "found": 144,
      "start": 0,
      "hit": [
        {
          "id": "418751",
          "fields": {
            "production_year": [
              "2016"
            ],
            "thumbnails_large_height": [
              "720"
            ],
            "content_provider_id": [
              "418751"
            ],
            "content_provider": [
              "Wibbitz"
            ],
            "videos_watermarked_uri": [
              "https://s3.amazonaws.com/egamitv-videos/videoelephant/18e1a9d6-7024-4b98-bb3b-91730b83004b/6db41bf9ddda4204c023c38caf7bb534.mp4"
            ],
            "duration": [
              "32"
            ],
            "id": [
              "18e1a9d6-7024-4b98-bb3b-91730b83004b"
            ],
            "videos_watermarked_definition": [
              "SD"
            ],
            "title": [
              "Who's going to be the next James Bond?"
            ],
            "videos_watermarked_filetype": [
              "MP4"
            ],
            "descriptions_long": [
              "The actor chosen to play the next James Bond will be an unexpected candidate, the franchise’s outgoing director has said, suggesting favourite Tom Hiddleston may not land the 007 role. The British film-maker Sam Mendes confirmed he will not be returning to direct the next film, saying he is ready to work on something new."
            ],
            "descriptions_default": [
              "The actor chosen to play the next James Bond will be an unexpected candidate, the franchise’s outgoing director has said, suggesting favourite Tom Hiddleston may not land th"
            ],
            "evergreen": [
              "no"
            ],
            "thumbnails_large_width": [
              "1280"
            ],
            "videos_watermarked_height": [
              "360"
            ],
            "videos_hd_uri": [
              "https://s3.amazonaws.com/egamitv-videos/videoelephant/18e1a9d6-7024-4b98-bb3b-91730b83004b/4c0a9e3c9851415b9e0bf56887acdfff.mp4"
            ],
            "videos_hd_width": [
              "1280"
            ],
            "thumbnails_small_height": [
              "80"
            ],
            "videos_watermarked_compression": [
              "H.264"
            ],
            "thumbnails_small_alttext": [
              "Who's going to be the next James Bond?"
            ],
            "videos_hd_height": [
              "720"
            ],
            "videos_hd_compression": [
              "H.264"
            ],
            "videos_hd_definition": [
              "HD"
            ],
            "videos_hd_filetype": [
              "MP4"
            ],
            "videos_watermarked_width": [
              "640"
            ],
            "slug": [
              "whos-going-to-be-the-next-james-bond"
            ],
            "thumbnails_large_alttext": [
              "Who's going to be the next James Bond?"
            ],
            "language": [
              "en"
            ],
            "thumbnails_small_src": [
              "https://s3.amazonaws.com/egamitv-videos/videoelephant/18e1a9d6-7024-4b98-bb3b-91730b83004b/7023d6abca2fbc76214f78e495445db4-140x80.png"
            ],
            "thumbnails_large_src": [
              "https://s3.amazonaws.com/egamitv-videos/videoelephant/18e1a9d6-7024-4b98-bb3b-91730b83004b/7023d6abca2fbc76214f78e495445db4-1280x720.png"
            ],
            "published": [
              "2016-05-30 00:02:36"
            ],
            "thumbnails_small_width": [
              "140"
            ]
          }
        },

				...

        {
          "id": "176454",
          "fields": {
            "production_year": [
              "2015"
            ],
            "thumbnails_large_height": [
              "720"
            ],
            "content_provider_id": [
              "176454"
            ],
            "content_provider": [
              "Cover Media"
            ],
            "videos_watermarked_uri": [
              "https://s3.amazonaws.com/egamitv-videos/videoelephant/35c114cc-8c59-4550-a7be-cc3cd5cba4e5/fd39e9bcf0bc8ff742bb9850e95c1833.mp4"
            ],
            "duration": [
              "60"
            ],
            "id": [
              "35c114cc-8c59-4550-a7be-cc3cd5cba4e5"
            ],
            "videos_watermarked_definition": [
              "SD"
            ],
            "title": [
              "James Bond to become comic and musical"
            ],
            "videos_watermarked_filetype": [
              "MP4"
            ],
            "descriptions_long": [
              "Super spy James Bond will soon be entering the worlds of comic books and musicals. Having conquered the realm of movies for more than 50 years, Ian Fleming's iconic character is set to branch out into new media."
            ],
            "descriptions_default": [
              "Super spy James Bond will soon be entering the worlds of comic books and musicals. Having conquered the realm of movies for more than 50 years, Ian Fleming's iconic character "
            ],
            "evergreen": [
              "no"
            ],
            "thumbnails_large_width": [
              "1280"
            ],
            "videos_watermarked_height": [
              "360"
            ],
            "videos_hd_uri": [
              "https://s3.amazonaws.com/egamitv-videos/videoelephant/35c114cc-8c59-4550-a7be-cc3cd5cba4e5/11903cf5215d30f3f04103daf3ee8355.mp4"
            ],
            "videos_hd_width": [
              "1280"
            ],
            "thumbnails_small_height": [
              "80"
            ],
            "videos_watermarked_compression": [
              "H.264"
            ],
            "thumbnails_small_alttext": [
              "James Bond to become comic and musical"
            ],
            "videos_hd_height": [
              "720"
            ],
            "videos_hd_compression": [
              "H.264"
            ],
            "videos_hd_definition": [
              "HD"
            ],
            "videos_hd_filetype": [
              "MP4"
            ],
            "videos_watermarked_width": [
              "640"
            ],
            "slug": [
              "james-bond-to-become-comic-and-musical"
            ],
            "thumbnails_large_alttext": [
              "James Bond to become comic and musical"
            ],
            "language": [
              "en"
            ],
            "thumbnails_small_src": [
              "https://s3.amazonaws.com/egamitv-videos/videoelephant/35c114cc-8c59-4550-a7be-cc3cd5cba4e5/a329a180d543bb378b745e67d17ccee8-140x80.png"
            ],
            "thumbnails_large_src": [
              "https://s3.amazonaws.com/egamitv-videos/videoelephant/35c114cc-8c59-4550-a7be-cc3cd5cba4e5/a329a180d543bb378b745e67d17ccee8-1280x720.png"
            ],
            "published": [
              "2015-07-07 12:12:45"
            ],
            "thumbnails_small_width": [
              "140"
            ]
          }
        }
      ]
    }
  },
}

```


