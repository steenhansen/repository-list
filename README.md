| Functional&nbsp;GitHub&nbsp;Projects | WebSite                                                  | Technologies                                                              |
| ------------------------------------ | -------------------------------------------------------- | ------------------------------------------------------------------------- |
| [type-czech-phone-recipes][rec_g]    | [Online Recipes][rec_w]                                  | Node.js, SSR, OAuth2, Selenium, MongoDB, React-Hooks, Storybook, Tailwind |
| [type-czech][tcz_g]                  | [NPM Package][tcz_n]                                     | Javascript runtime type checking in the spirit of clojure.spec            |
| [type-czech-always-on][aon_g]        | [Online Type-Czech Example][aon_w] <sup>[sleeping]</sup> | TypeCzech runtime type checking example with on/off switch                |
| [rxjs-breakout][brk_g]               | [Online Breakout][brk_w]                                 | RxJs, canvas, immutablejs                                                 |
| [crash-sms][sms_g]                   | [Online Site Monitor][sms_w]                             | Clojure, SMS, DynamoDB                                                    |
| [rxjs-label-maker][lbl_g]            | [Online Example Label Maker][lbl_w]                      | RxJs                                                                      |
| [rxjs-drag-n-drop][drg_g]            | [Online RxJs Drag and Drop][drg_w]                       | RxJs                                                                      |
| [clojure-text-diff ][ctd_g]          |                                                          | Clojure                                                                   |
| [Either-Monad][mon_g]                |                                                          | Either Monad                                                              |
| [Validation-Monad][val_g]            |                                                          | Validation Monad                                                          |
| [Ramda-Transducers ][ram_g]          |                                                          | Ramda Transducers                                                         |

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

| OO GitHub Projects                   | WebSite                                                         | Technologies                                                 |
| ------------------------------------ | --------------------------------------------------------------- | ------------------------------------------------------------ |
| [electric-snakes][elc_g]             | [Online Multi-Computer Game][elc_w] <sup>[sleeping]</sup>       | Typescript websockets immutable.js                           |
| [podcast-downloader][dsk_g]          | [Download Desktop EXE][dsk_w]                                   | Desktop exe podcast downloader<br>written in Lazarus/Delphi  |
| [react-hover-grid][rhg_g]            | [NPM Package][rhg_n]                                            | React component for image grids in OO                        |
|                                      | [Online Example React-Hover-Grids][rhg_w] <sup>[sleeping]</sup> | Nodejs Image processing                                      |
| [gmap-dragdrop-react][map_g]         | [NPM Package][map_n]                                            | React component enabling Drag/Drop<br>to/from Google Maps    |
|                                      | [Online Example Gmap-DragDrops][map_w] <sup>[sleeping]</sup>    | Object Oriented inheritance                                  |
| [Isomorphic-React-on-Heroku ][iso_g] | [Online Search/Sort/Filter Site - Podcast][pod_w]               | JavaScript Prototypal Inheritance                            |
|                                      | [Online Search/Sort/Filter Component - PDF][pdf_w]              | React, MongoDB bare Heroku component                         |
|                                      | [Online Search/Sort/Filter DB][rsd_w]                           | Google Sheet as a read-only database                         |
| [php-google-api-example][php_g]      | None - Was PHP Updating a Google Sheet                          | Deprecated - Google Sheets as a read/write database from PHP |

[elc_g]: https://github.com/steenhansen/electric-snakes
[elc_w]: https://electric-snakes.herokuapp.com/create-game
[dsk_g]: https://github.com/steenhansen/podcast-downloader
[dsk_w]: https://github.com/steenhansen/podcast-downloader/raw/master/podcast-downloader-exes.zip
[rhg_g]: https://github.com/steenhansen/react-hover-grid
[rhg_n]: https://www.npmjs.com/package/react-hover-grid
[rhg_w]: https://react-hover-grid.herokuapp.com
[map_g]: https://github.com/steenhansen/gmap-dragdrop-react
[map_n]: https://www.npmjs.com/package/gmap-dragdrop-react
[map_w]: https://gddr.herokuapp.com/maps
[iso_g]: https://github.com/steenhansen/Isomorphic-React-on-Heroku
[pod_w]: https://www.sffaudio.com/the-sffaudio-podcast/
[pdf_w]: https://sffaudio.herokuapp.com/pdf/table
[rsd_w]: https://docs.google.com/spreadsheets/d/1sbQ8NR7hvcm4EjSlyhmte0rYtI_G3vnc1o5KLPAW2lc/edit#gid=0
[php_g]: https://github.com/steenhansen/php-google-api-example

<div align="center">[sleeping] A slow to start free Heroku site</div>

### Why Not PHP ?

![PHP Lowest Paid Language](https://cdn.sstatic.net/insights/Img/Survey/2019/salary_language-1.svg?v=d63c4a852014)

![PHP Lowest Paid Language](https://media-exp1.licdn.com/dms/image/C5112AQHyvNSEydBeaw/article-cover_image-shrink_720_1280/0/1521536993350?e=1661385600&v=beta&t=6wJRX9782XM16K4tijqBvlQJ4Ezufs2PEonZ3pz__JA)

[Hansen Displays](https://web.archive.org/web/20110204235449/http://hansendisplays.com/)

[Persistant RAM Cartridge](https://atariage.com/forums/topic/287343-the-persistent-ram-cartridge/)
