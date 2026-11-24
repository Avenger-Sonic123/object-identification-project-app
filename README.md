# Object Identification — Image Gallery

A multi-page object-detection demo using pretrained COCO-SSD.

**Repository created:** 2022-12-09  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2022-12-08

## Features and implementation

- Five image categories.
- Individual p5.js canvases.
- Ml5 object detection callbacks.
- Bounding boxes, labels and confidence percentages.

## Technologies

HTML, CSS, JavaScript, Bootstrap, jQuery, p5.js, ml5.js.

## How the code works

Each of the five scene pages uses its own JavaScript detection loop and model/result callbacks.

## Project structure

| File | Purpose |
| --- | --- |
| [`bedroom.css`](bedroom.css) | Scene-specific styling |
| [`bedroom.html`](bedroom.html) | Scene-specific user interface |
| [`bedroom.js`](bedroom.js) | Scene-specific detection logic |
| [`bottles.css`](bottles.css) | Scene-specific styling |
| [`bottles.html`](bottles.html) | Scene-specific user interface |
| [`bottles.js`](bottles.js) | Scene-specific detection logic |
| [`deskandcomputer.css`](deskandcomputer.css) | Scene-specific styling |
| [`deskandcomputer.html`](deskandcomputer.html) | Scene-specific user interface |
| [`deskandcomputer.js`](deskandcomputer.js) | Scene-specific detection logic |
| [`fruitbasket.css`](fruitbasket.css) | Scene-specific styling |
| [`fruitbasket.html`](fruitbasket.html) | Scene-specific user interface |
| [`fruitbasket.js`](fruitbasket.js) | Scene-specific detection logic |
| [`index.html`](index.html) | Main page and user interface |
| [`style.css`](style.css) | Page styling |
| [`tvandac.css`](tvandac.css) | Scene-specific styling |
| [`tvandac.html`](tvandac.html) | Scene-specific user interface |
| [`tvandac.js`](tvandac.js) | Scene-specific detection logic |

Key functions in the source:
- `bedroom.js`: `gotResults()`.
- `bottles.js`: `gotResults()`.
- `deskandcomputer.js`: `gotResults()`.
- `fruitbasket.js`: `gotResults()`.
- `tvandac.js`: `gotResults()`.

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/object-identification-project-app.git
cd object-identification-project-app
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Open the index and choose a scene to view detections.

## Current status and limitations

Detection results depend on the pretrained model; no custom training or measured benchmark is included.

## Related project snapshots

Other repositories in this project family:
- [Object-Detector-Upgraded](https://github.com/Avenger-Sonic123/Object-Detector-Upgraded) — repository created 2022-12-17

---

Source reference: [`e722d059`](https://github.com/Avenger-Sonic123/object-identification-project-app/tree/e722d059975e125ca72d47854b1c2e988a07ab13) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
