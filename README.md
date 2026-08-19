# kamilsaim.github.io

Kullanici koku deposu. Iki isi var:

1. `/.well-known/assetlinks.json` — Android uygulamalarinin (TWA) siteyle
   eslesme beyani. Dogrulama **alan adi duzeyinde** yapildigi icin bu dosya
   proje deposunda degil, burada durmak zorunda. Yeni bir TWA uygulamasi
   eklendiginde dizine yeni bir girdi eklenir.
2. `index.html` — proje sayfalarina yonlendiren sade bir kok sayfa.

`.nojekyll` dosyasi zorunlu: Jekyll nokta ile baslayan klasorleri yayimlamaz,
o dosya olmadan `.well-known/assetlinks.json` 404 doner.
