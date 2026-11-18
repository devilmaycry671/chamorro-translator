# Fino’ CHamoru Translator

A Chamorro ↔ English translator website. Claude writes the translations, and a corpus of 8,580 real Chamorro sentences
(from [schyuler/Chamorro-Corpus-Builder](https://github.com/schyuler/Chamorro-Corpus-Builder)) shows how each word is actually used.

- `index.html`: the whole site (no build step).
- `corpus.json`: the Chamorro sentences with their sources.
- `vendor/anthropic-sdk-1.4.0.mjs`: the official Anthropic TypeScript SDK, bundled for the browser (Apache-2.0, see the license file next to it).

## How visitors translate

Each visitor pastes their own Claude API key (from console.anthropic.com) into the key box. The key is stored only in
their browser and is sent only to `api.anthropic.com`. **Never put your own API key into these files**; anything in a
public repo is visible to everyone.

The concordance (word search) works without a key.


Translations can be wrong. Check anything important with a fluent speaker.
