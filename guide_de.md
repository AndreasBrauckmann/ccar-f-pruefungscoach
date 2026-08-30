# Claude Certified Architect — Foundations Zertifizierung

| Sprache | Link |
|---------|------|
| Deutsch | [guide_de.md](guide_de.md) |
| English | [guide_en.md](guide_en.md) |

## Lernleitfaden (basierend auf dem offiziellen Prüfungsleitfaden)

---

## Einleitung

Die Zertifizierung **Claude Certified Architect — Foundations** bestätigt, dass eine Fachkraft fundierte Abwägungsentscheidungen treffen kann, wenn sie reale Claude-basierte Lösungen umsetzt. Die Prüfung bewertet Grundlagenwissen zu Claude Code, dem Claude Agent SDK, der Claude API und dem Model Context Protocol (MCP) — den Kerntechnologien für den Bau von Produktionsanwendungen mit Claude.

Die Prüfungsfragen beruhen auf realistischen Branchenszenarien: dem Aufbau agentischer Systeme für den Kundensupport, dem Entwurf von Multi-Agenten-Recherche-Pipelines, der Integration von Claude Code in CI/CD, der Erstellung von Werkzeugen für die Entwicklerproduktivität und der Extraktion strukturierter Daten aus unstrukturierten Dokumenten.

---

## Zielkandidat

Der ideale Kandidat ist ein **Lösungsarchitekt**, der Produktionsanwendungen mit Claude entwirft und ausliefert. Du solltest mindestens 6 Monate praktische Erfahrung haben mit:

- **Claude Agent SDK** — Multi-Agenten-Orchestrierung, Delegation an Subagenten, Tool-Integration, Lifecycle-Hooks
- **Claude Code** — CLAUDE.md, MCP-Server, Agent Skills, Planungsmodus
- **Model Context Protocol (MCP)** — Tools und Ressourcen für die Backend-Integration
- **Prompt Engineering** — JSON-Schemas, Few-shot-Beispiele, Vorlagen zur Datenextraktion
- **Kontextfenster** — Arbeit mit langen Dokumenten, Kontextweitergabe zwischen mehreren Agenten
- **CI/CD-Pipelines** — automatisiertes Code-Review, Testgenerierung
- **Eskalation und Zuverlässigkeit** — Fehlerbehandlung, Human-in-the-Loop

---

## Prüfungsformat

| Parameter | Wert |
|---|---|
| Fragetyp | Multiple Choice (1 von 4 richtig) |
| Bewertung | Skala 100–1000, Bestehensgrenze **720** |
| Malus für Raten | Keiner (beantworte jede Frage!) |
| Szenarien | 4 von 8 möglichen (zufällig ausgewählt) |

---

## Prüfungsinhalt: 5 Domänen

| Domäne | Gewichtung |
|---|---|
| 1. Agentenarchitektur und Orchestrierung | **27 %** |
| 2. Tool-Design und MCP-Integration | **18 %** |
| 3. Claude-Code-Konfiguration und Workflows | **20 %** |
| 4. Prompt Engineering und strukturierte Ausgabe | **20 %** |
| 5. Kontextverwaltung und Zuverlässigkeit | **15 %** |

---

## Prüfungsszenarien

### Szenario 1: Kundensupport-Agent
Du baust einen Agenten, der Retouren, Abrechnungsstreitigkeiten und Kontoprobleme mithilfe des Claude Agent SDK bearbeitet. Der Agent nutzt MCP-Tools (`get_customer`, `lookup_order`, `process_refund`, `escalate_to_human`). Das Ziel sind über 80 % Lösungsquote beim Erstkontakt mit angemessener Eskalation.

### Szenario 2: Code-Generierung mit Claude Code
Du nutzt Claude Code, um die Entwicklung zu beschleunigen: Code-Generierung, Refactoring, Debugging, Dokumentation. Du musst es mit benutzerdefinierten Slash-Befehlen und einer CLAUDE.md-Konfiguration integrieren und verstehen, wann der Planungsmodus einzusetzen ist.

### Szenario 3: Multi-Agenten-Recherchesystem
Ein Koordinator-Agent delegiert Aufgaben an spezialisierte Subagenten: Web-Recherche, Dokumentenanalyse, Synthese und Berichterstellung. Das System muss vollständige Berichte mit Quellenangaben erzeugen.

### Szenario 4: Werkzeuge für die Entwicklerproduktivität
Der Agent hilft Ingenieuren, unbekannte Codebasen zu erkunden, Boilerplate-Code zu generieren und Routineaufgaben zu automatisieren. Es werden integrierte Tools (Read, Write, Bash, Grep, Glob) und MCP-Server verwendet.

### Szenario 5: Claude Code für Continuous Integration
Integriere Claude Code in eine CI/CD-Pipeline für automatisierte Code-Reviews, Testgenerierung und Pull-Request-Feedback. Die Prompts müssen so gestaltet sein, dass False Positives minimiert werden.

### Szenario 6: Strukturierte Datenextraktion
Das System extrahiert Informationen aus unstrukturierten Dokumenten, validiert die Ausgabe mit JSON-Schemas und hält eine hohe Genauigkeit ein. Es muss Grenzfälle korrekt behandeln.

### Szenario 7: Architekturmuster für dialogbasierte KI
Du entwirfst mehrschrittige Konversationssysteme und deckst dabei die Verwaltung des Kontextfensters, das Fortbestehen von Anweisungen über mehrere Turns hinweg, Gedächtnisstrategien, Tool-Design für sichere Ausführung sowie den Umgang mit mehrdeutigen oder widersprüchlichen Nutzereingaben ab.

### Szenario 8: Agentische KI-Werkzeuge *(Inhalt fehlt — hilf uns, ihn zu ergänzen!)*
Dieses Szenario wurde von Prüfungskandidaten gemeldet, ist in diesem Leitfaden aber noch nicht abgedeckt. Wenn du auf der echten Prüfung Fragen aus diesem Szenario hattest, teile sie bitte in den [GitHub Issues](https://github.com/paullarionov/claude-certified-architect/issues), damit wir eine vollständige Abdeckung ergänzen können. Dein Beitrag hilft allen, die sich auf die Prüfung vorbereiten.

---

# Offizielle Dokumentation

| Ressource | URL |
|---|---|
| **Claude API — Messages** | https://platform.claude.com/docs/en/api/messages |
| **Claude API — Tool Use** | https://platform.claude.com/docs/en/build-with-claude/tool-use |
| **Claude API — Message Batches** | https://platform.claude.com/docs/en/build-with-claude/message-batches |
| **Claude Agent SDK — Overview** | https://platform.claude.com/docs/en/agent-sdk/overview |
| **Claude Agent SDK — Hooks** | https://platform.claude.com/docs/en/agent-sdk/hooks |
| **Claude Agent SDK — Subagents** | https://platform.claude.com/docs/en/agent-sdk/subagents |
| **Claude Agent SDK — Sessions** | https://platform.claude.com/docs/en/agent-sdk/sessions |
| **Model Context Protocol (MCP)** | https://modelcontextprotocol.io/ |
| **MCP — Tools** | https://modelcontextprotocol.io/docs/concepts/tools |
| **MCP — Resources** | https://modelcontextprotocol.io/docs/concepts/resources |
| **MCP — Servers** | https://modelcontextprotocol.io/docs/concepts/servers |
| **Claude Code — Documentation** | https://code.claude.com/docs/en/overview |
| **Claude Code — CLAUDE.md and Memory** | https://code.claude.com/docs/en/memory |
| **Claude Code — Skills (incl. slash commands)** | https://code.claude.com/docs/en/skills |
| **Claude Code — Hooks** | https://code.claude.com/docs/en/hooks |
| **Claude Code — Sub-agents** | https://code.claude.com/docs/en/sub-agents |
| **Claude Code — MCP Integration** | https://code.claude.com/docs/en/mcp |
| **Claude Code — GitHub Actions CI/CD** | https://code.claude.com/docs/en/github-actions |
| **Claude Code — GitLab CI/CD** | https://code.claude.com/docs/en/gitlab-ci-cd |
| **Claude Code — Headless (non-interactive mode)** | https://code.claude.com/docs/en/headless |
| **Prompt Engineering Guide** | https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview |
| **Extended Thinking** | https://platform.claude.com/docs/en/build-with-claude/extended-thinking |
| **Anthropic Cookbook (code examples)** | https://github.com/anthropics/anthropic-cookbook |

---

# TEIL I: THEORETISCHE GRUNDLAGEN

Dieser Teil behandelt die gesamte Theorie, die du brauchst, um die Prüfung erfolgreich zu bestehen. Das Material ist nach Technologien und Konzepten geordnet statt nach Prüfungsdomänen — das hilft dir, ein tieferes Verständnis für jedes Thema aufzubauen.

---

# Kapitel 1: Claude API — Grundlagen der Modellinteraktion

> Dokumentation: [Messages API](https://platform.claude.com/docs/en/api/messages) | [Prompt Engineering](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview)

## 1.1 Struktur einer API-Anfrage

Die Claude API folgt einem Anfrage-Antwort-Modell. Jede Anfrage an die Claude Messages API enthält:

```json
{
  "model": "claude-sonnet-4-6",
  "max_tokens": 1024,
  "system": "You are a helpful assistant.",
  "messages": [
    {"role": "user", "content": "Hi!"},
    {"role": "assistant", "content": "Hello!"},
    {"role": "user", "content": "How are you?"}
  ],
  "tools": [...],
  "tool_choice": {"type": "auto"}
}
```

**Wichtige Felder:**
- `model` — Modellauswahl (`claude-opus-4-6`, `claude-sonnet-4-6`, `claude-haiku-4-5`)
- `max_tokens` — maximale Anzahl Tokens in der Antwort
- `system` — der System-Prompt (definiert das Modellverhalten)
- `messages` — Gesprächsverlauf (**du musst den vollständigen Verlauf senden**, um die Kohärenz zu wahren)
- `tools` — Definitionen der verfügbaren Tools
- `tool_choice` — Strategie zur Tool-Auswahl

## 1.2 Nachrichtenrollen

Das `messages`-Array verwendet zwei Konversationsrollen plus eine Anweisungsrolle:
- `user` — Nutzernachrichten, einschließlich Tool-Ergebnissen (gesendet als `tool_result`-Content-Block innerhalb einer Nachricht mit der Rolle `user`, nicht als separate `tool`-Rolle)
- `assistant` — Modellantworten (enthalten, wenn der Verlauf mitgesendet wird), einschließlich Tool-Aufruf-Anfragen (`tool_use`-Content-Blöcke)
- `system` — kann über das Top-Level-Feld `system` gesetzt werden (gilt ab dem ersten Turn) oder inline in `messages` als `{"role": "system", ...}` (gilt ab diesem Punkt, vorbehaltlich der Platzierungsregeln — siehe unten)

Tool-Ergebnisse werden nicht als Nachricht mit der Rolle `"tool"` gesendet. Sie werden als Nachricht mit der Rolle `user` gesendet, deren Inhalt einen `tool_result`-Content-Block enthält:

```json
{
  "role": "user",
  "content": [
    {
      "type": "tool_result",
      "tool_use_id": "toolu_01...",
      "content": "..."
    }
  ]
}
```

`system` kann auch direkt als Rolle im `messages`-Array auftreten, nicht nur über den Top-Level-Parameter `system`. Das ist dafür gedacht, mitten im Gespräch Anweisungen hinzuzufügen, ohne das gecachte Präfix aus dem Top-Level-Feld `system` zu invalidieren. Es gelten bestimmte Platzierungsregeln:
- Muss unmittelbar auf einen `user`-Turn folgen (auch auf einen mit `tool_result`-Blöcken) oder auf einen `assistant`-Turn, der mit einem Server-Tool-Einsatz endet.
- Muss einem `assistant`-Turn vorausgehen oder das Array beenden.
- Darf nicht zwischen einem `tool_use`-Block und seinem `tool_result` stehen — das führt zu einem 400-Fehler.
- Spätere `system`-Nachrichten (auch die mitten im Gespräch) haben für die nachfolgenden Turns Vorrang vor früheren und vor dem Top-Level-Feld `system`.

**Von entscheidender Bedeutung:** Bei jeder API-Anfrage musst du den **vollständigen Gesprächsverlauf** senden. Das Modell hält keinen Zustand zwischen Anfragen — jeder Aufruf ist unabhängig.

## 1.3 Das Feld `stop_reason` in der Antwort

Die Antwort der Claude API enthält `stop_reason`; es gibt an, warum das Modell die Generierung gestoppt hat:

| Wert | Beschreibung | Aktion |
|---|---|---|
| `"end_turn"` | Das Modell hat seine Antwort abgeschlossen | Das Ergebnis dem Nutzer anzeigen |
| `"tool_use"` | Das Modell möchte ein Tool aufrufen | Das Tool ausführen und das Ergebnis zurückgeben |
| `"max_tokens"` | Token-Limit erreicht | Die Antwort ist abgeschnitten; ggf. das Limit erhöhen |
| `"stop_sequence"` | Eine Stopp-Sequenz wurde erreicht | Gemäß deiner Anwendungslogik behandeln |

Für agentische Systeme sind `"tool_use"` und `"end_turn"` am wichtigsten — sie steuern die Agentenschleife.

## 1.4 System-Prompt

Der System-Prompt ist eine spezielle Anweisung, die Kontext und Verhaltensregeln definiert. Er:
- ist nicht Teil des `messages`-Arrays; er wird separat im Feld `system` übergeben
- hat Vorrang vor Nutzernachrichten
- wird einmal geladen und gilt im gesamten Gespräch
- dient dazu, Rolle, Einschränkungen und Ausgabeformat festzulegen

**Wichtig für die Prüfung:** Die Formulierung des System-Prompts kann unbeabsichtigte Tool-Assoziationen erzeugen. Zum Beispiel kann eine Anweisung wie „verifiziere immer den Kunden" dazu führen, dass das Modell `get_customer` überbeansprucht, selbst wenn es unnötig ist.

## 1.5 Kontextfenster

Das Kontextfenster ist die gesamte Textmenge (in Tokens), die das Modell auf einmal verarbeiten kann. Es umfasst:
- den System-Prompt
- den vollständigen Nachrichtenverlauf
- Tool-Definitionen
- Tool-Ergebnisse

**Zentrale Probleme des Kontextfensters:**

1. **Lost-in-the-middle-Effekt:** Modelle verarbeiten Informationen am Anfang und Ende einer langen Eingabe zuverlässig, können aber Details in der Mitte übersehen. Gegenmaßnahme: Schlüsselinformationen nahe an Anfang oder Ende platzieren.

2. **Anhäufung von Tool-Ergebnissen:** Jeder Tool-Aufruf fügt dem Kontext Ausgabe hinzu. Gibt ein Tool 40+ Felder zurück, von denen nur 5 relevant sind, wird der Großteil des Kontexts verschwendet.

3. **Fortlaufende Zusammenfassung:** Beim Komprimieren des Verlaufs gehen Zahlenwerte, Prozentsätze und Datumsangaben oft verloren und werden vage („etwa", „ungefähr", „ein paar").

---

# Kapitel 2: Tools und `tool_use`

> Dokumentation: [Tool Use](https://platform.claude.com/docs/en/build-with-claude/tool-use)

## 2.1 Was ist `tool_use`

`tool_use` ist ein Mechanismus, der es Claude erlaubt, externe Funktionen aufzurufen. Das Modell führt keinen Code direkt aus — es erzeugt eine strukturierte Tool-Aufruf-Anfrage; dein Code führt sie aus und gibt das Ergebnis zurück.

## 2.2 Tool-Definition

Jedes Tool wird mit einem JSON-Schema definiert:

```json
{
  "name": "get_customer",
  "description": "Finds a customer by email or ID. Returns the customer profile, including name, email, order history, and account status. Use this tool BEFORE lookup_order to verify the customer's identity. Accepts an email (format: user@domain.com) or a numeric customer_id.",
  "input_schema": {
    "type": "object",
    "properties": {
      "email": {"type": "string", "description": "Customer email"},
      "customer_id": {"type": "integer", "description": "Numeric customer ID"}
    },
    "required": []
  }
}
```

**Von entscheidender Bedeutung bei einer Tool-Beschreibung:**

1. **Die Beschreibung ist der primäre Auswahlmechanismus.** Ein LLM wählt Tools anhand ihrer Beschreibungen aus. Minimale Beschreibungen („Ruft Kundeninformationen ab") führen zu Fehlern, wenn sich Tools überschneiden.

2. **In die Beschreibung aufnehmen:**
   - was das Tool tut und zurückgibt
   - Eingabeformate und Beispielwerte
   - Grenzfälle und Einschränkungen
   - wann dieses Tool statt ähnlicher Alternativen zu verwenden ist

3. **Vermeide** identische oder sich überschneidende Beschreibungen über mehrere Tools hinweg. Haben `analyze_content` und `analyze_document` nahezu identische Beschreibungen, verwechselt das Modell sie.

4. **Integrierte Tools vs. MCP-Tools:** Agenten bevorzugen unter Umständen integrierte Tools (Read, Grep) gegenüber MCP-Tools mit ähnlicher Funktion. Um das zu verhindern, stärke die Beschreibungen der MCP-Tools — hebe konkrete Vorteile, einzigartige Daten oder Kontext hervor, den integrierte Tools nicht liefern können.

## 2.3 Der Parameter `tool_choice`

`tool_choice` steuert, wie das Modell Tools auswählt:

| Wert | Verhalten | Wann zu verwenden |
|---|---|---|
| `{"type": "auto"}` | Das Modell entscheidet, ob es ein Tool aufruft oder in Textform antwortet | Standard für die meisten Fälle |
| `{"type": "any"}` | Das Modell **muss** irgendein Tool aufrufen | Wenn du garantierte strukturierte Ausgabe brauchst |
| `{"type": "tool", "name": "extract_metadata"}` | Das Modell **muss** ein bestimmtes Tool aufrufen | Wenn du einen erzwungenen ersten Schritt / eine feste Ausführungsreihenfolge brauchst |

**Wichtige Szenarien:**
- `tool_choice: "any"` + mehrere Extraktions-Tools → das Modell wählt das beste, du erhältst aber weiterhin strukturierte Ausgabe
- Erzwungene Auswahl → wenn du eine bestimmte erste Aktion garantieren musst (z. B. `extract_metadata` vor der Anreicherung)

## 2.4 JSON-Schemas für strukturierte Ausgabe

`tool_use` mit JSON-Schemas ist der **zuverlässigste** Weg, strukturierte Ausgabe von Claude zu erhalten. Es:
- garantiert syntaktisch gültiges JSON (keine fehlenden Klammern, keine überzähligen Kommata)
- erzwingt die geforderte Struktur (Pflichtfelder sind vorhanden)
- garantiert **nicht** die semantische Korrektheit (Werte können trotzdem falsch sein)

**Schema-Design — Kernprinzipien:**

```json
{
  "type": "object",
  "properties": {
    "category": {
      "type": "string",
      "enum": ["bug", "feature", "docs", "unclear", "other"]
    },
    "category_detail": {
      "type": ["string", "null"],
      "description": "Details if category = 'other' or 'unclear'"
    },
    "severity": {
      "type": "string",
      "enum": ["critical", "high", "medium", "low"]
    },
    "confidence": {
      "type": "number",
      "minimum": 0,
      "maximum": 1
    },
    "optional_field": {
      "type": ["string", "null"],
      "description": "Null if the information was not found in the source"
    }
  },
  "required": ["category", "severity"]
}
```

**Regeln für das Schema-Design:**
1. **Pflicht vs. optional:** Markiere Felder nur dann als Pflicht, wenn die Information immer verfügbar ist. Pflichtfelder drängen das Modell dazu, Werte zu erfinden, wenn Daten fehlen.
2. **Nullable-Felder:** Verwende `"type": ["string", "null"]` für Informationen, die fehlen können. Das Modell kann `null` zurückgeben, statt zu halluzinieren.
3. **Enums mit `"other"`:** Ergänze `"other"` + einen Detail-String, um Daten außerhalb deiner vordefinierten Kategorien nicht zu verlieren.
4. **Enum `"unclear"`:** Für Fälle, in denen das Modell keine Kategorie sicher wählen kann — ein ehrliches `"unclear"` ist besser als eine falsche Kategorie.

## 2.5 Syntax- vs. Semantikfehler

| Fehlertyp | Beispiel | Gegenmaßnahme |
|---|---|---|
| **Syntax** | Ungültiges JSON, falscher Feldtyp | `tool_use` mit einem JSON-Schema (eliminiert das) |
| **Semantik** | Summen stimmen nicht, Wert im falschen Feld, Halluzination | Validierungsprüfungen, Retry mit Feedback, Selbstkorrektur |

---

# Kapitel 3: Claude Agent SDK — Aufbau agentischer Systeme

> Dokumentation: [Agent SDK](https://platform.claude.com/docs/en/agent-sdk/overview) | [Hooks](https://platform.claude.com/docs/en/agent-sdk/hooks) | [Subagents](https://platform.claude.com/docs/en/agent-sdk/subagents) | [Sessions](https://platform.claude.com/docs/en/agent-sdk/sessions)

## 3.1 Was ist eine agentische Schleife

Die agentische Schleife ist das Kernmuster für die autonome Ausführung von Aufgaben. Das Modell antwortet nicht nur — es führt eine Abfolge von Aktionen aus:

```
1. Sende eine Anfrage an Claude mit Tools
2. Empfange eine Antwort
3. Prüfe stop_reason:
   - "tool_use"  -> führe das Tool aus, hänge das Ergebnis an den Verlauf an, zurück zu Schritt 1
   - "end_turn"  -> die Aufgabe ist abgeschlossen, zeige dem Nutzer das Ergebnis
4. Wiederhole bis zum Abschluss
```

**Das ist ein modellgesteuerter Ansatz:** Claude entscheidet anhand des Kontexts und vorheriger Tool-Ergebnisse, welches Tool als Nächstes aufgerufen wird. Das unterscheidet sich von fest kodierten Entscheidungsbäumen, bei denen die Abfolge der Aktionen festgelegt ist.

**Anti-Muster (vermeiden):**
- Den Assistenten-Text parsen, um den Abschluss zu erkennen („Task completed")
- Ein willkürliches Iterationslimit (z. B. `max_iterations=5`) als primäre Abbruchbedingung verwenden
- Prüfen, ob der Assistent textuellen Inhalt erzeugt hat, als Abschluss-Signal

**Korrekter Ansatz:** Das einzige zuverlässige Abschluss-Signal ist `stop_reason == "end_turn"`.

## 3.2 Konfiguration von `AgentDefinition`

`AgentDefinition` ist das Konfigurationsobjekt eines Agenten im Claude Agent SDK:

```python
agent = AgentDefinition(
    name="customer_support",
    description="Handles customer requests for returns and order issues",
    system_prompt="You are a customer support agent...",
    allowed_tools=["get_customer", "lookup_order", "process_refund", "escalate_to_human"],
    # Für einen Koordinator:
    # allowed_tools=["Task", "get_customer", ...]
)
```

**Wichtige Parameter:**
- `name` / `description` — Kennung und Beschreibung des Agenten
- `system_prompt` — System-Prompt mit Anweisungen
- `allowed_tools` — Liste der erlaubten Tools (Prinzip der geringsten Rechte)

## 3.3 Hub-and-Spoke: Koordinator und Subagenten

Eine Multi-Agenten-Architektur wird typischerweise als Hub-and-Spoke-Topologie aufgebaut:

```
         Koordinator
        /     |      \
   Subagent1  Subagent2  Subagent3
    (Suche)   (Analyse)   (Synthese)
```

**Der Koordinator ist verantwortlich für:**
- die Zerlegung der Aufgabe in Teilaufgaben
- die Entscheidung, welche Subagenten benötigt werden (dynamische Auswahl)
- die Delegation der Arbeit an Subagenten
- die Aggregation und Validierung der Ergebnisse
- die Behandlung von Fehlern und Wiederholungen
- die Übermittlung der Ergebnisse an den Nutzer

**Kritisches Prinzip: Subagenten haben einen isolierten Kontext.**
- Subagenten erben den Gesprächsverlauf des Koordinators **nicht** automatisch
- Der gesamte benötigte Kontext muss **explizit** im Subagenten-Prompt übergeben werden
- Subagenten teilen kein Gedächtnis über Aufrufe hinweg
- Die gesamte Kommunikation läuft über den Koordinator (für Beobachtbarkeit und Fehlerkontrolle)

## 3.4 Das `Task`-Tool zum Starten von Subagenten

Subagenten werden über das `Task`-Tool gestartet:

```python
# Die allowedTools des Koordinators müssen "Task" enthalten
coordinator_agent = AgentDefinition(
    allowed_tools=["Task", "get_customer"]
)
```

**Die explizite Kontextübergabe ist zwingend:**

```
# Schlecht: der Subagent hat keinen Kontext
Task: "Analyze the document"

# Gut: vollständiger Kontext im Prompt
Task: "Analyze the following document.
Document: [full document text]
Prior search results: [web search results]
Output format requirements: [schema]"
```

**Paralleles Starten:** Ein Koordinator kann mehrere `Task`s in einer Antwort aufrufen — die Subagenten laufen parallel:

```
# Eine Koordinator-Antwort enthält:
Task 1: "Search for articles about X"
Task 2: "Analyze document Y"
Task 3: "Search for articles about Z"
# Alle drei laufen gleichzeitig
```

## 3.5 Hooks im Agent SDK

Hooks ermöglichen das Abfangen und Transformieren an bestimmten Punkten im Lebenszyklus des Agenten.

**PostToolUse** fängt ein Tool-Ergebnis ab, bevor es dem Modell bereitgestellt wird:

```python
# Beispiel: Datumsformate aus verschiedenen MCP-Tools normalisieren
@hook("PostToolUse")
def normalize_dates(tool_result):
    # Unix-Zeitstempel -> ISO 8601 umwandeln
    # "Mar 5, 2025" -> "2025-03-05" umwandeln
    return normalized_result
```

**Ein Hook, der ausgehende Aufrufe abfängt,** blockiert Aktionen, die gegen Richtlinien verstoßen:

```python
# Beispiel: Rückerstattungen über 500 $ blockieren
@hook("PreToolUse")
def enforce_refund_limit(tool_call):
    if tool_call.name == "process_refund" and tool_call.args.amount > 500:
        return redirect_to_escalation(tool_call)
```

**Wesentlicher Unterschied: Hooks vs. Prompt-Anweisungen**

| Merkmal | Hooks | Prompt-Anweisungen |
|---|---|---|
| Garantie | **Deterministisch** (100 %) | **Probabilistisch** (> 90 %, nicht 100 %) |
| Wann zu verwenden | Kritische Geschäftsregeln, Finanzoperationen, Compliance | Allgemeine Präferenzen, Empfehlungen, Formatierung |
| Beispiel | Rückerstattungen > 500 $ blockieren | „Versuche zu lösen, bevor du eskalierst" |

**Regel:** Wenn ein Fehlschlag finanzielle, rechtliche oder sicherheitsrelevante Folgen hat — nutze Hooks, keine Prompts.

# Kapitel 4: Model Context Protocol (MCP)

> Dokumentation: [MCP](https://modelcontextprotocol.io/) | [Tools](https://modelcontextprotocol.io/docs/concepts/tools) | [Resources](https://modelcontextprotocol.io/docs/concepts/resources) | [Servers](https://modelcontextprotocol.io/docs/concepts/servers)

## 4.1 Was ist MCP

Das Model Context Protocol (MCP) ist ein offenes Protokoll zur Anbindung externer Systeme an Claude. MCP definiert drei primäre Ressourcentypen:

1. **Tools** — Funktionen, die der Agent aufrufen kann, um Aktionen auszuführen (CRUD-Operationen, API-Aufrufe, Befehlsausführung)
2. **Resources** — Daten, die der Agent als Kontext lesen kann (Dokumentation, Datenbankschemas, Inhaltskataloge)
3. **Prompts** — vordefinierte Prompt-Vorlagen für wiederkehrende Aufgaben

## 4.2 MCP-Server

Ein MCP-Server ist ein Prozess, der das MCP-Protokoll implementiert und Tools/Ressourcen bereitstellt. Wenn du dich mit einem MCP-Server verbindest:
- werden alle Tools automatisch erkannt
- sind die Tools aller verbundenen Server gleichzeitig verfügbar
- bestimmen die Tool-Beschreibungen, wie das Modell sie nutzen wird

## 4.3 Konfiguration von MCP-Servern

**Projektkonfiguration (`.mcp.json`)** — für die Nutzung im Team:

```json
{
  "mcpServers": {
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {
        "GITHUB_TOKEN": "${GITHUB_TOKEN}"
      }
    },
    "jira": {
      "command": "npx",
      "args": ["-y", "mcp-server-jira"],
      "env": {
        "JIRA_TOKEN": "${JIRA_TOKEN}"
      }
    }
  }
}
```

**Kernpunkte:**
- `.mcp.json` liegt im Projektstamm und wird in der Versionskontrolle verwaltet
- Umgebungsvariablen (`${GITHUB_TOKEN}`) werden für Geheimnisse verwendet — die Tokens selbst werden nicht committet
- Verfügbar für alle Projektmitwirkenden

**Nutzerkonfiguration (`~/.claude.json`)** — für persönliche/experimentelle Server:
- Liegt im Home-Verzeichnis des Nutzers
- Wird nicht über die Versionskontrolle geteilt
- Geeignet für persönliche Experimente und Tests

**Auswahl der Server:**
- Für Standardintegrationen (Jira, GitHub, Slack) sind bestehende Community-MCP-Server vorzuziehen
- Eigene Server nur für einzigartige, teamspezifische Workflows bauen

## 4.4 Das Flag `isError` in MCP

Wenn ein MCP-Tool auf einen Fehler stößt, verwendet es `isError: true` in der Antwort. Das signalisiert dem Agenten, dass der Aufruf fehlgeschlagen ist.

**Strukturierter Fehler (gut):**

```json
{
  "isError": true,
  "content": {
    "errorCategory": "transient",
    "isRetryable": true,
    "message": "The service is temporarily unavailable. Timeout while calling the orders API.",
    "attempted_query": "order_id=12345",
    "partial_results": null
  }
}
```

**Generischer Fehler (Anti-Muster):**

```json
{
  "isError": true,
  "content": "Operation failed"
}
```

Ein generischer Fehler liefert dem Agenten keine Information für die Entscheidungsfindung — soll er es erneut versuchen, die Anfrage ändern oder eskalieren?

## 4.5 MCP-Resources

Resources sind Daten, die ein Agent anfordern kann, um Kontext zu erhalten, ohne Aktionen auszuführen:

- Inhaltskataloge (z. B. eine Liste aller Projektaufgaben, hierarchische Navigation)
- Datenbankschemas (Verständnis der Datenstruktur)
- Dokumentation (API-Referenzen, interne Leitfäden)
- Zusammenfassungen von Issues/Aufgaben

**Vorteil von Resources:** Der Agent benötigt keine explorativen Tool-Aufrufe, um zu verstehen, welche Daten existieren. Eine Resource liefert sofort eine „Landkarte".

---

# Kapitel 5: Claude Code — Konfiguration und Workflows

> Dokumentation: [Claude Code](https://code.claude.com/docs/en/overview) | [Memory / CLAUDE.md](https://code.claude.com/docs/en/memory) | [Skills](https://code.claude.com/docs/en/skills) | [MCP](https://code.claude.com/docs/en/mcp) | [Hooks](https://code.claude.com/docs/en/hooks) | [Sub-agents](https://code.claude.com/docs/en/sub-agents) | [GitHub Actions](https://code.claude.com/docs/en/github-actions) | [Headless](https://code.claude.com/docs/en/headless)

## 5.1 Die CLAUDE.md-Hierarchie

CLAUDE.md ist die Anweisungsdatei (bzw. -dateien) für Claude Code. Es gibt eine dreistufige Hierarchie:

```
1. Nutzerebene: ~/.claude/CLAUDE.md
   - Gilt nur für diesen Nutzer
   - Wird NICHT über die Versionskontrolle geteilt
   - Persönliche Präferenzen und Arbeitsstil

2. Projektebene: .claude/CLAUDE.md oder eine CLAUDE.md im Projektstamm
   - Gilt für alle Projektmitwirkenden
   - Wird über die Versionskontrolle verwaltet
   - Coding-Standards, Test-Standards, Architekturentscheidungen

3. Verzeichnisebene: CLAUDE.md in Unterverzeichnissen
   - Gilt bei der Arbeit mit Dateien in diesem Verzeichnis
   - Konventionen speziell für diesen Teil der Codebasis
```

**Häufiger Fehler:** Ein neues Teammitglied erhält die Projektanweisungen nicht, weil sie in `~/.claude/CLAUDE.md` (Nutzerebene) statt in `.claude/CLAUDE.md` (Projektebene) abgelegt wurden.

## 5.2 Die `@path`-Syntax (Datei-Importe)

CLAUDE.md kann externe Dateien über `@path` referenzieren und die Konfiguration so modular machen:

```markdown
# Project CLAUDE.md

Coding standards are described in @./standards/coding-style.md
Test requirements are in @./standards/testing-requirements.md
Project overview is in @README.md and dependencies are in @package.json
```

**Regeln für `@path`:**
- `@` unmittelbar vor dem Dateipfad verwenden (kein Leerzeichen)
- Relative und absolute Pfade werden unterstützt
- Relative Pfade werden relativ zu der Datei aufgelöst, die den Import enthält
- Die maximale Verschachtelungstiefe für Importe beträgt 5

Das vermeidet Duplizierung und lässt jedes Paket nur die relevanten Standards einbinden.

## 5.3 Das Verzeichnis `.claude/rules/`

`.claude/rules/` ist eine Alternative zu einer monolithischen CLAUDE.md und dient dazu, Regeln nach Thema zu organisieren:

```
.claude/rules/
  testing.md          -- Test-Konventionen
  api-conventions.md  -- API-Konventionen
  deployment.md       -- Deployment-Regeln
  react-patterns.md   -- React-Muster
```

**Schlüsselmerkmal: YAML-Frontmatter mit `paths` für bedingtes Laden:**

```yaml
---
paths: ["src/api/**/*"]
---

For API files, use async/await with explicit error handling.
Each endpoint must return a standard response wrapper.
```

```yaml
---
paths: ["**/*.test.tsx", "**/*.test.ts"]
---

Tests must use describe/it blocks.
Use data factories instead of hardcoding.
Do not mock the database—use a test database.
```

**So funktioniert es:**
- Eine Regel wird **nur** geladen, wenn Claude Code eine Datei bearbeitet, die zum `paths`-Muster passt
- Das spart Kontext und Tokens — irrelevante Regeln werden nicht geladen
- Glob-Muster erlauben es, Konventionen nach Dateityp anzuwenden, unabhängig vom Ablageort (ideal für Tests, die über die Codebasis verstreut sind)

**Wann `.claude/rules/` mit `paths` vs. eine CLAUDE.md auf Verzeichnisebene:**
- `.claude/rules/` mit `paths` — wenn Konventionen für Dateien gelten, die über viele Verzeichnisse verteilt sind (Tests, Migrationen)
- CLAUDE.md auf Verzeichnisebene — wenn Konventionen an ein bestimmtes Verzeichnis gebunden sind und anderswo nicht benötigt werden

## 5.4 Benutzerdefinierte Slash-Befehle und Skills

> **Hinweis:** In der aktuellen Claude-Code-Version sind benutzerdefinierte Befehle (`.claude/commands/`) mit Skills (`.claude/skills/`) zusammengeführt. Beide Formate erzeugen `/name`-Befehle. Der Prüfungsleitfaden verweist auf `.claude/commands/` — dieses Format wird weiterhin unterstützt.

Slash-Befehle sind wiederverwendbare Prompt-Vorlagen, die über `/name` aufgerufen werden:

**Format `.claude/commands/` (Legacy, unterstützt):**

```
.claude/commands/
  review.md        -- /review -- Standard-Code-Review
  test-gen.md      -- /test-gen -- Testgenerierung
```

**Format `.claude/skills/` (aktuell):**

```
.claude/skills/
  review/SKILL.md  -- /review -- mit Frontmatter-Konfiguration
  test-gen/SKILL.md
```

**Projektbefehle** (`.claude/commands/` oder `.claude/skills/`):
- Werden in der Versionskontrolle gespeichert und sind beim Klonen des Repos für alle verfügbar
- Sorgen für einheitliche Workflows im gesamten Team

**Nutzerbefehle** (`~/.claude/commands/` oder `~/.claude/skills/`):
- Persönliche Befehle, die nicht über die Versionskontrolle geteilt werden
- Für individuelle Workflows

## 5.5 Skills — `.claude/skills/`

Skills sind fortgeschrittene Befehle, die über das SKILL.md-Frontmatter konfiguriert werden:

```yaml
---
context: fork
allowed-tools: ["Read", "Grep", "Glob"]
argument-hint: "Path to the directory to analyze"
---

Analyze the code structure in the specified directory.
Output a report on dependencies and architectural patterns.
```

**Frontmatter-Parameter:**

| Parameter | Beschreibung |
|---|---|
| `context: fork` | Führt den Skill in einem isolierten Subagenten aus. Ausführliche Ausgabe belastet die Hauptsitzung nicht |
| `allowed-tools` | Schränkt ein, welche Tools verfügbar sind (Sicherheit — z. B. kann der Skill keine Dateien löschen, wenn es nicht erlaubt ist) |
| `argument-hint` | Hinweis, der bei Aufruf ohne Parameter nach einem Argument fragt |

**Wann ein Skill vs. CLAUDE.md:**
- **Skill** — bedarfsgesteuerter Aufruf für eine bestimmte Aufgabe (Review, Analyse, Generierung)
- **CLAUDE.md** — stets geladene allgemeine Standards und Konventionen

**Persönliche Skills (`~/.claude/skills/`):**
- Lege persönliche Varianten unter anderen Namen an, damit du Teammitglieder nicht beeinträchtigst

## 5.6 Planungsmodus vs. direkte Ausführung

**Planungsmodus:**
- Das Modell untersucht und plant nur; es nimmt keine Änderungen vor
- Nutzt Read, Grep, Glob, um die Codebasis zu erkunden
- Erzeugt einen Umsetzungsplan, den der Nutzer freigibt
- Sichere Erkundung ohne Seiteneffekte

**Wann den Planungsmodus verwenden:**
- Große Änderungen (Dutzende Dateien)
- Mehrere plausible Ansätze (Microservices: Wie definiert man die Grenzen?)
- Architekturentscheidungen (Welches Framework? Welche Struktur?)
- Unbekannte Codebasis (du musst verstehen, bevor du änderst)
- Bibliotheks-Migrationen, die 45+ Dateien betreffen

**Wann direkte Ausführung verwenden:**
- Ein-Datei-Korrekturen mit einem klaren Stacktrace
- Hinzufügen einer einzelnen Validierungsprüfung
- Gut verstandene, eindeutige Änderungen

**Kombinierter Ansatz:**
1. Planungsmodus für Untersuchung und Entwurf
2. Der Nutzer gibt den Plan frei
3. Direkte Ausführung zur Umsetzung des freigegebenen Plans

**Explore-Subagent** — ein spezialisierter Subagent zum Erkunden der Codebasis:
- Isoliert ausführliche Ausgabe vom Hauptkontext
- Gibt nur eine Zusammenfassung zurück
- Verhindert das Erschöpfen des Kontextfensters bei mehrphasigen Aufgaben

## 5.7 Der Befehl `/compact`

`/compact` ist ein integrierter Befehl zum Komprimieren des Kontexts:
- Fasst den bisherigen Verlauf zusammen, um das Kontextfenster freizugeben
- Wird in langen Untersuchungssitzungen verwendet, wenn sich der Kontext mit ausführlicher Tool-Ausgabe füllt
- Risiko: exakte Zahlenwerte, Datumsangaben und spezifische Details können bei der Zusammenfassung verloren gehen

## 5.8 Der Befehl `/memory`

`/memory` ist ein integrierter Befehl zur Verwaltung des Gedächtnisses zwischen Sitzungen:
- Öffnet die Datei `CLAUDE.md` zur Bearbeitung, sodass du Notizen, Präferenzen und Kontext speichern kannst
- Informationen bleiben über Sitzungen hinweg erhalten und werden beim Start automatisch geladen
- Nützlich, um Projektkonventionen, Nutzerpräferenzen, häufig verwendete Befehle und den aktuellen Arbeitskontext zu speichern
- Alternative dazu, dieselben Anweisungen in jeder Sitzung erneut zu erklären

## 5.9 Claude Code CLI für CI/CD

**Das Flag `-p` (oder `--print`):**

```bash
claude -p "Analyze this pull request for security issues"
```

- Nicht-interaktiver Modus: verarbeitet den Prompt, gibt auf stdout aus, beendet sich
- Wartet nicht auf Nutzereingaben
- Der einzige korrekte Weg, Claude in CI/CD-Pipelines auszuführen

**Strukturierte Ausgabe für CI:**

```bash
claude -p "Review this PR" --output-format json --json-schema '{"type":"object",...}'
```

- `--output-format json` — Ausgabe als JSON
- `--json-schema` — Ausgabe gegen ein Schema validieren
- Das Ergebnis lässt sich parsen, um automatisch Inline-Kommentare am PR zu posten

**Isolierung des Sitzungskontexts:**
Dieselbe Claude-Sitzung, die den Code erzeugt hat, ist oft weniger wirksam darin, ihn zu prüfen (das Modell behält seinen Argumentationskontext und stellt seine eigenen Entscheidungen seltener infrage). Verwende eine unabhängige Instanz für das Review.

**Doppelte Kommentare vermeiden:**
Wenn du nach neuen Commits erneut prüfst, füge die vorherigen Review-Ergebnisse in den Kontext ein und weise Claude an, nur neue oder ungelöste Probleme zu melden.

## 5.10 `fork_session` und Sitzungsverwaltung

**`--resume <session-name>`** setzt eine benannte Sitzung fort:

```bash
claude --resume investigation-auth-bug
```

- Setzt ein früheres Gespräch mit gespeichertem Kontext fort
- Nützlich für lange Untersuchungen über mehrere Sitzungen hinweg
- Risiko: Wenn sich Dateien seit der vorherigen Sitzung geändert haben, können Tool-Ergebnisse veraltet sein

**`fork_session`** erzeugt einen unabhängigen Zweig aus einem gemeinsamen Kontext:

```
Untersuchung der Codebasis
         |
    fork_session
    /           \
Ansatz A:       Ansatz B:
Redux           Context API
```

- Beide Forks erben den Kontext bis zum Verzweigungspunkt
- Danach entwickeln sie sich unabhängig weiter
- Nützlich, um Ansätze zu vergleichen oder Strategien zu testen

**Wann eine neue Sitzung starten statt fortsetzen:**
- Tool-Ergebnisse sind veraltet (Dateien haben sich geändert)
- Es ist viel Zeit vergangen und der Kontext hat sich verschlechtert
- Es ist besser, mit „Hier ist eine kurze Zusammenfassung dessen, was wir gefunden haben: …" neu zu starten, als mit alten Tool-Daten fortzusetzen

---

# Kapitel 6: Prompt Engineering — Fortgeschrittene Techniken

> Dokumentation: [Prompt Engineering](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview) | [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook)

## 6.1 Few-shot-Prompting

Few-shot-Prompting ist das Einfügen von 2–4 Eingabe-/Ausgabe-Beispielen in einen Prompt, um das erwartete Verhalten zu demonstrieren.

**Warum Few-shot wirksamer ist als textliche Beschreibungen:**
- Eine vage Anweisung wie „sei präziser" kann auf viele Arten interpretiert werden
- Ein Beispiel zeigt unmissverständlich das erwartete Format und die Entscheidungslogik
- Das Modell verallgemeinert das Muster auf neue Fälle (es wiederholt nicht bloß die Beispiele)

**Arten von Few-shot-Beispielen und wann sie einzusetzen sind:**

1. **Beispiele für mehrdeutige Szenarien:**

```
Request: "My order is broken"
Action: Call get_customer -> lookup_order -> check status.
Rationale: "broken" may mean a damaged item; you need order details.

Request: "Get me a manager"
Action: Immediately call escalate_to_human.
Rationale: The customer explicitly requests a human. Do not attempt to solve autonomously.
```

2. **Beispiele für die Ausgabeformatierung:**

```
Finding example:
{
  "location": "src/auth/login.ts:42",
  "issue": "SQL injection in the username parameter",
  "severity": "critical",
  "suggested_fix": "Use a parameterized query"
}
```

3. **Beispiele zur Trennung von akzeptablem und problematischem Code:**

```
// Acceptable (do not flag):
const items = data.filter(x => x.active);

// Problem (flag):
const items = data.filter(x => x.active == true); // Use strict equality ===
```

4. **Beispiele für die Extraktion aus verschiedenen Dokumentformaten:**

```
Document with inline citations:
"As shown in the study (Smith, 2023), the rate is 42%."
-> {"value": "42%", "source": "Smith, 2023", "type": "inline_citation"}

Document with bibliography references:
"The rate is 42%. [1]"
-> {"value": "42%", "source": "reference_1", "type": "bibliography"}
```

5. **Beispiele für informelle Maßangaben:**

```
Text: "about two handfuls of rice"
-> {"amount": "~100g", "original_text": "two handfuls", "precision": "approximate"}

Text: "a pinch of salt"
-> {"amount": "~1g", "original_text": "a pinch", "precision": "approximate"}
```

Few-shot ist besonders wirksam für die Extraktion informeller und nicht standardisierter Maßeinheiten, die für rein regelbasierte Anweisungen zu vielfältig sind.

**Regeln zur Formatnormalisierung in Prompts:**
Wenn du strikte JSON-Schemas für strukturierte Ausgabe verwendest, ergänze Normalisierungsregeln im Prompt:

```
Normalization:
- Dates: always ISO 8601 (YYYY-MM-DD); "yesterday" -> compute an absolute date
- Currency: numeric amount + currency code; "five bucks" -> {"amount": 5, "currency": "USD"}
- Percentages: decimal fraction; "half" -> 0.5
```

Das verhindert semantische Fehler, bei denen das JSON syntaktisch gültig ist, die Werte aber inkonsistent sind.

## 6.2 Explizite Kriterien vs. vage Anweisungen

**Schlecht (vage):**

```
Check code comments for accuracy.
Be conservative—report only high-confidence findings.
```

**Gut (explizite Kriterien):**

```
Flag a comment as problematic ONLY if:
1. The comment describes behavior that CONTRADICTS the actual code behavior
2. The comment references a non-existent function or variable
3. A TODO/FIXME comment refers to a bug that has already been fixed in code

Do NOT flag:
- Comments that are merely stylistically outdated
- Comments with minor wording inaccuracies
- Missing comments (that is a separate category)
```

**Schweregrad-Kriterien mit Beispielen definieren:**

```
CRITICAL: Runtime failure for users
  Example: NullPointerException while processing a payment

HIGH: Security vulnerability
  Example: SQL injection, XSS, missing authorization checks

MEDIUM: Logic bug without immediate impact
  Example: Wrong sorting, off-by-one error

LOW: Code quality
  Example: Duplication, suboptimal algorithm for small data
```

## 6.3 Prompt Chaining

Prompt Chaining zerlegt eine komplexe Aufgabe in eine Abfolge fokussierter Schritte:

```
Step 1: Analyze auth.ts (local issues only)
       -> Output: list of issues in auth.ts

Step 2: Analyze database.ts (local issues only)
       -> Output: list of issues in database.ts

Step 3: Integration pass (cross-file dependencies)
       -> Output: issues at module boundaries
```

**Warum das wichtig ist:**
- Vermeidet **Aufmerksamkeitsverdünnung** — wenn das Modell zu viele Dateien auf einmal erhält, kann es Bugs in manchen Dateien übersehen und andere nur oberflächlich kommentieren
- Sorgt für gleichbleibende Analysequalität pro Datei
- Erlaubt die separate Analyse dateiübergreifender Wechselwirkungen

**Wann Prompt Chaining vs. dynamische Zerlegung:**
- **Prompt Chaining** — vorhersehbare, wiederholbare Aufgaben (Code-Review, Datei-Migrationen)
- **Dynamische Zerlegung** — offene Untersuchungen, bei denen sich Teilaufgaben erst während der Ausführung klären

## 6.4 Das „Interview"-Muster

Bevor Claude eine Lösung umsetzt, stellt es klärende Fragen:

```
Claude: "Before implementing caching for the API, a few questions:
1. Which cache invalidation strategy do you prefer—TTL or event-based?
2. Is stale data acceptable when the cache is unavailable?
3. Should caching be per-user or global?
4. What is the expected data volume to cache?"
```

**Wann das nützlich ist:**
- Unbekannte Domäne (Fintech, Gesundheitswesen, Rechtssysteme)
- Aufgaben mit nicht offensichtlichen Auswirkungen (Cache-Strategien, Fehlermodi)
- Mehrere gangbare Ansätze, bei denen die beste Wahl vom Kontext abhängt

## 6.5 Validierung und Retry-with-Feedback

Wenn extrahierte Daten die Validierung nicht bestehen:

```
Step 1: Extract data from the document
Step 2: Validate (Pydantic, JSON Schema, business rules)
Step 3: If there's an error—retry with context:
  - The original document
  - The previous (incorrect) extraction
  - The specific error: "Field 'total' = 150, but sum(line_items) = 145. Re-check values."
```

**Wann ein Retry wirksam ist:**
- Formatfehler (Datum im falschen Format)
- Strukturfehler (ein Feld an der falschen Stelle)
- Arithmetische Inkonsistenzen (das Modell kann nachrechnen)

**Wann ein Retry NICHT hilft:**
- Die Information fehlt im Quelldokument
- Der benötigte Kontext ist extern (die Daten stehen in einem anderen, nicht bereitgestellten Dokument)

**Pydantic als Validierungswerkzeug:**
Pydantic ist eine Python-Bibliothek zur schemabasierten Datenvalidierung. Für die Prüfung sind die Kernpunkte:
- **Strukturvalidierung:** Typen, Pflichtangaben, Enum-Beschränkungen — im Code geprüft, nachdem das JSON von Claude empfangen wurde
- **Semantische Validierung:** benutzerdefinierte Validatoren erzwingen Geschäftslogik (Summe der Positionen entspricht dem Gesamtbetrag; start_date < end_date)
- **Validierungs-Retry-Schleifen:** Bei einem Pydantic-Validierungsfehler eine Fehlermeldung konstruieren und Claude mit dem Fehlerkontext erneut prompten
- **JSON-Schema-Generierung:** Pydantic-Modelle können JSON-Schema für `tool_use` erzeugen und liefern so eine einzige Wahrheitsquelle

## 6.6 Selbstkorrektur

Ein Muster zur Erkennung interner Widersprüche:

```json
{
  "stated_total": "$150.00",
  "calculated_total": "$145.00",
  "conflict_detected": true,
  "line_items": [
    {"name": "Widget A", "price": 75.00},
    {"name": "Widget B", "price": 70.00}
  ]
}
```

Das Modell extrahiert sowohl den angegebenen Wert als auch einen berechneten Wert — weichen sie voneinander ab, erlaubt `conflict_detected` es, die Diskrepanz zu behandeln.

---

# Kapitel 7: Message Batches API

> Dokumentation: [Message Batches](https://platform.claude.com/docs/en/build-with-claude/message-batches)

## 7.1 Überblick

Mit der Message Batches API kannst du Stapel von Anfragen zur asynchronen Verarbeitung einreichen:

| Merkmal | Wert |
|---|---|
| Ersparnis | **50 %** gegenüber synchronen Aufrufen |
| Verarbeitungsfenster | Bis zu **24 Stunden** (keine Latenz-SLA-Garantie) |
| Mehrschrittiges Tool-Calling | **Nicht unterstützt** (eine Anfrage = eine Antwort) |
| Korrelation | Feld `custom_id`, um Anfrage und Antwort zu verknüpfen |

## 7.2 Wann Batch-API vs. synchrone API

| Aufgabe | API | Warum |
|---|---|---|
| Pre-Merge-PR-Prüfung | **Synchron** | Der Entwickler wartet; 24 Stunden sind inakzeptabel |
| Nächtlicher Tech-Debt-Bericht | **Batch** | Ergebnis wird bis zum Morgen benötigt; 50 % Ersparnis |
| Wöchentliches Sicherheitsaudit | **Batch** | Nicht dringend; 50 % Ersparnis |
| Interaktives Code-Review | **Synchron** | Sofortige Antwort erforderlich |
| Verarbeitung von 10.000 Dokumenten | **Batch** | Massenverarbeitung; die Ersparnis ist erheblich |

## 7.3 Verwendung von `custom_id`

```json
{
  "custom_id": "doc-invoice-2024-001",
  "params": {
    "model": "claude-sonnet-4-6",
    "max_tokens": 1024,
    "messages": [{"role": "user", "content": "Extract data from: ..."}]
  }
}
```

`custom_id` erlaubt dir:
- das Ergebnis dem Ursprungsdokument zuzuordnen
- bei einem Fehlschlag nur die fehlgeschlagenen Dokumente erneut einzureichen
- die erneute Verarbeitung erfolgreicher Dokumente zu vermeiden

## 7.4 Umgang mit Fehlschlägen in Batches

1. Reiche einen Batch von 100 Dokumenten ein
2. 95 sind erfolgreich; 5 schlagen fehl (Kontextlimit überschritten)
3. Identifiziere die Fehlschläge anhand von `custom_id`
4. Passe die Strategie an (z. B. lange Dokumente in Blöcke aufteilen)
5. Reiche nur die 5 fehlgeschlagenen Dokumente erneut ein

## 7.5 SLA-Planung

Wenn du ein Ergebnis in 30 Stunden brauchst und die Batch-API bis zu 24 Stunden benötigen kann:
- Einreichungsfenster: 30 - 24 = **6 Stunden**
- Batches müssen spätestens 24 Stunden vor der Frist eingereicht werden
- Bei häufigen Einreichungen in 4-Stunden-Fenster aufteilen

---

# Kapitel 8: Strategien zur Aufgabenzerlegung

## 8.1 Feste Pipelines (Prompt Chaining)

Jeder Schritt ist im Voraus definiert:

```
Document -> Metadata extraction -> Data extraction -> Validation -> Enrichment -> Final output
```

**Wann zu verwenden:**
- Die Aufgabenstruktur ist vorhersehbar (Reviews folgen immer derselben Vorlage)
- Alle Schritte sind von vornherein bekannt
- Du brauchst Stabilität und Reproduzierbarkeit

## 8.2 Dynamische adaptive Zerlegung

Teilaufgaben werden auf Basis von Zwischenergebnissen erzeugt:

```
1. "Add tests for a legacy codebase"
2. -> First: map the structure (Glob, Grep)
3. -> Found: 3 modules with no tests, 2 with partial coverage
4. -> Prioritize: start with the payments module (high risk)
5. -> During work: discovered a dependency on an external API
6. -> Adapt: add a mock for the external API before writing tests
```

**Wann zu verwenden:**
- Offene, untersuchende Aufgaben
- Wenn der volle Umfang von vornherein unbekannt ist
- Wenn jeder Schritt von den Ergebnissen des vorherigen abhängt

## 8.3 Mehrfach-Durchlauf-Code-Review

Für Pull Requests mit 10+ Dateien:

```
Pass 1 (per-file): Analyze auth.ts -> list local issues
Pass 1 (per-file): Analyze database.ts -> list local issues
Pass 1 (per-file): Analyze routes.ts -> list local issues
...
Pass 2 (integration): Analyze relationships between files
  -> Cross-file issues: inconsistent types, circular dependencies
```

**Warum ein einziger Durchlauf über 14 Dateien schlecht ist:**
- Aufmerksamkeitsverdünnung: tiefe Analyse für manche Dateien, oberflächlich für andere
- Inkonsistente Kommentare: ein Muster wird in einer Datei beanstandet, in einer anderen freigegeben
- Übersehene Bugs: offensichtliche Fehler werden aufgrund kognitiver Überlastung übersprungen

---

# Kapitel 9: Eskalation und Human-in-the-Loop

## 9.1 Wann an einen Menschen eskalieren

**Eskalationsauslöser (klare Regeln):**

| Situation | Aktion |
|---|---|
| Der Kunde fordert ausdrücklich „einen Manager" | Sofort eskalieren; nicht versuchen zu lösen |
| Die Richtlinie deckt die Anfrage nicht ab | Eskalieren (z. B. Preisanpassung an einen Wettbewerber, wenn die Richtlinie dazu schweigt) |
| Der Agent kommt nicht voran | Nach einer angemessenen Anzahl von Versuchen eskalieren |
| Finanzoperation über einem Schwellenwert | Eskalieren (am besten per Hook erzwungen, nicht per Prompt) |
| Mehrere Treffer bei der Kundensuche | Nach zusätzlichen Identifikationsmerkmalen fragen; nicht raten |

**Was KEIN zuverlässiger Auslöser ist:**

| Unzuverlässige Methode | Warum sie versagt |
|---|---|
| Stimmungsanalyse | Die Stimmung des Kunden korreliert nicht mit der Komplexität des Falls |
| Vom Modell selbst eingeschätzte Konfidenz (1–10) | Das Modell kann selbstsicher falsch liegen; die Kalibrierung ist schlecht |
| Ein automatischer Klassifikator | Overengineering; erfordert ggf. Trainingsdaten, die du nicht hast |

## 9.2 Eskalationsmuster

**Sofortige Eskalation:**

```
Customer: "I want to speak to a manager"
Agent: [immediately calls escalate_to_human]
NOT: "I can help with your issue, let me..."
```

**Eskalation nach einem Lösungsversuch:**

```
Customer: "My refrigerator broke two days after purchase"
Agent: [checks the order, offers a warranty replacement]
If the customer is not satisfied -> escalate
```

**Differenzierte Eskalation (anerkennen → lösen → bei Wiederholung eskalieren):**

```
Customer: "This is outrageous, I'm very unhappy with the quality!"
Agent: [acknowledges frustration] "I understand your frustration."
       [offers resolution] "I can offer a replacement or a refund."
Customer: "No, I want to talk to someone!"
Agent: [customer insists again -> immediate escalation]
```

Kernprinzip: zuerst die Emotion anerkennen, dann eine konkrete Lösung vorschlagen und nur dann eskalieren, wenn der Kunde den Wunsch nach einem Menschen wiederholt. Nicht schon bei der ersten Unmutsäußerung eskalieren (das ist nicht dasselbe wie die Bitte um einen Manager).

**Eskalation bei einer Richtlinienlücke:**

```
Customer: "Competitor X has this item 30% cheaper—give me a discount"
Policy: covers price adjustments only on your own site
Agent: [escalates — policy does not cover competitor price matching]
```

## 9.3 Strukturierte Übergabeprotokolle

Bei einer Eskalation sollte der Agent eine strukturierte Zusammenfassung an einen Menschen übergeben:

```json
{
  "customer_id": "CUST-12345",
  "customer_name": "Ivan Petrov",
  "issue_summary": "Refund request for a damaged item",
  "order_id": "ORD-67890",
  "root_cause": "Item arrived damaged; photos attached",
  "actions_taken": [
    "Verified customer via get_customer",
    "Confirmed order via lookup_order",
    "Offered a standard replacement — customer insists on a refund"
  ],
  "refund_amount": "$89.99",
  "recommended_action": "Approve a full refund",
  "escalation_reason": "Customer requested to speak with a manager"
}
```

Der menschliche Bearbeiter hat keinen Zugriff auf das vollständige Gesprächsprotokoll — er sieht nur diese Zusammenfassung. Deshalb muss sie vollständig und in sich abgeschlossen sein.

## 9.4 Konfidenzkalibrierung und menschliche Aufsicht

Für Datenextraktionssysteme:

1. **Konfidenzwerte auf Feldebene:** Das Modell gibt pro extrahiertem Feld einen Konfidenzwert aus
2. **Kalibrierung:** Nutze gelabelte Validierungsdatensätze, um die Schwellenwerte einzustellen
3. **Routing:**
   - Hohe Konfidenz + stabile Genauigkeit -> automatisierte Verarbeitung
   - Niedrige Konfidenz oder mehrdeutige Quellen -> menschliches Review

**Geschichtete Zufallsstichprobe:**
- Auch bei Extraktionen mit hoher Konfidenz regelmäßig eine Stichprobe prüfen
- Eine aggregierte Genauigkeit von 97 % kann für einen bestimmten Dokumenttyp 40 % Fehler verbergen
- Analysiere die Genauigkeit nach Dokumenttyp und nach Feld, nicht nur insgesamt

---

# Kapitel 10: Fehlerbehandlung in Multi-Agenten-Systemen

## 10.1 Fehlerkategorien

| Kategorie | Beispiele | Wiederholbar | Aktion des Agenten |
|---|---|---|---|
| **Transient** | Timeout, 503, Netzwerkausfall | Ja | Retry mit exponentiellem Backoff |
| **Validierung** | Ungültiges Eingabeformat, fehlendes Pflichtfeld | Nein (Eingabe korrigieren) | Anfrage ändern und erneut versuchen |
| **Geschäftlich** | Richtlinienverstoß, Schwellenwert überschritten | Nein | Dem Nutzer erklären; eine Alternative vorschlagen |
| **Berechtigung** | Zugriff verweigert | Nein | Eskalieren |

## 10.2 Anti-Muster bei der Fehlerbehandlung

| Anti-Muster | Problem | Korrekter Ansatz |
|---|---|---|
| Generischer Status „search unavailable" | Der Koordinator kann nicht entscheiden, wie er sich erholt | Fehlertyp, Anfrage, Teilergebnisse, Alternativen zurückgeben |
| Stilles Unterdrücken (leeres Ergebnis = Erfolg) | Der Koordinator denkt, es gab keine Treffer, dabei war es ein Fehlschlag | „Keine Ergebnisse" von „Suchfehler" unterscheiden |
| Abbruch des gesamten Workflows bei einem Fehlschlag | Du verlierst alle Teilergebnisse | Mit Teilergebnissen weitermachen; Lücken kennzeichnen |
| Endlose Retries innerhalb eines Subagenten | Latenz und verschwendete Ressourcen | Lokale Erholung (1–2 Retries), dann an den Koordinator weitergeben |

## 10.3 Ein strukturierter Subagenten-Fehler

```json
{
  "status": "partial_failure",
  "failure_type": "timeout",
  "attempted_query": "AI impact on music industry 2024",
  "partial_results": [
    {"title": "AI Music Generation Report", "url": "...", "relevance": 0.8}
  ],
  "alternative_approaches": [
    "Try a narrower query: 'AI music composition tools'",
    "Use an alternative data source"
  ],
  "coverage_impact": "Not covered: AI impact on music production"
}
```

Das liefert dem Koordinator die Informationen, die er zur Entscheidung braucht:
- Retry mit einer geänderten Anfrage?
- Teilergebnisse verwenden?
- An einen anderen Subagenten delegieren?
- Ohne diesen Abschnitt weitermachen und die Lücke kennzeichnen?

## 10.4 Abdeckungshinweise in der finalen Synthese

```markdown
## Report: AI Impact on Creative Industries

### Visual Art (FULL COVERAGE)
[research results]

### Music (PARTIAL COVERAGE — search agent timeout)
[partial results]
⚠️ Note: coverage for this section is limited due to a timeout in the search agent.

### Literature (FULL COVERAGE)
[research results]
```

---

# Kapitel 11: Kontextverwaltung in Produktionssystemen

## 11.1 Fakten in einen separaten Block extrahieren

Statt sich auf den Gesprächsverlauf zu verlassen (der bei der Zusammenfassung an Qualität verliert), extrahiere Schlüsselfakten in einen strukturierten Block:

```
=== CASE FACTS (updated whenever a new fact appears) ===
Customer ID: CUST-12345
Order ID: ORD-67890
Order Date: 2025-01-15
Order Amount: $89.99
Issue: Damaged item on delivery
Customer Request: Full refund
Status: Pending manager approval
===
```

Füge diesen Block in jeden Prompt ein, unabhängig davon, wie der Verlauf zusammengefasst wird.

## 11.2 Tool-Ergebnisse beschneiden

Wenn `lookup_order` 40+ Felder zurückgibt, du für die aktuelle Aufgabe aber nur 5 brauchst:

```python
# PostToolUse hook: keep only relevant fields
@hook("PostToolUse", tool="lookup_order")
def trim_order_fields(result):
    return {
        "order_id": result["order_id"],
        "status": result["status"],
        "total": result["total"],
        "items": result["items"],
        "return_eligible": result["return_eligible"]
    }
```

Das spart Kontext und reduziert Rauschen.

## 11.3 Positionsbewusste Eingabe

Platziere kritische Informationen mit Blick auf den Lost-in-the-middle-Effekt:

```
[KEY FINDINGS — at the top]
Found 3 critical vulnerabilities...

[DETAILED RESULTS — middle]
=== File auth.ts ===
...
=== File database.ts ===
...

[ACTION ITEMS — at the end]
Priority: fix auth.ts vulnerabilities before merge.
```

## 11.4 Scratchpad-Dateien

Bei langen Untersuchungen kann der Agent Schlüsselerkenntnisse in eine Scratchpad-Datei schreiben:

```
# investigation-scratchpad.md
## Key findings
- PaymentProcessor in src/payments/processor.ts inherits from BaseProcessor
- refund() is called from 3 places: OrderController, AdminPanel, CronJob
- External PaymentGateway API has a rate limit of 100 req/min
- Migration #47 added refund_reason (NOT NULL) — 2024-12-01
```

Wenn der Kontext an Qualität verliert (oder in einer neuen Sitzung), kann der Agent das Scratchpad konsultieren, statt die Erkundung erneut auszuführen.

## 11.5 Delegation an Subagenten zum Schutz des Kontexts

```
Main agent: "Investigate dependencies of the payments module"
  -> Subagent (Explore): reads 15 files, traces imports
  -> Returns: "Payments depends on AuthService, OrderModel, and the external PaymentGateway API"

Main agent: keeps one line in context instead of 15 files
```

**Separate Kontextschicht:**
In Multi-Agenten-Systemen arbeitet jeder Subagent innerhalb eines begrenzten Kontextbudgets — er erhält nur die für seine Aufgabe erforderlichen Informationen. Der Koordinator fungiert als separate Kontextschicht: Er aggregiert die Ausgaben der Subagenten, hält den globalen Zustand und teilt den Kontext zu. Das verhindert „Kontext-Leckagen", bei denen ein Agent das Fenster mit für andere irrelevanten Informationen verbraucht.

**Begrenzte Kontextbudgets für Subagenten:**
- Sende minimalen Kontext: eine spezifische Aufgabe + die nötigen Daten
- Weise den Subagenten an, strukturierte Ergebnisse zurückzugeben, keine Rohdaten-Dumps
- Verwende `allowedTools`, um das Toolset des Subagenten zu begrenzen — weniger Tools bedeuten weniger Ablenkung und niedrigere Kontextkosten

## 11.6 Strukturierte Zustandspersistenz (für die Wiederherstellung nach Abstürzen)

Jeder Agent exportiert seinen Zustand an einen bekannten Ort:

```json
// agent-state/web-search-agent.json
{
  "status": "completed",
  "queries_executed": ["AI music 2024", "AI music composition"],
  "results_count": 12,
  "key_findings": [...],
  "coverage": ["music composition", "music production"],
  "gaps": ["music distribution", "music licensing"]
}
```

Der Koordinator lädt beim Fortsetzen ein Manifest:

```json
// agent-state/manifest.json
{
  "web-search": "completed",
  "doc-analysis": "in_progress",
  "synthesis": "not_started"
}
```

---

# Kapitel 12: Herkunft (Provenance) bewahren

## 12.1 Das Problem des Attributionsverlusts

Beim Zusammenfassen von Ergebnissen aus mehreren Quellen kann die Verbindung „Aussage → Quelle" verloren gehen:

```
Bad: "The AI music market is estimated at $3.2B." (No source, no year.)

Good:
{
  "claim": "The AI music market is estimated at $3.2B.",
  "source_url": "https://example.com/report",
  "source_name": "Global AI Music Report 2024",
  "publication_date": "2024-06-15",
  "confidence": 0.9
}
```

## 12.2 Umgang mit widersprüchlichen Daten

Wenn zwei Quellen unterschiedliche Werte liefern:

```json
{
  "claim": "Share of AI-generated music on streaming platforms",
  "values": [
    {
      "value": "12%",
      "source": "Spotify Annual Report 2024",
      "date": "2024-03",
      "methodology": "Automated classification"
    },
    {
      "value": "8%",
      "source": "Music Industry Association Survey",
      "date": "2024-07",
      "methodology": "Survey of 500 labels"
    }
  ],
  "conflict_detected": true,
  "possible_explanation": "Difference in methodology and time period"
}
```

Wähle nicht willkürlich einen Wert. Bewahre beide mit Attribution und lass den Koordinator entscheiden.

## 12.3 Datumsangaben für die korrekte Interpretation einbeziehen

Ohne Datumsangaben können zeitliche Unterschiede als Widersprüche fehlinterpretiert werden:

```
Bad: "Source A says 10%, source B says 15%. Contradiction."
Good: "Source A (2023) says 10%, source B (2024) says 15%. Likely +5% growth over a year."
```

## 12.4 Nach Inhaltstyp darstellen

Zwinge nicht alles in ein Format:
- Finanzdaten -> Tabellen
- Nachrichten und Analysen -> Fließtext
- Technische Erkenntnisse -> strukturierte Listen
- Zeitreihen -> chronologische Ordnung

---

# Kapitel 13: Integrierte Tools von Claude Code

## 13.1 Referenz zur Tool-Auswahl

| Aufgabe | Tool | Beispiel |
|---|---|---|
| Dateien nach Name/Muster finden | **Glob** | `**/*.test.tsx`, `src/components/**/*.ts` |
| Innerhalb von Dateien suchen | **Grep** | Funktionsname, Fehlermeldung, Import |
| Eine Datei vollständig lesen | **Read** | Eine Datei zur Analyse laden |
| Eine neue Datei schreiben | **Write** | Eine Datei von Grund auf erstellen |
| Eine bestehende Datei präzise bearbeiten | **Edit** | Einen bestimmten Ausschnitt über einen eindeutigen Textabgleich ersetzen |
| Einen Shell-Befehl ausführen | **Bash** | git, npm, Tests ausführen, Build |

## 13.2 Strategie der schrittweisen Untersuchung

Lies nicht alle Dateien auf einmal. Baue das Verständnis schrittweise auf:

```
1. Grep: find entry points (function definition, export)
2. Read: read the found files
3. Grep: find usages (import, calls)
4. Read: read consumer files
5. Repeat until you have a complete picture
```

## 13.3 Fallback: Read + Write statt Edit

Wenn Edit wegen eines nicht eindeutigen Textabgleichs fehlschlägt:
1. Read — den vollständigen Dateiinhalt laden
2. Den Inhalt programmatisch ändern
3. Write — die aktualisierte Version schreiben

---

# TEIL II: NOTIZEN ZU DEN PRÜFUNGSDOMÄNEN

---

# Domäne 1: Agentenarchitektur und Orchestrierung (27 %)

## 1.1 Agentische Schleifen für die autonome Ausführung von Aufgaben entwerfen

### Kernwissen:
- Lebenszyklus der Agentenschleife: Claude-Anfrage senden, `stop_reason` prüfen (`"tool_use"` vs. `"end_turn"`), Tools ausführen, Ergebnisse für die nächste Iteration zurückgeben
- Tool-Ergebnisse werden an den Gesprächsverlauf angehängt, damit das Modell die nächste Aktion entscheiden kann
- Modellgesteuerte Entscheidungsfindung (Claude wählt das nächste Tool) vs. fest kodierte Entscheidungsbäume

### Kernkompetenzen:
- Flusssteuerung: die Schleife fortsetzen, wenn `stop_reason = "tool_use"`, und bei `"end_turn"` anhalten
- Tool-Ergebnisse zwischen den Iterationen an den Kontext anhängen
- Zu vermeidende Anti-Muster: den Assistenten-Text auf Abschluss parsen, willkürliche Iterationslimits als primären Stoppmechanismus verwenden

## 1.2 Multi-Agenten-Systeme orchestrieren (Koordinator–Subagent)

### Kernwissen:
- Hub-and-Spoke-Architektur: Der Koordinator besitzt die gesamte Kommunikation zwischen Agenten, die Fehlerbehandlung und das Routing
- Subagenten arbeiten mit isoliertem Kontext — sie erben den Verlauf des Koordinators nicht automatisch
- Verantwortlichkeiten des Koordinators: Aufgabenzerlegung, Delegation, Ergebnisaggregation, dynamische Auswahl der Subagenten
- Risiko einer zu engen Zerlegung durch den Koordinator

### Kernkompetenzen:
- Die Recherche-Abdeckung auf die Subagenten aufteilen, um Duplizierung zu minimieren
- Iterative Verfeinerungsschleifen umsetzen (der Koordinator bewertet die Synthese und leitet Aufgaben neu)
- Die gesamte Kommunikation über den Koordinator leiten, um Beobachtbarkeit zu gewährleisten

## 1.3 Subagenten-Aufrufe, Kontextübergabe und Starten konfigurieren

### Kernwissen:
- Das `Task`-Tool startet Subagenten; die `allowedTools` des Koordinators müssen `"Task"` enthalten
- Der Subagenten-Kontext muss explizit in den Prompt aufgenommen werden; Subagenten erben keinen Elternkontext
- Konfiguration von `AgentDefinition`: Beschreibungen, System-Prompts, Tool-Beschränkungen
- Sitzungsverwaltung über `fork_session`, um Alternativen zu erkunden

### Kernkompetenzen:
- Die vollständigen Ausgaben vorheriger Agenten in den Subagenten-Prompt aufnehmen
- Strukturierte Formate verwenden, um bei der Kontextübergabe Daten von Metadaten zu trennen
- Parallele Subagenten über mehrere `Task`-Aufrufe in einem einzigen Koordinator-Turn starten
- Koordinator-Prompts in Form von Zielen und Qualitätskriterien schreiben statt als Schritt-für-Schritt-Anweisungen

## 1.4 Mehrschrittige Workflows mit Enforcement- und Handoff-Mustern umsetzen

### Kernwissen:
- Der Unterschied zwischen **programmatischem Enforcement** (Hooks, Vorbedingungen) und **Prompt-Anleitung** zum Ordnen eines Workflows
- Wenn du deterministische Garantien brauchst (z. B. Identitätsprüfung vor Finanzoperationen), reichen Prompts allein nicht aus
- Strukturierte Übergabeprotokolle bei der Eskalation (Kunden-ID, Grund, empfohlene Aktion)

### Kernkompetenzen:
- Programmatische Vorbedingungen, die nachgelagerte Aufrufe blockieren, bis vorherige Schritte abgeschlossen sind (z. B. `process_refund` blockieren, bis `get_customer` eine verifizierte ID zurückgibt)
- Mehrteilige Kundenanfragen in separate Punkte zerlegen
- Strukturierte Zusammenfassungen erzeugen, wenn an einen Menschen eskaliert wird

## 1.5 Agent-SDK-Hooks zum Abfangen von Tool-Aufrufen und Normalisieren von Daten

### Kernwissen:
- Hook-Muster (z. B. `PostToolUse`), um Tool-Ergebnisse abzufangen, bevor das Modell sie konsumiert
- Hooks, die ausgehende Aufrufe abfangen, um Compliance-Regeln durchzusetzen (z. B. Rückerstattungen über einem Schwellenwert blockieren)
- Hooks liefern **deterministische Garantien** vs. Prompt-Anweisungen, die **probabilistische Compliance** liefern

### Kernkompetenzen:
- `PostToolUse`-Hooks zum Normalisieren von Datenformaten (Unix-Zeitstempel, ISO 8601, numerische Statuscodes)
- Abfang-Hooks, um richtlinienwidrige Aktionen zu blockieren und auf Eskalation umzuleiten
- Hooks gegenüber Prompts wählen, wenn Geschäftsregeln garantierte Compliance erfordern

## 1.6 Strategien zur Aufgabenzerlegung für komplexe Workflows

### Kernwissen:
- **Feste Pipelines** (Prompt Chaining) vs. **dynamische adaptive Zerlegung** auf Basis von Zwischenergebnissen
- Prompt Chaining: sequentielle Schritte (jede Datei separat analysieren, dann einen Integrationsdurchlauf)
- Adaptive Untersuchungspläne, die Teilaufgaben auf Basis des Entdeckten erzeugen

### Kernkompetenzen:
- Prompt Chaining für vorhersehbare, mehrteilige Reviews nutzen; dynamische Zerlegung für offene Untersuchungen
- Große Code-Reviews in eine Analyse pro Datei plus einen separaten dateiübergreifenden Integrationsdurchlauf aufteilen
- Offene Aufgaben zerlegen: zuerst die Struktur kartieren, dann einen priorisierten Plan aufbauen

## 1.7 Sitzungszustand, Fortsetzen und Forking

### Kernwissen:
- `--resume <session-name>` zum Fortsetzen benannter Sitzungen
- `fork_session`, um aus einem gemeinsamen Kontext unabhängige Untersuchungszweige zu erzeugen
- Die Bedeutung, den Agenten beim Fortsetzen von Sitzungen über Dateiänderungen zu informieren
- Eine neue Sitzung mit einer strukturierten Zusammenfassung kann zuverlässiger sein als das Fortsetzen mit veralteten Ergebnissen

### Kernkompetenzen:
- `--resume` verwenden, um benannte Untersuchungssitzungen fortzusetzen
- `fork_session` verwenden, um Ansätze parallel zu vergleichen
- Zwischen Fortsetzen (Kontext noch aktuell) und Neustart einer Sitzung (Ergebnisse veraltet) wählen

---

# Domäne 2: Tool-Design und MCP-Integration (18 %)

## 2.1 Tool-Schnittstellen mit klaren Beschreibungen entwerfen

### Kernwissen:
- Tool-Beschreibungen sind der **primäre Mechanismus**, mit dem ein LLM Tools auswählt; minimale Beschreibungen führen zu unzuverlässiger Auswahl
- Die Bedeutung, Eingabeformate, Beispielanfragen, Grenzfälle und Anwendungsgrenzen aufzunehmen
- Mehrdeutige oder sich überschneidende Beschreibungen verursachen Fehlrouting
- Die Formulierung des System-Prompts kann unbeabsichtigte Assoziationen zu Tools erzeugen

### Kernkompetenzen:
- Beschreibungen schreiben, die jedes Tool klar von ähnlichen Alternativen abgrenzen
- Tools umbenennen, um funktionale Überschneidungen zu beseitigen (z. B. `analyze_content` -> `extract_web_results`)
- Allzweck-Tools in spezialisierte Tools mit klaren Eingabe-/Ausgabeverträgen aufteilen

## 2.2 Strukturierte Fehlerantworten für MCP-Tools umsetzen

### Kernwissen:
- Das Flag `isError` in MCP-Tool-Antworten
- Der Unterschied zwischen **transienten Fehlern** (Timeouts), **Validierungsfehlern** (fehlerhafte Eingabe), **Geschäftsfehlern** (Richtlinienverstöße) und **Zugriffs-/Berechtigungsfehlern**
- Generische Fehler („Operation failed") verhindern korrekte Erholungsentscheidungen
- Der Unterschied zwischen wiederholbaren und nicht wiederholbaren Fehlern

### Kernkompetenzen:
- Strukturierte Metadaten zurückgeben, etwa `errorCategory` (transient/validation/permission), `isRetryable` und eine menschenlesbare Meldung
- `retryable: false` für Verstöße gegen Geschäftsregeln mit klaren, an den Nutzer gerichteten Erklärungen verwenden
- Lokale Erholung innerhalb von Subagenten bei transienten Fehlern; nur Fehler weitergeben, die sie nicht lösen können
- Zugriffsfehler (Retry-Entscheidung) von gültigen leeren Ergebnissen (keine Treffer) unterscheiden

## 2.3 Tools über Agenten verteilen und `tool_choice` konfigurieren

### Kernwissen:
- Zu viele Tools pro Agent (z. B. 18 statt 4–5) **verringern** die Zuverlässigkeit der Tool-Auswahl
- Agenten mit Tools außerhalb ihrer Spezialisierung neigen dazu, sie falsch zu verwenden
- Eingeschränkter Tool-Zugriff: nur rollenrelevante Tools plus ein begrenzter Satz rollenübergreifender Hilfsmittel
- `tool_choice`: `"auto"`, `"any"` und erzwungene Tool-Auswahl (`{"type": "tool", "name": "..."}`)

### Kernkompetenzen:
- Das Toolset jedes Subagenten auf das für seine Rolle Relevante beschränken
- Allgemeine Tools durch eingeschränkte Alternativen ersetzen (z. B. `fetch_url` -> `load_document`)
- `tool_choice: "any"` verwenden, um einen Tool-Aufruf statt einer Textantwort zu garantieren
- Ein bestimmtes Tool erzwingen, um die Ausführungsreihenfolge sicherzustellen

## 2.4 MCP-Server in Claude Code und Agenten-Workflows integrieren

### Kernwissen:
- Geltungsbereich von MCP-Servern: Projekt (`.mcp.json`) für Teams vs. Nutzer (`~/.claude.json`) für Experimente
- Ersetzen von Umgebungsvariablen in `.mcp.json` (z. B. `${GITHUB_TOKEN}`) für die Geheimnisverwaltung
- Tools aller verbundenen MCP-Server werden bei der Verbindung erkannt und sind gleichzeitig verfügbar
- MCP-Resources als „Inhaltskataloge" (Aufgabenzusammenfassungen, Datenbankschemas), um explorative Tool-Aufrufe zu reduzieren

### Kernkompetenzen:
- Gemeinsam genutzte MCP-Server im Projekt-`.mcp.json` mit Tokens auf Basis von Umgebungsvariablen konfigurieren
- Persönliche/experimentelle Server in `~/.claude.json` halten
- Community-MCP-Server gegenüber eigenen Servern für Standardintegrationen bevorzugen

## 2.5 Integrierte Tools auswählen und anwenden (Read, Write, Edit, Bash, Grep, Glob)

### Kernwissen:
- **Grep**: innerhalb von Dateiinhalten suchen (Funktionsnamen, Fehlermeldungen, Importe)
- **Glob**: Dateien nach Namens-/Erweiterungsmustern finden
- **Read/Write**: Operationen auf ganzen Dateien; **Edit**: präzise Änderungen über eindeutige Textabgleiche
- Wenn Edit wegen nicht eindeutiger Treffer fehlschlägt, auf Read + Write ausweichen

### Kernkompetenzen:
- Grep für die Inhaltssuche und Glob für die Dateisuche nach Mustern verwenden
- Das Verständnis schrittweise aufbauen: Grep der Einstiegspunkte, dann Read, um Abläufe zu verfolgen
- Funktionsnutzung durch Wrapper-Module verfolgen

---

# Domäne 3: Claude-Code-Konfiguration und Workflows (20 %)

## 3.1 CLAUDE.md mit Hierarchie, Geltungsbereich und modularer Organisation konfigurieren

### Kernwissen:
- CLAUDE.md-Hierarchie: Nutzer (`~/.claude/CLAUDE.md`), Projekt (`.claude/CLAUDE.md` oder `CLAUDE.md` im Stamm) und Verzeichnisebene (CLAUDE.md in Unterverzeichnissen)
- Einstellungen auf Nutzerebene gelten nur für einen Nutzer und werden nicht über die Versionskontrolle geteilt
- `@path`-Syntax zum Referenzieren externer Dateien (z. B. `@./standards/coding-style.md`), um CLAUDE.md zu modularisieren
- Das Verzeichnis `.claude/rules/` für themenfokussierte Regeldateien statt einer monolithischen CLAUDE.md

### Kernkompetenzen:
- Hierarchieprobleme diagnostizieren (ein neues Teammitglied verpasst Anweisungen, weil sie auf Nutzer- statt auf Projektebene liegen)
- `@path` (z. B. `@./standards/testing.md`) verwenden, um Standards gezielt in die CLAUDE.md jedes Pakets einzubinden
- Eine große CLAUDE.md in mehrere `.claude/rules/`-Dateien aufteilen (testing.md, api-conventions.md, deployment.md)

## 3.2 Benutzerdefinierte Slash-Befehle und Skills erstellen und konfigurieren

### Kernwissen:
- **Projektbefehle** in `.claude/commands/` (über die Versionskontrolle geteilt) vs. **Nutzerbefehle** in `~/.claude/commands/`
- Skills in `.claude/skills/` mit `SKILL.md`-Frontmatter: `context: fork`, `allowed-tools`, `argument-hint`
- `context: fork` führt den Skill in einem isolierten Subagenten-Kontext aus, sodass er die Hauptsitzung nicht belastet
- Persönliche Skill-Varianten können unter anderen Namen in `~/.claude/skills/` liegen

### Kernkompetenzen:
- Projekt-Slash-Befehle in `.claude/commands/` ablegen, damit das gesamte Team sie erhält
- `context: fork` verwenden, um Skills mit ausführlicher Ausgabe zu isolieren
- `allowed-tools` verwenden, um einzuschränken, welche Tools ein Skill nutzen kann
- `argument-hint` verwenden, um Entwickler zu erforderlichen Parametern aufzufordern

## 3.3 Pfadspezifische Regeln für bedingtes Laden von Konventionen verwenden

### Kernwissen:
- `.claude/rules/`-Dateien können ein YAML-Frontmatter `paths` enthalten, um Regeln auf Basis von Glob-Mustern zu aktivieren
- Pfad-eingeschränkte Regeln laden **nur** beim Bearbeiten passender Dateien und sparen Kontext und Tokens
- Glob-basierte Pfadregeln können einer CLAUDE.md auf Verzeichnisebene vorzuziehen sein, wenn Konventionen über viele Verzeichnisse gelten (z. B. Tests)

### Kernkompetenzen:
- `.claude/rules/`-Dateien mit `paths: ["terraform/**/*"]` erstellen, damit sie nur beim Arbeiten an passenden Dateien laden
- Glob-Muster (`**/*.test.tsx`) verwenden, um Konventionen nach Dateityp anzuwenden, unabhängig vom Ort
- Pfadspezifische Regeln einer CLAUDE.md auf Verzeichnisebene vorziehen, wenn Konventionen die gesamte Codebasis betreffen

## 3.4 Entscheiden, wann Planungsmodus vs. direkte Ausführung

### Kernwissen:
- **Planungsmodus**: für komplexe Aufgaben mit großen Änderungen, mehreren gangbaren Ansätzen und Architekturentscheidungen
- **Direkte Ausführung**: für einfache, gut verstandene Änderungen (z. B. Hinzufügen einer einzelnen Validierung)
- Der Planungsmodus ermöglicht sichere Erkundung der Codebasis, bevor Änderungen vorgenommen werden
- Der Explore-Subagent isoliert ausführliche Erkundungsausgabe

### Kernkompetenzen:
- Den Planungsmodus für Aufgaben mit architektonischen Konsequenzen verwenden (Microservices, Migrationen, die 45+ Dateien betreffen)
- Direkte Ausführung für Korrekturen mit einem klaren Stacktrace und einer einzelnen Datei verwenden
- Den Explore-Subagenten verwenden, um das Erschöpfen des Kontextfensters bei mehrphasigen Aufgaben zu verhindern
- Ansätze kombinieren: planen für die Erkundung, dann ausführen für die Umsetzung

## 3.5 Iterative Verfeinerung für schrittweise Verbesserung

### Kernwissen:
- Konkrete Eingabe-/Ausgabe-Beispiele sind der wirksamste Weg, Erwartungen zu kommunizieren
- **Testgetriebene Iteration**: zuerst Tests schreiben, dann anhand der Fehlschläge iterieren
- Das „Interview"-Muster: Claude stellt Fragen, um nicht offensichtliche Designüberlegungen aufzudecken
- Wann alle Probleme in einer Nachricht bereitstellen (voneinander abhängig) vs. nacheinander (unabhängig)

### Kernkompetenzen:
- 2–3 konkrete Eingabe-/Ausgabe-Beispiele bereitstellen, um Transformationsanforderungen zu klären
- Testsätze mit erwartetem Verhalten, Grenzfällen und Leistungsanforderungen vor der Umsetzung aufbauen
- Das Interview-Muster verwenden, um Designaspekte aufzudecken (Cache-Invalidierung, Fehlermodi)
- Konkrete Testfälle mit Beispiel-Eingaben und erwarteten Ausgaben für Grenzfälle bereitstellen

## 3.6 Claude Code in CI/CD-Pipelines integrieren

### Kernwissen:
- Das Flag `-p` (oder `--print`) für den nicht-interaktiven Modus in automatisierten Pipelines
- `--output-format json` und `--json-schema` für strukturierte Ausgabe in CI
- CLAUDE.md liefert Projektkontext (Test-Standards, Review-Kriterien) für CI-ausgelöstes Claude Code
- **Isolierung des Sitzungskontexts**: dieselbe Sitzung, die den Code erzeugt hat, ist beim Prüfen weniger wirksam als eine unabhängige Instanz

### Kernkompetenzen:
- Claude Code in CI mit `-p` ausführen, um Hängen bei interaktiver Eingabe zu vermeiden
- `--output-format json` + `--json-schema` für strukturierte Ergebnisse verwenden (z. B. Inline-PR-Kommentare)
- Beim erneuten Ausführen nach neuen Commits die vorherigen Review-Ergebnisse einbeziehen (nur neue/ungelöste Probleme melden)
- Test-Standards und verfügbare Fixtures in CLAUDE.md dokumentieren, um die Qualität der Testgenerierung zu verbessern
- Bestehende Testdateien in den Kontext aufnehmen, wenn neue Tests generiert werden, um Duplizierung zu vermeiden und den Stil einheitlich zu halten

---

# Domäne 4: Prompt Engineering und strukturierte Ausgabe (20 %)

## 4.1 Prompts mit expliziten Kriterien entwerfen, um die Genauigkeit zu verbessern

### Kernwissen:
- Explizite Kriterien sind wirksamer als vage Anweisungen (z. B. „Kommentare nur markieren, wenn sie dem Code widersprechen" vs. „die Richtigkeit von Kommentaren prüfen")
- Allgemeine Anleitung wie „sei konservativer" wirkt schlechter als konkrete kategoriale Kriterien
- Die Wirkung von False Positives auf das Vertrauen der Entwickler: hohe False-Positive-Raten in manchen Kategorien untergraben das Vertrauen in die genauen Kategorien

### Kernkompetenzen:
- Review-Kriterien definieren: was zu melden ist (Bugs, Sicherheit) vs. was zu ignorieren ist (kleinere Stilfragen)
- Kategorien mit hohen False-Positive-Raten vorübergehend deaktivieren
- Explizite Schweregrad-Kriterien mit Codebeispielen für jede Stufe definieren

## 4.2 Few-shot-Prompting nutzen, um die Konsistenz der Ausgabe zu verbessern

### Kernwissen:
- Few-shot-Beispiele sind die wirksamste Methode, um durchgängig formatierte, umsetzbare Ausgabe zu erzeugen
- Few-shot kann den Umgang mit mehrdeutigen Fällen demonstrieren (Tool-Auswahl, Lücken in der Testabdeckung)
- Few-shot hilft dem Modell, auf neue Muster zu verallgemeinern, statt nur Standardwerte zu wiederholen
- Few-shot kann Halluzinationen bei Extraktionsaufgaben reduzieren

### Kernkompetenzen:
- 2–4 gezielte Beispiele für mehrdeutige Szenarien mit Begründung bereitstellen
- Few-shot-Beispiele einbeziehen, die das Ausgabeformat demonstrieren (Ort, Problem, Schweregrad, Lösungsvorschlag)
- Beispiele bereitstellen, die akzeptable Code-Muster von echten Problemen unterscheiden
- Beispiele für korrekte Extraktion aus Dokumenten mit unterschiedlichen Strukturen bereitstellen

## 4.3 Strukturierte Ausgabe mit `tool_use` und JSON-Schemas erzwingen

### Kernwissen:
- `tool_use` mit JSON-Schemas ist der zuverlässigste Weg, schemakonforme Ausgabe zu garantieren und JSON-Syntaxfehler zu eliminieren
- Mit `tool_choice: "auto"` kann das Modell Text zurückgeben; mit `"any"` muss es ein Tool aufrufen; die erzwungene Auswahl wählt ein bestimmtes Tool
- Strikte JSON-Schemas eliminieren Syntaxfehler, verhindern aber keine semantischen Fehler (Summen stimmen nicht; Werte in falschen Feldern)
- Schema-Design: Pflicht- vs. optionale Felder; Enums mit „other" plus Detail-String zur Erweiterbarkeit

### Kernkompetenzen:
- Extraktions-Tools mit JSON-Schemas definieren und Daten aus `tool_use`-Ergebnissen parsen
- `tool_choice: "any"` verwenden, um strukturierte Ausgabe zu garantieren, wenn mehrere Schemas existieren
- Einen bestimmten Tool-Aufruf erzwingen: `tool_choice: {"type": "tool", "name": "extract_metadata"}`
- Felder optional/nullable machen, wenn die Quelle die Information möglicherweise nicht enthält, um das Erfinden von Werten zu vermeiden
- Enum-Werte wie `"unclear"` und `"other"` plus Detailfelder für erweiterbare Kategorisierung verwenden

## 4.4 Validierung, Retries und Feedback-Schleifen für die Extraktionsqualität umsetzen

### Kernwissen:
- Retry-with-Error-Feedback: konkrete Validierungsfehler in den Retry-Prompt aufnehmen, um Korrekturen anzuleiten
- Retries sind wirkungslos, wenn die Information schlicht nicht in der Quelle vorhanden ist
- Gestaltung der Feedback-Schleife: das Muster verfolgen, das einen Befund ausgelöst hat (`detected_pattern`)
- Semantische Fehler (Summen stimmen nicht) vs. Syntaxfehler (durch `tool_use` adressiert)

### Kernkompetenzen:
- Folge-Prompts mit dem Originaldokument, einer fehlerhaften Extraktion und spezifischen Validierungsfehlern
- Erkennen, wann ein Retry wirkungslos ist (die benötigte Information steht nur in einem externen Dokument)
- `detected_pattern`-Felder in Befunde aufnehmen, um False Positives zu analysieren
- Selbstkorrektur gestalten, indem sowohl `calculated_total` als auch `stated_total` extrahiert werden, um Diskrepanzen zu erkennen

## 4.5 Effiziente Batch-Verarbeitungsstrategien entwerfen

### Kernwissen:
- Message Batches API: 50 % Ersparnis, Verarbeitungsfenster bis zu 24 Stunden, keine Latenz-SLA-Garantien
- Batch-Verarbeitung eignet sich für nicht blockierende Aufgaben (nächtliche Berichte, Audits) und nicht für blockierende Aufgaben (Pre-Merge-Prüfungen)
- Die Batch-API unterstützt kein mehrschrittiges Tool-Calling innerhalb einer einzelnen Anfrage
- `custom_id`-Felder korrelieren Anfrage/Antwort innerhalb von Batches

### Kernkompetenzen:
- Die synchrone API für blockierende Prüfungen verwenden; die Batch-API für nächtliche/wöchentliche Arbeitslasten
- Die Batch-Einreichungskadenz an SLA-Bedürfnissen ausrichten (z. B. 4-Stunden-Fenster für eine 30-Stunden-Garantie bei 24-stündiger Verarbeitung)
- Fehlschläge behandeln, indem nur fehlgeschlagene Dokumente erneut eingereicht werden (identifiziert über `custom_id`)
- Prompts anhand einer Stichprobe iterieren, bevor eine großangelegte Verarbeitung läuft

## 4.6 Multi-Instanz- und Multi-Pass-Review-Architekturen entwerfen

### Kernwissen:
- Grenzen des Selbst-Reviews: Das Modell behält seinen Argumentationskontext und stellt seine eigenen Entscheidungen seltener infrage
- Unabhängige Review-Instanzen (ohne Generierungskontext) sind besser darin, subtile Probleme zu finden
- Multi-Pass-Review: lokale Analyse pro Datei plus ein dateiübergreifender Integrationsdurchlauf, um Aufmerksamkeitsverdünnung zu vermeiden

### Kernkompetenzen:
- Eine zweite unabhängige Claude-Instanz verwenden, um Änderungen ohne Generierungskontext zu prüfen
- Reviews über mehrere Dateien in Durchläufe pro Datei plus Integrationsdurchläufe für die dateiübergreifende Datenflussanalyse aufteilen
- Verifikationsdurchläufe mit selbst eingeschätzter Konfidenz verwenden, um Reviews kalibriert zu routen

---

# Domäne 5: Kontextverwaltung und Zuverlässigkeit (15 %)

## 5.1 Gesprächskontext verwalten, um kritische Informationen zu bewahren

### Kernwissen:
- Risiken der fortlaufenden Zusammenfassung: Zahlenwerte, Prozentsätze und Datumsangaben werden zu vagen Zusammenfassungen verdichtet
- Lost-in-the-middle-Effekt: Modelle verarbeiten Anfang und Ende langer Eingaben zuverlässig, können aber Befunde aus der Mitte übersehen
- Tool-Ausgaben können sich im Kontext unverhältnismäßig zur Relevanz anhäufen (40+ Felder, wo 5 benötigt werden)
- Die Bedeutung, in nachfolgenden API-Anfragen den vollständigen Gesprächsverlauf zu senden

### Kernkompetenzen:
- Transaktionsfakten in einen persistenten „Case-Facts"-Block außerhalb des zusammengefassten Verlaufs extrahieren
- Ausführliche Tool-Ausgaben auf die relevanten Felder beschneiden
- Schlüsselbefunde an den Anfang der aggregierten Daten stellen, mit expliziten Abschnittsüberschriften
- Von Subagenten verlangen, dass sie Metadaten (Datumsangaben, Quellen) in strukturierte Ausgaben aufnehmen

## 5.2 Wirksame Eskalationsmuster entwerfen und Mehrdeutigkeit auflösen

### Kernwissen:
- Geeignete Eskalationsauslöser: ausdrückliche Bitte um einen Menschen, Richtlinienlücken/-ausnahmen, Unfähigkeit voranzukommen
- Sofortige Eskalation (ausdrückliche Bitte) vs. Lösungsversuch (im Rahmen des Agenten)
- Stimmungsanalyse und selbst eingeschätzte Modellkonfidenz sind unzuverlässige Stellvertreter für die Fallkomplexität
- Mehrere Kundentreffer erfordern das Nachfragen zusätzlicher Identifikationsmerkmale, kein heuristisches Raten

### Kernkompetenzen:
- Explizite Eskalationskriterien mit Few-shot-Beispielen im System-Prompt
- Ausdrückliche Bitten um einen Menschen sofort und ohne weitere Untersuchung ausführen
- Eskalieren, wenn die Richtlinie zu einer bestimmten Anfrage mehrdeutig ist oder schweigt
- Nach zusätzlichen Identifikationsmerkmalen fragen, wenn Tool-Ergebnisse mehrere Treffer enthalten

## 5.3 Strategien zur Fehlerweitergabe in Multi-Agenten-Systemen umsetzen

### Kernwissen:
- Strukturierter Fehlerkontext (Fehlertyp, Anfrage, Teilergebnisse, Alternativen) ermöglicht eine klügere Erholung des Koordinators
- Zugriffsfehler (Timeouts erfordern eine Retry-Entscheidung) von gültigen leeren Ergebnissen (keine Treffer) unterscheiden
- Generische Fehlerstatus („search unavailable") verbergen wertvollen Kontext vor dem Koordinator
- Stilles Unterdrücken oder der Abbruch des gesamten Workflows bei einem einzigen Fehlschlag sind beide Anti-Muster

### Kernkompetenzen:
- Strukturierten Fehlerkontext zurückgeben: Fehlertyp, was versucht wurde, Teilergebnisse, mögliche Alternativen
- Zugriffsfehler von gültigen leeren Ergebnissen unterscheiden
- Lokale Erholung in Subagenten bei transienten Fehlern; nur nicht behebbare Fehler mit Teilergebnissen weitergeben
- Die Abdeckung in der Synthese kennzeichnen: was gut belegt ist vs. wo Lücken bleiben

## 5.4 Kontext effizient verwalten bei der Untersuchung großer Codebasen

### Kernwissen:
- Kontextverfall in langen Sitzungen: Das Modell beginnt, instabile Antworten zu geben und auf „typische Muster" statt auf konkrete Klassen zu verweisen
- Scratchpad-Dateien bewahren Schlüsselbefunde über Kontextgrenzen hinweg
- Die Delegation an Subagenten isoliert ausführliche Erkundungsausgabe
- Strukturierte Zustandspersistenz ermöglicht die Wiederherstellung nach Abstürzen

### Kernkompetenzen:
- Subagenten für spezifische Fragen starten, während die übergeordnete Koordination im Hauptagenten bleibt
- Scratchpad-Dateien verwenden, um Schlüsselbefunde zu speichern und später darauf zu verweisen
- Schlüsselbefunde zusammenfassen, bevor Subagenten der nächsten Phase gestartet werden
- `/compact` verwenden, um den Kontextverbrauch bei langen Untersuchungen zu reduzieren

## 5.5 Workflows mit menschlicher Aufsicht und Konfidenzkalibrierung entwerfen

### Kernwissen:
- Aggregierte Kennzahlen (z. B. 97 % Gesamtgenauigkeit) können schlechte Leistung bei bestimmten Dokumenttypen oder Feldern verdecken
- Geschichtete Zufallsstichproben messen Fehlerraten in Extraktionen mit hoher Konfidenz
- Konfidenzkalibrierung auf Feldebene mithilfe gelabelter Validierungsdatensätze
- Genauigkeit nach Dokumenttyp und Feldsegment validieren, bevor automatisiert wird

### Kernkompetenzen:
- Geschichtete Zufallsstichproben umsetzen, um neue Fehlermuster zu erkennen
- Genauigkeit nach Dokumenttyp und Feld analysieren, um stabile Leistung zu validieren
- Konfidenzwerte auf Feldebene ausgeben und Review-Schwellen mithilfe gelabelter Daten kalibrieren
- Extraktionen mit niedriger Konfidenz oder mehrdeutiger Quelle an das menschliche Review routen

## 5.6 Herkunft bewahren und Unsicherheit bei der Synthese aus mehreren Quellen behandeln

### Kernwissen:
- Attribution geht bei der Zusammenfassung verloren, wenn „Aussage → Quelle"-Zuordnungen nicht bewahrt werden
- Strukturierte Zuordnungen müssen bei der Aggregation erhalten bleiben
- Widersprüchliche Statistiken behandeln, indem Konflikte mit Attribution gekennzeichnet werden, statt willkürlich einen Wert zu wählen
- Veröffentlichungs-/Erhebungsdaten einbeziehen, um zeitliche Unterschiede nicht als Widersprüche fehlzudeuten

### Kernkompetenzen:
- Von Subagenten „Aussage → Quelle"-Zuordnungen verlangen (URL, Dokumentname, Zitate)
- Berichte so strukturieren, dass stabile Befunde von umstrittenen getrennt werden
- Widersprüchliche Werte mit Anmerkungen bewahren und an den Koordinator zur Abstimmung weitergeben
- Veröffentlichungsdaten für die korrekte zeitliche Interpretation einbeziehen
- Inhalte nach Typ darstellen: Finanzdaten als Tabellen, Nachrichten als Fließtext, technische Befunde als strukturierte Listen

---

# Beispiele für Prüfungsfragen mit Erläuterungen

## Frage 1 (Szenario: Kundensupport-Agent)

**Situation:** Die Daten zeigen, dass der Agent in 12 % der Fälle `get_customer` überspringt und `lookup_order` nur mit dem Namen des Kunden aufruft, was zu falschen Rückerstattungen führt.

**Welche Änderung ist am wirksamsten?**

- A) Eine programmatische Vorbedingung hinzufügen, die `lookup_order` und `process_refund` blockiert, bis über `get_customer` eine ID ermittelt wurde **[RICHTIG]**
- B) Den System-Prompt verbessern
- C) Few-shot-Beispiele hinzufügen
- D) Einen Routing-Klassifikator implementieren

**Warum A:** Wenn kritische Geschäftslogik eine bestimmte Tool-Reihenfolge verlangt, liefert Software **deterministische Garantien**, die prompt-basierte Ansätze (B, C) nicht bieten können. D adressiert die Verfügbarkeit, nicht die Tool-Reihenfolge.

---

## Frage 2 (Szenario: Kundensupport-Agent)

**Situation:** Der Agent ruft bei bestellbezogenen Fragen oft `get_customer` statt `lookup_order` auf. Die Tool-Beschreibungen sind minimal und ähnlich.

**Was ist der erste Schritt?**

- A) Few-shot-Beispiele
- B) Die Beschreibung jedes Tools um Eingabeformate, Beispiele und Grenzen erweitern **[RICHTIG]**
- C) Eine Routing-Schicht hinzufügen
- D) Die Tools zusammenführen

**Warum B:** Tool-Beschreibungen sind der primäre Auswahlmechanismus des Modells. Das ist die Korrektur mit dem geringsten Aufwand und der größten Wirkung. A fügt Tokens hinzu, ohne die Ursache zu adressieren. C ist Overengineering. D erfordert mehr Aufwand als gerechtfertigt.

---

## Frage 3 (Szenario: Kundensupport-Agent)

**Situation:** Der Agent löst nur 55 % der Fälle bei einem Ziel von 80 %. Er eskaliert einfache Fälle und versucht, komplexe Richtlinien­ausnahmen autonom zu behandeln.

**Wie verbesserst du die Kalibrierung?**

- A) Explizite Eskalationskriterien mit Few-shot-Beispielen hinzufügen **[RICHTIG]**
- B) Selbst eingeschätzte Konfidenz (1–10) mit automatischer Eskalation
- C) Ein separater Klassifikator, trainiert auf historischen Daten
- D) Stimmungsanalyse

**Warum A:** Das adressiert direkt die Ursache — unklare Entscheidungsgrenzen. B ist unzuverlässig (das Modell kann selbstsicher falsch liegen). C ist Overengineering. D löst ein anderes Problem (Stimmung != Komplexität).

---

## Frage 4 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Du brauchst einen benutzerdefinierten `/review`-Befehl für ein Standard-Code-Review, der dem ganzen Team beim Klonen des Repositorys zur Verfügung steht.

**Wo solltest du die Befehlsdatei anlegen?**

- A) `.claude/commands/` im Projekt-Repository **[RICHTIG]**
- B) `~/.claude/commands/`
- C) `CLAUDE.md` im Stamm
- D) `.claude/config.json`

**Warum A:** Projektbefehle, die in `.claude/commands/` liegen, sind versionskontrolliert und automatisch für alle verfügbar. B ist für persönliche Befehle. C ist für Anweisungen, nicht für Befehlsdefinitionen. D existiert nicht.

---

## Frage 5 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Du musst einen Monolithen in Microservices umstrukturieren (Dutzende Dateien, Entscheidungen zu Servicegrenzen).

**Welchen Ansatz solltest du verwenden?**

- A) Planungsmodus: die Codebasis erkunden, Abhängigkeiten verstehen, einen Ansatz entwerfen **[RICHTIG]**
- B) Direkte Ausführung, schrittweise
- C) Direkte Ausführung mit detaillierten Vorab-Anweisungen
- D) Direkte Ausführung und zum Planungsmodus wechseln, wenn es schwierig wird

**Warum A:** Der Planungsmodus ist für große Änderungen, mehrere mögliche Ansätze und Architekturentscheidungen konzipiert. B riskiert teure Nacharbeit. C setzt voraus, dass du die Struktur bereits kennst. D ist reaktiv.

---

## Frage 6 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Eine Codebasis hat je nach Bereich unterschiedliche Konventionen (React, API, Datenbank). Tests liegen beim Code. Du möchtest, dass die Konventionen automatisch angewendet werden.

**Welchen Ansatz solltest du verwenden?**

- A) `.claude/rules/`-Dateien mit YAML-Frontmatter und Glob-Mustern **[RICHTIG]**
- B) Alles in die `CLAUDE.md` im Stamm packen
- C) Skills in `.claude/skills/`
- D) Eine `CLAUDE.md` in jedem Verzeichnis

**Warum A:** `.claude/rules/` mit Glob-Mustern (z. B. `**/*.test.tsx`) ermöglicht die automatische Anwendung von Konventionen anhand von Dateipfaden — ideal für Tests, die über die Codebasis verteilt sind. B verlässt sich auf die Inferenz des Modells. C ist manuell/bedarfsgesteuert. D funktioniert schlecht, wenn relevante Dateien in vielen Verzeichnissen liegen.

---

## Frage 7 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Das System recherchiert „KI-Auswirkungen auf die Kreativbranchen", aber die Berichte decken nur die bildende Kunst ab. Der Koordinator hat das Thema zerlegt in: „KI in digitaler Kunst", „KI im Grafikdesign", „KI in der Fotografie".

**Was ist die Ursache?**

- A) Der Synthese-Agent erkennt keine Lücken
- B) Der Koordinator hat die Aufgabe zu eng zerlegt **[RICHTIG]**
- C) Der Web-Recherche-Agent sucht nicht gründlich genug
- D) Der Dokumentenanalyse-Agent filtert nicht-visuelle Quellen heraus

**Warum B:** Die Logs zeigen, dass der Koordinator „Kreativbranchen" nur in visuelle Teilthemen zerlegt hat und Musik, Literatur und Film völlig ausgelassen hat. Die Subagenten haben korrekt gearbeitet — das Problem ist, was ihnen zugewiesen wurde.

---

## Frage 8 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Ein Web-Recherche-Subagent läuft bei der Recherche zu einem komplexen Thema in einen Timeout. Du musst gestalten, wie die Fehlerinformation an den Koordinator zurückgegeben wird.

**Welcher Ansatz zur Fehlerweitergabe ermöglicht die beste intelligente Erholung?**

- A) Strukturierten Fehlerkontext an den Koordinator zurückgeben: Fehlertyp, Anfrage, Teilergebnisse und Alternativen **[RICHTIG]**
- B) Automatische Retries mit exponentiellem Backoff innerhalb des Subagenten umsetzen, dann einen generischen Status „search unavailable" zurückgeben
- C) Den Timeout innerhalb des Subagenten abfangen und ein leeres Ergebnis als Erfolg markiert zurückgeben
- D) Die Timeout-Ausnahme an einen Top-Level-Handler weitergeben, der den gesamten Workflow beendet

**Warum A:** Strukturierter Fehlerkontext gibt dem Koordinator, was er braucht, um zu entscheiden, ob er mit einer geänderten Anfrage erneut versucht, einen alternativen Ansatz probiert oder mit Teilergebnissen weitermacht. B verbirgt Kontext hinter einem generischen Status. C tarnt einen Fehlschlag als Erfolg. D bricht den gesamten Workflow unnötig ab.

---

## Frage 9 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Der Synthese-Agent muss beim Zusammenführen von Ergebnissen oft bestimmte Aussagen verifizieren. Aktuell gibt der Synthese-Agent, wenn eine Verifikation nötig ist, die Kontrolle an den Koordinator zurück, der den Web-Recherche-Agenten aufruft und die Synthese anschließend mit den neuen Ergebnissen erneut ausführt. Das fügt 2–3 zusätzliche Runden pro Aufgabe hinzu und erhöht die Latenz um 40 %. Deine Auswertung zeigt, dass 85 % dieser Prüfungen einfache Faktenchecks sind (Datumsangaben, Namen, Statistiken), während 15 % eine tiefere Untersuchung erfordern.

**Wie reduzierst du den Overhead und bewahrst zugleich die Zuverlässigkeit?**

- A) Dem Synthese-Agenten ein eingeschränktes `verify_fact`-Tool für einfache Prüfungen geben und die komplexe Verifikation weiterhin über den Koordinator leiten **[RICHTIG]**
- B) Alle Verifikationsbedarfe in einem Batch sammeln und am Ende an den Koordinator zurückgeben
- C) Dem Synthese-Agenten vollen Zugriff auf alle Web-Recherche-Tools geben
- D) Proaktiv zusätzlichen Kontext um jede Quelle herum cachen

**Warum A:** Das wendet das Prinzip der geringsten Rechte an: Der Synthese-Agent bekommt genau das, was er für den häufigen 85-%-Fall (einfache Faktenchecks) braucht, während der koordinatorvermittelte Pfad für komplexe Untersuchungen erhalten bleibt. B führt blockierende Abhängigkeiten ein (spätere Syntheseschritte können von zuvor verifizierten Fakten abhängen). C durchbricht die Trennung der Verantwortlichkeiten. D verlässt sich auf spekulatives Caching, das den Bedarf nicht zuverlässig vorhersagen kann.

---

## Frage 10 (Szenario: Claude Code für CI)

**Situation:** Eine Pipeline führt `claude "Analyze this pull request for security issues"` aus, hängt aber und wartet auf interaktive Eingabe.

**Was ist der korrekte Ansatz?**

- A) Das Flag `-p` verwenden: `claude -p "Analyze this pull request for security issues"` **[RICHTIG]**
- B) `CLAUDE_HEADLESS=true` setzen
- C) stdin von `/dev/null` umleiten
- D) `--batch` verwenden

**Warum A:** `-p` (oder `--print`) ist der dokumentierte Weg, Claude Code im nicht-interaktiven Modus auszuführen. Es verarbeitet den Prompt, gibt auf stdout aus und beendet sich. Die anderen Optionen sind entweder nicht existierende Funktionen oder Unix-Behelfslösungen.

---

## Frage 11 (Szenario: Claude Code für CI)

**Situation:** Das Team möchte die API-Kosten für die automatisierte Analyse senken. Claude bedient derzeit zwei Workflows in Echtzeit: (1) eine blockierende Pre-Merge-Prüfung, die abgeschlossen sein muss, bevor Entwickler einen PR mergen können, und (2) einen Tech-Debt-Bericht, der über Nacht für das Morgen-Review erzeugt wird. Ein Manager schlägt vor, beide auf die Message Batches API umzustellen, um 50 % zu sparen.

**Wie solltest du diesen Vorschlag bewerten?**

- A) Batch-Verarbeitung nur für Tech-Debt-Berichte verwenden; Echtzeit-Aufrufe für Pre-Merge-Prüfungen beibehalten **[RICHTIG]**
- B) Beide Workflows auf Batch-Verarbeitung umstellen und auf Abschluss pollen
- C) Für beide Echtzeit-Aufrufe beibehalten, um Reihenfolgeprobleme in Batch-Ergebnissen zu vermeiden
- D) Beide auf Batch-Verarbeitung umstellen mit Rückfall auf Echtzeit, wenn ein Batch zu lange dauert

**Warum A:** Die Message Batches API spart 50 %, aber die Verarbeitungszeit kann bis zu 24 Stunden betragen, ohne garantierte Latenz-SLA. Das macht sie ungeeignet für blockierende Pre-Merge-Prüfungen, bei denen Entwickler warten, aber ideal für nächtliche Batch-Arbeitslasten wie Tech-Debt-Berichte.

---

## Frage 12 (Szenario: Code-Review über mehrere Dateien)

**Situation:** Ein Pull Request ändert 14 Dateien in einem Bestandsverfolgungsmodul. Ein Einzeldurchlauf-Review aller Dateien liefert inkonsistente Ergebnisse: detaillierte Kommentare für manche Dateien, oberflächliche für andere, übersehene offensichtliche Bugs und widersprüchliches Feedback (ein Muster wird in einer Datei beanstandet, aber in identischem Code in einer anderen Datei freigegeben).

**Wie solltest du das Review umstrukturieren?**

- A) In fokussierte Durchläufe aufteilen: jede Datei einzeln auf lokale Probleme analysieren, dann einen separaten Integrationsdurchlauf für dateiübergreifende Datenflüsse ausführen **[RICHTIG]**
- B) Von den Entwicklern verlangen, große PRs in Einreichungen von 3–4 Dateien aufzuteilen
- C) Auf ein höherstufiges Modell mit größerem Kontextfenster wechseln, um alle 14 Dateien in einem Durchlauf zu prüfen
- D) Drei unabhängige vollständige PR-Review-Durchläufe ausführen und nur Probleme melden, die in mindestens zwei Läufen gefunden werden

**Warum A:** Fokussierte Durchläufe adressieren direkt die Ursache — Aufmerksamkeitsverdünnung bei der Verarbeitung vieler Dateien auf einmal. Die Analyse pro Datei sorgt für gleichbleibende Tiefe, und ein separater Integrationsdurchlauf erfasst dateiübergreifende Probleme. B verschiebt die Last auf die Entwickler, ohne das System zu verbessern. C ist ein Irrtum: mehr Kontext behebt die Aufmerksamkeitsqualität nicht. D unterdrückt echte Bugs, indem es einen Konsens über inkonsistente Erkennungen verlangt.

---

# Übungsprüfung

> 60 Fragen über 4 Szenarien. Format und Schwierigkeitsgrad entsprechen der echten Prüfung.
>
> Alternativ kannst du diese Fragen in einer prüfungsähnlichen HTML-Datei üben: [Practical Test (EN)](practical_test_en.html)

## Szenario: Multi-Agenten-Recherchesystem

---

## Frage 1 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Ein Dokumentenanalyse-Agent stellt fest, dass zwei glaubwürdige Quellen bei einer Schlüsselkennzahl direkt widersprüchliche Statistiken enthalten: Ein Regierungsbericht nennt 40 % Wachstum, eine Branchenanalyse 12 %. Beide Quellen wirken glaubwürdig, und die Diskrepanz könnte die Forschungsschlussfolgerungen wesentlich beeinflussen. Wie sollte der Dokumentenanalyse-Agent damit am wirksamsten umgehen?

**Welcher Ansatz ist am wirksamsten?**

- A) Glaubwürdigkeitsheuristiken anwenden, um die wahrscheinlich richtige Zahl zu wählen, die Analyse mit diesem Wert abschließen und eine Fußnote zur Diskrepanz ergänzen.
- B) Beide Zahlen in die Analyseausgabe aufnehmen, ohne sie als widersprüchlich zu kennzeichnen, und den Synthese-Agenten anhand des weiteren Kontexts entscheiden lassen, welche zu verwenden ist.
- C) Die Analyse stoppen und sofort an den Koordinator eskalieren mit der Bitte, vor dem Weitermachen zu entscheiden, welche Quelle maßgeblicher ist.
- D) Die Analyse mit beiden Zahlen abschließen, den Konflikt explizit mit Quellenangabe kennzeichnen und den Koordinator entscheiden lassen, wie die Daten abzustimmen sind, bevor sie an die Synthese übergeben werden. **[RICHTIG]**

**Warum D:** Dieser Ansatz bewahrt die Trennung der Verantwortlichkeiten: Der Analyse-Agent schließt seine Kernarbeit ohne Blockade ab, bewahrt beide widersprüchlichen Werte mit klarer Attribution und übergibt die Abstimmung korrekt an den Koordinator, der den weiteren Kontext hat.

---

## Frage 2 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Der Web-Recherche- und der Dokumentenanalyse-Agent haben ihre Aufgaben abgeschlossen und die Ergebnisse an den Koordinator zurückgegeben. Was ist der nächste Schritt zur Erstellung eines integrierten Forschungsberichts?

**Welcher nächste Schritt ist am geeignetsten?**

- A) Jeder Agent sendet seine Ergebnisse direkt an den Berichts-Agenten und umgeht den Koordinator.
- B) Der Dokumentenanalyse-Agent fordert die Web-Recherche-Ergebnisse an und führt sie intern zusammen.
- C) Der Koordinator übergibt beide Ergebnismengen an den Synthese-Agenten zur einheitlichen Integration. **[RICHTIG]**
- D) Der Koordinator verkettet die Rohausgaben beider Agenten und gibt sie als Endergebnis zurück.

**Warum C:** In einer Koordinator-Subagent-Architektur leitet der Koordinator beide Ergebnismengen an den Synthese-Agenten zur zentralen Integration weiter, wahrt die Kontrolle und stellt eine hochwertige Zusammenführung sicher.

---

## Frage 3 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Ein Dokumentenanalyse-Subagent scheitert häufig bei der Verarbeitung von PDF-Dateien: Einige haben beschädigte Abschnitte, die Parsing-Ausnahmen auslösen, andere sind passwortgeschützt, und manchmal hängt die Parsing-Bibliothek bei großen Dateien. Aktuell beendet jede Ausnahme den Subagenten sofort und gibt einen Fehler an den Koordinator zurück, der entscheiden muss, ob er es erneut versucht, überspringt oder die gesamte Aufgabe scheitern lässt. Das verursacht übermäßige Koordinator-Beteiligung bei routinemäßiger Fehlerbehandlung. Welche architektonische Verbesserung ist am wirksamsten?

**Welche Verbesserung ist am wirksamsten?**

- A) Einen eigenen Fehlerbehandlungs-Agenten erstellen, der alle Fehlschläge über eine gemeinsame Warteschlange überwacht und Erholungsmaßnahmen entscheidet und Neustartbefehle direkt an Subagenten sendet.
- B) Den Subagenten so konfigurieren, dass er immer Teilergebnisse mit Erfolgsstatus zurückgibt und Fehlerdetails in Metadaten einbettet; der Koordinator behandelt alle Antworten als erfolgreich.
- C) Den Koordinator alle Dokumente validieren lassen, bevor sie an den Subagenten gesendet werden, und Dokumente ablehnen, die Fehler verursachen könnten.
- D) Lokale Erholung im Subagenten für transiente Fehler umsetzen und nur Fehler an den Koordinator eskalieren, die er nicht lösen kann, inklusive versuchter Schritte und Teilergebnisse. **[RICHTIG]**

**Warum D:** Behandle Fehler auf der niedrigsten Ebene, die sie lösen kann. Lokale Erholung reduziert die Koordinator-Last und eskaliert dennoch wirklich nicht behebbare Probleme mit vollem Kontext und Teilfortschritt.

---

## Frage 4 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Nachdem du das System auf „KI-Auswirkungen auf die Kreativbranchen" hast laufen lassen, beobachtest du, dass jeder Subagent erfolgreich abschließt: Der Web-Recherche-Agent findet relevante Artikel, der Dokumentenanalyse-Agent fasst sie korrekt zusammen und der Synthese-Agent erzeugt kohärenten Text. Die Endberichte decken jedoch nur die bildende Kunst ab und lassen Musik, Literatur und Film völlig aus. In den Koordinator-Logs siehst du, dass er das Thema in drei Teilaufgaben zerlegt hat: „KI in digitaler Kunst", „KI im Grafikdesign" und „KI in der Fotografie". Was ist die wahrscheinlichste Ursache?

**Was ist die wahrscheinlichste Ursache?**

- A) Dem Synthese-Agenten fehlen Anweisungen, Abdeckungslücken zu erkennen.
- B) Der Dokumentenanalyse-Agent filtert nicht-visuelle Quellen wegen zu strenger Relevanzkriterien heraus.
- C) Die Aufgabenzerlegung des Koordinators ist zu eng und weist den Subagenten Arbeit zu, die nicht alle relevanten Bereiche abdeckt. **[RICHTIG]**
- D) Die Anfragen des Web-Recherche-Agenten sind unzureichend und sollten erweitert werden, um mehr Sektoren abzudecken.

**Warum C:** Der Koordinator hat ein breites Thema nur in Teilaufgaben zur bildenden Kunst zerlegt und Musik, Literatur und Film völlig ausgelassen. Da die Subagenten ihre Aufträge korrekt ausgeführt haben, ist die enge Zerlegung die offensichtliche Ursache.

---

## Frage 5 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Der Web-Recherche-Subagent liefert Ergebnisse für nur 3 von 5 angeforderten Quellenkategorien (Wettbewerber-Websites und Branchenberichte gelingen, aber Nachrichtenarchive und Social Feeds laufen in einen Timeout). Der Dokumentenanalyse-Subagent verarbeitet alle bereitgestellten Dokumente erfolgreich. Der Synthese-Subagent muss aus vorgelagerten Eingaben gemischter Qualität eine Zusammenfassung erzeugen. Welche Strategie zur Fehlerweitergabe ist am wirksamsten?

**Welche Strategie zur Fehlerweitergabe ist am wirksamsten?**

- A) Die Synthese nur mit den erfolgreichen Quellen fortsetzen und eine Ausgabe erzeugen, ohne zu erwähnen, welche Daten nicht verfügbar waren.
- B) Der Synthese-Subagent gibt einen Fehler an den Koordinator zurück und löst wegen unvollständiger Daten einen vollständigen Retry oder ein Scheitern der Aufgabe aus.
- C) Der Synthese-Subagent bittet den Koordinator, die getimten Quellen mit längerem Timeout erneut zu versuchen, bevor die Synthese beginnt.
- D) Die Syntheseausgabe mit Abdeckungshinweisen strukturieren, die angeben, welche Schlussfolgerungen gut belegt sind und wo aufgrund nicht verfügbarer Quellen Lücken bestehen. **[RICHTIG]**

**Warum D:** Abdeckungshinweise setzen eine graceful degradation mit Transparenz um, bewahren den Wert der abgeschlossenen Arbeit und geben die Unsicherheit weiter, damit fundierte Entscheidungen über die Konfidenz möglich sind.

---

## Frage 6 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Der Dokumentenanalyse-Subagent stößt auf eine beschädigte PDF-Datei, die er nicht parsen kann. Was ist beim Entwurf der Fehlerbehandlung des Systems der wirksamste Weg, mit diesem Fehlschlag umzugehen?

**Welcher Ansatz ist am wirksamsten?**

- A) Einen Fehler mit Kontext an den Koordinator-Agenten zurückgeben, damit dieser entscheiden kann, wie weiter vorzugehen ist. **[RICHTIG]**
- B) Das beschädigte Dokument stillschweigend überspringen und die restlichen Dateien weiterverarbeiten, um den Workflow nicht zu unterbrechen.
- C) Das Parsen des Dokuments automatisch dreimal mit exponentiellem Backoff wiederholen, bevor ein Fehlschlag gemeldet wird.
- D) Eine Ausnahme werfen, die den gesamten Recherche-Workflow beendet.

**Warum A:** Einen Fehler mit Kontext an den Koordinator zurückzugeben, ist am wirksamsten, weil es dem Koordinator eine fundierte Entscheidung ermöglicht — die Datei überspringen, eine alternative Parsing-Methode versuchen oder den Nutzer benachrichtigen — und dabei die Sichtbarkeit des Fehlschlags erhalten bleibt.

---

## Frage 7 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Produktions-Logs zeigen ein hartnäckiges Muster: Anfragen wie „analysiere den hochgeladenen Quartalsbericht" werden in 45 % der Fälle an den Web-Recherche-Agenten statt an den Dokumentenanalyse-Agenten geleitet. Bei der Prüfung der Tool-Definitionen stellst du fest, dass der Web-Recherche-Agent ein Tool `analyze_content` mit der Beschreibung „analyzes content and extracts key information" hat, während der Dokumentenanalyse-Agent ein Tool `analyze_document` mit der Beschreibung „analyzes documents and extracts key information" hat. Wie solltest du das Fehlrouting-Problem beheben?

**Wie solltest du das Fehlrouting-Problem beheben?**

- A) Einen Vor-Routing-Klassifikator hinzufügen, der erkennt, ob der Nutzer sich auf hochgeladene Dateien oder Web-Inhalte bezieht, bevor der Koordinator über die Delegation entscheidet.
- B) Das Web-Recherche-Tool in `extract_web_results` umbenennen und seine Beschreibung auf „processes and returns information retrieved from web search and URLs" aktualisieren. **[RICHTIG]**
- C) Dem Koordinator-Prompt Few-shot-Beispiele hinzufügen, die korrektes Routing zeigen: „Nutzer lädt einen Quartalsbericht hoch → Dokumentenanalyse-Agent" und „Nutzer fragt nach einer Webseite → Web-Recherche-Agent".
- D) Die Beschreibung des Dokumentenanalyse-Tools um Nutzungsbeispiele wie „Use for uploaded PDFs, Word docs, and spreadsheets" erweitern und das Web-Recherche-Tool unverändert lassen.

**Warum B:** Das Web-Recherche-Tool in `extract_web_results` umzubenennen und seine Beschreibung so zu aktualisieren, dass sie explizit auf Web-Suche und URLs verweist, beseitigt die Ursache direkt, indem die semantische Überschneidung zwischen den beiden Tool-Namen und -Beschreibungen entfernt wird. Das macht den Zweck jedes Tools eindeutig und ermöglicht es dem Koordinator, Dokumentenanalyse zuverlässig von Web-Suche zu unterscheiden.

---

## Frage 8 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Ein Kollege schlägt vor, dass der Dokumentenanalyse-Agent seine Ergebnisse direkt an den Synthese-Agenten sendet und den Koordinator umgeht. Was ist der Hauptvorteil, den Koordinator als zentralen Knotenpunkt für die gesamte Kommunikation zwischen Subagenten beizubehalten?

**Was ist der Hauptvorteil, den Koordinator als zentralen Knotenpunkt beizubehalten?**

- A) Der Koordinator kann alle Interaktionen beobachten, Fehler einheitlich behandeln und entscheiden, welche Informationen jeder Subagent erhalten soll. **[RICHTIG]**
- B) Der Koordinator bündelt mehrere Anfragen an Subagenten und reduziert so die Gesamtzahl der API-Aufrufe und die Gesamtlatenz.
- C) Das Routing über den Koordinator ermöglicht eine automatische Retry-Logik, die direkte Aufrufe zwischen Agenten nicht unterstützen können.
- D) Subagenten nutzen isoliertes Gedächtnis, und direkte Kommunikation würde komplexe Serialisierung erfordern, die nur der Koordinator durchführen kann.

**Warum A:** Das Koordinator-Muster bietet zentrale Sichtbarkeit auf alle Interaktionen, einheitliche Fehlerbehandlung im gesamten System und feingranulare Kontrolle darüber, welche Informationen jeder Subagent erhält — das sind die Hauptvorteile einer sternförmigen Kommunikationstopologie.

---

## Frage 9 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Der Web-Recherche-Subagent läuft bei der Recherche zu einem komplexen Thema in einen Timeout. Du musst gestalten, wie die Information über diesen Fehlschlag an den Koordinator zurückgegeben wird. Welcher Ansatz zur Fehlerweitergabe ermöglicht die beste intelligente Erholung?

**Welcher Ansatz zur Fehlerweitergabe ermöglicht die beste intelligente Erholung?**

- A) Strukturierten Fehlerkontext an den Koordinator zurückgeben, inklusive Fehlertyp, ausgeführter Anfrage, etwaiger Teilergebnisse und möglicher alternativer Ansätze. **[RICHTIG]**
- B) Den Timeout innerhalb des Subagenten abfangen und ein leeres Ergebnis als erfolgreich markiert zurückgeben.
- C) Automatische Retries mit exponentiellem Backoff innerhalb des Subagenten umsetzen und erst nach Erschöpfung der Retries einen generischen Status „search unavailable" zurückgeben.
- D) Die Timeout-Ausnahme direkt an den Top-Level-Handler weitergeben und den gesamten Recherche-Workflow beenden.

**Warum A:** Strukturierten Fehlerkontext zurückzugeben — inklusive Fehlertyp, ausgeführter Anfrage, Teilergebnissen und alternativen Ansätzen — gibt dem Koordinator alles, was er für intelligente Erholungsentscheidungen braucht (z. B. Retry mit geänderter Anfrage oder Weitermachen mit Teilergebnissen). Es bewahrt maximalen Kontext für fundierte Entscheidungen auf Koordinationsebene.

---

## Frage 10 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** In deinem Systementwurf hast du dem Dokumentenanalyse-Agenten Zugriff auf ein Allzweck-Tool `fetch_url` gegeben, damit er Dokumente per URL herunterladen kann. Produktions-Logs zeigen, dass dieser Agent nun häufig Suchmaschinen-Ergebnisseiten herunterlädt, um Ad-hoc-Web-Suche durchzuführen — ein Verhalten, das über den Web-Recherche-Agenten laufen sollte — und dadurch inkonsistente Ergebnisse verursacht. Welche Korrektur ist am wirksamsten?

**Welche Korrektur ist am wirksamsten?**

- A) `fetch_url` durch ein Tool `load_document` ersetzen, das validiert, dass URLs auf Dokumentformate verweisen. **[RICHTIG]**
- B) `fetch_url` aus dem Dokumentenanalyse-Agenten entfernen und alles URL-Abrufen über den Koordinator an den Web-Recherche-Agenten leiten.
- C) Eine Filterung umsetzen, die `fetch_url`-Aufrufe an bekannte Suchmaschinen-Domains blockiert und andere URLs zulässt.
- D) Dem Prompt des Dokumentenanalyse-Agenten die Anweisung hinzufügen, dass `fetch_url` nur zum Herunterladen von Dokument-URLs verwendet werden soll, nicht zur Suche.

**Warum A:** Ein Allzweck-Tool durch ein dokumentspezifisches Tool zu ersetzen, das URLs gegen Dokumentformate validiert, behebt die Ursache, indem die Fähigkeit auf Schnittstellenebene eingeschränkt wird. Das folgt dem Prinzip der geringsten Rechte und macht unerwünschtes Suchverhalten unmöglich statt lediglich unerwünscht.

---

## Frage 11 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Bei der Recherche zu einem breiten Thema beobachtest du, dass der Web-Recherche-Agent und der Dokumentenanalyse-Agent dieselben Teilthemen untersuchen, was zu erheblicher Duplizierung in ihren Ausgaben führt. Der Token-Verbrauch verdoppelt sich fast, ohne dass die Recherchebreite oder -tiefe proportional zunimmt. Wie geht man am wirksamsten damit um?

**Wie geht man am wirksamsten damit um?**

- A) Beide Agenten parallel zu Ende laufen lassen und den Koordinator anschließend die überlappenden Ergebnisse deduplizieren lassen, bevor sie an den Synthese-Agenten übergeben werden.
- B) Der Koordinator partitioniert den Rechercheraum explizit vor der Delegation und weist jedem Agenten unterschiedliche Teilthemen oder Quellentypen zu. **[RICHTIG]**
- C) Einen Mechanismus mit gemeinsamem Zustand umsetzen, in dem Agenten ihren aktuellen Fokusbereich protokollieren, damit andere Agenten Duplizierung während der Ausführung dynamisch vermeiden können.
- D) Auf sequentielle Ausführung umstellen, bei der die Dokumentenanalyse erst nach Abschluss der Web-Suche läuft und die Web-Suche-Ergebnisse als Kontext nutzt, um Duplizierung zu vermeiden.

**Warum B:** Dass der Koordinator den Rechercheraum explizit vor der Delegation partitioniert, ist am wirksamsten, weil es die Ursache — unklare Aufgabengrenzen — adressiert, bevor die Arbeit beginnt. Es bewahrt die Parallelität und verhindert doppelten Aufwand und verschwendete Tokens.

---

## Frage 12 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Während der Recherche fragt der Web-Recherche-Subagent drei Quellenkategorien mit unterschiedlichen Ergebnissen ab: akademische Datenbanken liefern 15 relevante Arbeiten, Branchenberichte liefern „0 Ergebnisse" und Patentdatenbanken liefern „Connection timeout". Welcher Ansatz ermöglicht beim Entwurf der Fehlerweitergabe an den Koordinator die besten Erholungsentscheidungen?

**Welcher Ansatz ermöglicht die besten Erholungsentscheidungen?**

- A) Die Ergebnisse zu einer einzigen Erfolgsprozent-Kennzahl aggregieren (z. B. „67 % Quellenabdeckung") mit auf Anfrage verfügbaren Detail-Logs.
- B) Sowohl „Timeout" als auch „0 Ergebnisse" als Fehlschläge melden, die ein Eingreifen des Koordinators erfordern.
- C) Transiente Fehlschläge intern wiederholen und nur hartnäckige Fehler melden.
- D) Zugriffsfehler (Timeout), die eine Retry-Entscheidung erfordern, von gültigen leeren Ergebnissen („0 Ergebnisse") unterscheiden, die erfolgreiche Anfragen darstellen. **[RICHTIG]**

**Warum D:** Ein Timeout (Zugriffsfehler) und „0 Ergebnisse" (gültiges leeres Ergebnis) sind semantisch verschiedene Ausgänge, die unterschiedliche Reaktionen erfordern. Sie zu unterscheiden erlaubt es dem Koordinator, die Patentdatenbank erneut zu versuchen und zugleich die „0 Ergebnisse" der Branchenberichte als gültigen, informativen Befund zu akzeptieren.

---

## Frage 13 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Das Produktionsmonitoring zeigt inkonsistente Synthesequalität. Wenn die aggregierten Ergebnisse ~75K Tokens umfassen, zitiert der Synthese-Agent zuverlässig Informationen aus den ersten 15K Tokens (Web-Suche-Schlagzeilen/-Snippets) und den letzten 10K Tokens (Schlussfolgerungen der Dokumentenanalyse), übersieht aber oft kritische Befunde in den mittleren 50K Tokens — selbst wenn sie die Forschungsfrage direkt beantworten. Wie solltest du die aggregierte Eingabe umstrukturieren?

**Wie solltest du die aggregierte Eingabe umstrukturieren?**

- A) Alle Subagenten-Ausgaben vor der Aggregation auf unter 20K Tokens zusammenfassen, um den Inhalt im zuverlässigen Verarbeitungsbereich des Modells zu halten.
- B) Subagenten-Ergebnisse schrittweise an den Synthese-Agenten streamen und zuerst die Web-Suche-Ergebnisse vollständig verarbeiten, dann die Ergebnisse der Dokumentenanalyse hinzufügen.
- C) Eine Zusammenfassung der Schlüsselbefunde an den Anfang der aggregierten Eingabe stellen und die Detailergebnisse mit expliziten Abschnittsüberschriften zur besseren Navigation organisieren. **[RICHTIG]**
- D) Eine Rotation umsetzen, die über die Rechercheaufgaben hinweg abwechselt, welche Subagenten-Ergebnisse zuerst erscheinen, damit beide Quellen im Zeitverlauf gleichermaßen die Top-Position erhalten.

**Warum C:** Eine Zusammenfassung der Schlüsselbefunde an den Anfang zu stellen, nutzt Primacy-Effekte, sodass kritische Informationen an der zuverlässigst verarbeiteten Position stehen. Explizite Abschnittsüberschriften im gesamten Text helfen dem Modell, sich zurechtzufinden und dem Inhalt in der Mitte Aufmerksamkeit zu schenken, und mildern so direkt das Lost-in-the-middle-Phänomen.

---

## Frage 14 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Im Test umfasst die kombinierte Ausgabe des Web-Recherche-Agenten (85K Tokens inklusive Seiteninhalt) und des Dokumentenanalyse-Agenten (70K Tokens inklusive Gedankenketten) insgesamt 155K Tokens, aber der Synthese-Agent arbeitet am besten mit Eingaben unter 50K Tokens. Welche Lösung ist am wirksamsten?

**Welche Lösung ist am wirksamsten?**

- A) Die vorgelagerten Agenten so anpassen, dass sie strukturierte Daten (Schlüsselfakten, Zitate, Relevanzwerte) statt ausführlicher Inhalte und Begründungen zurückgeben. **[RICHTIG]**
- B) Einen zwischengeschalteten Zusammenfassungs-Agenten hinzufügen, der die Befunde vor der Übergabe an die Synthese verdichtet.
- C) Den Synthese-Agenten die Befunde in aufeinanderfolgenden Batches verarbeiten lassen und den Zustand zwischen den Aufrufen halten.
- D) Die Befunde in einer Vektordatenbank speichern und dem Synthese-Agenten Such-Tools geben, um während seiner Arbeit abzufragen.

**Warum A:** Die vorgelagerten Agenten so anzupassen, dass sie strukturierte Daten zurückgeben, behebt die Ursache, indem das Token-Volumen an der Quelle reduziert wird, während wesentliche Informationen erhalten bleiben. Es vermeidet die Übergabe sperriger Seiteninhalte und Argumentationsspuren, die Tokens aufblähen, ohne den Syntheseschritt zu verbessern.

---

## Frage 15 (Szenario: Multi-Agenten-Recherchesystem)

**Situation:** Im Test beobachtest du, dass der Synthese-Agent beim Zusammenführen von Ergebnissen oft bestimmte Aussagen verifizieren muss. Aktuell gibt der Synthese-Agent, wenn eine Verifikation nötig ist, die Kontrolle an den Koordinator zurück, der den Web-Recherche-Agenten aufruft und die Synthese dann mit den Ergebnissen erneut aufruft. Das fügt 2–3 zusätzliche Schleifen pro Aufgabe hinzu und erhöht die Latenz um 40 %. Deine Auswertung zeigt, dass 85 % dieser Verifikationen einfache Faktenchecks sind (Datumsangaben, Namen, Statistiken) und 15 % eine tiefere Recherche erfordern. Welcher Ansatz reduziert den Overhead am wirksamsten und bewahrt zugleich die Systemzuverlässigkeit?

**Welcher Ansatz ist am wirksamsten?**

- A) Dem Synthese-Agenten Zugriff auf alle Web-Recherche-Tools geben, damit er jeden Verifikationsbedarf direkt ohne Koordinator-Schleifen bearbeiten kann.
- B) Den Synthese-Agenten alle Verifikationsbedarfe sammeln lassen und sie am Ende als Batch an den Koordinator zurückgeben, der sie dann alle auf einmal an den Web-Recherche-Agenten sendet.
- C) Den Web-Recherche-Agenten proaktiv zusätzlichen Kontext um jede Quelle während der Erst­recherche cachen lassen, in Erwartung, dass die Synthese eine Verifikation benötigt.
- D) Dem Synthese-Agenten ein `verify_fact`-Tool mit begrenztem Umfang für einfache Prüfungen geben und komplexe Verifikationen über den Koordinator an den Web-Recherche-Agenten leiten. **[RICHTIG]**

**Warum D:** Ein Faktenverifikations-Tool mit begrenztem Umfang lässt den Synthese-Agenten 85 % der einfachen Prüfungen direkt bearbeiten und eliminiert die meisten Schleifen, während der Koordinator-Delegationspfad für die 15 % komplexen Verifikationen erhalten bleibt. Das wendet das Prinzip der geringsten Rechte an und reduziert die Latenz erheblich.

---

## Szenario: Claude Code für Continuous Integration

---

## Frage 16 (Szenario: Claude Code für Continuous Integration)

**Situation:** Deine CI-Pipeline führt die Claude Code CLI (im `--print`-Modus) aus und nutzt die CLAUDE.md, um Projektkontext für das Code-Review bereitzustellen; die Entwickler finden die Reviews im Allgemeinen gehaltvoll. Sie berichten jedoch, dass die Integration der Befunde in den Workflow schwierig ist — Claude gibt erzählende Absätze aus, die manuell in PR-Kommentare kopiert werden müssen. Das Team möchte jeden Befund automatisch als separaten Inline-PR-Kommentar an der relevanten Codestelle posten, was strukturierte Daten mit Dateipfad, Zeilennummer, Schweregrad und Lösungsvorschlag erfordert. Welcher Ansatz ist am wirksamsten?

**Welcher Ansatz ist am wirksamsten?**

- A) Der CLAUDE.md einen Abschnitt „Output Format for Review" mit Beispielen strukturierter Befunde hinzufügen, damit Claude das erwartete Format aus dem Projektkontext lernt.
- B) Die CLI-Flags `--output-format json` und `--json-schema` verwenden, um strukturierte Befunde zu erzwingen, und die Ausgabe dann parsen, um Inline-Kommentare über die GitHub-API zu posten. **[RICHTIG]**
- C) Explizite Formatierungsanweisungen in den Review-Prompt aufnehmen, die verlangen, dass jeder Befund einer parsbaren Vorlage wie `[FILE:path] [LINE:n] [SEVERITY:level] ...` folgt.
- D) Das erzählende Review-Format beibehalten und einen Zusammenfassungsschritt hinzufügen, der mit Claude eine strukturierte JSON-Zusammenfassung der Befunde erzeugt.

**Warum B:** `--output-format json` mit `--json-schema` erzwingt strukturierte Ausgabe auf CLI-Ebene und garantiert wohlgeformtes JSON mit den erforderlichen Feldern (Dateipfad, Zeilennummer, Schweregrad, Lösungsvorschlag), das zuverlässig geparst und über die GitHub-API als Inline-PR-Kommentar gepostet werden kann. Es nutzt integrierte CLI-Fähigkeiten, die speziell für strukturierte Ausgabe entworfen wurden.

---

## Frage 17 (Szenario: Claude Code für Continuous Integration)

**Situation:** Dein Team nutzt Claude Code, um Code-Vorschläge zu erzeugen, aber du bemerkst ein Muster: nicht offensichtliche Probleme — Performance-Optimierungen, die Grenzfälle brechen, Aufräumarbeiten, die unerwartet das Verhalten ändern — werden erst erkannt, wenn ein anderes Teammitglied den PR prüft. Claudes Argumentation während der Generierung zeigt, dass es diese Fälle bedacht, aber seinen Ansatz für korrekt befunden hat. Welcher Ansatz adressiert direkt die Ursache dieser Selbstprüfungs-Beschränkung?

**Welcher Ansatz adressiert direkt die Ursache?**

- A) Eine zweite unabhängige Instanz von Claude Code ausführen, um die Änderungen ohne Zugriff auf die Argumentation des Generators zu prüfen. **[RICHTIG]**
- B) Den Extended-Thinking-Modus für die Generierungsphase aktivieren, um eine gründlichere Abwägung vor der Erzeugung der Vorschläge zu ermöglichen.
- C) Dem Generierungs-Prompt explizite Selbstprüfungsanweisungen hinzufügen, die Claude bitten, seine eigenen Vorschläge zu kritisieren, bevor die Ausgabe finalisiert wird.
- D) Vollständige Testdateien und Dokumentation in den Prompt-Kontext aufnehmen, damit Claude das erwartete Verhalten während der Generierung besser versteht.

**Warum A:** Eine zweite unabhängige Claude-Code-Instanz ohne Zugriff auf die Argumentation des Generators adressiert direkt die Ursache, indem sie den Bestätigungsfehler (confirmation bias) vermeidet. Diese „frischer Blick"-Perspektive spiegelt das menschliche Peer-Review wider, bei dem ein anderer Prüfer Probleme erkennt, die der Autor wegrationalisiert hat.

---

## Frage 18 (Szenario: Claude Code für Continuous Integration)

**Situation:** Deine Code-Review-Komponente ist iterativ: Claude analysiert die geänderte Datei und kann dann verwandte Dateien (Importe, Basisklassen, Tests) über Tool-Aufrufe anfordern, um Kontext zu verstehen, bevor es das finale Feedback gibt. Deine Anwendung definiert ein Tool, mit dem Claude Dateiinhalte anfordern kann; Claude ruft das Tool auf, erhält Ergebnisse und setzt die Analyse fort. Du evaluierst Batch-Verarbeitung, um API-Kosten zu senken. Was ist die primäre technische Beschränkung, wenn man Batch-Verarbeitung für diesen Workflow in Betracht zieht?

**Was ist die primäre technische Beschränkung?**

- A) Die Batch-Verarbeitung enthält keine Korrelations-IDs, um Ausgaben den Eingabeanfragen zuzuordnen.
- B) Das asynchrone Modell kann Tools nicht mitten in einer Anfrage ausführen und Ergebnisse zurückgeben, damit Claude die Analyse fortsetzt. **[RICHTIG]**
- C) Die Batch-API unterstützt keine Tool-Definitionen in den Anfrageparametern.
- D) Die Batch-Verarbeitungslatenz von bis zu 24 Stunden ist für Pull-Request-Feedback zu langsam, obwohl der Workflow ansonsten funktionieren würde.

**Warum B:** Ein „Fire-and-forget"-asynchrones Batch-API-Modell hat keinen Mechanismus, um einen Tool-Aufruf während einer Anfrage abzufangen, das Tool auszuführen und Ergebnisse zurückzugeben, damit Claude die Analyse fortsetzt. Das ist grundlegend inkompatibel mit iterativen Tool-Calling-Workflows, die mehrere Tool-Anfrage/Antwort-Runden innerhalb einer einzigen logischen Interaktion erfordern.

---

## Frage 19 (Szenario: Claude Code für Continuous Integration)

**Situation:** Dein CI/CD-System führt drei Claude-basierte Analysen aus: (1) schnelle Stilprüfungen bei jedem PR, die das Mergen bis zum Abschluss blockieren, (2) umfassende wöchentliche Sicherheitsaudits der gesamten Codebasis und (3) nächtliche Testfallgenerierung für kürzlich geänderte Module. Die Message Batches API bietet 50 % Ersparnis, aber die Verarbeitung kann bis zu 24 Stunden dauern. Du möchtest die API-Kosten optimieren und dabei eine akzeptable Entwicklererfahrung wahren. Welche Kombination ordnet jede Aufgabe korrekt einem API-Ansatz zu?

**Welche Kombination ist korrekt?**

- A) Die Message Batches API für alle drei Aufgaben verwenden, um die 50 % Ersparnis zu maximieren, und die Pipeline so konfigurieren, dass sie auf Batch-Abschluss pollt.
- B) Synchrone Aufrufe für PR-Stilprüfungen verwenden; die Message Batches API für wöchentliche Sicherheitsaudits und nächtliche Testgenerierung. **[RICHTIG]**
- C) Synchrone Aufrufe für alle drei Aufgaben für gleichbleibende Antwortzeiten verwenden und sich auf Prompt-Caching verlassen, um die Kosten über die Arbeitslasten hinweg zu senken.
- D) Synchrone Aufrufe für PR-Stilprüfungen und nächtliche Testgenerierung verwenden; die Message Batches API nur für wöchentliche Sicherheitsaudits.

**Warum B:** PR-Stilprüfungen blockieren Entwickler und erfordern sofortige Antworten über synchrone Aufrufe, während wöchentliche Sicherheitsaudits und nächtliche Testgenerierung geplante Aufgaben mit flexiblen Fristen sind, die ein Batch-Fenster von bis zu 24 Stunden tolerieren können — und für beide die 50 % Ersparnis mitnehmen.

---

## Frage 20 (Szenario: Claude Code für Continuous Integration)

**Situation:** Deine automatisierten Reviews finden echte Probleme, aber die Entwickler berichten, das Feedback sei nicht umsetzbar. Befunde enthalten Formulierungen wie „complex ticket routing logic" oder „potential null pointer", ohne anzugeben, was genau zu ändern ist. Wenn du detaillierte Anweisungen wie „always include concrete fix suggestions" hinzufügst, erzeugt das Modell weiterhin inkonsistente Ausgabe — mal detailliert, mal vage. Welche Prompting-Technik erzeugt am zuverlässigsten durchgängig umsetzbares Feedback?

**Welche Prompting-Technik ist am zuverlässigsten?**

- A) Die Anweisungen weiter verfeinern mit expliziteren Anforderungen für jeden Teil des Feedback-Formats (Ort, Problem, Schweregrad, vorgeschlagene Korrektur).
- B) Das Kontextfenster erweitern, um mehr umliegende Codebasis einzubeziehen, damit das Modell genug Informationen für konkrete Korrekturvorschläge hat.
- C) Einen Zwei-Durchlauf-Ansatz umsetzen, bei dem ein Prompt Probleme identifiziert und ein zweiter Korrekturen erzeugt, was Spezialisierung ermöglicht.
- D) 3–4 Few-shot-Beispiele hinzufügen, die das exakt geforderte Format zeigen: identifiziertes Problem, Ort im Code, konkreter Korrekturvorschlag. **[RICHTIG]**

**Warum D:** Few-shot-Beispiele sind die wirksamste Technik, um ein einheitliches Ausgabeformat zu erreichen, wenn Anweisungen allein variable Ergebnisse liefern. 3–4 Beispiele bereitzustellen, die die exakt gewünschte Struktur zeigen (Problem, Ort, konkrete Korrektur), gibt dem Modell ein konkretes Muster zum Nachahmen, was zuverlässiger ist als abstrakte Anweisungen.

---

## Frage 21 (Szenario: Claude Code für Continuous Integration)

**Situation:** Deine CI-Pipeline enthält zwei Claude-basierte Code-Review-Modi: einen Pre-Merge-Commit-Hook, der den PR-Merge bis zum Abschluss blockiert, und eine „Deep Analysis", die über Nacht läuft, auf Batch-Abschluss pollt und detaillierte Vorschläge am PR postet. Du möchtest die API-Kosten mit der Message Batches API senken, die 50 % Ersparnis bietet, aber Polling erfordert und bis zu 24 Stunden dauern kann. Welcher Modus sollte Batch-Verarbeitung nutzen?

**Welcher Modus sollte Batch-Verarbeitung nutzen?**

- A) Nur der Pre-Merge-Commit-Hook.
- B) Nur die Deep Analysis. **[RICHTIG]**
- C) Beide Modi.
- D) Keiner der Modi.

**Warum B:** Die Deep Analysis ist ein idealer Kandidat für Batch-Verarbeitung, weil sie bereits über Nacht läuft, Verzögerung toleriert und ein Polling-Modell nutzt, bevor Ergebnisse veröffentlicht werden — was zur asynchronen, polling-basierten Architektur der Message Batches API passt und 50 % Ersparnis mitnimmt.

---

## Frage 22 (Szenario: Claude Code für Continuous Integration)

**Situation:** Dein automatisiertes Review analysiert Kommentare und Docstrings. Der aktuelle Prompt weist Claude an, „check that comments are accurate and up to date". Die Befunde markieren oft akzeptable Muster (TODO-Marker, einfache Beschreibungen), während sie Kommentare übersehen, die Verhalten beschreiben, das der Code nicht mehr umsetzt. Welche Änderung adressiert die Ursache dieser inkonsistenten Analyse?

**Welche Änderung adressiert die Ursache?**

- A) `git blame`-Daten einbeziehen, damit Claude Kommentare identifizieren kann, die älter als jüngste Codeänderungen sind.
- B) Few-shot-Beispiele irreführender Kommentare hinzufügen, damit das Modell ähnliche Muster in der Codebasis erkennt.
- C) TODO-, FIXME- und beschreibende Kommentarmuster vor der Analyse herausfiltern, um Rauschen zu reduzieren.
- D) Explizite Kriterien angeben: Kommentare nur markieren, wenn das von ihnen behauptete Verhalten dem tatsächlichen Verhalten des Codes widerspricht. **[RICHTIG]**

**Warum D:** Explizite Kriterien — Kommentare nur markieren, wenn das behauptete Verhalten dem tatsächlichen Codeverhalten widerspricht — adressieren direkt die Ursache, indem eine vage Anweisung durch eine präzise Definition dessen ersetzt wird, was ein Problem darstellt. Das reduziert False Positives bei akzeptablen Mustern und das Übersehen wirklich irreführender Kommentare.

---

## Frage 23 (Szenario: Claude Code für Continuous Integration)

**Situation:** Dein automatisiertes Code-Review-System zeigt inkonsistente Schweregrad-Einstufungen — ähnliche Probleme wie Null-Pointer-Risiken werden in manchen PRs als „critical" eingestuft, in anderen nur als „medium". Entwicklerbefragungen zeigen wachsendes Misstrauen — viele beginnen, Befunde ungelesen zu verwerfen, weil „die Hälfte falsch ist". Kategorien mit hohen False Positives untergraben das Vertrauen in die genauen Kategorien. Welcher Ansatz stellt das Vertrauen der Entwickler am besten wieder her und verbessert zugleich das System?

**Welcher Ansatz stellt das Vertrauen der Entwickler am besten wieder her?**

- A) Kategorien mit hohen False Positives (Stil, Benennung, Dokumentation) vorübergehend deaktivieren und nur hochpräzise Kategorien behalten, während die Prompts verbessert werden. **[RICHTIG]**
- B) Alle Kategorien aktiviert lassen, aber bei jedem Befund Konfidenzwerte anzeigen, damit Entwickler entscheiden können, was sie untersuchen.
- C) Alle Kategorien aktiviert lassen und in den nächsten Wochen Few-shot-Beispiele hinzufügen, um die Genauigkeit jeder Kategorie zu verbessern.
- D) Eine einheitliche Reduktion der Strenge über alle Kategorien hinweg anwenden, um die Gesamt-False-Positive-Rate zu senken.

**Warum A:** Kategorien mit hohen False Positives vorübergehend zu deaktivieren, stoppt die Vertrauenserosion sofort, indem verrauschte Befunde entfernt werden, die Entwickler dazu bringen, alles zu verwerfen, während der Wert hochpräziser Kategorien wie Sicherheit und Korrektheit erhalten bleibt. Es schafft außerdem Raum, die Prompts für die problematischen Kategorien zu verbessern, bevor sie wieder aktiviert werden.

---

## Frage 24 (Szenario: Claude Code für Continuous Integration)

**Situation:** Dein automatisiertes Review erzeugt Testfallvorschläge für jeden PR. Bei einem PR, der Kursabschluss-Tracking hinzufügt, schlägt Claude 10 Testfälle vor, aber Entwickler-Feedback zeigt, dass 6 davon Szenarien duplizieren, die die bestehende Test-Suite bereits abdeckt. Welche Änderung reduziert doppelte Vorschläge am wirksamsten?

**Welche Änderung ist am wirksamsten?**

- A) Die bestehende Testdatei in den Kontext aufnehmen, damit Claude bestimmen kann, welche Szenarien bereits abgedeckt sind. **[RICHTIG]**
- B) Die angeforderte Anzahl an Vorschlägen von 10 auf 5 reduzieren, in der Annahme, dass Claude die wertvollsten Fälle zuerst priorisiert.
- C) Anweisungen hinzufügen, die Claude anweisen, sich ausschließlich auf Grenzfälle und Fehlerbedingungen zu konzentrieren statt auf Erfolgs­pfade.
- D) Eine Nachverarbeitung umsetzen, die Vorschläge herausfiltert, deren Beschreibungen über Schlüsselwort-Überlappung zu bestehenden Testnamen passen.

**Warum A:** Die bestehende Testdatei einzubeziehen, behebt die Ursache der Duplizierung: Claude kann nur dann keine bereits abgedeckten Szenarien vorschlagen, wenn es weiß, welche Tests bereits existieren. Das gibt Claude die Information, um wirklich neue, wertvolle Tests vorzuschlagen.

---

## Frage 25 (Szenario: Claude Code für Continuous Integration)

**Situation:** Nachdem ein erstes automatisiertes Review 12 Befunde identifiziert hat, pusht ein Entwickler neue Commits, um Probleme zu beheben. Ein erneutes Review erzeugt 8 Befunde, aber die Entwickler berichten, dass 5 davon frühere Kommentare zu Code duplizieren, der in den neuen Commits bereits behoben wurde. Was ist der wirksamste Weg, dieses redundante Feedback zu eliminieren und dabei die Gründlichkeit zu wahren?

**Was ist der wirksamste Weg, redundantes Feedback zu eliminieren?**

- A) Das Review nur ausführen, wenn der PR erstellt wird und im finalen Pre-Merge-Zustand ist, und Zwischen-Commits überspringen.
- B) Einen Nachverarbeitungsfilter hinzufügen, der Befunde entfernt, die über Dateipfade und Problembeschreibungen zu früheren passen, bevor Kommentare gepostet werden.
- C) Den Review-Umfang auf die im jüngsten Push geänderten Dateien beschränken und Dateien aus früheren Commits ausschließen.
- D) Frühere Review-Befunde in den Kontext aufnehmen und Claude anweisen, nur neue oder noch ungelöste Probleme zu melden. **[RICHTIG]**

**Warum D:** Frühere Review-Befunde in den Kontext aufzunehmen, lässt Claude neue Probleme von solchen unterscheiden, die in jüngsten Commits bereits behoben wurden. Das bewahrt die Gründlichkeit des Reviews und nutzt Claudes Argumentation, um redundantes Feedback zu behobenem Code zu vermeiden.

---

## Frage 26 (Szenario: Claude Code für Continuous Integration)

**Situation:** Dein Pipeline-Skript führt `claude "Analyze this pull request for security issues"` aus, aber der Job hängt endlos. Die Logs zeigen, dass Claude Code auf interaktive Eingabe wartet. Was ist der korrekte Ansatz, Claude Code in einer automatisierten Pipeline auszuführen?

**Was ist der korrekte Ansatz?**

- A) Ein Flag `--batch` hinzufügen: `claude --batch "Analyze this pull request for security issues"`.
- B) Das Flag `-p` hinzufügen: `claude -p "Analyze this pull request for security issues"`. **[RICHTIG]**
- C) stdin von `/dev/null` umleiten: `claude "Analyze this pull request for security issues" < /dev/null`.
- D) Die Umgebungsvariable `CLAUDE_HEADLESS=true` vor der Ausführung des Befehls setzen.

**Warum B:** Das Flag `-p` (oder `--print`) ist der dokumentierte Weg, Claude Code nicht-interaktiv auszuführen. Es verarbeitet den Prompt, gibt das Ergebnis auf stdout aus und beendet sich, ohne auf Nutzereingaben zu warten — ideal für CI/CD-Pipelines.

---

## Frage 27 (Szenario: Claude Code für Continuous Integration)

**Situation:** Ein Pull Request ändert 14 Dateien in einem Bestandsverfolgungsmodul. Ein Einzeldurchlauf-Review, das alle Dateien gemeinsam analysiert, liefert inkonsistente Ergebnisse: detailliertes Feedback zu manchen Dateien, aber oberflächliche Kommentare zu anderen, übersehene offensichtliche Bugs und widersprüchliches Feedback (ein Muster wird in einer Datei beanstandet, aber identischer Code in einer anderen Datei desselben PR freigegeben). Wie solltest du das Review umstrukturieren?

**Wie solltest du das Review umstrukturieren?**

- A) Drei unabhängige vollständige PR-Review-Durchläufe ausführen und nur Probleme markieren, die in mindestens zwei der drei Läufe auftreten.
- B) In fokussierte Durchläufe aufteilen: jede Datei einzeln auf lokale Probleme prüfen, dann einen separaten integrationsorientierten Durchlauf ausführen, um dateiübergreifende Datenflüsse zu untersuchen. **[RICHTIG]**
- C) Von den Entwicklern verlangen, große PRs vor dem automatisierten Review in kleinere Einreichungen von 3–4 Dateien aufzuteilen.
- D) Auf ein größeres Modell mit größerem Kontextfenster wechseln, damit es allen 14 Dateien in einem Durchlauf ausreichend Aufmerksamkeit schenken kann.

**Warum B:** Fokussierte Durchläufe pro Datei adressieren die Ursache — Aufmerksamkeitsverdünnung —, indem sie gleichbleibende Tiefe und zuverlässige lokale Problemerkennung sicherstellen. Ein separater integrationsorientierter Durchlauf deckt dann dateiübergreifende Belange wie Abhängigkeits- und Datenfluss-Wechselwirkungen ab.

---

## Frage 28 (Szenario: Claude Code für Continuous Integration)

**Situation:** Dein automatisiertes Code-Review erzeugt im Schnitt 15 Befunde pro Pull Request, und die Entwickler berichten eine False-Positive-Rate von 40 %. Der Engpass ist die Untersuchungszeit: Entwickler müssen jeden Befund anklicken, um Claudes Begründung zu lesen, bevor sie entscheiden, ob sie ihn beheben oder verwerfen. Deine CLAUDE.md enthält bereits umfassende Regeln für akzeptable Muster, und die Stakeholder haben jeden Ansatz abgelehnt, der Befunde filtert, bevor Entwickler sie sehen. Welche Änderung adressiert die Untersuchungszeit am besten?

**Welche Änderung adressiert die Untersuchungszeit am besten?**

- A) Von Claude verlangen, seine Begründung und eine Konfidenzschätzung direkt in jeden Befund aufzunehmen. **[RICHTIG]**
- B) Einen Nachverarbeiter hinzufügen, der Befundmuster analysiert und solche automatisch unterdrückt, die zu historischen False-Positive-Signaturen passen.
- C) Befunde als „blocking issues" vs. „suggestions" kategorisieren, mit unterschiedlichen Review-Anforderungen je Stufe.
- D) Claude so konfigurieren, dass es nur Befunde mit hoher Konfidenz zeigt und unsichere Markierungen herausfiltert, bevor Entwickler sie sehen.

**Warum A:** Begründung und Konfidenz direkt in jeden Befund aufzunehmen, reduziert die Untersuchungszeit, indem Entwickler schnell triagieren können, ohne jeden Befund zu öffnen. Es erfüllt die „keine Filterung"-Vorgabe, weil alle Befunde sichtbar bleiben, während die Entscheidungsfindung der Entwickler beschleunigt wird.

---

## Frage 29 (Szenario: Claude Code für Continuous Integration)

**Situation:** Die Analyse deines automatisierten Code-Reviews zeigt große Unterschiede bei den False-Positive-Raten nach Befundkategorie: Sicherheits-/Korrektheitsbefunde haben 8 % False Positives, Performance-Befunde 18 %, Stil-/Benennungsbefunde 52 % und Dokumentationsbefunde 48 %. Entwicklerbefragungen zeigen wachsendes Misstrauen — viele beginnen, Befunde ungelesen zu verwerfen, weil „die Hälfte falsch ist". Kategorien mit hohen False Positives untergraben das Vertrauen in die genauen Kategorien. Welcher Ansatz stellt das Vertrauen der Entwickler am besten wieder her und verbessert zugleich das System?

**Welcher Ansatz stellt das Vertrauen der Entwickler am besten wieder her?**

- A) Kategorien mit hohen False Positives (Stil, Benennung, Dokumentation) vorübergehend deaktivieren und nur hochpräzise Kategorien behalten, während die Prompts verbessert werden. **[RICHTIG]**
- B) Alle Kategorien aktiviert lassen, aber bei jedem Befund Konfidenzwerte anzeigen, damit Entwickler entscheiden können, was sie untersuchen.
- C) Alle Kategorien aktiviert lassen und in den nächsten Wochen Few-shot-Beispiele hinzufügen, um die Genauigkeit jeder Kategorie zu verbessern.
- D) Eine einheitliche Reduktion der Strenge über alle Kategorien hinweg anwenden, um die Gesamt-False-Positive-Rate zu senken.

**Warum A:** Kategorien mit hohen False Positives vorübergehend zu deaktivieren, stoppt die Vertrauenserosion sofort, indem verrauschte Befunde entfernt werden, die Entwickler dazu bringen, alles zu verwerfen, während der Wert hochpräziser Kategorien wie Sicherheit und Korrektheit erhalten bleibt. Es schafft außerdem Raum, die Prompts für die problematischen Kategorien zu verbessern, bevor sie wieder aktiviert werden.

---

## Frage 30 (Szenario: Claude Code für Continuous Integration)

**Situation:** Dein Team möchte die API-Kosten für die automatisierte Analyse senken. Aktuell unterstützen synchrone Claude-Aufrufe zwei Workflows: (1) eine blockierende Pre-Merge-Prüfung, die abgeschlossen sein muss, bevor Entwickler mergen können, und (2) einen Tech-Debt-Bericht, der über Nacht für das Review am nächsten Morgen erzeugt wird. Dein Manager schlägt vor, beide auf die Message Batches API umzustellen, um 50 % zu sparen. Wie solltest du diesen Vorschlag bewerten?

**Wie solltest du diesen Vorschlag bewerten?**

- A) Beide auf Batch-Verarbeitung umstellen mit Rückfall auf synchrone Aufrufe, wenn Batches zu lange dauern.
- B) Beide Workflows auf Batch-Verarbeitung umstellen mit Status-Polling zur Abschlussprüfung.
- C) Batch-Verarbeitung nur für Tech-Debt-Berichte verwenden; synchrone Aufrufe für Pre-Merge-Prüfungen beibehalten. **[RICHTIG]**
- D) Für beide Workflows synchrone Aufrufe beibehalten, um Probleme mit der Reihenfolge von Batch-Ergebnissen zu vermeiden.

**Warum C:** Die Verarbeitung der Message Batches API kann bis zu 24 Stunden dauern, ohne Latenz-SLA, was für nächtliche Tech-Debt-Berichte akzeptabel, aber für blockierende Pre-Merge-Prüfungen inakzeptabel ist, bei denen Entwickler warten. Das ordnet jeden Workflow anhand der Latenzanforderungen der richtigen API zu.

---

## Szenario: Code-Generierung mit Claude Code

---

## Frage 31 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Du hast Claude Code gebeten, eine Funktion zu implementieren, die API-Antworten in ein internes normalisiertes Format transformiert. Nach zwei Iterationen entspricht die Ausgabestruktur immer noch nicht den Erwartungen — manche Felder sind anders verschachtelt und Zeitstempel sind falsch formatiert. Du hast die Anforderungen in Prosa beschrieben, aber Claude interpretiert sie jedes Mal anders.

**Welcher Ansatz ist für die nächste Iteration am wirksamsten?**

- A) Ein JSON-Schema schreiben, das die erwartete Ausgabestruktur beschreibt, und Claudes Ausgabe nach jeder Iteration dagegen validieren.
- B) 2–3 konkrete Eingabe-/Ausgabe-Beispiele bereitstellen, die die erwartete Transformation für repräsentative API-Antworten zeigen. **[RICHTIG]**
- C) Die Anforderungen mit mehr technischer Präzision neu schreiben und exakte Feldzuordnungen, Verschachtelungsregeln und Zeitstempel-Formatstrings angeben.
- D) Claude bitten, sein aktuelles Verständnis der Anforderungen zu erläutern, um zu identifizieren, wo die Interpretationen auseinandergehen.

**Warum B:** Konkrete Eingabe-/Ausgabe-Beispiele beseitigen die den Prosabeschreibungen innewohnende Mehrdeutigkeit, indem sie Claude die exakt erwarteten Transformationsergebnisse zeigen. Das adressiert direkt die Ursache — die Fehlinterpretation textueller Anforderungen —, indem eindeutige Muster für Feldverschachtelung und Zeitstempelformatierung bereitgestellt werden.

---

## Frage 32 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Du musst Slack als neuen Benachrichtigungskanal hinzufügen. Die bestehende Codebasis hat klare, etablierte Muster für E-Mail-, SMS- und Push-Kanäle. Slacks API bietet jedoch grundlegend unterschiedliche Integrationsansätze — Incoming Webhooks (einfach, einseitig), Bot-Tokens (unterstützen Zustellbestätigung und programmatische Kontrolle) oder Slack Apps (zweiseitige Events, erfordert Workspace-Genehmigung). Deine Aufgabe lautet „add Slack support", ohne die Integrationsmethode anzugeben oder erweiterte Funktionen wie Zustellverfolgung zu verlangen.

**Wie solltest du diese Aufgabe angehen?**

- A) Im Modus der direkten Ausführung mit Incoming Webhooks beginnen, um dem bestehenden einseitigen Benachrichtigungsmuster zu entsprechen.
- B) In den Planungsmodus wechseln, um die Integrationsoptionen und architektonischen Implikationen zu erkunden, und vor der Umsetzung eine Empfehlung präsentieren. **[RICHTIG]**
- C) Im Modus der direkten Ausführung beginnen, indem eine Slack-Kanalklasse anhand bestehender Muster gerüstet und die Entscheidung zur Integrationsmethode zurückgestellt wird.
- D) Im Modus der direkten Ausführung mit einem Bot-Token-Ansatz beginnen, um sicherzustellen, dass eine Zustellbestätigung möglich ist.

**Warum B:** Die Slack-Integration hat mehrere gültige Ansätze mit deutlich unterschiedlichen architektonischen Implikationen, und die Anforderungen sind mehrdeutig. Der Planungsmodus erlaubt es, die Abwägungen zwischen Webhooks, Bot-Tokens und Slack Apps zu bewerten und sich vor der Umsetzung auf einen Ansatz zu einigen.

---

## Frage 33 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Deine CLAUDE.md-Datei ist auf 400+ Zeilen angewachsen und enthält Coding-Standards, Test-Konventionen, eine detaillierte PR-Review-Checkliste, Deployment-Anweisungen und Datenbankmigrationsverfahren. Du möchtest, dass Claude die Coding-Standards und Test-Konventionen immer befolgt, die Anleitung zu PR-Review, Deployment und Migrationen aber nur beim Ausführen dieser Aufgaben anwendet.

**Welcher Umstrukturierungsansatz ist am wirksamsten?**

- A) Alle Anleitungen in separate Skills-Dateien verschieben, nach Workflow-Typ organisiert, und in der CLAUDE.md nur eine kurze Projektbeschreibung belassen.
- B) Alles in der CLAUDE.md belassen, aber die `@import`-Syntax verwenden, um es nach Kategorie in separat gepflegte Dateien zu organisieren.
- C) Die CLAUDE.md in Dateien unter `.claude/rules/` mit pfadgebundenen Glob-Mustern aufteilen, sodass jede Regel nur für die relevanten Dateitypen lädt.
- D) Universelle Standards in der CLAUDE.md belassen und Skills für workflow-spezifische Anleitung (PR-Review, Deployment, Migrationen) mit Trigger-Schlüsselwörtern erstellen. **[RICHTIG]**

**Warum D:** CLAUDE.md-Inhalt lädt in jeder Sitzung und stellt sicher, dass Coding-Standards und Test-Konventionen immer gelten, während Skills bei Bedarf aufgerufen werden, wenn Claude Trigger-Schlüsselwörter erkennt — ideal für workflow-spezifische Anleitung wie PR-Review, Deployment und Migrationen.

---

## Frage 34 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Du bist damit beauftragt, die monolithische Anwendung deines Teams in Microservices umzustrukturieren. Das betrifft Änderungen über Dutzende Dateien und erfordert Entscheidungen zu Servicegrenzen und Modulabhängigkeiten.

**Welchen Ansatz solltest du wählen?**

- A) In den Planungsmodus wechseln, um die Codebasis zu erkunden, Abhängigkeiten zu verstehen und den Umsetzungsansatz zu entwerfen, bevor Änderungen vorgenommen werden. **[RICHTIG]**
- B) Im Modus der direkten Ausführung beginnen und erst zum Planen wechseln, nachdem während der Umsetzung unerwartete Komplexität aufgetreten ist.
- C) Im Modus der direkten Ausführung beginnen und schrittweise Änderungen vornehmen und die Umsetzung natürliche Servicegrenzen aufzeigen lassen.
- D) Direkte Ausführung mit detaillierten Vorab-Anweisungen verwenden, die jede Servicestruktur festlegen.

**Warum A:** Der Planungsmodus ist die richtige Strategie für komplexe architektonische Umstrukturierungen wie das Aufteilen eines Monolithen: Er ermöglicht sichere Erkundung und fundierte Entscheidungen zu den Grenzen, bevor man sich auf potenziell teure Änderungen über viele Dateien festlegt.

---

## Frage 35 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Dein Team hat einen Skill `/analyze-codebase` erstellt, der eine tiefe Codeanalyse durchführt — Abhängigkeitsscan, Testabdeckungszählungen und Code-Qualitätskennzahlen. Nach dem Ausführen des Befehls berichten Teammitglieder, dass Claude in der Sitzung weniger reaktionsfähig wird und den Kontext der ursprünglichen Aufgabe verliert.

**Wie behebst du das am wirksamsten und behältst dabei die vollen Analysefähigkeiten?**

- A) `context: fork` im Skill-Frontmatter hinzufügen, um die Analyse in einem isolierten Subagenten-Kontext auszuführen. **[RICHTIG]**
- B) `model: haiku` im Frontmatter hinzufügen, um ein schnelleres, günstigeres Modell für die Analyse zu verwenden.
- C) Den Skill in drei kleinere Skills aufteilen, die jeweils weniger Ausgabe erzeugen.
- D) Dem Skill Anweisungen hinzufügen, alle Ergebnisse vor der Anzeige in eine kurze Zusammenfassung zu komprimieren.

**Warum A:** `context: fork` führt die Analyse in einem isolierten Subagenten-Kontext aus, sodass die große Ausgabe das Kontextfenster der Hauptsitzung nicht belastet und Claude die ursprüngliche Aufgabe nicht aus den Augen verliert. Es bewahrt die volle Analysefähigkeit und hält die Hauptsitzung reaktionsfähig.

---

## Frage 36 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Dein Team nutzt einen Skill `/commit` in `.claude/skills/commit/SKILL.md`. Ein Entwickler möchte ihn für seinen persönlichen Workflow anpassen (anderes Commit-Message-Format, zusätzliche Prüfungen), ohne Teammitglieder zu beeinträchtigen.

**Was empfiehlst du?**

- A) Eine persönliche Version unter `~/.claude/skills/` mit einem anderen Namen anlegen, z. B. `/my-commit`. **[RICHTIG]**
- B) Bedingte Logik auf Basis des Benutzernamens im Frontmatter des Projekt-Skills hinzufügen.
- C) Eine persönliche Version unter `~/.claude/skills/commit/SKILL.md` mit demselben Namen anlegen.
- D) `override: true` im Frontmatter des persönlichen Skills setzen, um ihn gegenüber der Projektversion zu priorisieren.

**Warum A:** Persönliche Skills haben Vorrang vor Projekt-Skills mit demselben Namen, sodass die Wiederverwendung des Namens `commit` den Skill des Teams für diesen einen Entwickler stillschweigend verdecken würde — er würde keine Updates mehr erhalten, wann immer das Team `/commit` verbessert, und müsste sich merken, dass er unter demselben Befehl einen anderen Skill ausführt. Die persönliche Variante `/my-commit` zu nennen, vermeidet diese Kollision vollständig: Der Entwickler nutzt weiterhin das gepflegte `/commit` des Teams und erhält einen separaten, klar benannten Skill für seinen persönlichen Workflow, ohne Verwechslungsrisiko und ohne Team-Updates zu verpassen.

---

## Frage 37 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Dein Team nutzt Claude Code seit Monaten. Kürzlich berichten drei Entwickler, dass Claude die Anleitung „always include comprehensive error handling" befolgt, aber ein vierter, gerade neu hinzugekommener Entwickler sagt, Claude befolge sie nicht. Alle vier arbeiten im selben Repo und haben aktuellen Code.

**Was ist die wahrscheinlichste Ursache und Lösung?**

- A) Die Anleitung liegt in den `~/.claude/CLAUDE.md`-Dateien der ursprünglichen Entwickler auf Nutzerebene, nicht in der Projekt-`.claude/CLAUDE.md`. Die Anweisung in die Datei auf Projektebene verschieben, damit alle Teammitglieder sie erhalten. **[RICHTIG]**
- B) Die `~/.claude/CLAUDE.md` des neuen Entwicklers enthält widersprüchliche Anweisungen, die die Projekteinstellungen überschreiben; er sollte den widersprüchlichen Abschnitt löschen.
- C) Claude Code lernt nutzerspezifische Präferenzen im Laufe der Zeit; der neue Entwickler muss die Anforderung wiederholen, bis Claude sie sich „merkt".
- D) Claude Code cachet die CLAUDE.md nach dem ersten Lesen; die ursprünglichen Entwickler nutzen gecachte Versionen. Alle sollten den Claude-Code-Cache leeren.

**Warum A:** Wenn die Anleitung nur zu den Nutzer-Konfigurationen der ursprünglichen Entwickler hinzugefügt wurde und nicht zur `.claude/CLAUDE.md` auf Projektebene, erhalten neue Teammitglieder sie nicht. Sie in die Konfiguration auf Projektebene zu verschieben, stellt sicher, dass alle aktuellen und künftigen Teammitglieder die Anleitung automatisch erhalten.

---

## Frage 38 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Du stellst fest, dass das Einbinden von 2–3 vollständigen Endpunkt-Implementierungsbeispielen als Kontext die Konsistenz beim Generieren neuer API-Endpunkte deutlich verbessert. Dieser Kontext ist jedoch nur beim Erstellen neuer Endpunkte nützlich — nicht beim Debuggen, Code-Review oder anderer Arbeit im API-Verzeichnis.

**Welcher Konfigurationsansatz ist am wirksamsten?**

- A) Endpunkt-Beispiele und Musterdokumentation zur Projekt-CLAUDE.md hinzufügen, damit sie immer verfügbar sind.
- B) Endpunkt-Beispiele bei jeder Generierungsanfrage manuell referenzieren, indem Code in den Prompt kopiert wird.
- C) Pfadspezifische Regeln in `.claude/rules/api/` konfigurieren, die Endpunkt-Beispiele enthalten und aktiv werden, wenn im API-Verzeichnis gearbeitet wird.
- D) Einen Skill erstellen, der die Endpunkt-Beispiele referenziert und musterbefolgende Anweisungen enthält und bei Bedarf über einen Slash-Befehl aufgerufen wird. **[RICHTIG]**

**Warum D:** Ein bei Bedarf aufgerufener Skill lädt den Beispielkontext nur beim Generieren neuer Endpunkte, nicht bei unverwandten Aufgaben wie Debuggen oder Review. Das hält den Hauptkontext sauber und bewahrt zugleich hochwertige Generierung, wenn sie benötigt wird.

---

## Frage 39 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Dein Team hat einen Skill `/migration` erstellt, der Datenbankmigrationsdateien generiert. Er nimmt den Migrationsnamen über `$ARGUMENTS` entgegen. In der Produktion beobachtest du drei Probleme: (1) Entwickler führen den Skill oft ohne Argumente aus, was schlecht benannte Dateien verursacht, (2) der Skill nutzt manchmal Datenbankschema-Details aus unverwandten früheren Gesprächen, und (3) ein Entwickler hat versehentlich eine destruktive Test-Bereinigung ausgeführt, als der Skill breiten Tool-Zugriff hatte.

**Welcher Konfigurationsansatz behebt alle drei Probleme?**

- A) Positionsparameter `$1` und `$2` statt `$ARGUMENTS` verwenden, um spezifische Eingaben zu erzwingen, explizite Schemadatei-Referenzen über die `@`-Syntax zur Kontextsteuerung einbinden und eine Frontmatter-Beschreibung mit einer Warnung vor destruktiven Operationen hinzufügen.
- B) `argument-hint` im Frontmatter hinzufügen, um erforderliche Parameter anzufordern, `context: fork` verwenden, um die Ausführung zu isolieren, und `allowed-tools` auf Datei-Schreiboperationen beschränken. **[RICHTIG]**
- C) In `/migration-create` und `/migration-apply` aufteilen, Validierungsanweisungen hinzufügen, die den Migrationsnamen anfordern, falls er fehlt, und für jeden unterschiedliche `allowed-tools`-Umfänge verwenden.
- D) Validierungsanweisungen in der SKILL.md des Skills hinzufügen, um sicherzustellen, dass `$ARGUMENTS` ein gültiger Name ist, Anweisungen hinzufügen, früheren Gesprächskontext zu ignorieren, und verbotene Operationen auflisten.

**Warum B:** Das nutzt drei separate Konfigurationsfunktionen, um jedes Problem zu adressieren: `argument-hint` verbessert die Argumenteingabe und reduziert fehlende Argumente, `context: fork` verhindert Kontext-Leckagen aus früheren Gesprächen, und `allowed-tools` beschränkt den Skill auf sichere Datei-Schreiboperationen und verhindert destruktive Aktionen.

---

## Frage 40 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Deine Codebasis enthält Bereiche mit unterschiedlichen Coding-Konventionen: React-Komponenten nutzen funktionalen Stil mit Hooks, API-Handler nutzen async/await mit spezifischer Fehlerbehandlung, und Datenbankmodelle folgen dem Repository-Muster. Testdateien sind über die Codebasis verteilt, jeweils neben dem zu testenden Code (z. B. `Button.test.tsx` neben `Button.tsx`), und du möchtest, dass alle Tests unabhängig vom Ort denselben Konventionen folgen.

**Was ist der am besten unterstützte Weg, damit Claude beim Generieren von Code automatisch die korrekten Konventionen anwendet?**

- A) Alle Konventionen in die CLAUDE.md im Stamm packen, unter Überschriften für jeden Bereich, und Claude ableiten lassen, welcher Abschnitt gilt.
- B) Skills in `.claude/skills/` für jeden Codetyp erstellen und die Konventionen in jede SKILL.md einbetten.
- C) Eine separate CLAUDE.md-Datei in jedem Unterverzeichnis mit den Konventionen für diesen Bereich ablegen.
- D) Regeldateien unter `.claude/rules/` mit YAML-Frontmatter erstellen, das Glob-Muster angibt, um Konventionen bedingt anhand von Dateipfaden anzuwenden. **[RICHTIG]**

**Warum D:** `.claude/rules/`-Dateien mit YAML-Frontmatter und Glob-Mustern (z. B. `**/*.test.tsx`, `src/api/**/*.ts`) ermöglichen deterministische, pfadbasierte Anwendung von Konventionen unabhängig von der Verzeichnisstruktur. Das ist der am besten unterstützte Ansatz für querschnittliche Muster wie verteilte Testdateien.

---

## Frage 41 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Du möchtest einen benutzerdefinierten Slash-Befehl `/review` erstellen, der die Standard-Code-Review-Checkliste deines Teams ausführt. Er sollte jedem Entwickler beim Klonen oder Aktualisieren des Repositorys zur Verfügung stehen.

**Wo solltest du die Befehlsdatei anlegen?**

- A) In `~/.claude/commands/` im Home-Verzeichnis jedes Entwicklers.
- B) Im Projekt-Repository unter `.claude/commands/`. **[RICHTIG]**
- C) In `.claude/config.json` als Array von Befehlen.
- D) In der Projekt-CLAUDE.md im Stamm.

**Warum B:** Benutzerdefinierte Slash-Befehle unter `.claude/commands/` im Projekt-Repository abzulegen, stellt sicher, dass sie versionskontrolliert und automatisch für jeden Entwickler verfügbar sind, der das Repo klont oder aktualisiert. Das ist der vorgesehene Ort für benutzerdefinierte Befehle auf Projektebene in Claude Code.

---

## Frage 42 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Die CLAUDE.md deines Teams ist über 500 Zeilen angewachsen und vermischt TypeScript-Konventionen, Test-Anleitung, API-Muster und Deployment-Verfahren. Entwickler finden es schwer, die richtigen Abschnitte zu finden und zu aktualisieren.

**Welchen Ansatz unterstützt Claude Code, um Anweisungen auf Projektebene in fokussierte thematische Module zu organisieren?**

- A) Eine `.claude/config.yaml` definieren, die Dateimuster bestimmten Abschnitten innerhalb der CLAUDE.md zuordnet.
- B) Separate Markdown-Dateien in `.claude/rules/` erstellen, die je ein Thema abdecken (z. B. `testing.md`, `api-conventions.md`). **[RICHTIG]**
- C) Anweisungen in README.md-Dateien in relevanten Unterverzeichnissen aufteilen, die Claude automatisch als Anweisungen lädt.
- D) Mehrere Dateien namens CLAUDE.md auf verschiedenen Ebenen des Verzeichnisbaums erstellen, die jeweils die übergeordneten Anweisungen überschreiben.

**Warum B:** Claude Code unterstützt ein Verzeichnis `.claude/rules/`, in dem du separate Markdown-Dateien für thematische Anleitung erstellen kannst (z. B. `testing.md`, `api-conventions.md`), sodass Teams große Anweisungssätze in fokussierte, wartbare Module organisieren können.

---

## Frage 43 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Du erstellst einen benutzerdefinierten Skill `/explore-alternatives`, den dein Team nutzt, um vor der Wahl eines Ansatzes Umsetzungsansätze zu erarbeiten und zu bewerten. Entwickler berichten, dass nach dem Ausführen des Skills nachfolgende Claude-Antworten von der Alternativen-Diskussion beeinflusst werden — manchmal werden verworfene Ansätze referenziert oder Erkundungskontext behalten, der die eigentliche Umsetzung stört.

**Wie solltest du diesen Skill am wirksamsten konfigurieren?**

- A) Das `!`-Präfix im Skill verwenden, um die Erkundungslogik als Bash-Subprozess auszuführen.
- B) `context: fork` im Skill-Frontmatter hinzufügen. **[RICHTIG]**
- C) In zwei Skills aufteilen — `/explore-start` und `/explore-end` —, um Grenzen zu markieren, wann der Erkundungskontext verworfen werden soll.
- D) Den Skill in `~/.claude/skills/` statt in `.claude/skills/` erstellen.

**Warum B:** `context: fork` führt den Skill in einem isolierten Subagenten-Kontext aus, sodass Erkundungsdiskussionen den Hauptgesprächsverlauf nicht belasten. Das verhindert, dass verworfene Ansätze und Brainstorming-Kontext die nachfolgende Umsetzungsarbeit beeinflussen.

---

## Frage 44 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Dein Team möchte einen GitHub-MCP-Server hinzufügen, um über Claude Code PRs zu durchsuchen und den CI-Status zu prüfen. Jeder der sechs Entwickler hat seinen eigenen persönlichen GitHub-Zugriffstoken. Du möchtest ein einheitliches Toolset im Team, ohne Zugangsdaten in die Versionskontrolle zu committen.

**Welcher Konfigurationsansatz ist am wirksamsten?**

- A) Jeden Entwickler den Server im Nutzer-Scope über `claude mcp add --scope user` hinzufügen lassen.
- B) Einen MCP-Server-Wrapper erstellen, der Tokens aus einer `.env`-Datei liest und GitHub-API-Aufrufe proxyt, und den Wrapper zur Projekt-`.mcp.json` hinzufügen.
- C) Den Server zur Projekt-`.mcp.json` hinzufügen und Umgebungsvariablen-Ersetzung (`${GITHUB_TOKEN}`) für die Authentifizierung nutzen und die erforderliche Umgebungsvariable im Projekt-README dokumentieren. **[RICHTIG]**
- D) Den Server im Projekt-Scope mit einem Platzhalter-Token konfigurieren und den Entwicklern sagen, sie sollen ihn in ihrer lokalen Konfiguration überschreiben.

**Warum C:** Eine Projekt-`.mcp.json` mit Umgebungsvariablen-Ersetzung ist idiomatisch: Sie bietet eine einzige versionskontrollierte Wahrheitsquelle für die MCP-Konfiguration und lässt jeden Entwickler Zugangsdaten über Umgebungsvariablen liefern. Die Variable zu dokumentieren, macht das Onboarding leicht, ohne Geheimnisse zu committen.

---

## Frage 45 (Szenario: Code-Generierung mit Claude Code)

**Situation:** Du fügst über eine 120-Dateien-Codebasis hinweg Fehlerbehandlungs-Wrapper um externe API-Aufrufe hinzu. Die Arbeit hat drei Phasen: (1) alle Aufrufstellen und Muster ermitteln, (2) gemeinsam den Fehlerbehandlungsansatz entwerfen und (3) Wrapper einheitlich umsetzen. In Phase 1 erzeugt Claude große Ausgaben, die Hunderte von Aufrufstellen mit Kontext auflisten und das Kontextfenster füllen, bevor die Ermittlung abgeschlossen ist.

**Welcher Ansatz ist am wirksamsten, um die Aufgabe abzuschließen und dabei die Umsetzungskonsistenz zu wahren?**

- A) Einen Explore-Subagenten für Phase 1 verwenden, um die ausführliche Ermittlungsausgabe zu isolieren und eine Zusammenfassung zurückzugeben, dann die Phasen 2–3 im Hauptgespräch fortsetzen. **[RICHTIG]**
- B) Alle Phasen im Hauptgespräch durchführen und regelmäßig `/compact` verwenden, um den Kontextverbrauch beim Durchgehen der Dateien zu reduzieren.
- C) In den Headless-Modus mit `--continue` wechseln und zwischen Batch-Aufrufen explizite Kontextzusammenfassungen übergeben, um die Kontinuität zu wahren.
- D) Das Fehlerbehandlungsmuster in der CLAUDE.md definieren und die Dateien dann in Batches über mehrere Sitzungen verarbeiten und sich für die Konsistenz auf die gemeinsame Gedächtnisdatei verlassen.

**Warum A:** Ein Explore-Subagent isoliert die ausführliche Ermittlungsausgabe in einem separaten Kontext und gibt nur eine knappe Zusammenfassung an das Hauptgespräch zurück. Das bewahrt das Haupt-Kontextfenster für die Phasen des gemeinsamen Entwurfs und der konsistenten Umsetzung, in denen behaltener Kontext am wertvollsten ist.

---

## Szenario: Kundensupport-Agent

---

## Frage 46 (Szenario: Kundensupport-Agent)

**Situation:** Beim Testen bemerkst du, dass der Agent oft `get_customer` aufruft, wenn Nutzer nach dem Bestellstatus fragen, obwohl `lookup_order` angemessener wäre. Was solltest du zuerst prüfen, um dieses Problem zu adressieren?

**Was solltest du zuerst prüfen?**

- A) Einen Vorverarbeitungs-Klassifikator implementieren, der bestellbezogene Anfragen erkennt und direkt an `lookup_order` leitet.
- B) Die Anzahl der dem Agenten verfügbaren Tools reduzieren, um die Wahl zu vereinfachen.
- C) Dem System-Prompt Few-shot-Beispiele hinzufügen, die alle möglichen Muster bestellbezogener Anfragen abdecken, um die Tool-Auswahl zu verbessern.
- D) Die Tool-Beschreibungen prüfen, um sicherzustellen, dass sie den Zweck jedes Tools klar voneinander abgrenzen. **[RICHTIG]**

**Warum D:** Tool-Beschreibungen sind die primäre Eingabe, die das Modell zur Entscheidung nutzt, welches Tool aufzurufen ist. Wenn ein Agent durchgängig das falsche Tool wählt, ist der erste Diagnoseschritt, zu prüfen, ob die Tool-Beschreibungen den Zweck und die Anwendungsgrenzen jedes Tools klar trennen.

---

## Frage 47 (Szenario: Kundensupport-Agent)

**Situation:** Dein Agent bearbeitet Anfragen mit einem einzelnen Anliegen mit 94 % Genauigkeit (z. B. „I need a refund for order #1234"). Wenn Kunden aber mehrere Anliegen in einer Nachricht einbringen (z. B. „I need a refund for order #1234 and also want to update the shipping address for order #5678"), fällt die Genauigkeit der Tool-Auswahl auf 58 %. Der Agent löst meist nur ein Anliegen oder vermischt Parameter über Anfragen hinweg. Welcher Ansatz verbessert die Zuverlässigkeit bei Anfragen mit mehreren Anliegen am wirksamsten?

**Welcher Ansatz ist am wirksamsten?**

- A) Eine Vorverarbeitungsschicht implementieren, die über einen separaten Modellaufruf Mehrfach-Anliegen-Nachrichten in separate Anfragen zerlegt, jede unabhängig behandelt und die Ergebnisse zusammenführt.
- B) Verwandte Tools zu wenigen universellen Tools zusammenfassen.
- C) Dem Prompt Few-shot-Beispiele hinzufügen, die korrekte Argumentation und Tool-Reihenfolge für Anfragen mit mehreren Anliegen demonstrieren. **[RICHTIG]**
- D) Eine Antwortvalidierung implementieren, die unvollständige Antworten erkennt und den Agenten automatisch erneut auffordert, übersehene Anliegen zu lösen.

**Warum C:** Few-shot-Beispiele, die korrekte Argumentation und Tool-Reihenfolge für Anfragen mit mehreren Anliegen zeigen, sind am wirksamsten, weil der Agent bei einzelnen Anliegen bereits gut arbeitet — was er braucht, ist eine Anleitung für das Muster, mehrere Anliegen zu zerlegen und zu routen und Parameter getrennt zu halten.

---

## Frage 48 (Szenario: Kundensupport-Agent)

**Situation:** Produktions-Logs zeigen, dass dein Agent für einfache Anfragen wie „refund for order #1234" das Anliegen in 3–4 Tool-Aufrufen mit 91 % Erfolg löst. Für komplexe Anfragen wie „I was billed twice, my discount didn't apply, and I want to cancel" braucht der Agent im Schnitt 12+ Tool-Aufrufe mit nur 54 % Erfolg — er untersucht Anliegen oft nacheinander und ruft für jedes redundante Kundendaten ab. Welche Änderung verbessert die Behandlung komplexer Anfragen am wirksamsten?

**Welche Änderung ist am wirksamsten?**

- A) Explizite Verifikations-Checkpoints zwischen den Phasen hinzufügen, die vom Agenten verlangen, den Fortschritt nach dem Lösen jedes Anliegens festzuhalten, bevor er zum nächsten übergeht.
- B) Die Anzahl der Tools reduzieren, indem `get_customer`, `lookup_order` und abrechnungsbezogene Tools zu einem einzigen `investigate_issue`-Tool zusammengefasst werden.
- C) Die Anfrage in separate Anliegen zerlegen, jedes parallel unter Nutzung des gemeinsamen Kundenkontexts untersuchen und dann eine finale Lösung synthetisieren. **[RICHTIG]**
- D) Dem System-Prompt Few-shot-Beispiele hinzufügen, die ideale Tool-Aufruf-Sequenzen für verschiedene vielschichtige Abrechnungsszenarien demonstrieren.

**Warum C:** Die Zerlegung in separate Anliegen und die parallele Untersuchung mit gemeinsamem Kundenkontext behebt beide Kernprobleme: Sie eliminiert redundante Datenabrufe durch Wiederverwendung des gemeinsamen Kontexts über Anliegen hinweg und reduziert die Gesamtzahl der Tool-Aufruf-Schleifen, indem die Untersuchung parallelisiert wird, bevor eine einzige Lösung synthetisiert wird.

---

## Frage 49 (Szenario: Kundensupport-Agent)

**Situation:** Dein Agent erreicht 55 % Lösungsquote beim Erstkontakt, deutlich unter dem Ziel von 80 %. Die Logs zeigen, dass er einfache Fälle eskaliert (Standardaustausch bei beschädigter Ware mit Fotobeleg), während er komplexe Situationen, die Richtlinienausnahmen erfordern, autonom zu behandeln versucht. Was ist der wirksamste Weg, die Eskalationskalibrierung zu verbessern?

**Was ist der wirksamste Weg, die Eskalationskalibrierung zu verbessern?**

- A) Vom Agenten verlangen, vor jeder Antwort seine Konfidenz auf einer Skala von 1–10 selbst einzuschätzen und automatisch an Menschen zu routen, wenn die Konfidenz unter einen Schwellenwert fällt.
- B) Ein separates Klassifikatormodell einsetzen, das auf historischen Tickets trainiert wurde, um vor dem Start des Hauptagenten vorherzusagen, welche Anfragen eine Eskalation brauchen.
- C) Dem System-Prompt explizite Eskalationskriterien mit Few-shot-Beispielen hinzufügen, die zeigen, wann zu eskalieren und wann autonom zu lösen ist. **[RICHTIG]**
- D) Eine Stimmungsanalyse implementieren, um den Frustrationsgrad des Kunden zu bestimmen und ab einem negativen Stimmungs-Schwellenwert automatisch zu eskalieren.

**Warum C:** Explizite Eskalationskriterien mit Few-shot-Beispielen adressieren direkt die Ursache — unklare Entscheidungsgrenzen zwischen einfachen und komplexen Fällen. Es ist die verhältnismäßigste, wirksamste erste Maßnahme, die dem Agenten ohne zusätzliche Infrastruktur beibringt, wann zu eskalieren und wann autonom zu lösen ist.

---

## Frage 50 (Szenario: Kundensupport-Agent)

**Situation:** Nach dem Aufruf von `get_customer` und `lookup_order` hat der Agent alle verfügbaren Systemdaten, steht aber weiterhin vor Unsicherheit. Welche Situation ist der am besten gerechtfertigte Auslöser, `escalate_to_human` aufzurufen?

**Welche Situation rechtfertigt eine Eskalation am ehesten?**

- A) Ein Kunde möchte eine gestern versandte und morgen ankommende Bestellung stornieren. Der Agent sollte eskalieren, weil der Kunde nach Erhalt des Pakets seine Meinung ändern könnte.
- B) Ein Kunde behauptet, eine Bestellung nicht erhalten zu haben, aber das Tracking zeigt, dass sie vor drei Tagen an seiner Adresse zugestellt und unterschrieben wurde. Der Agent sollte eskalieren, weil das Vorlegen widersprüchlicher Belege die Kundenbeziehung schädigen könnte.
- C) Ein Kunde verlangt Preisanpassung an einen Wettbewerber. Deine Richtlinien erlauben Preisanpassungen bei Preissenkungen auf der eigenen Website innerhalb von 14 Tagen, sagen aber nichts zu Wettbewerberpreisen. Der Agent sollte zur Richtlinienauslegung eskalieren. **[RICHTIG]**
- D) Eine Kundennachricht enthält sowohl eine Abrechnungsfrage als auch eine Produktrücksendung. Der Agent sollte eskalieren, damit ein Mensch beide Anliegen in einer Interaktion koordinieren kann.

**Warum C:** Das ist eine echte Richtlinienlücke: Die Unternehmensregeln decken Preissenkungen auf der eigenen Website ab, sagen aber nichts zur Preisanpassung an Wettbewerber. Der Agent darf keine Richtlinie erfinden und sollte für ein menschliches Urteil eskalieren, wie bestehende Regeln auszulegen oder zu erweitern sind.

---

## Frage 51 (Szenario: Kundensupport-Agent)

**Situation:** Produktions-Logs zeigen, dass dein Agent in 12 % der Fälle `get_customer` überspringt und `lookup_order` direkt nur mit dem vom Kunden angegebenen Namen aufruft, was manchmal zu falsch identifizierten Konten und falschen Rückerstattungen führt. Welche Änderung behebt dieses Zuverlässigkeitsproblem am wirksamsten?

**Welche Änderung ist am wirksamsten?**

- A) Few-shot-Beispiele hinzufügen, die zeigen, dass der Agent immer zuerst `get_customer` aufruft, auch wenn Kunden freiwillig Bestelldetails angeben.
- B) Einen Routing-Klassifikator implementieren, der jede Anfrage analysiert und nur eine für diesen Anfragetyp passende Teilmenge der Tools aktiviert.
- C) Eine programmatische Vorbedingung hinzufügen, die `lookup_order` und `process_refund` blockiert, bis `get_customer` einen verifizierten Kundenidentifikator zurückgibt. **[RICHTIG]**
- D) Den System-Prompt verstärken und darin festhalten, dass die Kundenverifikation über `get_customer` vor jeder Bestelloperation zwingend ist.

**Warum C:** Eine programmatische Vorbedingung liefert eine deterministische Garantie, dass die geforderte Reihenfolge eingehalten wird. Es ist der wirksamste Ansatz, weil er die Möglichkeit, die Verifikation zu überspringen, ausschließt — unabhängig vom LLM-Verhalten.

---

## Frage 52 (Szenario: Kundensupport-Agent)

**Situation:** Produktionskennzahlen zeigen, dass bei komplexen Abrechnungsstreitigkeiten oder Rücksendungen über mehrere Bestellungen die Kundenzufriedenheitswerte 15 % niedriger sind als bei einfachen Fällen — selbst wenn die Lösung technisch korrekt ist. Die Ursachenanalyse zeigt, dass der Agent zwar zutreffende Lösungen liefert, die Begründung aber inkonsistent erklärt: mal fehlen relevante Richtliniendetails, mal Zeitplan-Infos oder nächste Schritte. Die konkreten Kontextlücken variieren von Fall zu Fall. Du möchtest die Lösungsqualität verbessern, ohne menschliche Aufsicht hinzuzufügen. Welcher Ansatz ist am wirksamsten?

**Welcher Ansatz ist am wirksamsten?**

- A) Eine Selbstkritik-Phase hinzufügen, in der der Agent einen Antwortentwurf auf Vollständigkeit prüft — er stellt sicher, dass er das Anliegen des Kunden löst, relevanten Kontext einbezieht und Folgefragen antizipiert. **[RICHTIG]**
- B) Eine Bestätigungsphase hinzufügen, in der der Agent vor dem Abschluss fragt „Does this fully resolve your issue?" und Kunden bei Bedarf zusätzliche Informationen anfordern können.
- C) Das Modell für komplexe Fälle von Haiku auf Sonnet aufwerten und anhand einer definierten Komplexitätskennzahl routen.
- D) Few-shot-Beispiele im System-Prompt umsetzen, die vollständige Erklärungen für fünf häufige komplexe Falltypen zeigen und demonstrieren, wie Richtlinienkontext, Zeitpläne und nächste Schritte einzubeziehen sind.

**Warum A:** Eine Selbstkritik-Phase (das Evaluator-Optimizer-Muster) adressiert direkt die inkonsistente Erklärungsvollständigkeit, indem sie den Agenten zwingt, seinen eigenen Entwurf vor der Präsentation an konkreten Kriterien zu messen — etwa Richtlinienkontext, Zeitplänen und nächsten Schritten. Das erfasst fallspezifische Lücken ohne menschliche Aufsicht.

---

## Frage 53 (Szenario: Kundensupport-Agent)

**Situation:** Produktionskennzahlen zeigen, dass dein Agent im Schnitt 4+ API-Schleifen pro Lösung braucht. Die Analyse zeigt, dass Claude `get_customer` und `lookup_order` oft in separaten aufeinanderfolgenden Turns anfordert, selbst wenn beide von Anfang an nötig sind. Was ist der wirksamste Weg, die Anzahl der Schleifen zu reduzieren?

**Was ist der wirksamste Weg, die Schleifen zu reduzieren?**

- A) Eine spekulative Ausführung implementieren, die wahrscheinlich benötigte Tools automatisch parallel zu jedem angeforderten Tool aufruft und alle Ergebnisse zurückgibt, unabhängig davon, was angefordert wurde.
- B) `max_tokens` erhöhen, um Claude mehr Raum zum Planen zu geben und Tool-Anfragen natürlich zu kombinieren.
- C) Zusammengesetzte Tools wie `get_customer_with_orders` erstellen, die häufige Abfragekombinationen in einzelnen Aufrufen bündeln.
- D) Claude im Prompt anweisen, Tool-Anfragen in einem Turn zu bündeln und alle Ergebnisse vor dem nächsten API-Aufruf gemeinsam zurückzugeben. **[RICHTIG]**

**Warum D:** Claude anzuweisen, verwandte Tool-Anfragen in einem einzigen Turn zu bündeln, nutzt seine native Fähigkeit, mehrere Tools auf einmal anzufordern. Es behebt das Muster der sequentiellen Aufrufe direkt mit minimaler architektonischer Änderung.

---

## Frage 54 (Szenario: Kundensupport-Agent)

**Situation:** Produktions-Logs zeigen ein Muster: Kunden beziehen sich auf konkrete Beträge (z. B. „the 15% discount I mentioned"), aber der Agent antwortet mit falschen Werten. Die Untersuchung zeigt, dass diese Details vor 20+ Turns erwähnt und zu vagen Zusammenfassungen wie „promotional pricing was discussed" verdichtet wurden. Welche Korrektur ist am wirksamsten?

**Welche Korrektur ist am wirksamsten?**

- A) Den Zusammenfassungs-Schwellenwert von 70 % auf 85 % erhöhen, damit Gespräche mehr Spielraum haben, bevor die Zusammenfassung ausgelöst wird.
- B) Den vollständigen Gesprächsverlauf in einem externen Speicher ablegen und einen Abruf umsetzen, wenn der Agent Bezüge wie „as I mentioned" erkennt.
- C) Transaktionsfakten (Beträge, Datumsangaben, Bestellnummern) in einen persistenten „Case-Facts"-Block extrahieren, der außerhalb des zusammengefassten Verlaufs in jeden Prompt eingebunden wird. **[RICHTIG]**
- D) Den Zusammenfassungs-Prompt überarbeiten, damit er alle Zahlen, Prozentsätze, Datumsangaben und vom Kunden genannten Erwartungen wortwörtlich bewahrt.

**Warum C:** Zusammenfassung verliert von Natur aus präzise Details. Transaktionsfakten in einen strukturierten „Case-Facts"-Block außerhalb des zusammengefassten Verlaufs zu extrahieren, bewahrt kritische Informationen, sodass sie in jedem Prompt zuverlässig verfügbar sind, egal wie viele Turns zusammengefasst wurden.

---

## Frage 55 (Szenario: Kundensupport-Agent)

**Situation:** Dein `get_customer`-Tool gibt bei der Suche nach Namen alle Treffer zurück. Aktuell wählt Claude bei mehreren Ergebnissen den Kunden mit der jüngsten Bestellung, aber Produktionsdaten zeigen, dass dies bei mehrdeutigen Treffern in 15 % der Fälle das falsche Konto auswählt. Wie solltest du das adressieren?

**Wie solltest du das adressieren?**

- A) Ein Konfidenz-Bewertungssystem implementieren, das ab 85 % Konfidenz autonom handelt und unterhalb des Schwellenwerts eine Klärung anfordert.
- B) Claude anweisen, bei mehreren Treffern von `get_customer` einen zusätzlichen Identifikator (E-Mail, Telefon oder Bestellnummer) anzufordern, bevor eine kundenspezifische Aktion erfolgt. **[RICHTIG]**
- C) `get_customer` so ändern, dass es nur einen einzigen wahrscheinlichsten Treffer anhand eines Ranking-Algorithmus zurückgibt und so die Mehrdeutigkeit eliminiert.
- D) Dem Prompt Few-shot-Beispiele hinzufügen, die korrekte Argumentation und Tool-Reihenfolge für mehrdeutige Treffer demonstrieren.

**Warum B:** Den Nutzer nach einem zusätzlichen Identifikator zu fragen, ist der zuverlässigste Weg, Mehrdeutigkeit aufzulösen, weil der Nutzer definitives Wissen über seine Identität hat. Ein zusätzlicher Gesprächs-Turn ist ein kleiner Preis, um eine 15-%-Fehlerrate durch die Wahl des falschen Kontos zu eliminieren.

---

## Frage 56 (Szenario: Kundensupport-Agent)

**Situation:** Produktions-Logs zeigen ein konsistentes Muster: Wenn Kunden das Wort „account" in ihrer Nachricht verwenden (z. B. „I want to check my account for an order I made yesterday"), ruft der Agent in 78 % der Fälle zuerst `get_customer` auf. Wenn Kunden ähnliche Anfragen ohne „account" formulieren (z. B. „I want to check an order I made yesterday"), ruft er in 93 % der Fälle zuerst `lookup_order` auf. Die Tool-Beschreibungen sind klar und eindeutig. Was ist die wahrscheinlichste Ursache dieser Diskrepanz?

**Was ist die wahrscheinlichste Ursache?**

- A) Der System-Prompt enthält schlüsselwortsensitive Anweisungen, die das Verhalten anhand von Begriffen wie „account" steuern und unbeabsichtigte Tool-Auswahlmuster erzeugen. **[RICHTIG]**
- B) Das Basistraining des Modells erzeugt Assoziationen zwischen „account"-Terminologie und kundenbezogenen Operationen, die die Tool-Beschreibungen überschreiben.
- C) Das Modell braucht mehr Trainingsdaten zu Nachrichten mit mehreren Konzepten und sollte auf Beispielen feinabgestimmt werden, die sowohl „account"- als auch „order"-Terminologie enthalten.
- D) Die Tool-Beschreibungen brauchen zusätzliche Negativbeispiele, die angeben, wann jedes Tool NICHT zu verwenden ist, um diese schlüsselwortinduzierte Verwirrung zu verhindern.

**Warum A:** Das systematische schlüsselwortgesteuerte Muster (78 % vs. 93 %) deutet stark auf explizite Routing-Logik im System-Prompt hin, die auf das Wort „account" reagiert und den Agenten zu kundenbezogenen Tools lenkt. Da die Tool-Beschreibungen bereits klar sind, weist die Diskrepanz auf Anweisungen auf Prompt-Ebene hin, die eine unbeabsichtigte Verhaltenssteuerung erzeugen.

---

## Frage 57 (Szenario: Kundensupport-Agent)

**Situation:** Produktions-Logs zeigen, dass der Agent oft `get_customer` aufruft, wenn Nutzer nach Bestellungen fragen (z. B. „check my order #12345"), statt `lookup_order` aufzurufen. Beide Tools haben minimale Beschreibungen („Gets customer information" / „Gets order details") und akzeptieren ähnlich aussehende Identifikatorformate. Was ist der wirksamste erste Schritt, um die Zuverlässigkeit der Tool-Auswahl zu verbessern?

**Was ist der wirksamste erste Schritt?**

- A) Eine Routing-Schicht implementieren, die die Nutzereingabe vor jedem Turn analysiert und das korrekte Tool anhand erkannter Schlüsselwörter und ID-Muster vorauswählt.
- B) Beide Tools zu einem einzigen `lookup_entity` zusammenfassen, das jeden Identifikator akzeptiert und intern entscheidet, welches Backend abzufragen ist.
- C) Dem System-Prompt Few-shot-Beispiele hinzufügen, die korrekte Tool-Auswahlmuster demonstrieren, mit 5–8 Beispielen, die bestellbezogene Anfragen an `lookup_order` leiten.
- D) Die Beschreibung jedes Tools um Eingabeformate, Beispielanfragen, Grenzfälle und Grenzen erweitern, die erklären, wann es statt ähnlicher Tools zu verwenden ist. **[RICHTIG]**

**Warum D:** Die Tool-Beschreibungen um Eingabeformate, Beispielanfragen, Grenzfälle und klare Grenzen zu erweitern, behebt direkt die Ursache — minimale Beschreibungen, die dem LLM nicht genug Informationen geben, um ähnliche Tools zu unterscheiden. Es ist ein erster Schritt mit geringem Aufwand und großer Wirkung, der den primären Mechanismus verbessert, den das LLM zur Tool-Auswahl nutzt.

---

## Frage 58 (Szenario: Kundensupport-Agent)

**Situation:** Du implementierst die Agentenschleife für deinen Support-Agenten. Nach jedem Claude-API-Aufruf musst du entscheiden, ob die Schleife fortgesetzt wird (angeforderte Tools ausführen und Claude erneut aufrufen) oder gestoppt wird (die finale Antwort dem Kunden präsentieren). Was bestimmt diese Entscheidung?

**Was bestimmt diese Entscheidung?**

- A) Das Feld `stop_reason` in Claudes Antwort prüfen — fortsetzen, wenn es `tool_use` ist, und stoppen, wenn es `end_turn` ist. **[RICHTIG]**
- B) Claudes Text auf Formulierungen wie „I'm done" oder „Can I help with anything else?" parsen — natürlichsprachliche Signale zeigen den Aufgabenabschluss an.
- C) Eine maximale Iterationszahl setzen (z. B. 10 Aufrufe) und beim Erreichen stoppen, unabhängig davon, ob Claude weitere Arbeit anzeigt.
- D) Prüfen, ob die Antwort Assistenten-Textinhalt enthält — wenn Claude erklärenden Text erzeugt hat, sollte die Schleife enden.

**Warum A:** `stop_reason` ist Claudes explizites strukturiertes Signal zur Schleifensteuerung: `tool_use` zeigt an, dass Claude ein Tool ausführen und die Ergebnisse zurückerhalten möchte, während `end_turn` anzeigt, dass Claude seine Antwort abgeschlossen hat und die Schleife enden sollte.

---

## Frage 59 (Szenario: Kundensupport-Agent)

**Situation:** Produktions-Logs zeigen, dass der Agent Ausgaben deiner MCP-Tools fehlinterpretiert: Unix-Zeitstempel von `get_customer`, ISO-8601-Datumsangaben von `lookup_order` und numerische Statuscodes (1=pending, 2=shipped). Einige Tools sind Drittanbieter-MCP-Server, die du nicht ändern kannst. Welcher Ansatz zur Datenformat-Normalisierung ist am wartbarsten?

**Welcher Ansatz ist am wartbarsten?**

- A) Einen PostToolUse-Hook verwenden, um Tool-Ausgaben abzufangen und Formatierungstransformationen anzuwenden, bevor der Agent sie verarbeitet. **[RICHTIG]**
- B) Die Tools, die du kontrollierst, so ändern, dass sie menschenlesbare Formate zurückgeben, und Wrapper für Drittanbieter-Tools erstellen.
- C) Ein `normalize_data`-Tool erstellen, das der Agent nach jedem Datenabruf aufruft, um Werte zu transformieren.
- D) Dem System-Prompt eine detaillierte Formatdokumentation hinzufügen, die die Datenkonventionen jedes Tools erklärt.

**Warum A:** Ein PostToolUse-Hook bietet einen zentralen, deterministischen Punkt, um alle Tool-Ausgaben — einschließlich Daten von Drittanbieter-MCP-Servern — abzufangen und zu normalisieren, bevor der Agent sie verarbeitet. Er ist wartbarer, weil die Transformationen im Code liegen und einheitlich angewendet werden, statt sich auf die LLM-Interpretation zu verlassen.

---

## Frage 60 (Szenario: Kundensupport-Agent)

**Situation:** Produktions-Logs zeigen, dass der Agent manchmal `get_customer` wählt, wenn `lookup_order` angemessener wäre, besonders bei mehrdeutigen Anfragen wie „I need help with my recent purchase". Du beschließt, dem System-Prompt Few-shot-Beispiele hinzuzufügen, um die Tool-Auswahl zu verbessern. Welcher Ansatz adressiert das Problem am wirksamsten?

**Welcher Ansatz ist am wirksamsten?**

- A) In jeder Tool-Beschreibung explizite „use when"- und „don't use when"-Anleitung hinzufügen, die mehrdeutige Fälle abdeckt.
- B) Beispiele nach Tool gruppiert hinzufügen — alle `get_customer`-Szenarien zusammen, dann alle `lookup_order`-Szenarien.
- C) 4–6 Beispiele hinzufügen, die auf mehrdeutige Szenarien abzielen, jeweils mit Begründung, warum ein Tool gegenüber plausiblen Alternativen gewählt wurde. **[RICHTIG]**
- D) 10–15 Beispiele klarer, eindeutiger Anfragen hinzufügen, die die korrekte Tool-Wahl für typische Szenarien jedes Tools demonstrieren.

**Warum C:** Few-shot-Beispiele gezielt auf die konkreten mehrdeutigen Szenarien auszurichten, in denen Fehler auftreten, mit expliziter Begründung, warum ein Tool Alternativen vorzuziehen ist, lehrt das Modell den vergleichenden Entscheidungsprozess, der für Grenzfälle nötig ist. Das ist wirksamer als generische Beispiele oder deklarative Regeln.

---

## Frage 61 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Dein `remove_team_member`-Tool nutzt einen Parameter `dry_run: boolean`, um Auswirkungen vor der Ausführung vorab anzuzeigen. Das Produktionsmonitoring zeigt, dass der Agent den Vorschau-Schritt umgeht, indem er direkt mit `dry_run=false` aufruft. Du musst sicherstellen, dass jeder Entfernung eine Vorschau vorausgeht, die der Nutzer ausdrücklich bestätigt.

**Was ist der zuverlässigste Ansatz?**

- A) Eine serverseitige Validierung hinzufügen, die `dry_run=false` nur zulässt, wenn innerhalb der letzten 60 Sekunden ein `dry_run=true`-Aufruf mit identischen Parametern erfolgt ist.
- B) Das Tool als bestätigungspflichtig annotieren und die Orchestrierungsschicht so konfigurieren, dass sie den Nutzer um Freigabe bittet, bevor Aufrufe an annotierte Tools weitergeleitet werden.
- C) Der Tool-Beschreibung detaillierte Anweisungen und Few-shot-Beispiele hinzufügen, die verlangen, dass der Agent immer zuerst mit `dry_run=true` aufruft und auf die Nutzerbestätigung wartet, bevor er erneut aufruft.
- D) Durch zwei Tools ersetzen: `preview_remove_member` gibt Auswirkungsdetails und einen Einmal-Bestätigungstoken zurück; `execute_remove_member` erfordert diesen Token und bindet die Ausführung an die Vorschau. **[RICHTIG]**

**Warum D:** Der Zwei-Tool-Token-Bindungsansatz macht es architektonisch unmöglich, ohne vorherige Vorschau auszuführen — das Ausführungs-Tool erfordert buchstäblich einen Token, den nur das Vorschau-Tool erzeugen kann. Das ist der einzige Ansatz, der die Beschränkung auf Code-Ebene erzwingt, statt sich auf LLM-Befolgung von Anweisungen (C), Zeit-Heuristiken (A) oder Orchestrierungsinfrastruktur (B) zu verlassen.

---

## Frage 62 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Das Produktionsmonitoring zeigt, dass dein `search_catalog`-Tool in 12 % der Fälle fehlschlägt: 8 % sind Netzwerk-Timeouts, die bei einem Retry gelingen, und 4 % sind Abfrage-Syntaxfehler, die unabhängig von Retries nie gelingen. Aktuell werden beide Fehlertypen identisch zurückgegeben, was verschwendete Retries verursacht.

**Wie solltest du die Fehlerbehandlung des Tools ändern?**

- A) Dem System-Prompt Few-shot-Beispiele hinzufügen, die demonstrieren, wie Netzwerkfehler von Syntaxfehlern zu unterscheiden sind.
- B) Retry-Logik mit exponentiellem Backoff einheitlich auf alle Fehler anwenden.
- C) Automatischen Retry mit Backoff für Netzwerk-Timeouts innerhalb des Tools umsetzen; Syntaxfehler sofort mit Details zur Parametervalidierung zurückgeben. **[RICHTIG]**
- D) Alle Fehler mit einem booleschen `retryable`-Flag und Fehlertyp-Details zurückgeben.

**Warum C:** Retries auf Tool-Ebene für transiente Fehler zu behandeln, ist die korrekte Abstraktionsgrenze — das Tool hat definitives Wissen über den Fehlertyp und kann deterministische Retry-Logik umsetzen, ohne sich darauf zu verlassen, dass der Agent ein Flag interpretiert (D) oder Anweisungen auf Prompt-Ebene befolgt (A). Einheitlicher Backoff (B) verschwendet Zeit bei Syntaxfehlern, die nie gelingen werden.

---

## Frage 63 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Im Verlauf mehrerer Turns zur Anlagestrategie hat ein Nutzer gesagt „I have a very low risk tolerance" und später „I want to maximize my returns". Nun fragt er: „What should I invest in?"

**Welcher Ansatz stellt am besten sicher, dass die Empfehlung der tatsächlichen Priorität des Nutzers entspricht?**

- A) Den Widerspruch benennen und den Nutzer klären lassen, was ihm wichtiger ist. **[RICHTIG]**
- B) Separate Empfehlungen für beide Szenarien geben.
- C) Mit der zuletzt geäußerten Präferenz fortfahren.
- D) Ein ausgewogenes Portfolio empfehlen, ohne den Konflikt anzusprechen.

**Warum A:** Wenn Nutzerpräferenzen einander direkt widersprechen, ist das Benennen des Konflikts und die Bitte um Klärung der einzige Weg, zu garantieren, dass die Empfehlung der wahren Absicht des Nutzers entspricht. Jeder andere Ansatz beinhaltet eine Annahme, die falsch sein kann — Renditemaximierung und geringe Risikotoleranz sind grundlegend unvereinbare Ziele, die eine menschliche Entscheidung erfordern.

---

## Frage 64 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Nutzer verfeinern Playlist-Präferenzen über mehrere Gesprächs-Turns. Zwei Nachrichten nachdem ein Nutzer „I love jazz" gesagt hat, fragt Claude „What genres do you enjoy?"

**Was ist die wahrscheinlichste Ursache?**

- A) Claude benötigt eine Vektordatenbank-Verbindung, um das Gesprächsgedächtnis zu halten.
- B) Das Kontextfenster des Modells wurde überschritten.
- C) Die Claude API erfordert einen `session_id`-Parameter.
- D) Deine Anwendung nimmt vorherige Nachrichten nicht in das `messages`-Array auf. **[RICHTIG]**

**Warum D:** Claude hat kein serverseitiges Gedächtnis — jeder API-Aufruf ist zustandslos. Ohne den vollständigen Gesprächsverlauf im `messages`-Array jeder Anfrage hat Claude kein Wissen über vorherige Turns. Vektordatenbanken (A) und `session_id` (C) sind nicht Teil von Claudes Architektur; ein Überlauf des Kontextfensters (B) ist bei einem Austausch von zwei Nachrichten unmöglich.

---

## Frage 65 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Nach einer 40-minütigen Koch-Sitzung erreicht das Gespräch 78.000 Tokens. Der Verlauf umfasst Allergien, Rezeptskalierung, geklärte Kochbegriffe und allgemeine Diskussion. Du musst Tokens reduzieren und dabei wichtige Informationen bewahren.

**Welcher Ansatz wägt Bewahrung und Token-Reduktion am besten ab?**

- A) Den gesamten Gesprächsverlauf zusammenfassen.
- B) Nur die jüngsten 20.000 Tokens behalten.
- C) Kritische strukturierte Daten (Allergien, Mengen, Präferenzen) extrahieren, die allgemeine Diskussion zusammenfassen und jüngste Austausche wortwörtlich behalten. **[RICHTIG]**
- D) Das vollständige Gespräch extern ablegen und relevante Teile per semantischer Suche abrufen.

**Warum C:** Der hybride Ansatz bewahrt die wertvollsten Informationen zu den geringsten Kosten. Kritische Fakten wie Allergien und Rezeptmengen werden in einen kompakten strukturierten Block extrahiert (was den Präzisionsverlust bei der Zusammenfassung verhindert), die allgemeine Diskussion wird zusammengefasst, und jüngste Austausche bleiben für die Gesprächskohärenz wortwörtlich. Die Optionen A und B riskieren den Verlust kritischer Ernährungsinformationen; D ist für eine einzelne Koch-Sitzung architektonisch überzogen.

---

## Frage 66 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Nutzer berichten, dass der Assistent bei längeren Gesprächen frühere Themen und Präferenzen aus den Augen verliert. Deine aktuelle Umsetzung behält nur die letzten 25 Nachrichtenpaare.

**Was ist die wirksamste Lösung?**

- A) Hybrider Ansatz: ältere Nachrichten zusammenfassen und jüngste wortwörtlich behalten. **[RICHTIG]**
- B) Vektorähnlichkeitssuche über den vollständigen Gesprächsverlauf.
- C) Das Fenster auf 50 Nachrichtenpaare erhöhen.
- D) Verworfene Nachrichten in jedem Turn zusammenfassen und die laufende Zusammenfassung voranstellen.

**Warum A:** Der hybride Ansatz adressiert beide Dimensionen des Problems: Er behält den exakten jüngsten Kontext (kritisch für die Gesprächskohärenz) und hält zugleich eine komprimierte Darstellung früherer Präferenzen (was den Totalverlust beim Verwerfen von Paaren verhindert). Das Fenster zu vergrößern (C) verschiebt dasselbe Problem nur. Vektorsuche (B) kann wichtigen Kontext verfehlen, der der aktuellen Anfrage nicht semantisch ähnlich ist. Vollständige Zusammenfassung pro Turn (D) erzeugt Overhead und häuft Zusammenfassungsfehler an.

---

## Frage 67 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Nutzer berichten, dass Latenz und Kosten steigen, wenn Gespräche 50 Turns überschreiten.

**Was ist die primäre Ursache?**

- A) Der gesamte Gesprächsverlauf wird bei jeder API-Anfrage mitgesendet. **[RICHTIG]**
- B) Das Modell erzeugt zunehmend längere Antworten.
- C) Datenbankoperationen werden langsamer, wenn der Verlauf wächst.
- D) Das Modell baut ein internes Nutzerprofil auf, das mehr Verarbeitung erfordert.

**Warum A:** Claudes API ist vollständig zustandslos — jede Anfrage muss den kompletten Gesprächsverlauf im `messages`-Array enthalten. Mit wachsenden Gesprächen trägt jede Anfrage mehr Tokens, was sowohl Verarbeitungslatenz als auch Kosten direkt erhöht. Das Modell hält keinen internen Zustand zwischen Aufrufen (D ist falsch), und die Antwortlänge ist nicht inhärent an die Gesprächslänge gebunden (B).

---

## Frage 68 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Nach drei Monaten wöchentlicher Sitzungen wächst der Gesprächsverlauf auf 85.000 Tokens. Wenn ein Nutzer fragt „What did we conclude about the theme of isolation?", gibt der Assistent generische Antworten, statt auf frühere Diskussionen zu verweisen.

**Was ist der wirksamste Ansatz?**

- A) Rollierende Fenster-Kürzung.
- B) Fortlaufende Zusammenfassung, die Schlüssel-Schlussfolgerungen erfasst.
- C) Semantische Embeddings mit Abruf relevanter Austausche. **[RICHTIG]**
- D) Strukturierte XML-Tags hinzufügen, die Diskussions-Schlussfolgerungen markieren.

**Warum C:** Semantische Suche über den Gesprächsverlauf ist der einzige Ansatz, der auf drei Monate Diskussion skaliert und zugleich bei Bedarf konkrete relevante Austausche zutage fördern kann. Ein rollierendes Fenster (A) würde den Großteil des Verlaufs verwerfen. Fortlaufende Zusammenfassung (B) komprimiert Diskussionen zu Abstraktionen, die genau die konkreten Schlussfolgerungen verlieren, nach denen Nutzer fragen. XML-Tags (D) erfordern die Umstrukturierung aller vergangenen Inhalte und lösen das Abrufproblem in dieser Größenordnung nicht.

---

## Frage 69 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Beim QA-Test befolgt Claude die System-Prompt-Richtlinien für die ersten 10–15 Turns, aber spätere Antworten weichen ab. Das Gespräch liegt noch innerhalb der Token-Limits.

**Was ist die beste Lösung?**

- A) Die Verhaltensrichtlinien in die erste Nutzernachricht verschieben.
- B) Nach 20 Turns ein neues Gespräch beginnen.
- C) Nachrichten mit der Rolle `user` einfügen, die die Richtlinien an Gesprächs-Bruchpunkten verstärken. **[RICHTIG]**
- D) Eine Validierung nach der Antwort verwenden, um nicht konforme Antworten neu zu generieren.

**Warum C:** Das periodische Einfügen von Verhaltenserinnerungen bekämpft Instruktionsabweichung direkt, indem es die Beschränkungen in regelmäßigen Abständen neu etabliert, während sich der Gesprächsverlauf anhäuft. Die Richtlinien in die erste Nutzernachricht zu verschieben (A) mindert ihre Autorität. Ein neues Gespräch zu beginnen (B) zerstört den Kontext. Validierung nach der Antwort (D) ist korrigierend statt vorbeugend und fügt erhebliche Latenz hinzu.

---

## Frage 70 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Dein KI-Tutor hat einen 2.800-Token-System-Prompt, der die Lehrmethodik und Anpassungsregeln definiert. Nach 12 Turns beginnt der Assistent, Kompetenzstufen zu ignorieren.

**Was ist die wirksamste Korrektur?**

- A) Alle 4–5 Turns Erinnerungen einfügen.
- B) Die ausführlichen Regeln durch Few-shot-Beispiele ersetzen, die die Anpassung an die Kompetenzstufe demonstrieren. **[RICHTIG]**
- C) Kritische Regeln an das Ende des System-Prompts stellen.
- D) Antworten bewerten und neu generieren, wenn die Schwierigkeitsstufe nicht passt.

**Warum B:** Ein 2.800-Token-System-Prompt mit deklarativen Regeln ist anfällig für Abweichung, weil abstrakte Regeln vom Modell verlangen, in jedem Turn über sie nachzudenken. Die ausführlichen Regeln durch konkrete Few-shot-Beispiele zu ersetzen, die die korrekte Anpassung an die Kompetenzstufe zeigen, gibt dem Modell klare Verhaltensmuster zum Nachahmen — das wird über viele Turns zuverlässiger befolgt als abstrakte Anweisungen. Das Einfügen von Erinnerungen (A) hilft, adressiert aber Symptome; die Platzierung am Ende (C) hilft anfangs, aber nicht gegen die Abweichung auf Turn-Ebene; Neugenerierung (D) ist teuer und korrigierend.

---

## Frage 71 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Dein Assistent muss einen enthusiastischen Ton wahren, seine Argumentation erklären und klärende Fragen stellen. Wo sollten diese Verhaltensrichtlinien definiert werden?

**Wo sollten diese Verhaltensrichtlinien definiert werden?**

- A) Jeder Nutzernachricht vorangestellt.
- B) Im System-Prompt. **[RICHTIG]**
- C) In der ersten Assistenten-Nachricht.
- D) In Umgebungsvariablen.

**Warum B:** Der System-Prompt ist speziell für persistente Verhaltensbeschränkungen und Richtlinien konzipiert, die im gesamten Gespräch gelten. Jeder Nutzernachricht voranzustellen (A) ist redundanter Overhead. Die erste Assistenten-Nachricht (C) ist unzuverlässig, weil das Modell von seinen eigenen früheren Aussagen abweichen kann. Umgebungsvariablen (D) haben keinen Einfluss auf das Modellverhalten.

---

## Frage 72 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Nutzer berichten von sich wiederholenden Antwort-Einleitungen wie „Certainly!" und „I'd be happy to help!"

**Was ist der wirksamste Ansatz?**

- A) Eine partielle Assistenten-Nachricht mit einer direkten Antwort-Einleitung anhängen. **[RICHTIG]**
- B) Die Temperatur-Einstellung senken.
- C) Antworten nachbearbeiten, um Begrüßungen zu entfernen.
- D) System-Prompt-Anweisungen hinzufügen, diese Formulierungen zu vermeiden.

**Warum A:** Das Vorbefüllen der Assistenten-Antwort mit dem Anfang einer direkten Antwort verhindert Begrüßungsmuster auf Generierungsebene — das Modell setzt beim Prefill fort, statt neue Einleitungsformulierungen zu erzeugen. System-Prompt-Anweisungen (D) können helfen, sind aber weniger zuverlässig, da das Modell weiterhin Varianten produzieren kann. Nachbearbeitung (C) ist eine fragile Behelfslösung. Die Temperatur (B) steuert Zufälligkeit, nicht spezifische Formulierungsmuster.

---

## Frage 73 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Ein Webhook meldet deinem System, dass das Paket eines Nutzers versandt wurde, während der Nutzer aktiv chattet. Du möchtest, dass der Assistent das natürlich in die nächste Antwort einbezieht.

**Was ist der beste Ansatz?**

- A) Den Versandstatus dem System-Prompt hinzufügen.
- B) Eine sofortige synthetische Nutzernachricht senden.
- C) Den Assistenten zwingen, in jedem Turn ein Status-Tool aufzurufen.
- D) Die Statusaktualisierung als Präfix an die nächste Nutzernachricht anhängen. **[RICHTIG]**

**Warum D:** Die Statusaktualisierung der nächsten Nutzernachricht voranzustellen, injiziert Echtzeit-Kontext an einer natürlichen Gesprächsgrenze, ohne den Fluss zu stören. Den System-Prompt zu ändern (A) erfordert einen Neuaufbau der Sitzung oder ist architektonisch umständlich. Eine synthetische Nutzernachricht (B) kann den natürlichen Dialogfluss brechen und die Zuordnung verwirren. In jedem Turn einen Tool-Aufruf zu erzwingen (C) ist verschwenderisch, wenn Ereignisse selten sind.

---

## Frage 74 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Nutzer senden häufig Anfragen wie „Book a venue for the party". Der Assistent stellt 4+ klärende Fragen, was zu 35 % Abbruch führt.

**Welcher Ansatz verbessert die Abwägung am besten?**

- A) Mit versteckten Standardwerten fortfahren.
- B) Alle klärenden Fragen in einer zusammengesetzten Nachricht stellen.
- C) Annahmen explizit benennen und fortfahren, dabei zu Korrekturen einladen. **[RICHTIG]**
- D) Ein strukturiertes Aufnahmeformular verwenden.

**Warum C:** Annahmen explizit zu benennen und fortzufahren, gibt dem Nutzer eine sofortige, nützliche Antwort und bewahrt zugleich seine Möglichkeit, falsche Annahmen zu korrigieren. Versteckte Standardwerte (A) lassen den Nutzer im Unklaren darüber, was angenommen wurde. Eine zusammengesetzte Frageliste (B) verlangt dem Nutzer weiterhin Vorabaufwand ab. Ein strukturiertes Formular (D) fügt mehr Reibung hinzu, nicht weniger — im Widerspruch zum Ziel, Abbrüche zu reduzieren.

---

## Frage 75 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Dein Assistent nutzt einen System-Prompt mit Handwerker-Persona. Frühe Turns folgen den Regeln, aber ab Turn 7 gibt der Assistent generische Ratschläge. Die Gesprächslänge beträgt nur 2.500 Tokens.

**Was ist die wahrscheinlichste Ursache?**

- A) System-Prompts etablieren nur das anfängliche Verhalten.
- B) Die Modellaufmerksamkeit schwächt sich ab, während sich Turns anhäufen.
- C) Angehäufte Assistenten-Antworten verdünnen den Einfluss des System-Prompts. **[RICHTIG]**
- D) Der System-Prompt wird nur einmal gesendet.

**Warum C:** Während sich Assistenten-Antworten im Gesprächsverlauf anhäufen, sinkt der Anteil des Textes, der die Verhaltensbeschränkungen des System-Prompts widerspiegelt, relativ zum wachsenden Umfang assistentengenerierten Inhalts. Das Modell gleicht sich zunehmend an seine eigenen früheren Ausgaben an statt an den System-Prompt, was die Abweichung selbst bei kurzer Token-Länge verstärkt. Der System-Prompt wird bei jedem API-Aufruf mitgesendet (D ist als alleinige Erklärung falsch), und ein Abbau der Modellaufmerksamkeit (B) tritt bei 2.500 Tokens nicht auf.

---

## Frage 76 (Szenario: Architekturmuster für dialogbasierte KI)

**Situation:** Nutzer stellen vage Anfragen wie „Can you help with the report?". Der Assistent antwortet, indem er mehrere Fragen stellt (welcher Bericht? welche Hilfe? Frist?), was zu 40 % Abbruch führt.

**Was ist die beste Lösung?**

- A) Vernünftige Annahmen treffen, sie explizit benennen und anbieten, sie anzupassen. **[RICHTIG]**
- B) Die Mehrdeutigkeit mit einem kleineren Modell klassifizieren, bevor geantwortet wird.
- C) Vordefinierte Interpretationen verwenden, ohne Annahmen zu benennen.
- D) Den Assistenten auf eine klärende Frage pro Turn beschränken.

**Warum A:** Mit vernünftigen, benannten Annahmen fortzufahren, eliminiert das Hin und Her vollständig und hält den Nutzer zugleich informiert und in Kontrolle. Vordefinierte stille Interpretationen (C) lassen Nutzer verwirrt zurück, wenn die Antwort nicht ihrer Absicht entspricht. Ein Ein-Frage-Limit (D) erfordert weiterhin Turns des Hin und Her. Ein kleineres Klassifikationsmodell (B) fügt Latenz und Infrastrukturkomplexität hinzu, ohne das UX-Kernproblem zu lösen.

---

# Praktische Übungen

## Übung 1: Multi-Tool-Agent mit Eskalationslogik

**Ziel:** Eine Agentenschleife mit Tool-Integration, strukturierter Fehlerbehandlung und Eskalation entwerfen.

**Schritte:**
1. 3–4 MCP-Tools mit detaillierten Beschreibungen definieren (zwei ähnliche Tools einbauen, um die Tool-Auswahl zu testen)
2. Eine Agentenschleife implementieren, die `stop_reason` prüft (`"tool_use"` / `"end_turn"`)
3. Strukturierte Fehlerantworten hinzufügen: `errorCategory`, `isRetryable`, Beschreibung
4. Einen Abfang-Hook implementieren, der Operationen über einem Schwellenwert blockiert und auf Eskalation umleitet
5. Mit mehrteiligen Anfragen testen

**Domänen:** 1 (Agentenarchitektur), 2 (Tools und MCP), 5 (Kontext und Zuverlässigkeit)

---

## Übung 2: Claude Code für die Teamentwicklung konfigurieren

**Ziel:** CLAUDE.md, benutzerdefinierte Befehle, pfadspezifische Regeln und MCP-Server konfigurieren.

**Schritte:**
1. Eine CLAUDE.md auf Projektebene mit universellen Standards erstellen
2. `.claude/rules/`-Dateien mit YAML-Frontmatter für verschiedene Codebereiche erstellen (`paths: ["src/api/**/*"]`, `paths: ["**/*.test.*"]`)
3. Einen Projekt-Skill unter `.claude/skills/` mit `context: fork` und `allowed-tools` erstellen
4. Einen MCP-Server in `.mcp.json` mit Umgebungsvariablen konfigurieren + eine persönliche Überschreibung in `~/.claude.json`
5. Planungsmodus vs. direkte Ausführung an Aufgaben unterschiedlicher Komplexität testen

**Domänen:** 3 (Claude-Code-Konfiguration), 2 (Tools und MCP)

---

## Übung 3: Pipeline zur strukturierten Datenextraktion

**Ziel:** JSON-Schemas, `tool_use` für strukturierte Ausgabe, Validierungs-/Retry-Schleifen, Batch-Verarbeitung.

**Schritte:**
1. Ein Extraktions-Tool mit einem JSON-Schema definieren (Pflicht-/optionale Felder, Enums mit „other", Nullable-Felder)
2. Eine Validierungsschleife aufbauen: bei einem Fehler Retry mit dem Dokument, der fehlerhaften Extraktion und dem spezifischen Validierungsfehler
3. Few-shot-Beispiele für Dokumente mit unterschiedlichen Strukturen hinzufügen
4. Batch-Verarbeitung über die Message Batches API nutzen: 100 Dokumente, Fehlschläge über `custom_id` behandeln
5. An Menschen routen: Konfidenzwerte auf Feldebene, Analyse nach Dokumenttyp

**Domänen:** 4 (Prompt Engineering), 5 (Kontext und Zuverlässigkeit)

---

## Übung 4: Eine Multi-Agenten-Recherche-Pipeline entwerfen und debuggen

**Ziel:** Subagenten-Orchestrierung, Kontextübergabe, Fehlerweitergabe, Synthese mit Quellenverfolgung.

**Schritte:**
1. Einen Koordinator mit 2+ Subagenten (`allowedTools` enthält `"Task"`, Kontext wird explizit in Prompts übergeben)
2. Subagenten parallel über mehrere `Task`-Aufrufe in einer einzigen Antwort ausführen
3. Strukturierte Subagenten-Ausgabe verlangen: Aussage, Zitat, Quellen-URL, Veröffentlichungsdatum
4. Einen Subagenten-Timeout simulieren: strukturierten Fehlerkontext an den Koordinator zurückgeben und mit Teilergebnissen weitermachen
5. Mit widersprüchlichen Daten testen: beide Werte mit Attribution bewahren; bestätigte von umstrittenen Befunden trennen

**Domänen:** 1 (Agentenarchitektur), 2 (Tools und MCP), 5 (Kontext und Zuverlässigkeit)

---

# Anhang: Technologien und Konzepte

| Technologie | Kernaspekte |
|---|---|
| **Claude Agent SDK** | AgentDefinition, Agentenschleifen, `stop_reason`, Hooks (PostToolUse), Starten von Subagenten über Task, `allowedTools` |
| **Model Context Protocol (MCP)** | MCP-Server, Tools, Resources, `isError`, Tool-Beschreibungen, `.mcp.json`, Umgebungsvariablen |
| **Claude Code** | CLAUDE.md-Hierarchie, `.claude/rules/` mit Glob-Mustern, `.claude/commands/`, `.claude/skills/` mit SKILL.md, Planungsmodus, `/compact`, `--resume`, `fork_session` |
| **Claude Code CLI** | `-p` / `--print` für den nicht-interaktiven Modus, `--output-format json`, `--json-schema` |
| **Claude API** | `tool_use` mit JSON-Schemas, `tool_choice` ("auto"/"any"/erzwungen), `stop_reason`, `max_tokens`, System-Prompts |
| **Message Batches API** | 50 % Ersparnis, Fenster bis zu 24 Stunden, `custom_id`, kein mehrschrittiges Tool-Calling |
| **JSON Schema** | Pflicht vs. optional, Nullable-Felder, Enum-Typen, "other" + Detail, strikter Modus |
| **Pydantic** | Schema-Validierung, semantische Fehler, Validierungs-/Retry-Schleifen |
| **Integrierte Tools** | Read, Write, Edit, Bash, Grep, Glob — Zweck und Auswahlkriterien |
| **Few-shot-Prompting** | Gezielte Beispiele für mehrdeutige Situationen, Verallgemeinerung auf neue Muster |
| **Prompt Chaining** | Sequentielle Zerlegung in fokussierte Durchläufe |
| **Kontextfenster** | Token-Budgets, fortlaufende Zusammenfassung, „lost in the middle", Scratchpad-Dateien |
| **Sitzungsverwaltung** | Resume, `fork_session`, benannte Sitzungen, Kontextisolierung |
| **Konfidenzkalibrierung** | Bewertung auf Feldebene, Kalibrierung auf gelabelten Datensätzen, geschichtete Stichproben |

---

# Nicht prüfungsrelevante Themen

Die folgenden angrenzenden Themen kommen in der Prüfung **NICHT** vor:

- Fine-Tuning von Claude-Modellen oder Training eigener Modelle
- Authentifizierung, Abrechnung oder Kontoverwaltung der Claude API
- Detaillierte Implementierung in bestimmten Programmiersprachen oder Frameworks (über das für die Tool-/Schema-Konfiguration Nötige hinaus)
- Bereitstellen oder Hosten von MCP-Servern (Infrastruktur, Netzwerk, Container-Orchestrierung)
- Claudes interne Architektur, Trainingsprozess oder Modellgewichte
- Constitutional AI, RLHF oder Methoden des Safety-Trainings
- Embedding-Modelle oder Implementierungsdetails von Vektordatenbanken
- Computer Use (Browser-Automatisierung, Desktop-Interaktion)
- Bildanalyse-Fähigkeiten (Vision)
- Streaming-API oder Server-Sent Events
- Rate-Limiting, Kontingente oder detaillierte API-Kostenberechnungen
- OAuth, API-Key-Rotation oder Details von Authentifizierungsprotokollen
- Cloud-provider-spezifische Konfigurationen (AWS, GCP, Azure)
- Performance-Benchmarks oder Kennzahlen zum Modellvergleich
- Implementierungsdetails von Prompt-Caching (über das Wissen, dass es existiert, hinaus)
- Token-Zählalgorithmen oder Tokenisierungs-Details

---

# Empfehlungen zur Vorbereitung

1. **Baue einen Agenten mit dem Claude Agent SDK** — implementiere eine vollständige Agentenschleife mit Tool-Calling, Fehlerbehandlung und Sitzungsverwaltung. Übe Subagenten und die explizite Kontextübergabe.

2. **Konfiguriere Claude Code für ein echtes Projekt** — nutze die CLAUDE.md-Hierarchie, pfadspezifische Regeln in `.claude/rules/`, Skills mit `context: fork` und `allowed-tools` sowie die MCP-Server-Integration.

3. **Entwirf und teste MCP-Tools** — schreibe Beschreibungen, die ähnliche Tools abgrenzen, gib strukturierte Fehler mit Kategorien und Retry-Flags zurück und teste gegen mehrdeutige Nutzeranfragen.

4. **Baue eine Datenextraktions-Pipeline** — nutze `tool_use` mit JSON-Schemas, Validierungs-/Retry-Schleifen, optionale/Nullable-Felder und Batch-Verarbeitung über die Message Batches API.

5. **Übe Prompt Engineering** — füge Few-shot-Beispiele für mehrdeutige Szenarien, explizite Review-Kriterien und Mehrfach-Durchlauf-Architekturen für große Code-Reviews hinzu.

6. **Studiere Muster der Kontextverwaltung** — extrahiere Fakten aus ausführlichen Ausgaben, nutze Scratchpad-Dateien und delegiere die Erkundung an Subagenten, um Kontextlimits zu bewältigen.

7. **Verstehe Eskalation und Human-in-the-Loop** — wann zu eskalieren ist (Richtlinienlücken, ausdrückliche Nutzeranfrage, Unfähigkeit voranzukommen) und konfidenzbasierte Routing-Workflows.

8. **Mache vor der echten Prüfung eine Übungsprüfung.** Sie verwendet dieselben Szenarien und dasselbe Format.

