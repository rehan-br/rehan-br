```bash
$ whoami
rehan bashir — full-stack + ai systems engineer

$ status --verbose
shipping · founder @ the developer guys · based in aldie, va

$ contact
rehanbr.com · thedeveloperguys.com · linkedin.com/in/rehanbr · rbashir2001@gmail.com
```

---

> **log, 2026** — most of what I ship can't afford to be wrong: clinical
> data, real inventory, real money. So I spend most of my time making the
> *database* enforce the rule, not a component that might forget to check
> it. The rest of the time I build stranger things — a race engineer that
> only speaks when something real changes, a recommender that has to earn
> its ranking against a model that's allowed to lose.

---

## systems online

| system | state | reads |
|---|---|---|
| `f1-race-engineer` | 🟠 testing first proto  | decodes F1 25 telemetry at 20Hz, speaks over voice only on real state change |
| `clinicos` | 🟠 private build | Postgres RLS is the authorization boundary — not a UI check |
| `vitacommerce` | 🟠 private build | lot-tracked inventory, allocated first-expired-first-out |
| `music-taste-engine` | 🟠 prototyping  | ranks new music against a taste model trained to be provably wrong sometimes |

<details>
<summary><b>changelog — smaller, finished builds</b></summary>
<br/>

- `sigil` — trace a shape, an LLM writes back its myth, permanent url
- `watcher` — an LLM plays twenty questions against a word you picked
- `liars-wordle` — the tile colors lie to you, on a hidden schedule
- `webcam-draw` — sketch in the air, tracked entirely client-side
- `buckshot-rl` — a PPO agent bounded by an exact solver, not just vibes

</details>

---

## incoming transmission

<table>
<tr>
<td width="100" align="center"><img src="assets/dg-logo.jpg" width="80" /></td>
<td>

**THE DEVELOPER GUYS** — *"we build apps that move you forward."*

A studio, not a solo act. Web apps, APIs, and AI agents that do real
work, built by people who stick around after the invoice clears.

[thedeveloperguys.com](https://thedeveloperguys.com) → [hello@thedeveloperguys.com](mailto:hello@thedeveloperguys.com)

</td>
</tr>
</table>

---

## stack

```
languages    typescript · python · sql
backend      fastapi · node.js · supabase · prisma
frontend     next.js · react · react native · tailwind
ai / ml      openai · anthropic · pytorch
data/infra   postgresql · docker · aws · cloudflare
```

---

## invariants

```
assert authority.lives_in(database)            # not ui.hidden_button
assert model.output ⊆ tool_call_results         # no invented facts
assert eval_harness.can_report_negative_result  # or it isn't an eval
assert finished(small_thing) > unfinished(impressive_thing)
```

---

## uptime

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com?user=rehan-br&hide_border=true&background=00000000&stroke=7C5CFC&ring=7C5CFC&fire=10b981&currStreakLabel=e4e4e7&sideLabels=9ca3af&currStreakNum=e4e4e7&sideNums=e4e4e7&dates=6b7280" />
</div>

---

<div align="center">

`rbashir2001@gmail.com` · [`github.com/rehan-br`](https://github.com/rehan-br)

<sub>-- open to interesting problems, always listening on this channel --</sub>

</div>
