# Space Catalyst Watch

English below · Magyar leírás lentebb

## English

`space-catalyst-watch` is a Codex skill for evidence-led, short-horizon research of selected U.S.-listed space equities. Its core watchlist covers:

- SpaceX (SPCX)
- Rocket Lab (RKLB)
- AST SpaceMobile (ASTS)
- Planet Labs (PL)
- Redwire (RDW)

Intuitive Machines (LUNR) is an event-driven reserve name, included only when a major mission, NASA/CLPS, contract, or financing event is relevant to the broader sector.

### What it produces

1. A compact **Catalyst Card** for a 1–4 week research horizon.
2. A weekly or monthly multi-company roundup when requested.
3. An evidence-led **BUY / NEUTRAL / SELL** research status with a clear invalidation condition.

The skill checks launch and test outcomes, deployment progress, major contracts, carrier or government partnerships, earnings and guidance, backlog, margins, cash runway, dilution risk, regulatory decisions, and execution milestones.

### Data integrity rules

- Primary sources come first: SEC/EDGAR, company investor relations, earnings material, and NASA, DoD, or FCC releases.
- A press release is not automatically a catalyst; it must change a prior expectation.
- Every current material fact requires a source and date.
- If markets are closed, the price is labelled as the last close.
- BUY, NEUTRAL, and SELL are informational research signals, not personalized investment advice or automated orders.

### Structure

```text
space-catalyst-watch/
├── SKILL.md
├── agents/openai.yaml
└── references/
    ├── catalyst-rubric.md
    └── ticker-universe.md
```

Use the skill with a request such as:

> Use $space-catalyst-watch to create a current catalyst card for the tracked space stocks.

## Magyar

A `space-catalyst-watch` egy Codex skill kiválasztott, amerikai tőzsdén jegyzett űripari részvények bizonyíték-alapú, rövid távú elemzéséhez. Az alap figyelőlista:

- SpaceX (SPCX)
- Rocket Lab (RKLB)
- AST SpaceMobile (ASTS)
- Planet Labs (PL)
- Redwire (RDW)

Az Intuitive Machines (LUNR) eseményvezérelt tartalék ticker: csak akkor kerül elő, ha nagy küldetés-, NASA/CLPS-, szerződéses vagy finanszírozási esemény a teljes szektor szempontjából is fontos.

### Kimenetek

1. Rövid **Catalyst Card** 1–4 hetes kutatási horizonttal.
2. Igény szerint heti vagy havi, több céget összevető összefoglaló.
3. Bizonyíték-alapú **BUY / NEUTRAL / SELL** kutatási státusz, egyértelmű érvénytelenítő feltétellel.

A skill vizsgálja az indítási és teszteredményeket, a telepítési előrehaladást, jelentős szerződéseket, carrier- és állami partnerségeket, earnings/guidance adatokat, backlogot, marzsot, cash runwayt, hígulási kockázatot, szabályozói döntéseket és végrehajtási mérföldköveket.

### Adatminőségi szabályok

- Elsődleges források: SEC/EDGAR, vállalati IR, earnings anyagok, valamint NASA-, DoD- és FCC-közlemények.
- Egy sajtóközlemény nem automatikusan katalizátor: korábbi várakozást kell megváltoztatnia.
- Minden aktuális, érdemi tényhez forrás és dátum kell.
- Zárt piac esetén az ár utolsó záróértékként szerepel.
- A BUY, NEUTRAL és SELL címke tájékoztató kutatási jelzés, nem személyre szabott befektetési tanács és nem automatikus megbízás.

### Használat

Például:

> Használd a $space-catalyst-watch skillt egy aktuális Catalyst Card elkészítéséhez a figyelt űripari részvényekről.

## License

Released under the [MIT License](LICENSE).
