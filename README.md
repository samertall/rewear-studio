# ReWear Studio

An interactive, wardrobe-first fashion product concept created by Samer Tallauze.

## What works

- Responsive style studio with three synthetic adult-model image comparisons and a before/after slider.
- Local wardrobe item creation, cost-per-wear calculations, and wear logging.
- Occasion-based, transparent rule-driven outfit planning.
- Wardrobe impact dashboard using actual entered prices and wear counts.
- Explicit photo permission gate and **local-only photo preview**; no photos are sent to servers.
- Local browser storage for wardrobe entries and saved looks.

## Important limitations

This is **not** a technically complete HackTheFashion submission yet. The hackathon listing restricts entry to students; Samer has confirmed current student enrollment. Eligibility remains subject to the organizer's official verification.

The hackathon description also lacks a usable, named try-on API, credentials and endpoint specification. Thus **no live virtual try-on API is integrated**; the three styling examples are pre-generated images, not live synthesis. The planner is rule-based, not an LLM agent. No actual size, body fit, carbon, or water savings are inferred.

## Run locally

This is a framework-free static app:

```sh
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## Privacy and consent

The demo's included fashion model is synthetic and adult. The user-upload control checks a declared adult/permission status; files are never transmitted or persisted. They are displayed using browser object URLs and can be cleared.

## Future integration

After the organizer supplies API docs and valid keys, add a secure server-side proxy and consent-gated generation flow. Never expose provider credentials in browser code; enforce adult-use and image permissions; document retention/deletion policies, upload limits, async job polling, and failure handling.

## Credits

Original product concept, interaction design, and front-end. Generated editorial demo model images are illustrative and are not FabricVTON outputs. © 2026 Samer Tallauze.
