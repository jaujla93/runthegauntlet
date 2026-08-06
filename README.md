# Gridiron Gauntlet

A draft-order combine for fantasy football leagues. Managers each run four
timed stations; highest score picks first. Nobody sees a score until every
manager has finished, then the board reveals last pick to first.

**Live:** https://jaujla93.github.io/runthegauntlet/

## How it works

1. The commissioner sets up a league and gets one private link per manager
2. Each manager runs the gauntlet once and receives a signed result code
3. The commissioner enters the codes; the board unlocks when all are in

## Stations

Eight exist. Each league runs four, chosen at setup, so it can be different
every season.

| Station | Skill tested |
| --- | --- |
| Snap Count | Reaction time |
| Playbook Recall | Sequence memory |
| Precision Passing | Anticipation |
| Two-Minute Drill | Scoring math under a clock |
| Route Tree | Visual search |
| Pocket Presence | Evasion |
| Audible | Interference and inhibition |
| Clock Management | Internal timing |

## Notes

- `index.html` is the entire application — no build step, no dependencies
- Result codes are signed per manager, so nobody can submit a score for
  anyone but themselves
- Append `#check` to the live URL for a deployment self-test
