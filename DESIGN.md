Designüberlegungen zu NEO auf der Truly Ergonomic
=================================================

Ich will hier kurz darlegen, was ich wo hin gelegt habe und warum.
Diese Begründungen sind oft subjektiv, bzw. meinen
häufigsten/wichtigsten Anwendungsfällen geschuldet.

„Wiki“ meint die Seite „Tips und Tricks zum Truly Ergonomic…“ im Neo-Wiki:
http://wiki.neo-layout.org/wiki/Hardwareentwicklung/Truly


Vorab: meine Anwendungsfälle
---------------------

Ich bin kein reiner Textvielschreiber.  Häufiger programmiere ich (R,
Lisp, Javascript), benutze die Shell oder schreibe LaTeX, manchmal
HTML.  Als Editor verwende ich hauptsächlich Emacs.  Beim Surfen im
Netz, Texte am Bildschirm Lesen und GUI-orientierte Programmen mische
ich Maus und Tastatur; darum liegt mir daran, wichtige Tasten und
Tastenkombinationen einhändig bedienen zu können (z.B. + bzw. Strg-+
zum Zoomen, Cursortasten, PgUp/Down, Home, End).


Die beiden Steuertastenkreuze
-----------------------------

Ich finde die vierte Ebene großartig, vor allem beim Editieren und
längere Texte schreiben.  Aber beim Rumlümmeln vorm Rechner beim
Surfen usw. (Kopf auf die Hand gestützt oder Hand an der Maus) hätte
ich gerne, wie oben gesagt, wichtige Steuertasten unkompliziert
greifbar.  Darum lasse ich im Unterschied zu den Vorschlägen im Wiki
beide „Steuerkreuze“ wie sie sind.

Allerdings liegen `End` und `<-` recht angenehm als Daumentaste.  Für
den Emacs könnte ich mir da Alt-Tasten vorstellen.  Vielleicht mach
ich das als Option für längere Editor-Sitzungen.


Vertauschen von j und y
-----------------------

Wie alle im Wiki vertausche ich `j` und `y`, so daß `j` an den
angestammten Platz kommt und `y` neben `x`.


Shift, Control und Enter
------------------------

Ich finde die Shift-Tasten auf Höhe der Grundlinie ganz angenehm.  In
der Mitte auf `Enter` (Wiki: Wolf) habe ich mal probiert, aber meine
Daumen sind für diese häufige Benutzung zu kurz, darum lasse ich auf
dieser Taste `Enter` bestehen.  (Verlängerungen drankleben möchte ich
erstmal nicht.)

Control brauche ich im Emacs dauernd.  Die deutlich höhere Lage im
Vergleich zur Standardtastatur ist ein Segen.  (In Vor-Neo-Zeiten
hatte ich Control immer auf `CapsLock` gelegt, damit wenigstens die
linke Hand nicht so runterkrallen muß.)

Der Nachteil ist, daß diese attraktiven Tasten nicht mehr für `Mod3`
und `Mod4` zur Verfügung stehen.


Tab auf linker Space-Taste
--------------------------

Ich schlage die Leertaste schon seit jeher immer nur mit rechts an,
darum ist der linke Daumen frei.  In der Shell, aber auch beim
Programmieren und Browsen, verwende ich Tab *sehr* häufig.

Für eine der Mod-Tasten kam die linke Leertaste mangels symmetrischem
Pendant für mich nicht in Frage.


Plus und Minus
--------------

Die Taste `-` rechts oben (neben der Null) lasse ich so wie sie bei
NEO ist.  Die `+ =`-Taste ganz rechts oben bekommt die Belegung von
Ziffernblock-`+`, mit einer Ergänzung: Umschalt-`+` ergibt `=` statt
nur wieder `+`. (Damit hat man ein bißchen mehr von dieser Taste, und
die Belegung passt auch besser zum Tastenbild.)

Damit ist bei mauslastigen Programmen Zoomen etc. mit der freien Hand
(Bei mir praktischerweise rechts…) bequem möglich.  Auch `Strg-+`
bzw. `-`, wie sie Firefox verwendet, sind dann noch einhändig
benutzbar.


Akzenttasten
------------

Das TECK hat nur zwei Akzenttasten (links oben): Akut und Gravis; ein
Circumflex fehlt.  Möchte man Standard-NEO möglichst nahe kommen,
sollte T1 („Circumflex“) links neben `1` auf der Gravis-Taste liegen,
T2 („Gravis“) rechts neben `0` und `-` auf der Plus-Taste und T3
(„Akut“) auf der schließenden eckigen Klammer.

Da ich die Plus-Taste als solche erhalten möchte, muß zumindest T2
woanders hin.  Und weil ich Akzente selten verwende und mir ihre Lage
in Standard-NEO noch nicht eingeprägt habe, bevorzuge ich T3 und T2
auf den Akut- und Gravis-Tasten, damit sie zum Tastenbild passen.

T1 kann dann entweder auf `] }` oder `\ |`, da habe ich keine
wirkliche Präferenz.  Ich habe jetzt `\ |` genommen, dann sind alle
Akzenttasten beisammen.  Andererseits liegen sie damit auch auf der
Vokal-Seite (mit denen sie ja hauptsächlich verwendet werden); für die
paar Male stört mich das nicht.

Evtl. könnte man da eine XKB-Option draus machen.


Weitere mögliche Anpassungen
----------------------------

Diese Ideen muß ich noch ausprobieren:

**Mod3 auf schwarzen Tasten?**

Damit wären für Emacs C- und M-Kombinationen mit 3.-Ebene-Zeichen
greifbarer.  Beispiele: `M-%`, `C-)`, `M--`


**T1 auf `CapsLock`, Mod3/4 auf `\ |` und `] }`**

Ein bißchen ärgerlich ist, daß ohne T1 die beiden Außentasten über
Umschalt frei wären für `Mod3` oder `Mod4`.  Vielleicht könnte man T1
nach oben auf `CapsLock` verbannen, das ja nicht gebraucht wird.  Dann
ist T1 zwar kaum noch „blind“ zu erreichen (zumindest alles andere als
bequem), aber wie gesagt brauche ich Akzente selten.


**Umschalt-`-` als Minus**

Das „echte Minus“ ist bei NEO nur über den Ziffernblock erreichbar.
Die `-`-Taste (rechts von `0`) ist auf Ebene 2 nicht belegt.  Da
könnte das Minus hin.

Das ist aber nicht rein TECK-spezifisch, könnte für Standard-NEO
vielleicht auch interessant sein.
