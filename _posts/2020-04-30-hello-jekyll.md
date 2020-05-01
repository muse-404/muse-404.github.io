---
comments: true
title: Hello Jekyll
description: "how i build my site by jekyll"
summary: 
comments: true
category: blog
tags: [blog, tech, jekyll, ruby]
header:
  teaser: "assets/img/posts/teaser/20200430_jekyll.jpg"
toc: true
toc_sticky: true
toc_label: "Content"
excerpt: "關於為什麼會無事找事做，換一換新東西的經歷"
---

事緣在之前一直也想打理一下blogger上的介面，但是發現限制實在是太大了。與其辛苦更改不如轉用其他的CMS。最後經過一番研究和整理，就是現在這個Jekyll＋GitHub的網站了。

# 之前為什麼用blogger?

當初我不用wordpress的其中一個原因就是寫財自/投資的blogger也是用blogger比較多，留言和連繫也比較方便（這算是其中一類platform stickiness吧），我自己也有私人的blog在wordpress上，比起不思進取的blogger，wordpress始終也是CMS的一哥，始終別人是賣錢的product，會有維護和更新。用的css和介面也選擇夠多，不像blogger就是n年前的Geocity（我想現在沒有很多人記得它吧），一直沒有改進。

# 為什麼想用Jekyll

自從認識了markdown後，真的覺得很方便。寫簡單的文件或是記事，很簡單就可以分類和有簡單的styling。最基的的連結，表單，等等也有。這樣不用每次也看html再設定。在網上研究後，發現Jekyll可以用markdown來製作網頁，如果用github page的hosting的話，還可以很簡單就設定到了。雖然我最關心的留言要用3rd parties tools - `Disqus` 來設定，這個比較在外國網站受歡近吧。可能我自己比較少在別人網站留言，所以一直也沒有注意有這些3rd parties tools。這次設定Jekyll的經驗，真的令我大開眼界。覺得自己有點像山頂洞人呢。

Markdown除了寫文章方便外，用來制作電子書也是很好的。遲些可以介紹一下。

# 處理過程

這兒大概寫了我的流程，中間遇到了的小問題就不詳說了。簡單來算我遇到的問題很多也是因為沒看readme而造成。

1. 裝好ruby （為了方便，我用的是老舊的macbook air，因為不想煩在windows上設定）
1. 開github account
1. 選好Jekyll Theme [^1]（這個過程其實很久，因為中間選中了，但改著改著又發現看不順眼）
1. export all post from blogger (as xml file)
1. convert the xml file into semi-markdown
1. git clone下 Jekyll Theme
1. 照readme的照改，順便導入自己blogger裡的文章
1. 在github account下，開一個同名的repository
1. git push overwrite master branch
1. 上github的page上，無錯的話 😇 就應該看到了你的網站了！

這個list寫完也覺得複雜呢，但沒法，自己一手一腳架設就是這回事。有import module可以快速導入也很不錯了。所以你在這網站看到舊的文章，也是用import轉換的，有些html在excerpt中會出現亂碼，但是看全文的不會，不是完美主義者的我就算了。這個網站的定位是一半proof of concept吧～哈哈

如果不想做自己的站，只想真的試一試Jekyll的話，簡單的在我/別人github裡clone了再build就行了。其實不用做太多。

舊的blogspot文轉換時也有很多限制，例如很多也沒有配圖。所以有時會看到重覆的配圖～

# 後話

如果不想研究coding的話，還是建議使用wordpress比較快。focus在爬格子上，可能得到的金錢回報會更多。Jekyll的架設過程比較像是DIY，雖然很快樂，但是如果你主打是「內容」的話，就應該努力集中寫文章，得到的讀者回應的機會會比較多。

# Reference


[^1]: [Jekyll Theme - Minimal Mistake](https://mmistakes.github.io/minimal-mistakes/)

[Jekyll](https://jekyllrb.com/)



