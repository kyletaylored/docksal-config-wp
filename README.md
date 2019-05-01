# Docksal Config: WordPress

This is a basic automated config when using Docksal and WordPress on Pantheon.

## Instructions
1. Clone to your site's root directory

```bash
cd <root site directory>
git clone https://github.com/kyletaylored/docksal-config-wp .docksal
```

2. Review and override the `docksal-local.env` and `docksal-local.yml` files as they require project specific variables.
3. Update any global variables as this is usually shared with your team. i.e `SITE_PATH`, `DOCROOT`, etc
4. Run `fin init`

```bash
fin init
```
