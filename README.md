# Savvy Admin — empty

The Savvy Admin prototype with no content: no streams, hosts, sponsors, polls, share card or
notification presets, game sets, word sets, scoring presets, reward sets, game modes or power-ups.
Users, the shop, seasons and the daily puzzle keep their sample data. Saved data lives in its own
browser storage (`savvy-mock-db-empty`), apart from the full prototype.

Live: https://massliharf.github.io/savvy-admin-empty/

---

# Savvy Admin

A clickable prototype of the Savvy admin dashboard: streams and their schedule, bundles and word sets, How to play & format, time slots, hosts, sponsors, polls, seasons, users and the shop. It runs entirely in the browser on a mock backend; sign in with any email and password.

**Live:** https://massliharf.github.io/savvy-admin/

The first version is kept on the `v1` branch (tag `v1`).

```bash
npm install
npm run dev            # http://localhost:5173
npm run build:pages    # the GitHub Pages build in dist-pages/
```

Reset the sample data with `window.__resetMockDb()` in the browser console. Words in Bundles are hidden behind the prototype password `savvywords`.

All names, images and data are sample content.
