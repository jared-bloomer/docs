# Lessons Learned: Refactor Site Code

- When using GitHub Pages, only Liquid (Jekyll) templates are supported. Jinja2 or other server-side templating languages will not be processed and will appear as literal text.
- Migrating to Jekyll layouts (`_layouts/default.html`) allows for reusable templates and proper site structure on GitHub Pages.
- Theme toggling for light/dark mode requires explicit management of Bootstrap background and text color classes for all relevant elements, including sections, headers, footers, and links.
- When switching to Jekyll, legacy template files (like `base.html`) should be removed to avoid confusion and keep the project clean.
