# LLM Engineering Lab — public demo

Website: https://ll9019m-code.github.io/llm-education-site/

26 learning modules, 18 practical labs and 12 engineering tools. Educational content is in Russian.

This repository contains only the compiled public website. It does not contain the private application repository/history, server configuration, credentials or runtime databases.

The public edition has no registration, OIDC or server API. Progress and personal benchmark measurements are stored in IndexedDB in the current browser. Clearing site data removes those records; there is no cross-device synchronization. The full server edition is maintained separately.

Routes use a hash so direct links and reloads work on GitHub Pages. Publication uses the main branch and `.nojekyll`.
