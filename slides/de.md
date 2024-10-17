---
title: Wie man einen (Retro-)Podcast from scratch startet
author: Christian Stankowic
description: Präsentation über den ThinkPad Musuem-Podcast
keywords: Marp, Presentation, ThinkPad, IBM, Lenovo, Podcast
marp: true
paginate: true
theme: think
---

<style>
    .container{
        display: flex;
    }
    .col{
        flex: 1;
    }
    .col25{
        width: 25%;
    }
    .col40{
        width: 40%;
    }
    .smol{
      font-size: 60%
    }
</style>

<!-- _class: lead -->

# 🔴 ThinkPad-Musuem

#### Wie man einen (Retro-)Podcast from scratch startet

<br>

Christian ~~Thinkowic~~ Stankowic
SUBSCRIBE 11
18.10.2024

---

<!-- _header: `whoami` -->

<div class="container">

<div class="col">

![w:500](./imgs/cstan.jpg)

</div>

<div class="col">

- Christian Stankowic
- [@stdevel@chaos.social](https://chaos.social/@stdevel) 🐘
- IT-Berater und -Trainer 👨🏻‍🏫
- sammelt obsolete Hardware
- Blogger ([cstan.io](https://cstan.io) 📖)
- Podcaster 🎙️
  - [FOCUS ON: Linux](https://focusonlinux.podigee.io) 🐧
  - [Faxinformatiker](https://faxinformatiker.de) 📠
  - [ThinkPad-Museum](https://thinkpad-museum.de/episode) 💻

</div>

</div>

<!--

- Blog seit 2008 (=16)
- war late to the party: habe Podcasts erst in der Pandemie für mich entdeckt
  - mit LNP und Chaosradio angefangen und dann weitere Podcasts entdeckt

-->

---

<!-- _header: ThinkPad-Museum -->

<div class="container">

<div class="col">

- Online-Museum als **Blog**
- listet Details der Sammlung auf
  - **57** <u>unterschiedliche</u> Notebooks
  - **3** PDAs, **1** Tablet
  - **10** Docking Stationen
  - ∞ Akkus und Kabel
- monatlicher **Podcast**
- 🔴 [thinkpad-museum.de](https://thinkpad-museum.de)

</div>

<div class="col">

![w:300 center](./imgs/museum.jpg)

</div>

</div>

---

<!-- _header: ThinkPad-Museum -->

<div class="container">

<div class="col">

![w:480 center](./imgs/museum_table.jpg)

Teil der Sammlung

</div>

<div class="col">

![w:580 center](./imgs/museum_transport.jpg)

Transport der Sammlung

</div>

</div>

---

<!-- _header: Agenda -->

1. Weg zur Idee 💡
1. Branding und Organisation 📝
1. Tools und Workflow 🔨
1. Hosting und Marketing 👨🏻‍💻

---

<!-- _header: Mal im Ernst - warum? -->

<div class="container">

<div class="col">

- Wieso eigentlich nicht? 🙃

<div style="display:contents;" data-marpit-fragment>

- **Begeisterung** für das Thema
- ThinkPads sind immernoch in Business- und Hacker:innen-Kreisen anzutreffen
- auch popkulturell relevant
- Bewegte Geschichte mit viel **Trivia** und **Kuriositäten**
  - Industriedesign
  - Absurde Hardware-Konzepte

</div>

</div>

<div class="col">

![w:480 center](./imgs/dog_shut_meme.jpg)

</div>

</div>

---

<!-- _header: Mal im Ernst - warum? -->

<div class="container">

<div class="col">

- erste **Umfragen** im Bekanntenkreis und auf Mastodon waren **optimistisch**
- Respekt vor nicht kalkulierbarem Aufwand

<div style="display:contents;" data-marpit-fragment>

- befreundeter Podcast lud mich zu genau diesem Thema ein
  - "*Kurz das Thema anreißen*"
  - [HK003 - ThinkPads](https://hacker-kultur.de/episodes/003.html) 🎙️
  - **02:28:55** 🫢

</div>

</div>

<div class="col">

![w:520 center](./imgs/bilbo_podcast_meme.jpg)

</div>

</div>

---

<!-- _header: ThinkPads 101 💻 -->

<div class="container">

<div class="col75">

- werden seit **1992** produziert
- stehen für **langlebige** Geräte
- **zeitloses** Design, praktikabel
- vielen kuriose **Experimente**
  - PDAs (IBM WorkPad)
  - PowerPC- und ARM-Notebooks
  - unübliche Erweiterungsmodule
  - Notebooks mit **zwei Displays**
- u.a. wegen gutem **Linux**-Support beliebt

</div>

<div class="col">

![w:520 center](./imgs/alice_meme.jpg)

Rabbit Hole in a nutshell

</div>

</div>

<!--

- Auf den PPC-Notebooks lief UNIX (IBM AIX)
- Kuriose Module: ausklappbares Numpad, PDA-Docking Station und TV-Tuner

-->

---

<!-- _header: Produktdesign on fleek: IBM PC Convertible Model 5140 (1986) -->
<!-- footer: '[[1]](https://richardsapperdesign.com/products/mod-5140/)' -->

![bg](./imgs/mod-5140-5.jpg)

<!--

- Notebook sieht seitlich betrachtet wie ein Krokodil aus
- Anspielung auf den Produktionsstandort Boca Raton (Florida), wo eine Alligator-Plage herrschte
- im Hintergrund: Richard Sapper
  - einer der bedeutendsten Produktdesigner der 2.Hälfe des 20.Jahrhunderts
  - gewann zahlreiche Preise für seine Designs

-->

---

<!-- _header: Stilvolle Tischlampe, popkulturelle Relevanz -->
<!-- footer: '[[2]](https://commons.wikimedia.org/wiki/File:Lampe_Tizio_von_Richard_Sapper.jpg), [[3]](https://productplacementblog.com/movies/lenovo-thinkpad-t61-laptop-used-by-christopher-plummer-as-harlan-thrombey-in-knives-out-2019/)' -->

<div class="container">

<div class="col">

![w:470 center](./imgs/artemide_tizio.jpg)

Artemide Tizio (1972)

</div>

<div class="col">

![w:710 center](./imgs/knives_out.jpg)

Knives Out (2019)

</div>

</div>

<!-- 
- Lampe kam ohne sichtbare Kabel aus
  - konnte ohne Federn einfach justiert werden
  - Gegengewichte erhöhen Stabilität und ergänzen das Design
- TPs treten schon lange auch außerhalb von "Nerdfilmen" auf
-->

---

<!-- _header: Unübliche Tastaturen und Bildschirme -->
<!-- footer: '[[4]](https://en.wikipedia.org/wiki/File:IBM_ThinkPad_701C_keyboard.jpg), [[5]](https://thinkwiki.de/W701)' -->

<div class="container">

<div class="col">

![w:520 center](./imgs/701c.jpg)

ThinkPad 701C (1995)

</div>

<div class="col">

![w:520 center](./imgs/w701ds.jpg)

ThinkPad W701ds (2010)

</div>

</div>

<!--
- 701c steht u.a. im Museum of Modern Art in New York
-->

---

<!-- _header: Der Zeit voraus: Tablets, die (noch) keine:r wollte -->
<!-- footer: '[[6]](https://richardsapperdesign.com/products/leapfrog/), [[7]](https://commons.wikimedia.org/wiki/Category:ThinkPad_360PE)' -->

<div class="container">

<div class="col">

![w:350 center](./imgs/leapfrog.jpg)

IBM Leapfrog (1992)

</div>

<div class="col">

![w:650 center](./imgs/360pe.jpg)

ThinkPad 360PE (1995)

</div>

</div>

---

<!-- _header: Warum als Podcast? -->
<!-- footer: 'Erinnerst Du dich noch an die 3 letzten Folien? 🥲' -->

- Menschen leiden unter einer sinkender **Aufmerksamkeitsspanne***
  - Blogs werden immer **seltener** (aufmerksam) gelesen
- Video ist zu aufwändig, [gibt es außerdem bereits](https://www.youtube.com/channel/UC-wmf-Avorzz9QPKzdYFgeg)
- ich wollte etwas **Neues lernen**, höre selbst gerne Podcasts
  - **Marktanalyse** hat gezeigt, dass es derartiges noch nicht gibt
  - bewusst auf deutsch gemacht, kleinere Bubble in Kauf genommen

![w:980 center](./imgs/blog_stats.png)

---

<!-- _header: Geplante Formate -->
<!-- footer: '' -->

<div class="container">

<div class="col">

**Abwechslung** von Anfang an wichtig, um Leute zu begeistern:

- **Geschichte** - Historischer Kontext zu IBM und co.
- **Menschen** - Designer:innen, Ingenieur:innen, **Community**
- **Modell** - einzelne Geräte/Serien
- **Technik** - z.B. VGA, Windows 3.x

</div>

<div class="col">

![w:520 center](./imgs/tpm007.jpg)

</div>

</div>

---

<!-- _header: Technische Wünsche -->
<!-- footer: 'Danke, [Stay Forever](https://www.stayforever.de/)!' -->

<div class="container">

<div class="col75">

- Kapitelmarken und Shownotes
  - sollten selbstverständlich sein
- **Audio-visuelles** Medium
- Ton sinnvoll mit **Kapitelbildern*** ergänzen
  - z.B. Detailshots der Geräte
  - Abwägung: Kontext muss auch ohne Bilder gegeben sein
- **Transkripte**
  - Barrierefreiheit und SEO

</div>

<div class="col">

![w:370 center](./imgs/chapters.jpg)

</div>

</div>

<!--
- Transkripte nicht nur für Gehörlose interessant, auch Menschen mit Konzentrationsschwierigkeiten profitieren davon
-->

---

<!-- _header: Branding -->
<!-- footer: 'Nein, das steht _nicht_ für **T**rusted **P**latform **M**odule! 🤡' -->

<div class="container">

<div class="col75">

- ThinkPad-Museum war naheliegend, ThinkPod bereits vergeben
- **TPM*** als Episoden-Prefix
- **Cover** mit TrackPoint für direkte Assoziation
- **Audioschema**
  - Stundenlang die üblichen **Kataloge** (u.a. [AudioJungle](https://audiojungle.net/)) durchsucht
  - wollte ein elektronisches Schema mit ikonischen ThinkPad-**Sounds**
  - Musiker im Bekanntenkreis kreierte exakt das 🥰

</div>

<div class="col25">

![w:320 center](./imgs/cover.jpg)

<audio controls>
  <source src="imgs/tp_sounds.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio> 

<audio controls>
  <source src="imgs/tpm_intro.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>

</div>

</div>

</div>

---

<!-- _header: Arbeitsorganisation -->
<!-- footer: 'Ein Desktop-Wiki oder Cloud-Dienst tut es auch' -->

- **Markdown**-Dokumente in **Git**-Repositories*
  - Repos für Episoden, Artwork, Webseite
  - Lesseons Learned: Git **LFS** für große Bilder
- **Kanban-Board** und Issues für Episoden-Planung
  - **Tags** für verschiedene Themen
- Pro Episode **zwei** Markdown-Dokumente
  - Inhaltliche Stichpunkte und Kapitel (`notes.md`)
  - Recherche-Notizen und Quellensammlungen (`dossier.md`)

<!--
- Repository kann mit Gäst:innen geteilt werden
- nicht ablesen, aber Stichpunkte und Moderationsanweisungen helfen
  - großer Unterschied alleine einen Podcast aufzunehmen vs. mit mehreren Menschen
 -->

---

<!-- _header: Arbeitsorganisation -->
<!-- footer: '' -->

![w:1200 center](./imgs/kanban.png)

---

<!-- _header: Tools -->
<!-- footer: 'Stabile Linux-Version wann? 👉🏻👈🏻🥹' -->

- Focusrite **Scarlett Solo** Gen 3 + beyerdynamic **DT 797 PV**
  - hier tut es auch was Günstigeres (z.B. RØDE NT-USB Mini)
  - ich finde Sprechgarnituren einfacher zu nutzen als Standmikrofone
- [REAPER](https://www.reaper.fm/) und [UltraSchall](https://ultraschall.fm/)*, [Studio-Link](https://studio-link.de/) für Gäst:innen
- Terminplanung mit [nuudel](https://nuudel.digitalcourage.de/)
- [GIMP](https://www.gimp.org/) für Bilder und Artwork
- [whisper.cpp](https://github.com/ggerganov/whisper.cpp) für Transkripte
- Statische Webseite mit [Hugo](https://gohugo.io/)
  - angepasstes [`hello-friend-ng` Theme](https://github.com/rhazdon/hugo-theme-hello-friend-ng)

<!--
- Scarlett Solo ca. 99 EUR
- DT 797 PV ca. 450 EUR
- UltraSchall perfekt für Leute die wenig Ahnung von Audio haben
  - UltraSchall auf MacBook Pro statt ThinkPad 🥲
-->

---

<!-- _header: Workflow -->
<!-- footer: '' -->

<div class="container">

<div class="col">

1. Themenauswahl (aus Backlog)
1. **Recherche** (Internet, Bücher)
1. Aufzeichnung
1. Schnitt und Post-Production
1. Kapitelmarken und **-bilder**
1. Export
1. **Transkript** erstellen lassen

= **~10h** pro Episode ⏲️

</div>

<div class="col">

![w:600 center](./imgs/whisper.png)

CPU goes brrr 🔥

</div>

</div>

---

<!-- _header: Schnitt und Postproduction -->

- Sprechpausen und **Versprecher** schneiden
- Nebengeräusche entfernen
- Sprachtracks **-23 LUFS** normalisieren
- Pro **Sprachtrack** aktivieren
  - VST: ReaEQ (Cockos)
  - JS: Ultraschall Dynamics
- JS: LUFS Loudness Metering auf **Mastertrack** aktivieren
- Export mit **Meta**-Informationen
  - Titel, Autor, Podcast, Jahr, Kategorie und Beschreibung

---

<!-- _header: Transkripte -->
<!-- footer: '' -->

- Es gibt zahlreiche **Services** für automatisierte Transkripte
  - Kosten pro Minute/Episode (oder persönlichen Daten)
- Ein Museum zu betreiben ist schon kostenintensiv genug 🫠
  - außerdem Freund des **Self-Hostings**
  - Webserver und lokale Rechenpower sind schon vorhanden

<div style="display:contents;" data-marpit-fragment>

- [OpenAI Whisper](https://github.com/openai/whisper) ist ein kostenfreies Modell für **Spracherkennung**
  - kann auf eigener Hardware benutzt werden
  - erfordert jedoch eine **NVIDIA**-Grafikkarte
  - mit [whisper.cpp](https://github.com/ggerganov/whisper.cpp) gibt es einen Fork mit **CPU**-Support
  - benötigt auf meiner Hardware die **~1,5-fache** Episodenlänge

</div>

---

<!-- _header: Hosting -->

- Es gibt zahlreiche Hosting-Angebote mit fairen Preisen
- Im Prinzip tut es aber schon ein einfacher Webserver
  - Feeds können auch mit Tools wie [Hugo](https://brendamour.net/2021/04/18/how-to-publish-podcasts-with-the-hugo-static-site-generator/) erstellt werden
  - Es gibt auch Plugins für gängige **CMS** wie WordPress

<div style="display:contents;" data-marpit-fragment>

- Im Fediverse bin ich auf [Castopod](https://castopod.org/) gestoßen
  - erfolgreich den regionalen Mastodon-Instanzbetreiber **generdsniped**
  - erster Podcast auf [podcasts.darmstadt.social](https://podcasts.darmstadt.social/) 🎉

</div>

---

<!-- _header: Castopod -->

<div class="container">

<div class="col">

- **Open Source-Plattform** für Podcast-Hosting
- Einfach zu benutzende WebUI
- unterstützt **ActivityPub**
  - kann direkt aus Mastodon und co. abonniert werden
  - Community-Interaktion
- zahlreiche **Zusatzfunktionen**
  - Themes
  - SEO, Monetarisierung

</div>

<div class="col">

![w:500 center](./imgs/castopod_logo.png)

![w:500 center](./imgs/castopod_screenshot.png)

</div>

</div>

<!--

- ermöglicht mehrere User und Podcast-Feeds

-->

---

<!-- _header: Castopod -->

- in **PHP** entwickelt
- kann u.a. via **Docker** oder Podman gehostet werden

<div style="display:contents;" data-marpit-fragment>

- Fiese **Stolperfalle**: [fehlender `range-requests`-Support im vorgefertigten Container-Image](https://code.castopod.org/adaures/castopod/-/issues/446)
  - zwingend von **Apple Podcasts** für Episodenstreams benötigt
  - Troubleshooting [trotz toller Hilfe](https://sendegate.de/t/apple-podcasts-die-folge-konnte-nicht-wiedergegeben-werden-versuche-es-erneut/16806) war nicht trivial
  - Lessons Learned: [Feed-URL validieren](https://www.castfeedvalidator.com/)

</div>

---

<!-- _header: Feed validieren -->

<div class="container">

<div class="col">

![w:580 center](./imgs/validate01.png)

</div>

<div class="col">

![w:600 center](./imgs/validate02.png)

</div>

</div>

---

<!-- _header: Marketing -->

- Ein Account auf [podcasts.social](https://podcasts.social) ist Pflicht!
  - Posts für **Episoden**, aber auch direkte Community-**Interaktion**
  - Best Practice: Aktuelle Episode ans Profil **pinnen**
  - **Bubble** aufbauen: **Hashtags** verfolgen, an **Konversationen** beteiligen

<div style="display:contents;" data-marpit-fragment>

- Feed in Datenbanken, wie [fyyd](https://fyyd.de/) eintragen
  - oft gibt es auch Special Interest-Projekte, wie z.B. [wisspod](https://wissenschaftspodcasts.de/)
- An anderen **Communities** beteiligen (z.B. [thinkpad-forum.de](https://thinkpad-forum.de))

</div>

<div style="display:contents;" data-marpit-fragment>

- Konferenzen wie diese besuchen (duh!)
  - Menschen lieben **Sticker** ✨
- **Kollaborationen** mit befreundeten Podcasts

</div>

<!--
- Postet was mit dem #thinkpad-Hashtag und ich antworte euch sehr wahrscheinlich
-->

---

<!-- _header: Analytics -->

- Selbstgehostetes [Matomo](https://matomo.org/) für die **Webseite** (Klicks/Quellen)
- [Mastometrics](https://mastometrics.com) für Mastodon-**Interaktionen**
- [OP3](https://op3.dev/) (**O**pen **P**odcast **P**refix **P**roject) für **Episoden**-Downloads
  - Client-Informationen über Weiterleitungen, erfordert Feed-Anpassung

![w:1000 center](./imgs/matomo_tpm.jpg)

<!--

- Podcasting soll Spaß machen, Analytics bitte nicht zu ernst nehmen
- OP3
  - Open Source-Service für datenschutz-konforme Podcast-Metriken
  - freie API, Quellcode kann auf GitHub eingesehen werden

-->

---

<!-- _header: Analytics (Mastometrics) -->

![w:1000 center](./imgs/mastometrics.png)

---

<!-- _header: Analytics (OP3) -->

![w:1200 center](./imgs/op3_01.png)

---

<!-- _header: Analytics (OP3) -->

![w:1180 center](./imgs/op3_02.png)

---

<!-- _header: Fazit und Ausblick -->

- Podcasts produzieren **macht Spaß**
  - es gibt für **alles** eine Nischen-Bubble
  - die Podcast-Szene freut sich aber über kuriose Themen
  - probiert es einfach aus - **Vielfalt** ist gut!

---

<!-- _header: Links und Bilderquellen -->

<div class="container">

<div class="col">

- [MRMCD 2024: ThinkPads - Eingabegeräte und Kuriositäten (Teil 2)](https://media.ccc.de/v/2024-339-thinkpads-geschichte-und-trivia) 🎥
- [FrOSCon 2024: ThinkPads - Geschichte und Nerdkultur (Teil 1)](https://media.ccc.de/v/froscon2024-3141-thinkpads) 🎥
- [BW099 - Ein denkwürdiges Notebook](https://besserwissen.podigee.io/99-thinkpad) 🎙️
- [HK003 - ThinkPads](https://hacker-kultur.de/episodes/003.html) 🎙️
- [ThinkPad Sounds](https://www.youtube.com/watch?v=G9vCBDV4ts4)
- [ThinkPad-Museum](https://thinkpad-museum.de)

</div>

<div class="col">

1. [IBM PC Convertible Model 5140](https://richardsapperdesign.com/products/mod-5140/)
1. [Artemide Tizio](https://commons.wikimedia.org/wiki/File:Lampe_Tizio_von_Richard_Sapper.jpg)
1. [ThinkPad T61 (Knives Out)](https://productplacementblog.com/movies/lenovo-thinkpad-t61-laptop-used-by-christopher-plummer-as-harlan-thrombey-in-knives-out-2019/)
1. [ThinkPad 701C](https://en.wikipedia.org/wiki/File:IBM_ThinkPad_701C_keyboard.jpg)
1. [ThinkPad W701](https://thinkwiki.de/W701)
1. [IBM Leapfrog](https://richardsapperdesign.com/products/leapfrog/)
1. [ThinkPad 360PE](https://commons.wikimedia.org/wiki/Category:ThinkPad_360PE)

</div>

</div>

---

<!-- _class: lead -->

# 🔴 Danke für die Aufmerksamkeit
