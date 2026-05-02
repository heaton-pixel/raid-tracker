## Features

### Food Tracker
Tracks how many champions you have ready to ascend and how much food you have at each star tier.

|   Tier   |   Food required  |
|----------|------------------|
| 2★ → 3★ | 2 food champions |
| 3★ → 4★ | 3 food champions |
| 4★ → 5★ | 4 food champions |

- Use the **+/-** buttons to set your counts
- The tracker calculates how many upgrades you can do right now
- **Chain tracking** — champions produced at one tier automatically flow into the food count for the next tier up
- Progress bar shows how close your food stock is to covering all your upgrades
- Status banner tells you if you're ready or still short

---

### Mercy Tracker
Tracks your pull count for each shard type.

| Shard | Counter | Mercy starts | Increase per pull |
|---------|-----------|-----------------|-------------------|
| Ancient | Epic      | After 20 pulls  | +2% |
| Ancient | Legendary | After 200 pulls | +5% |
|  Void   | Epic      | After 20 pulls  | +2% |
|  Void   | Legendary | After 200 pulls | +5% |
| Sacred  | Legendary | After 12 pulls  | +2% |
| Primal  | Legendary | After 75 pulls  | +1% |
| Primal  | Mythical  | After 200 pulls | +10% |

- Tap **+** each time you pull a shard without hitting that rarity
- Counter shows pulls remaining until mercy activates
- Once mercy is active the number turns **amber** and shows your boosted chance
- If the boosted chance gets critically high the counter turns **red and pulses**
- Each rarity counter is **independent** — pulling an Epic resets only the Epic counter, not Legendary
- Hit the red **Reset** button for a counter when you pull that rarity

---

## How data is saved

Your counts are automatically saved to your browser's local storage after every change. They survive page refreshes and closing the tab. To wipe everything and start fresh use the **Reset Food** button at the top or the individual reset buttons on each mercy counter.

> ⚠️ Clearing your browser data or cache will erase your saved counts.


## Notes

- Requires an internet connection on first load to fetch the Cinzel font from Google Fonts. After that it works offline.
- Mercy rates are based on the official in-game Mercy System table.
- Food chain logic assumes upgraded champions go directly into food for the next tier, not as base champions to ascend.
