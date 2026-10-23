# Ideen-Gericht

Zwölf Claudes prüfen, ob deine Idee taugt. Ein Ankläger sagt, warum sie scheitert, ein Verteidiger hält dagegen, zwölf Geschworene stimmen blind ab, und ein Richter fällt das Urteil mit einem Test, den du diese Woche machen kannst.

## In Claude Code verwenden
Den Ordner `ideen-gericht` unter `~/.claude/skills/` ablegen, sodass `SKILL.md` direkt in `~/.claude/skills/ideen-gericht/` liegt. Mit installiertem Git:

Windows (PowerShell):
```powershell
git clone https://github.com/neubauerwilli/ideen-gericht "$env:USERPROFILE\.claude\skills\ideen-gericht"
```
Mac/Linux:
```bash
git clone https://github.com/neubauerwilli/ideen-gericht ~/.claude/skills/ideen-gericht
```
Vorhandene Installation nicht erneut klonen oder ungeprüft überschreiben. Dann in Claude Code `/ideen-gericht` aufrufen und deine Idee in ein bis drei Sätzen dazuschreiben. [Offizielle Skill-Dokumentation](https://code.claude.com/docs/en/skills).

## In Claude (App oder Web) verwenden
Den Ordner als ZIP packen und in Claude unter **Customize > Skills > + > Create skill > Upload a skill** hochladen. Danach „Stell meine Idee vor Gericht: …“ schreiben. [Offizielle Anleitung](https://support.claude.com/en/articles/12512180-use-skills-in-claude).

Ohne Installation: den [Prompt zum Einfügen](prompt-zum-einfuegen.md) in einen neuen Chat kopieren.

## So läuft die Verhandlung
Anklageschrift → Ankläger und Verteidiger (getrennt) → zwölf Geschworene (blind) → Auszählung → Urteil: NICHT SCHULDIG, AUF BEWÄHRUNG oder SCHULDIG, mit den drei Einwänden, die zählen, und dem nächsten Test. Alles landet als `urteil-<idee>.md` im Arbeitsordner.

In Claude Code laufen die Rollen als getrennte Unteragenten: Ankläger und Verteidiger auf Sonnet, die Geschworenen auf Haiku (günstig, für mehr Tiefe auf Sonnet umstellen), der Richter auf Sonnet. Im normalen Chat spielt Claude die Rollen nacheinander, die Trennung ist dort schwächer.

## Die Geschworenen
Buchhalterin · Zielkunde · Konkurrent · Investorin · Vertriebler · Marketing-Chefin · Technikerin · Kunde der Alternative · Frühe Anwenderin · Juristin · Mitarbeiter · Zukunftsforscher

## Was das Urteil bedeutet
Eine Simulation aus zwölf Blickwinkeln, kein Markttest und keine Rechts-, Steuer- oder Anlageberatung. Zahlen, die du nicht nennst, stehen als Annahme da. Eingelesene Inhalte verarbeitet der verwendete KI-Dienst. Der Skill ist kostenlos; Claude-Zugang und Nutzungslimits gelten separat. Zwölf Geschworene sind vierzehn bis fünfzehn Unteragenten pro Verhandlung, das kostet entsprechend Nutzungslimit.

Von Willi Neubauer · Lizenz: [MIT](LICENSE).

## Beispiel und Prüfstand · 23.10.2026
Eine echte Verhandlung mit allen fünfzehn Rollen als getrennte Unteragenten liegt in [`beispiel-urteil.md`](beispiel-urteil.md): eine deutschsprachige KI-Community für 29 Euro im Monat. Ergebnis 8 zu 4, Urteil AUF BEWÄHRUNG, mit Test für die Woche.
