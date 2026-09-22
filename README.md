# MakeCode Arcade tutorials in Russian

Russian learner-facing MakeCode Arcade material for Neuronka. This repository
is the separate publishing project used by the Arcade course; it is not the
course-planning repository.

## Student links

Students only open the assigned link. There is nothing to install, clone, or
configure. `lang=ru` selects Russian tutorial text, and `lockedEditor=1` keeps
the learner in the lesson flow.

| Material | What it contains | Pinned learner link |
|---|---|---|
| Full of Stories | Four short creative activities in one Skillmap | [Open Skillmap](https://arcade.makecode.com/--skillmap?lang=ru&lockedEditor=1#github:nzanco/makecode-arcade-ru-tutorials/skillmaps/full-of-stories#v0.2.0) |
| Chase the Pizza | Standalone guided game tutorial | [Open tutorial](https://arcade.makecode.com/?lang=ru&lockedEditor=1#tutorial:https://github.com/nzanco/makecode-arcade-ru-tutorials/tutorials/chase-the-pizza#v0.2.0) |
| Первый спрайт (M01 L01) | Five guided steps: create a sprite, then place it with one number | [Open tutorial](https://arcade.makecode.com/?lang=ru&lockedEditor=1#tutorial:https://github.com/nzanco/makecode-arcade-ru-tutorials/tutorials/m01-l01#v0.2.0) |

## Repository layout

```text
tutorials/                         standalone tutorials
skillmaps/<skillmap>.md            a Skillmap's Russian map
skillmaps/<skillmap>/              that Skillmap's canonical tutorial sources
_locales/ru/<same-relative-path>   matching Russian tutorial views
```

For example, `skillmaps/full-of-stories/greeting-card.md` is the canonical
source and `_locales/ru/skillmaps/full-of-stories/greeting-card.md` is what a
student sees with `lang=ru`. The five Full of Stories files are intentional:
one map and four separate activities, not duplicate versions.

See [AGENTS.md](AGENTS.md) before changing course content or links.

## Source and license

This repository holds two kinds of file, and they have different origins.

**Adapted from upstream.** `chase-the-pizza` and the `full-of-stories`
skillmap derive from Microsoft MakeCode Arcade's
[`pxt-arcade`](https://github.com/microsoft/pxt-arcade) repository, MIT
licensed, and are published here as modified Russian localizations. The
upstream copyright notice is retained in [LICENSE](LICENSE).

**Written by Neuronka.** `m01-l01` and every tutorial added for the Neuronka
Arcade course are original work, not a translation of any upstream file. They
are copyright Neuronka and released under the same MIT licence, so one grant
covers the whole repository and nobody has to work out which file is which.

MakeCode Arcade and related marks remain the property of their respective
owners. Nothing here implies endorsement by or affiliation with Microsoft.
