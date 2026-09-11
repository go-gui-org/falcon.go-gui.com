# falcon.go-gui.com

Landing page for Falcon, the terminal emulator built on
[go-term](https://github.com/go-gui-org/go-term) and
[go-gui](https://go-gui.com). Served at <https://falcon.go-gui.com>
via GitHub Pages.

## Layout

- `index.html` — the whole site. CSS lives inline in its `<style>` block.
- `CNAME` — custom domain. Do not remove; Pages needs it on every deploy.
- `.nojekyll` — serve files as-is.

## Preview

```sh
python3 -m http.server -d .
```

## Demo video

The `#demo` section holds a placeholder. Drop `falcon-demo.mp4` plus a
poster next to `index.html` and swap the placeholder for a
`<video controls poster>` inside the existing `.term` chrome.
