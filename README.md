# When Netflix adapts a book, does anyone go looking for it?

**MSc thesis · KEDGE Business School · in progress**
*Working title: The Impact of Netflix Adaptations on Book Sales: A Data Analytics Perspective*

Everyone "knows" a Netflix adaptation sends people back to the book. I wanted to check whether that's true, and how big the bump really is, using public data.

&nbsp;

## Where it's at

| | |
|---|---|
| ✓ | **Sample built:** 101 books adapted by Netflix, after exclusions and replacements |
| ✓ | **Google Trends collected:** one continuous monthly window per book, 12 months before and 12 months after release |
| ✓ | **Goodreads collected and verified:** rating, ratings count, reviews count and first publication year for all 101 books; release dates double-checked |
| ✓ | **First full analysis run:** event-time chart, main model, event study, robustness checks, placebo test, group and genre comparisons |
| ✓ | **Literature review planned:** 7 sections, 37 sources and a gap table comparing 11 earlier studies |
| ✎ | **Now:** writing the literature review; the analysis is with my supervisor for feedback |
| ○ | **Next:** methodology chapter, then results and discussion |

&nbsp;

## The approach

- **One question per book:** how did interest in this book change in the months around its Netflix release, compared with its own months before?
- **Search interest as the signal.** Book sales data isn't public, so Google search interest stands in for reader demand, with Goodreads activity as a second view.
- **Careful about cause.** The design shows how demand moves around a release. The thesis only claims more than an association where the method supports it.
- **Stress-tested:** a placebo test (fake release dates), robustness checks, and comparisons by genre and by group.

## Data

| Source | What it gives | Why |
|---|---|---|
| Google Trends | Monthly search interest, searched as book title + author | A public, consistent proxy for attention to the book |
| Goodreads | Rating, ratings count, reviews count, first publication year | Reader activity and book characteristics |
| Netflix release dates | Release month for each adaptation | The event each window is centred on |

## Coming to this repo

The analysis notebook, the cleaned datasets and the figures will be added once my supervisor has reviewed the approach.

&nbsp;

---

Made by **Vigneshwari Nalla (Vee)** · MSc Data Analytics for Business, KEDGE Business School
[website](https://vigneshwari2408.github.io/vigneshwari-portfolio/) · [linkedin](https://www.linkedin.com/in/vigna24/) · [all projects](https://github.com/vigneshwari2408)
