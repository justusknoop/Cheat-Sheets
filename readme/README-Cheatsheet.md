# Überschriften, Absätze, Zeilenumbrüche
# H1
## H2
### H3
#### H4
##### H5
###### H6

Absatz durch Leerzeile trennen.

Erzwungener Zeilenumbruch am Zeilenende␠␠  ← zwei Leerzeichen
oder mit <br>.

# Textformatierung
*Kursiv*  _Kursiv_
**Fett**  __Fett__
***Fett/Kursiv***
~~Durchgestrichen~~
`Inline-Code`
<mark>Highlight</mark>      <!-- HTML -->
<sub>tief</sub> <sup>hoch</sup>  <!-- HTML -->

# Listen
- Punkt A
  - Unterpunkt
* Alternativ
+ Alternativ

1. Erster
2. Zweiter
   1. Verschachtelt

# Aufgabenlisten (Checkboxen)
- [ ] Offen
- [x] Erledigt

# Zitate / Callouts (Hinweisboxen)
> Einfaches Zitat

> [!NOTE]
> Info-Hinweis

> [!TIP]
> Tipp

> [!IMPORTANT]
> Wichtig

> [!WARNING]
> Warnung

> [!CAUTION]
> Achtung

# Links & Bilder
[Linktext](https://example.com "optional Titel")
<https://example.com>                <!-- Auto-Link -->

## Referenzlinks:
[Linktext][id]
[id]: https://example.com "Titel"

## Bilder:
![Alt-Text](./img/pic.png "optional Titel")
<img src="./img/pic.png" width="300" alt="Alt">   <!-- HTML für Größe -->

## Bild als Link:
[![Alt](./img/badge.svg)](https://ziel)

# Codeblöcke & Syntax-Highlighting
```powershell
Write-Host "Hello" 
``` 

```bash
echo "Hello"
```

```json
{ "key": "value" }
```

# Diff-Darstellung:
+ neu
- entfernt

# Fußnoten
Text mit Fußnote[^1].

[^1]: Fußnotentext.

# Emojis, Erwähnungen, Verweise
:tada: :rocket:               <!-- Emoji Shortcodes -->
@username                     <!-- Mention -->
#123                        <!-- Issue/PR in gleichem Repo -->
org/repo#123                  <!-- Issue/PR in anderem Repo -->
abcdef1                       <!-- Commit-SHA (gekürzt) -->

# Kollapsbare Bereiche
<details>
  <summary>Aufklappen</summary>

  Versteckter Inhalt, Code, Bilder, Tabellen…

</details>

# Trennlinien & Kommentare

---        <!-- oder *** oder ___ -->
<!-- HTML-Kommentar, wird nicht angezeigt -->

# Escape/Maskierung
\*maskiert\* \_maskiert\_ \`maskiert\`

# Inline-HTML (eingeschränkt)
Erlaubt: <br> <sub> <sup> <kbd> <details> <summary> <img> <mark> <abbr> …>

CSS/JS wird größtenteils entfernt. Style-Attribute sind eingeschränkt.

# Relative Pfade
[Dokumentation](docs/README.md)
![Bild](assets/logo.png)

# Badges (häufig in READMEs)
![Build](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
