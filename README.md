# DREAM 2026

Website for **DREAM — Disease Reasoning, Experimentation and Modelling**, a free, one-day symposium bringing together machine learning and disease biology.

- **When:** Monday 7 December 2026, 9am–5pm AEDT (UTC+11).
- **Where:** Garvan Institute of Medical Research, 384 Victoria St, Darlinghurst, NSW 2010, Australia.
- **Register free:** https://www.trybooking.com/DQTHJ
- **Submit an abstract:** https://forms.gle/L9x6VF7z8Hk69Yss9 — deadline 20 November 2026.
- **Contact:** dream@garvan.org.au

Live site: https://ai-dream-workshop.github.io/neurips2026/

DREAM is an independent event at Garvan. The existing `neurips2026` URL is retained because it is linked from event publicity.

## Development

Single-file static site (`index.html`) hosted on GitHub Pages. No build step or dependencies are required. Preview locally with:

```sh
python3 -m http.server 8000 --directory neurips2026
```

Run this command from the parent `dream_website` directory, then open http://localhost:8000. If your terminal is already in this repository, use `python3 -m http.server 8000` instead.

## Content still to finalize

- Detailed program: talk order, lengths, session times, and panel participants.
- Whether Lazar Atanackovic will receive a program slot.
- Current organizer credits.
- Recording and remote-talk arrangements, if offered.
- Public access to the abstract form; an unauthenticated automated check returned HTTP 401.

Keep the `#schedule` and `#cfp` anchors stable for existing links. Coordinate future event-detail changes with the TryBooking listing and promotional flyer.
