# mythology-quiz — redirect only

This repository exists solely so that the old address

    https://rpalasamudrum-cloud.github.io/mythology-quiz/

keeps working. The quiz was renamed to **Panchamrutha** and now lives at

    https://rpalasamudrum-cloud.github.io/panchamrutha/

GitHub redirects renamed *repository* URLs but **not** GitHub Pages URLs, so the
old Pages address returned 404 after the rename. This repo restores it.

`index.html` and `404.html` are the same page, so any path under the old address
redirects, not just the root. The redirect is done three ways — a canonical link,
a meta refresh, and `location.replace` — with a visible link as a last resort if
scripting is off.

Nothing else belongs here. The game itself is in the `panchamrutha` repository.
