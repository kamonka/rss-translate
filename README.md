# rss-translate

rss translate any to any

![](https://github.com/talengu/rss-translate/workflows/circle_translate/badge.svg)
![](https://github.com/talengu/rss-translate/workflows/Deploy/badge.svg)

you can edit [test.ini](https://github.com/talengu/rss-translate/edit/main/test.ini) to add orginal rss url. [help](https://github.com/talengu/rss-translate/issues/2)

next find the translated link in [https://talengu.github.io/rss-translate/](https://talengu.github.io/rss-translate/)

## 20230814 update
- support proxy mode. you can set `action = "proxy"` in test.ini like [source010](https://github.com/talengu/rss-translate/blob/f6648c5262f4fa0926310dbe43fff820bf727ac7/test.ini#L67).
 Proxy mode does not translate the rss, and directly show the original rss.

## 20230702 update 
- use [main2.py](https://github.com/talengu/rss-translate/blob/main/main2.py) in [circle_translate.yml](https://github.com/talengu/rss-translate/blob/aeb61bc36eb1a22fd003677b5209291cf7cb4a87/.github/workflows/circle_translate.yml#L38)
- atom is bad now base on an atom paraser to find. NOW SUPPORT
        use [feedparser](https://pythonhosted.org/feedparser/)
- fix google translate limit . NOW SUPPORT

## rss translate links

 - source001 [https://rsseverything.com/feed/0057471e-3f41-443d-9a01-00131858648c.xml](https://rsseverything.com/feed/0057471e-3f41-443d-9a01-00131858648c.xml) -> [UCPress_rss.xml](rss/UCPress_rss.xml)
 - source002 [https://rsseverything.com/feed/4e53f62c-4162-41a0-8d1d-0b6cf0c720b5.xml](https://rsseverything.com/feed/4e53f62c-4162-41a0-8d1d-0b6cf0c720b5.xml) -> [PUPress_rss.xml](rss/PUPress_rss.xml)
 - source003 [https://rsseverything.com/feed/e727076a-9260-40c6-b0f4-c25719614d87.xml](https://rsseverything.com/feed/e727076a-9260-40c6-b0f4-c25719614d87.xml) -> [CUPress_rss.xml](rss/CUPress_rss.xml)
