# Sufficiency Compass – Public Frontend

This repository contains only the public presentation layer of the Sufficiency Compass.

The public frontend includes wording, help text, navigation, input controls, bilingual presentation and PDF/print rendering. It intentionally does not include the cross-module rules, rule precedence, early-outcome logic, outcome derivation or action derivation.

Those functions are executed by a separate private decision engine.

## Configuration

After the private engine has been deployed, edit `config.js`:

```js
window.SUFFICIENCY_COMPASS_API = "https://YOUR-ENGINE-URL";
```

## Research status

- Research artefact: Frozen Toolkit V1
- Web architecture: v0.3
- Status: validation prototype
