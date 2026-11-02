# 🧭 MRTrip raziskovalni agent

Agent v Claude Code, ki po svetovnem spletu išče, **kaj je popularno**, **kaj izboljšati** in **katere inovacije** se pojavljajo – za aplikacijo MRTrip.

## Uporaba
1. Izpolni `mrtrip/PROJEKT.md` (opis aplikacije, konkurenti, težave).
2. V Claude Code (v tem repozitoriju) napiši:
   - `/mrtrip-raziskava` – splošni pregled
   - `/mrtrip-raziskava AI funkcije za načrtovanje poti` – ciljana tema
   - ali kar: *"Uporabi mrtrip-raziskovalca in preveri, kaj je nova konkurenca."*
3. Poročilo se shrani v `mrtrip/porocila/LLLL-MM-DD-<tema>.md`.

Vsako novo poročilo upošteva prejšnja in izpostavi, kaj je novega.

## Datoteke
- `.claude/agents/mrtrip-raziskovalec.md` – definicija agenta (navodila, orodja, oblika poročila)
- `.claude/commands/mrtrip-raziskava.md` – ukaz `/mrtrip-raziskava`
- `mrtrip/PROJEKT.md` – kontekst o aplikaciji
- `mrtrip/porocila/` – shranjena poročila
