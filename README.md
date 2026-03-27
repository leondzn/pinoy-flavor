# Pinoy Flavor

A Crusader Kings III mod that adds authentic Philippine cultural flavor for the **Tagalog**, **Bisayan**, and **Iloko** cultures.

Out of the box, CK3 assigns generic Austronesian, Sanskrit, or Dravidian labels to Philippine rulers and their courts. This mod overrides those with historically grounded Filipino terms drawn from pre-colonial Philippine society.

---

## Features

### Ruler Titles (All Tiers)

| Tier | Tagalog (M/F) | Bisayan (M/F) | Iloko (M/F) |
|------|--------------|--------------|-------------|
| Barony | Gat / Dayang | Timawa | Apo |
| County | Datu / Dayang | Datu / Dayang | Apo |
| Duchy | Lakan / Lakambini | Punong Datu / Punong Dayang | Nangato nga Apo |
| Kingdom | Rajah / Hara | Rajah / Hara | Apo nga Ari |
| Empire | Dakilang Rajah / Dakilang Hara | Rajah nga Tanan / Hara nga Tanan | Dakkel nga Apo |

Religion-specific overrides:

| Layer | Tagalog | Bisayan | Iloko |
|-------|---------|---------|-------|
| Hindu/Buddhist Empire | Maharajah / Maharani | — | Maharajah / Maharani |
| Hindu/Buddhist Kingdom | — | — | Rajah |
| Muslim Kingdom | Sultan / Sultana | Sultan / Sultana | Sultan / Sultana |
| Muslim Empire | Sultan / Sultana | Sultan / Sultana | Sultan nga Dakkel / Sultana nga Dakkel |

### Court & Family Titles

**Prince & Princess** — Children of Philippine rulers use indigenous terms instead of the generic "Prince" or Dravidian Sanskrit labels:

| Culture | Male | Female |
|---------|------|--------|
| Tagalog | Anak ng Rajah | Anak ng Hara |
| Bisayan | Anak sa Rajah | Anak sa Hara |
| Iloko | Anak ti Apo | Anak ti Apo |

**Queen/Empress Mother** — The mother of a reigning ruler:

| Culture | Title |
|---------|-------|
| Tagalog | Ina ng Rajah |
| Bisayan | Inahan sa Rajah |
| Iloko | Ina ti Apo |

**Babaylan (Court Chaplain)** — The court's spiritual specialist. Pre-colonial Philippines had distinct religious roles that bore no resemblance to a "Court Chaplain." All three cultures use the historical term:

| Culture | Male | Female |
|---------|------|--------|
| Tagalog | Babaylan | Babaylan |
| Bisayan | Babaylan | Babaylan |
| Iloko | Babaylan | Babaylan |

---

## Installation

### Steam Workshop
Subscribe on the [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3692712244).

### Manual
1. Download or clone this repository.
2. Copy the `pinoy-flavor` folder into your CK3 mod directory:
   - **Windows:** `%USERPROFILE%\Documents\Paradox Interactive\Crusader Kings III\mod\`
   - **Linux:** `~/.local/share/Paradox Interactive/Crusader Kings III/mod/`
3. Enable the mod in the CK3 launcher.

---

## Compatibility

- **CK3 version:** 1.18.4
- **Save games:** Safe to add mid-playthrough. No events, decisions, or game rules are modified.
- **Files touched:**
  - `common/flavorization/` — three new flavorization files
  - `localization/english/culture/` — three new localization files
- **Conflicts:** Will conflict with any mod that also defines flavorization blocks for `name_list_tagalog`, `name_list_bisayan`, or `name_list_iloko`. Load order should not matter for everything else.

---

## Contributing

Historical accuracy and readability is the priority. If you know of better-attested terms, regional variants, or missing titles, please open an issue or submit a pull request.

---

## License

MIT — see [LICENSE](LICENSE).
