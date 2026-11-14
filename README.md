# Lift Log

A strength-training tracker for several people. Each person picks their name (no password) and logs their own sets.

**Published version:** https://claude.ai/artifact/CjbMhm1MHet5w4VHqMXmLQ. Workouts are saved online with the page, so they show up on any device. People need edit access from the page's Share menu to log sets.

**Local version:** open `index.html` directly in a browser. Data stays in that browser only.

- **Who's lifting?** screen: pick your name or add a new one. The app remembers your last pick on each device.
- **Log** sets (weight × reps) for 30 common lifts, or pick "+ Custom exercise…", type a name, and it's added to your list
- Shows what you lifted **last time** and pre-fills the weight
- Automatic **PR** detection per rep count, plus an estimated 1RM (Epley formula)
- **History** by day, **Progress** chart (est. 1RM, top weight, or volume), and a rep-records table
- Rest timer, lb/kg setting, and custom exercise list for each person
- Export a JSON backup or CSV; import a backup to merge it into the current person's log
