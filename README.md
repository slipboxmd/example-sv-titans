# example-sv-titans — source corpus

Raw source texts for the **Silicon Valley Titans** example slipbox: writing by
founder/operator/investor essayists, filtered to one theme — **building and
running technology startups.**

This repo holds only the sources. It is mounted as a git submodule at
`examples/sv-titans/sources` in [slipboxmd/slipbox](https://github.com/slipboxmd/slipbox),
which holds the roster, curation rubric, and the generated slipbox notes.

## Layout

One folder per author. Web-fetched essays are markdown with frontmatter recording
the origin URL; books and archives are PDFs.

## Status — partial

Acquired: Paul Graham (173 topic-filtered essays), Naval Ravikant (Almanack),
Marc Andreessen (pmarca archive), Jeff Bezos (shareholder letters), Sam Altman
(7 essays). Nine more authors are still to be added — see `SOURCES.md` in the
parent repo.

## Attribution

Texts are © their respective authors, included for study and to demonstrate the
slipbox pipeline. See [NOTICE.md](./NOTICE.md). Rights holders: open an issue to
request removal.
