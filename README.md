# ZANK HALFTONE

Free, browser-local DTF halftone preparation tool. The core screen is deterministic image processing: luminance → levels → rotated halftone screen → mask → original-alpha × mask → transparent PNG.

## Run

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
```

No backend, login, paid API, watermark, or upload service is required.
