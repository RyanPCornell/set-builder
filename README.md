# Build Your Own SET

A hands-on sandbox for teaching **systems thinking** — built for
*SOS 110: Building a Sustainable World* (Arizona State University).

**▶ Try it: https://ryanpcornell.github.io/set-builder/**

Students drag social, ecological and technical components onto a canvas, connect
them with reinforcing (`+`) and balancing (`−`) arrows, and find out whether what
they've drawn actually behaves like a *system* — or is just a pile of parts.

## What it does

- **18 components** across three domains — social (households, government,
  markets, culture, equity, workers), ecological (freshwater, soil, air,
  wildlife, climate, forests) and technical (grid, roads, water & sewer,
  factories, data, waste).
- **Directed links with polarity.** Drag from one component to another to draw an
  arrow; choose whether it *amplifies* or *dampens*. Click an arrow to flip it.
- **Live feedback-loop detection.** Every directed cycle is found and classified
  as *reinforcing* or *balancing* by counting the negative links around it.
- **A three-point check**: all three domains present, a cross-domain link, and
  a feedback loop.
- **Shock the system.** A disturbance propagates through the graph and the tool
  reports whether it ran away, was absorbed, or kept circulating — the difference
  between non-linearity and resilience, shown rather than defined.
- **An Explanation.** A box for writing, in plain language, why your system is
  drawn the way it is and what each arrow is doing. It starts blank — including
  when you load an example — and whatever you write prints on the PDF.
- **Two examples** to load and pick apart: fast fashion, whose reinforcing
  consumption loop outruns a slower corrective one, and a managed fishery whose
  loops all balance.
- **Save as PDF.** Exports a one-page sheet with the diagram, the component and
  connection lists, the checklist, every loop found, and your explanation at the
  foot — for turning in.

## Running it

It is a single self-contained HTML file with no build step, no dependencies and
no backend. Open `index.html` in a browser, or serve the folder statically.
Everything is hand-drawn SVG; nothing is tracked and nothing leaves the browser.

## Reuse

Free to use in your own classroom. The generator that produces this page lives
alongside the SOS 110 slide decks it was extracted from, so the shared copy and
the in-class version stay identical.
