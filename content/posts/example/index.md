+++
title = "Perisa Buchmann"
date = "2023-01-01"
draft = true
pinned = false
tags = ["Lilo", "Example"]
image = "/img/default-image.jpg"
description = "Über Perisa Buchmann die so schön ist das man es kaum fassen kann. Sie ist eine juge liebe Frau die von ihren Freundinnen Schnüggeli genannt wird."
footnotes = "In der Fusszeile können zum Beispiel Bildquellen angegeben werden. Dieser Text ist abgetrennt durch eine Linie und etwas kleiner."
+++
In einer malerischen kleinen Stadt, umgeben von sanften Hügeln und einem klaren Fluss, lebte eine junge Frau namens Perisa Buchmann. Sie war für ihre atemberaubende Schönheit bekannt, die die Menschen in ihrer Umgebung immer wieder in Erstaunen versetzte.

Perisa, liebevoll von ihren Freunden "das Schnüggeli" genannt, besaß eine Schönheit, die jenseits der Worte lag. Ihr langes, seidiges Haar fiel in sanften Wellen über ihre Schultern, umrahmte ihr Gesicht mit einer bezaubernden Eleganz. Die Augen von Perisa waren wie zwei funkelnde Edelsteine, tief und geheimnisvoll, und sie strahlten eine unbeschreibliche Wärme aus. Ihre Lippen trugen stets ein bezauberndes Lächeln, das die Herzen der Menschen im Sturm eroberte.

Perisa war jedoch nicht nur schön von außen, sondern auch von innen. Sie besaß eine Güte und Sanftmut, die jeden, der ihr begegnete, berührte. Sie war stets bereit, anderen zu helfen und ein offenes Ohr für ihre Sorgen zu haben. Ihre Freundlichkeit kannte keine Grenzen, und sie verbreitete Freude und Liebe, wohin sie auch ging.

Die Menschen in der Stadt bewunderten Perisa nicht nur für ihre äußere Schönheit, sondern auch für ihre inneren Qualitäten. Sie war eine Quelle der Inspiration für viele, die von ihrem edlen Charakter und ihrer aufrichtigen Freundlichkeit beeindruckt waren.

Eines Tages kam ein Wanderer in die Stadt, ein junger Mann namens David, der von fernen Ländern und Abenteuern träumte. Als er Perisa zum ersten Mal sah, war er sofort von ihrer Schönheit und Anmut verzaubert. Doch während er sich langsam in Perisa verliebte, erkannte er auch ihre wahren Qualitäten jenseits ihres Aussehens. Er schätzte ihre Freundlichkeit, ihre Sanftmut und ihre Großzügigkeit und erkannte, dass sie weit mehr war als nur ein hübsches Gesicht.

Die beiden verbrachten viel Zeit miteinander, teilten ihre Träume und Hoffnungen und erlebten gemeinsam viele Abenteuer. Mit der Zeit wuchs ihre Liebe und Festigkeit, und sie wussten, dass sie füreinander bestimmt waren.

Perisa Buchmann, das Schnüggeli, war nicht nur eine Frau von atemberaubender Schönheit, sondern auch eine Seele voller Güte und Liebe, die die Herzen der Menschen berührte und die Welt um sie herum mit ihrem Licht erhellt. Und in ihrer Liebe zu David fand sie das größte Glück, das sie sich je hätte vorstellen können



















![<3](bildschirmfoto-2022-08-25-um-14.45.55-kopie.png "Perisa Buchmann das Schnüggeli")

**Empfehlung für Bilder**: Meist empfiehlt sich, ein Bild ganz zuoberst im `Inhalt`-Feld einzufügen. Zusätzlich sollte man dieses auch im `Bild`-Feld angeben, damit es in der Blogübersicht erscheint.

### Tipps zu Bildgrössen

Ein Richtwert für Bilder ist, dass diese wenn möglich nicht grösser als `400kb` sein sollten. Man kann sie so verkleinern, dass die Breite höchstens `1200px` gross ist. Dies ist für die meisten Bildschirme mehr als genug.

### Bildunterschrift

Wenn bei einem Bild ein `ALT TEXT` erfasst wird, so wird dieser als Bildunterschrift im Artikel angezeigt.

## Horizontale Linie

Eine Horizontale Linie kann man entweder durch ein `<hr>` einfügen oder indem man im `Markdown`-Modus drei Striche `---` einfügt. So sieht die Linie aus:

- - -

## Lead

{{<lead>}}
Oft haben Artikel unterhalb des Haupttitels einen einführenden Lead, der etwas grösser dargestellt wird.
{{</lead>}}

`{{</*lead*/>}}`\
Ein Lead steht zwischen zwei solchen Blöcken.\
`{{</*/lead*/>}}`

## Kasten

{{<box>}}
In dieser Box können Texte, Bilder, Videos oder andere Inhalte dargestellt werden.
{{</box>}}

`{{</*box*/>}}`\
Der Inhalt einer Box muss wie hier von zwei Blöcken umgeben werden.\
`{{</*/box*/>}}`

{{<box title="Ausklappbare Box">}}
Wird ein Titel angegeben, so kann die Box ausgeklappt werden.

Dies eignet sich auch für längere Inhalte.

![](/img/default-image.jpg)

Auch Bilder können in eine Box gepackt werden.
{{</box>}}

`{{</*box title="Ausklappbare Box"*/>}}`\
Wird ein Titel angegeben, so kann die Box ausgeklappt werden.\
`{{</*/box*/>}}`

## Video, Audio und andere Medien einbetten

Es kann auch `HTML-Code` eingefügt werden. Manchmal geht dies etwas einfacher, wenn man dazu in den `Markdown`-Modus wechselt.

Damit können zum Beispiel Filme, Audiodateien oder Karten eingebettet werden. Meist sind auf den entsprechenden Plattformen (YouTube, Vimeo, Google Maps, etc.) entsprechende Code-Ausschnitte vorbereitet, die man direkt in den Blog einfügen kann. Am besten auf der jeweiligen Plattform nach einem Knopf für `embed` oder `share` suchen.

Bei Videos ist es ideal, wenn sie sich automatisch **an die Bildschirmgrösse anpassen**. Dies geht am einfachsten mit den hinterlegten YouTube- und Vimeo-Codes:

### YouTube einbetten

Einbetten von YouTube-Videos mit dem Code: `{{</*youtube video_id*/>}}`

(Die `video_id` steht bei jedem YouTube-Video in der Browser-URL.)

{{<youtube kQjtK32mGJQ>}}

### Vimeo einbetten

Einbetten von Vimeo-Videos geht mit dem Code: `{{</*vimeo video_id*/>}}`

{{<vimeo 194276412>}}

### Code und Code-Blöcke

Mit dem Code-Symbol `<>` können Wörter auf `diese Art` hervorgehoben werden. Dies wird zum Beispiel für Tastenkombinationen wie `ctrl+s` oder für `Programmiercode` verwendet. Auch Math-Formeln können so ausgedrückt werden: `y = mx + b`.

Für längere solche Abschnitte verwendet man am besten das Code-Block-Symbol. Damit wird ein solcher Block erstellt:

```
const sun1 = "sun" + "il";
const sun2 = "su" + "n" + "il";
sun1 === sun2;
```

## Spass haben

😀 Viel Spass mit deinem Blog!