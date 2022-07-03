| Functional&nbsp;GitHub&nbsp;Projects | WebSite                                                  | Technologies                                                                                                                                                          |
| ------------------------------------ | -------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type-czech-phone-recipes][rec_g]    | [Online Recipes][rec_w]                                  | vite-plugin-ssr, OAuth2, Selenium, MongoDB, React-Hooks, Redux, [Storybook on Chromatic.com](https://www.chromatic.com/library?appId=6269af43d179dc004af9a1ec&inviteToken=5fd55d68b13f4f51bc57632bcad949ba), Tailwind, Isomorphic HMR &amp; ESM for development via Vite                                |
| [type-czech][tcz_g]                  | [NPM Package][tcz_n]                                     | Javascript runtime type checking in the spirit of clojure.spec                                                                                                        |
| [type-czech-always-on][aon_g]        | [Online Type-Czech Example][aon_w] <sup>[sleeping]</sup> | TypeCzech runtime type checking example with on/off switch.<br>Checks Roman, Word, Float, and Integer number types                                                    |
| [rxjs-breakout][brk_g]               | [Online Breakout][brk_w]                                 | RxJs, canvas, immutablejs                                                                                                                                             |
| [crash-sms][sms_g]                   | [Online Site Monitor][sms_w]                             | Clojure, SMS, DynamoDB                                                                                                                                                |
| [rxjs-label-maker][lbl_g]            | [Online Example Label Maker][lbl_w]                      | RxJs &amp; [Snap-Shot Tests](https://steenhansen.github.io/rxjs-label-maker/tests/testing-frame.html), labelled 'CHECK', that pass in Chrome, and now fail in Firefox |
| [rxjs-drag-n-drop][drg_g]            | [Online RxJs Drag and Drop][drg_w]                       | RxJs                                                                                                                                                                  |
| [clojure-text-diff ][ctd_g]          |                                                          | Clojure                                                                                                                                                               |
| [Either-Monad][mon_g]                |                                                          | Either Monad                                                                                                                                                          |
| [Validation-Monad][val_g]            |                                                          | Validation Monad                                                                                                                                                      |
| [Ramda-Transducers ][ram_g]          |                                                          | Ramda Transducers                                                                                                                                                     |

[rec_g]: https://github.com/steenhansen/type-czech-phone-recipes
[rec_w]: https://phone-recipes.herokuapp.com/steenhansen1942/gmail.com
[tcz_g]: https://github.com/steenhansen/type-czech
[tcz_n]: https://www.npmjs.com/package/type-czech
[aon_g]: https://github.com/steenhansen/type-czech-always-on
[aon_w]: https://type-czech-always-on.herokuapp.com
[brk_g]: https://github.com/steenhansen/rxjs-breakout
[brk_w]: https://steenhansen.github.io/gh-pages/
[sms_g]: https://github.com/steenhansen/crash-sms
[sms_w]: https://fathomless-woodland-85635.herokuapp.com/
[lbl_g]: https://github.com/steenhansen/rxjs-label-maker
[lbl_w]: https://steenhansen.github.io/rxjs-label-maker/
[drg_g]: https://github.com/steenhansen/rxjs-drag-n-drop
[drg_w]: https://steenhansen.github.io/rxjs-drag-n-drop/
[ctd_g]: https://github.com/steenhansen/clojure-text-diff
[mon_g]: https://gist.github.com/steenhansen/f9a9e9eee2fd563e378d8ddfce98cf0a
[val_g]: https://gist.github.com/steenhansen/5a0dbad5388a79ebb900b257fc7a129c
[ram_g]: https://gist.github.com/steenhansen/3e8c320725c6196c9a259661473dec42

| Docker&nbsp;Containers&nbsp;and Databases | WebSite                                  | Technologies                                                                   |
| ----------------------------------------- | ---------------------------------------- | ------------------------------------------------------------------------------ |
| [sffaudio-search-docker-compose ][sli_g]  | [Online Search SFF-Audio Content][sli_w] | Docker-Compose on Linode<br>with Neo4j-Graph-DB, SVG, SPA                      |
| [sffaudio-search-docker-run ][swi_g]      | [Docker Image][swi_d]                    | Docker-Run on local Windows<br>with Neo4j-Graph-DB                             |
| [sffaudio-search-kubernetes][sku_g]       | [Docker Image][sku_d]                    | Kubernetes Linode example<br>is turned off                                     |
| [sffaudio-graph-ql ][sgr_g]               | [Online Graph-QL][sgr_w]                 | GraphQL - Press the triangular "Run"<br>button for an 'Arthur C. Clark' search |
|                                           | [Online JSON][sgr_j]                     | PDF/Podcast/MP3s media that is written<br> by 'Arthur C. Clark'                |

[sli_g]: https://github.com/steenhansen/sffaudio-search-docker-compose
[sli_w]: http://45.79.183.31/?author=isaac-asimov
[swi_g]: https://github.com/steenhansen/sffaudio-search-docker-run
[swi_d]: https://hub.docker.com/r/steenhansen/sff-audio-search
[sku_g]: https://github.com/steenhansen/sffaudio-search-kubernetes
[sku_d]: https://hub.docker.com/r/steenhansen/sff-audio-kube
[sgr_g]: https://github.com/steenhansen/sffaudio-graph-ql
[sgr_w]: https://sffaudio-graph-ql.herokuapp.com/graphiql?operationName=serch_ql&query=query%20serch_ql(%24search_parameter%3A%20String!)%20%7B%0A%20%20search_site_content(search_text%3A%20%24search_parameter)%20%7B%0A%20%20%20%20%20%20...%20on%20ArticlePage%7B%20ID%20headline%20article_post%20%20%20%7D%2C%0A%20%20%20%20...%20on%20MentionPage%7B%20ID%20headline%20mention_post%20%20%20%7D%2C%0A%20%20%20%20...%20on%20RsdMedia%20%7B%20ID%20rsd_post%20resource%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20book%7B%20author%20title%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20podcast%20%7B%20description%20mp3%20length%20episode%20%7D%20%20%20%7D%2C%0A%20%20%20%20...%20on%20SffAudioMedia%20%7B%20ID%20sffaudio_post%20narrator%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20possiblebook%7B%20author%20title%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20podcast%20%7B%20description%20mp3%20length%20episode%20%7D%20%20%20%7D%2C%0A%20%20%20%20...%20on%20PdfMedia%20%7B%20ID%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20book%7B%20author%20title%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20issues%20%7B%20url%20publisher%20pages%20%7D%20%20%20%7D%0A%20%20%7D%0A%7D%0A&variables=%7B%0A%20%20%22search_parameter%22%3A%20%22Clarke%22%0A%7D
[sgr_j]: https://sffaudio-graph-ql.herokuapp.com/graphql?operationName=serch_ql&query=%0Aquery%20serch_ql(%24search_parameter%3A%20String!)%20%7B%0A%20search_site_content(search_text%3A%20%24search_parameter)%20%7B%0A%20...%20on%20ArticlePage%7B%20ID%20headline%20article_post%20%7D%2C%0A%20...%20on%20MentionPage%7B%20ID%20headline%20mention_post%20%7D%2C%0A%20...%20on%20RsdMedia%20%7B%20ID%20rsd_post%20resource%0A%20book%20%7B%20author%20title%20%7D%0A%20podcast%20%7B%20description%20mp3%20length%20episode%20%7D%20%7D%2C%0A%20...%20on%20SffAudioMedia%20%7B%20ID%20sffaudio_post%20narrator%20about%0A%20possiblebook%7B%20author%20title%20%7D%0A%20podcast%20%7B%20description%20mp3%20length%20episode%20%7D%20%7D%2C%0A%20...%20on%20PdfMedia%20%7B%20ID%0A%20book%20%7B%20author%20title%20%7D%0A%20issues%20%7B%20url%20publisher%20pages%20%7D%20%7D%0A%20%7D%0A%7D%20&variables=%7B%20%22search_parameter%22%3A%20%22clarke%22%7D

| OO GitHub Projects                  | WebSite                                                                 | Technologies                                                                   |
| ----------------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| [electric-snakes][elc_g]            | [Online Multi-Computer Game][elc_w] <sup>[sleeping]</sup>               | Typescript, websockets, Redux, immutable.js                                    |
| [podcast-downloader][dsk_g]         | [Download Desktop EXE][dsk_w]                                           | Desktop exe podcast downloader<br>written in Lazarus/Delphi                    |
| [react-hover-grid][rhg_g]           | [React-Hover-Grids NPM Package][rhg_n]                                  | React component for image grids in OO                                          |
|                                     | [React-Hover-Grids Online Example][rhg_w] <sup>[sleeping]</sup>         | Nodejs Image processing, [example Hover GitHub][rhg_e]                         |
| [gmap-dragdrop-react][map_g]        | [Gmap-DragDrops NPM Package][map_n]                                     | React component enabling Drag/Drop<br>to/from Google Maps, not RxJS            |
|                                     | [Gmap-DragDrops Online Example][map_w] <sup>[sleeping]</sup>            | Object Oriented inheritance, [example Map GitHub][map_e]                       |
| [Isomorphic-React-on-Heroku][iso_g] | [Heroku Search/Sort/Filter Podcasts][pod_h] -- [Google Sheet DB][pod_s] | [Podcast SFFaudio.com WordPress page][pod_w] JavaScript Prototypal Inheritance |
|                                     | [Heroku Search/Sort/Filter PDFs][pdf_h] -- [Google Sheet DB][pdf_s]     | [PDF SFFaudio.com WordPress page][pdf_w] React, MongoDB, SSR                   |
|                                     | [Heroku Search/Sort/Filter MP3s][rsd_h] -- [Google Sheet DB][rsd_s]     | [MP3 SFFaudio.com WordPress page][rsd_w] Google Sheet as a read-only database  |
| [php-google-api-example][php_g]     | Was a PHP library that updated Google Sheets                            | Deprecated - Google Sheets as a read/write database from PHP                   |
| [sffaudio-podcasts-angular][ang_g]  | Was a replaced Angular version of Isomorphic-React-on-Heroku            | Deprecated - by use of React                                                   |

[pod_h]: https://sffaudio.herokuapp.com/podcast/table
[pdf_h]: https://sffaudio.herokuapp.com/pdf/table
[rsd_h]: https://sffaudio.herokuapp.com/rsd/table
[pod_s]: https://docs.google.com/spreadsheets/d/1cWtA1AaY83cBuU_6vt64adDeR-dfT-X1U5VgvCRVMAg/edit#gid=0
[rsd_s]: https://docs.google.com/spreadsheets/d/1VFMgWy6wmTkFIpeNW-NkZdWmpz5iZcuULgMpjn8_QgU/edit#gid=0
[pdf_s]: https://docs.google.com/spreadsheets/d/1sbQ8NR7hvcm4EjSlyhmte0rYtI_G3vnc1o5KLPAW2lc/edit#gid=0
[pod_w]: https://www.sffaudio.com/the-sffaudio-podcast/
[pdf_w]: https://www.sffaudio.com/public-domain-pdf-page/
[rsd_w]: https://www.sffaudio.com/reading-short-and-deep/
[elc_g]: https://github.com/steenhansen/electric-snakes
[elc_w]: https://electric-snakes.herokuapp.com/create-game
[dsk_g]: https://github.com/steenhansen/podcast-downloader
[dsk_w]: https://github.com/steenhansen/podcast-downloader/raw/master/podcast-downloader-exes.zip
[rhg_g]: https://github.com/steenhansen/react-hover-grid
[rhg_n]: https://www.npmjs.com/package/react-hover-grid
[rhg_w]: https://react-hover-grid.herokuapp.com
[rhg_e]: https://github.com/steenhansen/react-hover-grid-examples
[map_g]: https://github.com/steenhansen/gmap-dragdrop-react
[map_n]: https://www.npmjs.com/package/gmap-dragdrop-react
[map_w]: https://gddr.herokuapp.com/maps
[map_e]: https://github.com/steenhansen/gmap-dragdrop-examples
[iso_g]: https://github.com/steenhansen/Isomorphic-React-on-Heroku
[php_g]: https://github.com/steenhansen/php-google-api-example
[ang_g]: https://github.com/steenhansen/sffaudio-podcasts-angular

<div align="center">[sleeping] A slow to start free Heroku site</div>

---

[Hansen Displays, 1/3 Owner](https://web.archive.org/web/20110204235449/http://hansendisplays.com/) - [Post Card](/images/hansen-displays-photo.jpg) - [Price List](/images/hansen-displays-brochure_us.pdf)

[Persistant RAM Cartridge, 1/3 Owner](https://atariage.com/forums/topic/287343-the-persistent-ram-cartridge/) - [Persistant RAM Image](/images/persistant-ram-front.jpg)

[Ikea Standing Desk Blog](https://www.jerkersearcher.com/)

---

[From Stack Overflow Developer Survey Results 2018](https://insights.stackoverflow.com/survey/2018#work-_-salary-and-experience-by-language)

[Languages 2018](https://cdn.sstatic.net/insights/Img/Survey/2018/salary_language-1.svg?v=3f273db9f512)


