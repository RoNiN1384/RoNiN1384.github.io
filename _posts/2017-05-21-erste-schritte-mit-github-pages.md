---
layout: post
title: "GitHub Pages und Jekyll"
description: "Als Beginner bei GitHub und speziell beim Erstellen einer Seite mittels GitHub Pages gibt es ein paar kleine Steinchen, über die ich prompt gestolpert bin."
comments: false
keywords: "GitHub, GitHub Pages, Jekyll, kramdown, _config.yml"
---

## Erste tapsige Schritte

<p class="justify" markdown="1">
Am Anfang dachte ich mir es wäre eine gute Idee meine Gedanken zu verschiedensten Themen, die mir so durch die hohle Birne schießen, ohne großen Aufwand einfach bei GitHub abzulegen. Eine Versionsverwaltung, nicht nur für den Inhalt, sondern darüber hinaus für das ganze Drumherum (z.B. das Layout und die dazugehörigen Stylesheets) ist meines Erachtens eine feine Sache und so habe ich mich dafür entschieden einen Versuch mit dem zu GitHub gehörenden Dienst GitHub Pages[^01] zu wagen.
</p>

<p class="justify" markdown="1">
Es ist mir dabei nicht entgangen, dass GitHub an dieser Stelle Nutzern die *Magie* von Jekyll[^02] an die Hand gibt. Also mal fix rein geschaut, was man mit Jekyll denn so alles anstellen kann und direkt gefallen daran gefunden, dass ich damit kein Content Management System[^03] in die Weiten des Internet hinaus schicken muss um meine frohe Kunde zu verbreiten. Stattdessen kann ich nun meine geistigen Ergüsse veredelt durch die *Magie* Jekylls als statische Inhalte losziehen lassen um hier und dort kapernden und brandschatzenden Gesindel so wenig Angriffsfläche wie möglich zu bieten. Schließlich kann selbst die kleinste dynamische Nußschale noch Angriffen ausgesetzt sein und möchte hin und wieder durch Updates gestärkt werden, damit diese nicht gelingen. Über das Für und Wider eines Content Management Systems werde ich mich hier zu einem späteren Zeitpunkt noch einmal auslassen, also zurück zum Text.
</p>

<p class="justify" markdown="1">
Nun habe ich mich also aufgemacht GitHub Pages und Jekyll einen Besuch abzustatten in der Hoffnung, dass wir alsbald allerbeste Freunde würden. Dank einer recht ausführlichen Kommunikationsrichtlinie[^04] gelang es mir in der Verständigung recht schnell erste Erfolge zu erzielen. Erst einmal ein Repository für unser zukünftiges Baby nach der Formel `USERNAME.github.io`{: .inlined }[^05] erstellt, ein Aussehen[^06] festgelegt, hier und da ein wenig an den Schräubchen gedreht und dann mal geschaut, welche magischen Kräfte Jekyll noch vor mir verbirgt.
</p>

<p class="justify" markdown="1">
Da gab es offensichtlich einiges, was mir durch die beiden vorenthalten wurde, was aber alsbald ans Tageslicht kam, als ich mir Jekyll mal zur Seite nahm und Ihn zu mir einlud[^07]. Erst in einem persönlichen Gespräch - ohne die Anwesenheit von GitHub - wurde mir gewahr, dass er doch ganz schön unter der Herrschaft von GitHub zu leiden hat und sein volles Potenzial erst bereitwillig entfaltete, als ich Ihn mir ins Vertrauen nahm und seinen ganz persönlichen Ausführungen[^08] lauschte. Besonders hatte es mir der Komfort Ihm Tipps zur Organisation[^09] meiner Habseligkeiten (unter Seiner Obhut) z.B. mittels `source: DIR`{: .inlined } aufgeben zu können angetan.
</p>

## Die Odyssee beginnt

<p class="justify" markdown="1">
Unter meiner Obhut verhielt sich Jekyll wie von mir erwartet und ich war froher Dinge Ihn nun also von meinen Vorstellungen überzeugt zu haben. Also schickte ich mein Hab und Gut auf die Reise und rechnete nicht damit, dass GitHub meinem neu gewonnen Freund die Leviten lesen wird und all meine Organisation direkt wieder zu nichte macht. Anfangs war mir überhaupt nicht bewusst, wo denn nun der Haken ist und warum mir GitHub statt meiner Seite zu Testzwecken nur diese schnöde "Ich will diese Seite aber nicht anzeigen" Meldung vorsetzte:
</p>

![GitHub Pages 404]({{ site.url }}/assets/images{{ page.id }}/github-404.PNG){:class="center"}

<p class="justify" markdown="1">
Doch nach ausgiebigem Studium der mir gebotenen Erläuterungen[^04] fand ich schließlich heraus, dass GitHub hinter den Kulissen gegen mich intrigierte und die gegebene `_config.yml`{: .inlined } zurechtstutzte[^10].
</p>

> AAAAAAAAAAAAAAAARRRRRGGGGHHHH!!!!!1!11elf

Ok, tief durchatmen und das Ganze erst einmal ruhen lassen.

## Auf ein Neues

<p class="justify" markdown="1">
Es fällt also schon mal flach, dass ich den ganzen Content in einen extra Ordner packen kann, das ist schade aber letztlich dann doch kein Beinbruch. Wenn mir GitHub schon diese Möglichkeit nimmt, will ich es doch wenigstens beim Design der Seite etwas individueller haben. Dazu habe ich neue Kleider für meinen Freund Jekyll herausgesucht[^11] und wie man sieht noch meine eigene Note verpasst. Nun gut, mit dem neuen Design also wieder zurück zu GitHub. Das Design "geforkt", angepasst und dann in mein Seitenrepository übernommen. Zum Abschluss den Beispielinhalt wegputzen und hiermit meinen ersten eigenen Inhalt erstellen und voila:
</p>

![Startseite]({{ site.url }}/assets/images{{ page.id }}/startseite.PNG){:class="center"}

<p class="justify" markdown="1">
War doch gar nicht so schwer, zumindest dann nicht, wenn man nicht wie ich gerne seinen eigenen Weg geht, GitHub schränkt den Spielraum für meinen Geschmack ein wenig zu weit ein. Einerseits schaffen Sie damit einen sehr einfachen Einstieg, andererseits wie auch in meinem Fall ein paar verquere Stolperfallen, auf die ich so nicht gefasst war. Ich werde sehen, wie sich diese anfängliche Hassliebe mit GitHub Pages entwickelt und was für Überraschungen in diesem Zusammenhang noch auf mich warten. Z.B. habe ich die Seite noch nicht mit meiner eigenen Domain unterlegt und die ganzen Möglichkeiten von Jekyll habe ich auch noch nicht ausgelotet - Stichwort kramdown[^12].
</p>

Aber das ist eine andere Geschichte, für einen anderen Beitrag zu einer anderen Zeit, in diesem Sinne wünsche ich euch allen eine gute Nacht.

<p class="right" markdown="1">
Michael H.
</p>

---

[^01]: [GitHub Pages, Offizielle Seite](https://pages.github.com/){:target="_blank"} - abgerufen am 21.05.2017
[^02]: [Jekyll, Offizielle Seite](https://jekyllrb.com/){:target="_blank"} - abgerufen am 21.05.2017
[^03]: [Content Management System, Artikel bei Wikipedia](https://de.wikipedia.org/wiki/Content-Management-System){:target="_blank"} - abgerufen am 21.05.2017
[^04]: [Using Jekyll as a static site generator with GitHub Pages](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/){:target="_blank"} - abgerufen am 21.05.2017
[^05]: [User & Organization Pages](https://help.github.com/articles/user-organization-and-project-pages/#user--organization-pages){:target="_blank"} - abgerufen am 21.05.2017
[^06]: [Supported Themes](https://pages.github.com/themes/){:target="_blank"} - abgerufen am 21.05.2017
[^07]: [Install with RubyGems](https://jekyllrb.com/docs/installation/#install-with-rubygems){:target="_blank"} - abgerufen am 21.05.2017
[^08]: [Jekyll Dokumentation](https://jekyllrb.com/docs/home/){:target="_blank"} - abgerufen am 21.05.2017
[^09]: [Jekyll globale Konfigurationseinstellungen](https://jekyllrb.com/docs/configuration/#global-configuration){:target="_blank"} - abgerufen am 21.05.2017
[^10]: [Configuration settings you cannot change](https://help.github.com/articles/configuring-jekyll/#configuration-settings-you-cannot-change){:target="_blank"} - abgerufen am 21.05.2017
[^11]: [Thinkspace - just another minimalist Jekyll theme](http://jekyllthemes.org/themes/thinkspace/){:target="_blank"} - abgerufen am 21.05.2017
[^12]: [kramdown, Offizielle Seite](https://kramdown.gettalong.org/){:target="_blank"} - abgerufen am 21.05.2017
