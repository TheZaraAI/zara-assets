# TheZaraAI publish assets

Transient host for Instagram publishing. Files are fetched by the Graph API during
the publish window, then safe to prune. Keep this repo SMALL — Pages builds fail
past ~1GB and that silently kills scheduled posts (learned 2026-08-06).
