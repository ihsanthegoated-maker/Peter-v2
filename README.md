# Peter Studio — Complete browser version

## What it does
- Enter one topic and choose a duration/style.
- Generates a short narration script from a built-in template.
- Generates spoken narration locally in the browser using Kokoro via Transformers.js.
- Creates an original animated cartoon host and animated background scenes.
- Adds timed captions and records the result as a narrated vertical WebM video.
- Exports an SRT subtitle file separately.

## Run on Android
1. Upload `index.html` to a GitHub repository.
2. Enable GitHub Pages (Settings → Pages → Deploy from branch → main → /root).
3. Open the published URL in Chrome.
4. Keep a good internet connection for the first voice-model download. The model is cached by the browser after download.
5. Enter a topic, tap Generate, wait for narration and rendering, then Download.

You can also test by opening index.html, but browsers may restrict module loading from local files. Hosting on GitHub Pages is recommended.

## Limits
- The voice model is downloaded from Hugging Face through Transformers.js and runs locally; the first download is large and may be slow. Android device memory and browser support vary.
- Video export is WebM (with audio and captions). Some social apps accept WebM; otherwise convert to MP4 using a trusted converter.
- Script generation uses a local template, not a remote LLM. This keeps the workflow free and avoids requiring an API key, but it is not as creative as a paid LLM.
- Visuals are original animated graphics, not generated photorealistic clips or downloaded gameplay footage.
- No unlimited high-quality AI video generator can be promised for R0.
