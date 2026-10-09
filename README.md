# Chromatoscope

Compare several Sanger sequencing chromatograms (.ab1) side by side, to check alleles at a glance.

I created it to study heteroallelic and heterozygous mutations, because the two underlying sequences can sometimes be tough to decipher!

**Use it live, nothing to download:** https://chloe-soulard.github.io/tools/chromatoscope.html
(all my tools are on my website: https://chloe-soulard.github.io/tools/)

**Video tutorial:** https://youtu.be/ahzqcpbq5lk

Or download `Chromatoscope.html` and open it in any web browser to use it offline. Either way, your files are read locally: they never leave your computer.

No file at hand? Click "Load a made-up example" on the start screen: a wild type and three lines edited at the same guide, two of them carrying two different alleles, so their peaks overlap past the cut site.

## What it does

- Opens several `.ab1` files at once (button or drag and drop)
- Puts every trace on a common base-by-base axis, so runs with different peak spacing line up
- Slide, lock and reorder traces to align alleles, set a reference track for the position ruler
- Search a motif across all traces (an N never counts as a match)
- Add free-text rows aligned to the bases, to annotate guides, primers or mutations
- Zoom, adjust amplitude and track height, light and dark themes
- Export the current view as PNG

Developed with Claude. Feel free to use and share!
