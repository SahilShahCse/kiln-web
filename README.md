# kiln-web

The compiled Kiln console, served at <https://sahilshahcse.github.io/kiln-web/>.

**This repository holds build output only.** The source lives in a private
repository and is not published here. Deployed by `deploy-web.sh` in the
source tree, which replaces this directory wholesale on every release so a
stale `main.dart.js` can never sit beside a fresh service worker.

Signing in is required. The bundle carries the Supabase project ref and the
publishable key, both public by design; that key on its own reads nothing.
Row-level security and authentication protect the data.
