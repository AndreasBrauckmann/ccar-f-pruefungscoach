# CCAR-F Prüfungscoach

Übungsmaterial und Coach-Anweisung für die Zertifizierung **Claude Certified
Architect – Foundations (CCAR-F)**. Ursprünglich ein Claude.ai-Projekt, hier als
Repo gesichert.

## Inhalt

| Datei | Zweck |
|---|---|
| `CLAUDE.md` | Rolle + Ablauf des mündlichen Prüfungscoachs, Datei-Schema, Projektkontext |
| `ANLEITUNG.md` | Repo als claude.ai-Projekt oder auf Handy / iPad / Linux-Server / Linux-PC / Mac bereitstellen und damit arbeiten |
| `questions_de.json` | 60 Übungsfragen auf Deutsch (`exams.ccar-f.questions`) |
| `questions_en.json` | dieselben 60 Fragen auf Englisch (gleiche `id`s) |
| `guide_de.md` | vollständiger Study Guide auf **Deutsch** (Übersetzung von `guide_en.md`) |
| `guide_en.md` | vollständiger Study Guide auf **Englisch** (1:1 aus dem Community-Repo) |

## Study Guide

| Sprache | Link |
|---------|------|
| Deutsch | [guide_de.md](guide_de.md) |
| English | [guide_en.md](guide_en.md) |

## Bereitstellen

Ausführlich in **[`ANLEITUNG.md`](ANLEITUNG.md)** — pro Gerät (Terminal via Claude Code
oder claude.ai-Projekt), inkl. Zugang zum privaten Repo per `gh` / SSH-Key / Token.

## Nutzung

Mit Claude Code in diesem Ordner starten — `CLAUDE.md` wird automatisch geladen.
Dann z. B. „Deutsch" bzw. „Englisch" wählen und „Starte die Prüfung" sagen.

Fragen einzeln aus dem JSON holen:

```python
import json
qs = json.load(open("questions_de.json", encoding="utf-8"))["exams"]["ccar-f"]["questions"]
q = next(x for x in qs if x["id"] == 17)
print(q["situation"], q["question"], q["options"], q["correctLetter"])
```

## Hinweis

Die Fragen stammen aus einem inoffiziellen Community-Lernleitfaden
(github.com/paullarionov/claude-certified-architect) und sind **kein** offizieller
Anthropic-Prüfungsauszug. Deutsche Übersetzung von Claude, nicht offiziell geprüft.
Privates Repo, nur zum Lernen.
