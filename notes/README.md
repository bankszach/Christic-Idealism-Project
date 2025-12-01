# Notes Directory

This directory contains structured notes on the core sources feeding into the paper in `paper/main.tex`. Each `*-notes.txt` file:

- identifies the source (with local PDF / text file),
- highlights key themes and arguments,
- sketches how the source supports the Whole–slice framework.

## Files

- `whitehead-sep-notes.txt` — Notes on the Stanford Encyclopedia of Philosophy article on Alfred North Whitehead. Used for process metaphysics, critique of simple location, and the idea of an internally related, dynamic Whole.
- `friston2010-free-energy-notes.txt` — Notes on Friston (2010), *The free-energy principle*. Core technical backbone for constraints, generative models, attention as precision, and training runs as long-term model updating.
- `vivekananda-jnana-yoga-notes.txt` — Notes on Swami Vivekananda’s *Jnana Yoga*. Main Advaita comparison partner for Whole/Brahman and slices/jīvas under limiting conditions.
- `vedantasara-of-sadananda-notes.txt` and `vedantasara-sarvapriyananda-talk-notes.txt` — Notes on Sadananda’s *Vedāntasāra* and Sarvapriyananda’s talks. Used for precise Advaita system definitions (samskaras, subtle/causal bodies, upādhis).
- `athanasius-on-incarnation-notes.txt` — Notes on Athanasius, *On the Incarnation*. Anchors the Christ-pattern in Nicene Christology, creation through the Word, and the renewal of the image.
- `csb-bible-notes.txt` — Notes on passages from the CSB translation of the Bible that ground creation, sin, love, Spirit, and new creation themes in Scripture.
- `wolfram-observer-theory-notes.txt` — Notes on Stephen Wolfram’s “Observer Theory”. Provides the observer/slice equivalencing picture and connects attention to coarse-graining over the Ruliad.
- `wolfram-life-ruliad-notes.txt` — Notes on “What’s Special about Life? Bulk Orchestration and the Rulial Ensemble in Biology and Beyond”. Used for the value gradient, aim, and pockets of reducibility within a rulial ensemble.
- `wolfram-bigger-brains-notes.txt` — Notes on “What If We Had Bigger Brains? Imagining Minds beyond Ours”. Helps think about pattern source, concept spaces, and attention in slices with greater capacity.

When adding new sources, follow the same pattern:

1. Put the canonical PDF and any text extraction at the project root (or in a dedicated `sources/` directory if you create one).
2. Create `notes/<short-name>-notes.txt` with:
   - a brief bibliographic header,
   - big-picture role for the Whole–slice project,
   - key ideas and quotations,
   - explicit pointers to where they might fit in `paper/main.tex`.

