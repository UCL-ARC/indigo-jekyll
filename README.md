# Indigo Jekyll

Based on release 2 of the UCL Design Language (https://github.com/UCL-WAMS/indigo)

This is a Jekyll remote-theme Template providing templates, statics and example components for Indigo based sites.

## Instructions

1. Add gh username and repository to your `_config.yml` file under the `remote_theme` key:
   ```yaml
   remote_theme: UCL-ARC/indigo-jekyll
   ```
2. Add pages with YAML frontmatter per Jekyll instructions
3. Push to gh-pages branch

## Development

- CSS
  - Update sass and generate css as: 
    ```bash
	sass screen.scss ../css/screen.css
	sass screen.scss ../css/screen.min.css --style compressed
	```
