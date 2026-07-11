# Demo Blueprints

WordPress Playground blueprints for spinning up on-demand demo sites.

## Demos

| Demo | Launch | Blueprint |
| --- | --- | --- |
| Starter | [Launch](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/pattonwebz/playground-blueprints/main/blueprints/starter.json) | [starter.json](blueprints/starter.json) |
| A11y Theme Unit Test | [Launch](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/pattonwebz/playground-blueprints/main/blueprints/a11y-theme-unit-test.json) | [a11y-theme-unit-test.json](blueprints/a11y-theme-unit-test.json) |
| A11y Theme Unit Test + Accessibility Checker | [Launch](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/pattonwebz/playground-blueprints/main/blueprints/a11y-theme-unit-test-with-checker.json) | [a11y-theme-unit-test-with-checker.json](blueprints/a11y-theme-unit-test-with-checker.json) |

The A11y Theme Unit Test demo imports the [WP Accessibility team's theme unit test data](https://github.com/wpaccessibility/a11y-theme-unit-test) — the standard Theme Unit Test content tuned for accessibility testing.

## Structure

- `blueprints/` — Playground blueprint JSON files
- `content/` — WXR export files referenced by blueprints

## Usage

Launch any blueprint with:

```
https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/pattonwebz/playground-blueprints/main/blueprints/<name>.json
```

For customer-facing links, pin to a tag or commit SHA instead of `main` so demos don't change when the repo is edited.

Test a blueprint locally before publishing:

```
npx @wp-playground/cli server --blueprint=blueprints/<name>.json
```
