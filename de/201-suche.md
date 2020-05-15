---
next: 'Voice benutzen'
next_href: '200-using-voice'
next_aria: 'voice benutzen'
---
# Die Suchfunktion
Die Voice-Suchfunktion erfasst nur unterstützte Texte; Alttexte werden nicht durchsucht.

<details><summary><h4>Nach einem Sutta suchen</h4></summary>

Um ein bestimmtes Sutta anzuzeigen, geben Sie das entsprechende Kürzel ein, wie etwa: 
<kbd>AN12.23</kbd>

Für eine längere Wiedergabeliste können Sie Suttakennziffern mit Kommas abtrennen:
<kbd>SN12.22, SN12.23</kbd>

Für eine Reihe aufeinanderfolgender Suttas können Sie auch einen Bindestrich benutzen:
<kbd>SN12.22-23</kbd>

Die Suttas, die Sie als Suchergebnisse erhalten, können Sie entweder online hören oder herunterladen.

##### Sprache und Übersetzer

Wenn Sie eine bestimmte Übersetzung suchen, geben Sie Sprache und Übersetzer an. Zum Beispiel:

* <kbd>mn23/de/mettiko</kbd> ist die deutsche Übersetzung von MN 23 von Bhikkhu Mettiko.
* <kbd>mn23/de/sabbamitta</kbd> ist die deutsche Übersetzung von MN 23 von Anagarika Sabbamitta.

Wenn Sie nach einer anderen Sprache suchen wollen, ändern Sie bitte die Übersetzungssprache in den Einstellungen.

</details><!--COMMENT: Sutta Search-->

<details><summary><h4>Nach einer Wendung suchen</h4></summary>

Geben Sie eine exakte Wendung ein (unabhängig von Groß- oder Kleinschreibung), um ein Sutta mit dieser Wendung zu finden. Zum Beispiel: <kbd>Wurzel des Leidens</kbd>.

Für Wendungen auf Pali können Sie Wörter in lateinischer Schrift ohne diakritische Zeichen eingeben: <kbd>chando hi mūlaṃ dukkhassa</kbd>

Wenn man sich über Wortendungen nicht sicher ist, kann man auch Teile einer Wendung eingeben: <kbd>mūlaṃ dukkha</kbd>
</details><!--COMMENT: Phrase Search-->

<details><summary><h4>Nach Schlüsselwörtern suchen</h4></summary>

Wenn Sie sich nicht genau an eine Wendung erinnern können, geben Sie einfach die Worte, die Sie wissen, durch Leerzeichen getrennt ein. Voice wird die Suttas finden, in denen alle Suchwörter vorkommen. Zum Beispiel: <kbd>leiden wurzel</kbd>

Die Suche nach Schlüsselwörtern ist langsamer als die Suche nach einer Wendung und kann zu mehr Ergebnissen führen.
</details><!--COMMENT: Keyword search-->

<details><summary><h4>Suchergebnisse</h4></summary>

Die Suchergebnisse werden nach Relevanz angeordnet. Der Relevanzwert ist einfach die Summe aus der Anzahl der Treffer und dem Anteil der Segmente, die einen Treffer enthalten. Suttas, in denen der Suchbegriff häufig vorkommt, haben die höchste Relevanz.

Voice zeigt normalerweise bis zu fünf Suchergebnisse an. Benutzen Sie die [Einstellungen](/dhammaregen/de/201-einstellungen), wenn Sie die maximale Zahl der Suchergebnisse erhöhen wollen. Für mehr Suchergebnisse dauert es länger.
</details><!--COMMENT:Number of Search Results-->

<details><summary><h4>Erweiterte Suche</h4></summary>

#### Reguläre Ausdrücke

Viele Benutzer von SuttaCentral nutzen `grep` für die Suche. `grep` ist ein sehr leistungsstarkes Suchprogramm und unterstützt auch die Möglichkeit, [Treffer](https://www.google.com/search?q=grep+-E+option) über [reguläre Ausdrücke](https://de.wikipedia.org/wiki/Regul%C3%A4rer_Ausdruck) zu finden. Voice unterstützt [Ripgrep](https://github.com/BurntSushi/ripgrep) mit regulären Ausdrücken (z. B. <kbd>wurzel.\*leiden</kbd>).

#### Suchparameter

Sie können Ihre Suche mit erweiterten Einstellungen anpassen. Erweiterten Einstellungen wird ein Minuszeichen "-" vorangestellt:

* **-sl ISO_LANG_2**  Legt die Sprache für die Suche fest, z. B.: <kbd>-sl de</kbd> durchsucht deutsche Texte.
* **-d NUMBER**  Legt die maximale Zahl der Ergebnisse fest, z. B.: <kbd>-d 50</kbd> findet bis zu 50 Suttas.
* <kbd>-ml 3</kbd>  Zeigt nur Ergebnisse, die in drei Sprachen vorliegen.
* <kbd>-tc:mn</kbd> Beschränkt Suchergebnisse auf den Majjhima Nikaya.

| Parameter | Zu durchsuchende Texte |
| :-----: | :-----: |
| -tc:ab | Abhidhamma |
| -tc:an | Aṅguttara Nikāya |
| -tc:as | Adhikaraṇasamatha |
| -tc:ay | Aniyata |
| -tc:bi | Bhikkhuni |
| -tc:bu | Bhikkhu |
| -tc:dn | Dīgha Nikāya |
| -tc:kd | Khandhaka |
| -tc:kn | Khuddaka Nikāya |
| -tc:mn | Majjhima Nikāya |
| -tc:ms | Mahasaṅgīti Tipiṭaka |
| -tc:np | Nissaggiya Pācittiya |
| -tc:pc | Pācittiya |
| -tc:pd | Pātidesanīya |
| -tc:pj | Pārājika |
| -tc:pvr | Parivāra | 
| -tc:prv | Parivāra | 
| -tc:sk | Sekhiya |
| -tc:sn | Saṃyutta Nikāya |
| -tc:ss | Saṅghādisesa |
| -tc:su | Sutta |
| -tc:thag | Theragāthā |
| -tc:thig | Therīgāthā |
| -tc:tv | Theravāda |
| -tc:vb | Vibhaṅga |
| -tc:vin | Vinaya |
</details>

<details><summary><h4>Häufig gestellte Fragen</h4></summary>

#### Warum unterscheiden sich meine Suchergebnisse von denen auf SuttaCentral.net?
Voice durchsucht nur segmetierte Texte, das sind Texte, bei denen kleine Textabschnitte nummeriert wurden, um sie in verschiedenen Übersetzungen miteinander in Beziehung setzen zu können. Voice durchsucht nicht alle Übersetzungen, die man auf SuttaCentral findet. Derzeit gibt es viele, die daran arbeiten, mehr segmentierte Texte hinzuzufügen.

</details>
