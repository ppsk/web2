# Web Slovensko

Web pro vznikajici Piratskou stranu na Slovensku.

## Funkcionality

Celý web bude vyvíjen agilně, čili spustíme první funkční verzi. Mnoho textů, designových prvků se ještě jistě bude měnit.
Prebirame funkcionality z https://github.com/pirati-cz/webpraha2

TODO:
- z webu "Praha" udelat web "Slovensko"


## Náhled a kompilace

Stránka je k vidění na `http://ppsk.github.io/web2/`,
lokálně je třeba kompilovat: `jekyll serve --baseurl ''`


## Standardizace tagů

TBD


## Adresařova struktura

```
├── _config.yml       - konfigurační soubor
├── _data             - yaml soubory nahrazující DB
├── _includes         - html snippety (hlavička, patička, ...)
│   ├── footer.html   -- patička stránky
│   ├── header.html   -- hlavička stránky
│   └── head.html     -- meta hlavička stránky
├── _layouts          - kompletní šablony stránek
├── _people           - vlastní kolekce obsahující stránky jednotlivých osob
│   ├── osoba.md    
│   └── ...
├── _posts            - příspěvky pro blog v markdownu
├── _sass             - sass styly (konvertované do css)
├── _site             - vygenerovaná stránka
├── assets            - přílohy (obrázky, pdf etc.)
│   └── img           
├── blog              - složka blog / aktuality
│   └── index.html    
├── css               - styly
│   └── main.scss     -- hlavní styl
├── kontakt           
│   └── index.html    
├── o-nas          
│   └── index.html    
├── program
│   └── index.html    
├── transparence
│   └── index.html
├── zapoj-se
│   └── index.html       
└── index.html        - úvodní stránka
```



## Použité technologie

- [CSS / JS frontend Foundation 6](http://foundation.zurb.com/), [dokumentace](http://foundation.zurb.com/sites/docs/)
- [CSS template](http://foundation.zurb.com/templates-previews-sites-f6/news-magazine.html)
- integrace soc. sití
  - [Integrace FB](https://365tipu.wordpress.com/2015/07/04/tip185-co-je-to-open-graph-a-proc-je-potreba-aby-designeri-webu-vedeli-o-co-jde/)
  - [Ladění FB](https://365tipu.wordpress.com/2015/04/13/tip103-co-delat-kdyz-facebook-odmita-vlozit-odkaz-na-web/)
- [Disqus a Google analytics, Twitter light share](http://joshualande.com/jekyll-github-pages-poole)
- [Responsibilita](http://design.google.com/resizer/)
