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
 - source004 [https://rsseverything.com/feed/6e34b882-d6a9-4207-97a5-968c7d9da10b.xml](https://rsseverything.com/feed/6e34b882-d6a9-4207-97a5-968c7d9da10b.xml) -> [RLibrary_rss.xml](rss/RLibrary_rss.xml)
 - source005 [https://rss.stephenslab.top/feed/4498.xml](https://rss.stephenslab.top/feed/4498.xml) -> [anekdot1_rss.xml](rss/anekdot1_rss.xml)
 - source006 [https://www.anekdot.ru/rss/export_j.xml](https://www.anekdot.ru/rss/export_j.xml) -> [anekdot2_rss.xml](rss/anekdot2_rss.xml)
 - source007 [https://feedx.net/rss/scmp.xml](https://feedx.net/rss/scmp.xml) -> [scmp_rss.xml](rss/scmp_rss.xml)
 - source008 [https://rss.stephenslab.top/feed/5049.xml](https://rss.stephenslab.top/feed/5049.xml) -> [libgen_rss.xml](rss/libgen_rss.xml)
 - source009 [https://rsseverything.com/zh/feed/738019e8-a62c-4816-b737-6d2554689bd0.xml](https://rsseverything.com/zh/feed/738019e8-a62c-4816-b737-6d2554689bd0.xml) -> [NTNon_rss.xml](rss/NTNon_rss.xml)
 - source010 [https://rsseverything.com/zh/feed/5226.xml](https://rsseverything.com/zh/feed/5226.xml) -> [NYTbestsellers_rss.xml](rss/NYTbestsellers_rss.xml)
 - source011 [https://rsseverything.com/feed/4593.xml](https://rsseverything.com/feed/4593.xml) -> [jokechina_rss.xml](rss/jokechina_rss.xml)
 - source012 [https://ftr.fivefilters.net/makefulltextfeed.php?url=https://politepol.com/fd/TMRgeTPtPeA1.xml](https://ftr.fivefilters.net/makefulltextfeed.php?url=https://politepol.com/fd/TMRgeTPtPeA1.xml) -> [studywar_rss.xml](rss/studywar_rss.xml)
 - source013 [http://ftr.fivefilters.net/makefulltextfeed.php?url=https://www.twz.com/feed&amp;max=3&amp;links=preserve](http://ftr.fivefilters.net/makefulltextfeed.php?url=https://www.twz.com/feed&amp;max=3&amp;links=preserve) -> [TheWarZone_rss.xml](rss/TheWarZone_rss.xml)
 - source014 [https://rss-bridge.org/bridge01/?action=display&bridge=FeedMergeBridge&feed_name=TMDB&feed_1=https://rssweball.top/feed/418b4655-0038-4b9a-a9a8-f4a89ea15cf2.xml&feed_2=https://rssweball.top/feed/5bd9f12b-0c84-4419-aa20-4f576746357d.xml&feed_3=&feed_4=&feed_5=&feed_6=&feed_7=&feed_8=&feed_9=&feed_10=&limit=&format=Atom](https://rss-bridge.org/bridge01/?action=display&bridge=FeedMergeBridge&feed_name=TMDB&feed_1=https://rssweball.top/feed/418b4655-0038-4b9a-a9a8-f4a89ea15cf2.xml&feed_2=https://rssweball.top/feed/5bd9f12b-0c84-4419-aa20-4f576746357d.xml&feed_3=&feed_4=&feed_5=&feed_6=&feed_7=&feed_8=&feed_9=&feed_10=&limit=&format=Atom) -> [TMDB_rss.xml](rss/TMDB_rss.xml)
