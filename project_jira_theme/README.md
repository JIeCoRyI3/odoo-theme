### Project Jira Theme (Odoo 17)

Jira-inspired visual theme for the Odoo backend. Applies colors, typography, hover and drag styles to kanban, list and form views (Project included).

### Features
- Jira-like palette (blues, neutrals) and modern Inter-based typography
- Enhanced kanban columns and cards: shadows, hover lift, drag feedback
- Subtle list view highlighting and refined headers
- Cleaner form view with updated statusbar and buttons
- Global backend scope (no view checks)

### Install
1. Copy or symlink this addon into your Odoo addons path, e.g.:
```bash
ln -s /workspace/project_jira_theme /opt/odoo/addons/project_jira_theme
```
2. Ensure the addons path in `odoo.conf` includes the directory containing this module.
3. Update Apps list in Odoo and install "Project Jira Theme".

No configuration is required. Styles are injected via `web.assets_backend`.

### Uninstall
- Remove the module from Apps. Cache-busted assets will revert to default.

### Technical
- Assets: `project_jira_theme/static/src/scss/project_jira_theme.scss`
- Manifest: registers SCSS in `web.assets_backend`
- Scope: `.o_web_client` (applies across backend)

### License
LGPL-3

