# Emergency Fund Calculator

SimpleKit Emergency Fund Calculator is a static, privacy-friendly planning tool that helps users:

- estimate an emergency fund target
- compare that target with current savings
- see the remaining shortfall
- estimate how long it may take to reach the goal

## Stack

- static `index.html`
- local styling in `assets/css/styles.css`
- calculator logic in `assets/js/app.js`
- shared SimpleKit shell from `https://core.simplekit.app`

## Notes

- The shared SimpleKit core linkage is preserved.
- The Google Analytics snippet in `index.html` is preserved.
- No build step is required.
- Inputs stay in the browser and can be shared through URL parameters when copying a calculator link.

## Main Features

- core emergency fund calculator inputs
- prominent 3, 6, 9, and 12 month target selection
- advanced options for interest, bi-weekly contributions, lump-sum boost, and custom months
- dynamic plain-English summary and guidance
- progress bar and projected target timing
- educational content, FAQ, and related-tool links

## Local Preview

Because this is a static repo, you can preview it with any simple file server from the project root, for example:

```bash
python3 -m http.server
```
