# Christoph Ludwig genannt Grosse

## Applied AI & Agent Systems Engineer

Ich entwerfe und implementiere KI-Systeme, die auch unter realen Bedingungen verständlich bleiben: auf Edge-Hardware, bei lokaler Ausführung, wechselnden Zuständen, Modellfehlern und der Notwendigkeit, Abläufe nachträglich erklären zu können.

Mein Schwerpunkt liegt auf prüfbarer und testbarer Entwicklung: deterministische Agenten-Orchestrierung, lokale Edge-KI, Datenpipelines mit Herkunftsnachweisen, Sicherheitsgrenzen und Verifikationswerkzeuge.

Meine Arbeit verbindet angewandte KI mit ernsthaftem Systems Engineering:

- deterministische Control Planes für KI-Agenten
- Datenaufbereitung und Trainingsworkflows mit Provenienz
- lokale LLM-Laufzeitarchitektur und explizite Sicherheitsgrenzen
- hardwareunabhängige Sprachassistenten-Architektur
- reproduzierbare Tests, Receipts, Zustandswechsel und Wiederanlaufpfade

## Ausgewählte Projekte

| Projekt | Was es zeigt |
|---|---|
| [Optimismus Prime](https://github.com/Chappie-2Pac/optimismus-prime) | SQLite-CAS-Zustandswechsel, Lease Fencing, deterministisches Dispatching, Receipts, Replay-Behandlung und Recovery |
| [Chappie](https://github.com/Chappie-2Pac/chappie-public) · [Release v1.0.0](https://github.com/Chappie-2Pac/chappie-public/releases/tag/v1.0.0) | Provenienzorientierte Datenaufbereitung, deterministische Teaching Units, Qualitätsgates und Unsloth/QLoRA-Trainingsorchestrierung |
| [Seniorbot](https://github.com/Chappie-2Pac/seniorbot) | ASR → Dialog → lokales LLM → TTS mit austauschbaren Adaptern und begrenztem Zustand |

Chappie verbindet seinen Orchestrierungskern mit einer integrierten `custom-llm-lab`-Datenaufbereitung: Quellenextraktion, Provenienz, Chunking, Teaching-Unit-Erzeugung, Validierung, Review und Export führen in einen GPU-orientierten Unsloth/QLoRA-Trainingspfad. Das öffentliche Repository zeigt die reproduzierbare Engineering-Oberfläche; private Datensätze, Modellgewichte und Laufzeitartefakte bleiben außerhalb des öffentlichen Snapshots.

## Verifikation

- [![Optimismus Prime CI](https://github.com/Chappie-2Pac/optimismus-prime/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Chappie-2Pac/optimismus-prime/actions/workflows/ci.yml) Vollständige Control-Plane-Testsuite: lokal 1.180 Tests und 1.216 Subtests verifiziert
- [![Chappie CI](https://github.com/Chappie-2Pac/chappie-public/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Chappie-2Pac/chappie-public/actions/workflows/ci.yml) 107 Offline-Tests, Package-Build und öffentlicher Import-Smoke-Test
- [![Seniorbot CI](https://github.com/Chappie-2Pac/seniorbot/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Chappie-2Pac/seniorbot/actions/workflows/ci.yml) Testmatrix für Python 3.10–3.12

## So entwickle ich KI-Systeme

1. Zustände, Verträge und Fehlerbilder definieren, bevor Modellfunktionen ergänzt werden.
2. Provenienz und Nachweise nahe an Daten und Ausführung halten.
3. Sicherheitsentscheidungen explizit im Code abbilden, statt auf Prompt-Konventionen zu vertrauen.
4. Test-Harness und Wiederanlaufpfad als Teil des Features bauen.
5. Wiederverwendbare Engineering-Komponenten von hardware-, daten- und deploymentspezifischem Betrieb trennen.

## Kerntechnologien

Python · POSIX Shell · SQLite · Git · Linux · pytest · lokale LLM-Laufzeiten · Unsloth/QLoRA · ASR/TTS-Adapterdesign · YAML/JSON-Workflow-Verträge · Provenienz- und Datenqualitätstools · explizite Sicherheitsgrenzen

## Zielrollen

AI Engineer, LLM Infrastructure Engineer, Applied AI Engineer, Agent Systems Engineer, Edge AI Engineer oder AI Platform Engineer – überall dort, wo zuverlässige Modellintegration und starkes Software Engineering gleichermaßen zählen.

## Portfolio-Fallstudien

- [Chappie – Daten- und QLoRA-Pipeline](https://werkstatt-core.ludwig-grosse484994.chatgpt.site/chappie)
- [Seniorbot – lokaler Edge-Sprachassistent](https://werkstatt-core.ludwig-grosse484994.chatgpt.site/seniorbot)
- [Optimismus Prime – Agenten-Orchestrierung](https://werkstatt-core.ludwig-grosse484994.chatgpt.site/optimismus-prime)
- [Über meinen Engineering-Ansatz](https://werkstatt-core.ludwig-grosse484994.chatgpt.site/about)

## Einstieg

- [Optimismus-Prime-Architektur](https://github.com/Chappie-2Pac/optimismus-prime#architecture)
- [Chappie-v1.0.0-Quickstart](https://github.com/Chappie-2Pac/chappie-public#quick-start)
- [Seniorbot-Pipeline](https://github.com/Chappie-2Pac/seniorbot#architecture)

## Kontakt

Portfolio: [Werkstatt Core](https://werkstatt-core.ludwig-grosse484994.chatgpt.site/)

LinkedIn: [Christoph Ludwig genannt Grosse](https://linkedin.com/in/christoph-ludwig-enannt-grosse-a7b830452)

E-Mail: [ludwig-grosse@gmx.de](mailto:ludwig-grosse@gmx.de)
