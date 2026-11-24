# pagerline-sandbox

Demo sandbox for [Pagerline](https://github.com/Akar-Samudra-Artifisial/pagerline), an on-call HUD for Even Realities G2.

The CI in this repo **fails on purpose**: `add()` in `index.js` has a bug, so `node --test` fails. Pagerline picks up the failed `workflow_run` webhook, shows it on the glasses, and lets you rerun the job or comment on it.

Do not fix the bug — the demo needs it.
