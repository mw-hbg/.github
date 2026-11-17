# Security policy / Sicherheitsrichtlinie

[English](#english) · [Deutsch](#deutsch)

This policy applies to all repositories of mw-hbg that have no `SECURITY.md`
of their own. / Gilt für alle Repositories von mw-hbg ohne eigene `SECURITY.md`.

## English

### Reporting a vulnerability

Please **do not** open a public issue for security problems. Use GitHub's
private reporting instead: open the affected repository, then
**Security → Report a vulnerability**. You will get an answer as soon as
possible; these are hobby projects, so please allow a few days.

Helpful details: project and Home Assistant version, what an attacker could do
and how to reproduce it.

### Principles of these projects

* Only the access that is strictly needed – no Home Assistant API access, no
  host network, no privileged mode unless a project explains why in its own
  security policy.
* Apps ship an AppArmor profile; code that faces the internet runs as an
  unprivileged user.
* No passwords are stored; tokens and secrets stay in the private storage of
  the app or integration.
* Upstream code is pinned to a reviewed version and updated deliberately.

## Deutsch

### Sicherheitslücke melden

Bitte **kein** öffentliches Issue für Sicherheitsprobleme anlegen, sondern die
vertrauliche Meldung von GitHub nutzen: das betroffene Repository öffnen, dann
**Security → Report a vulnerability**. Eine Antwort kommt so bald wie möglich;
das sind Hobbyprojekte, bitte ein paar Tage Geduld.

Hilfreich: Projekt- und Home-Assistant-Version, was ein Angreifer tun könnte und
wie es sich nachstellen lässt.

### Grundsätze dieser Projekte

* Nur der Zugriff, der unbedingt nötig ist – kein Zugriff auf die
  Home-Assistant-API, kein Host-Netzwerk, kein privilegierter Modus, außer ein
  Projekt begründet es in seiner eigenen Sicherheitsrichtlinie.
* Apps bringen ein AppArmor-Profil mit; Code, der aus dem Internet erreichbar
  ist, läuft als eingeschränkter Benutzer.
* Passwörter werden nicht gespeichert; Tokens und Geheimnisse bleiben im
  privaten Speicher der App bzw. Integration.
* Fremder Code ist auf eine geprüfte Version festgelegt und wird bewusst
  aktualisiert.
