# Agent Log

Append-only record of automated and agent-assisted changes to this repository.
Newest entry first. No participant data, committee or faculty names, credentials,
or tokens.

---

## 2026-09-01 - Adopt the shared ink; ground gradient kept

Links the shared token file and points the text colour at the shared ink. The ground
gradient stays local.

**One contrast repair, and a mistake worth recording.** Two placeholder paragraphs used a
hardcoded `#6b7280`, measuring **4.48** on the light `.clipboard` surface (`#faf6eb`) -
just under AA. My first attempt repointed them at `--text-muted`, which is a *light* grey
tuned for the dark ground: on light paper that measured **2.35**, making it worse. Worse
still, the replacement was too broad and caught **12** occurrences, hardcoding ten
legitimate dark-ground uses. Both were reverted, and only the two inline placeholders now
carry a paper-safe `#616974` at 5.14.

The lesson: this page mixes a dark ground with a light clipboard surface, so `--text-muted`
is correct in one context and wrong in the other. Check which surface an element actually
sits on before repointing a colour, and scope the replacement to the element, not the token.

**Verified.** Zero contrast failures; tightest pair 5.14. `.controls-panel` is always
`1fr 1fr`, so the `grid-column: span 2` on its transfer button is safe.
