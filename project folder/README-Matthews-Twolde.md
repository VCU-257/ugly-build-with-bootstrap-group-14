# Student Name: Matthews Twolde

## 1. My Assigned Work
- payment-success.html (themed + interactive)
- payment-error.html (themed + interactive)
- custom.css (shared theme file applied across all team pages)

## 2. AI / LLM Usage
Yes, I used an AI tool to help with theming and adding JavaScript interactions.

* **What I asked the AI:**
  - "How do I override Bootstrap's :root CSS variables to change the primary and success colors without using SCSS?"

* **How it helped & What I learned:**
  The AI showed me how to override `--bs-primary`, `--bs-success`, and `--bs-body-bg` directly in a `custom.css` file linked after Bootstrap — this avoids needing SCSS compilation. I learned that Bootstrap components like `.btn-primary` still need their own class-level overrides in addition to the `:root` variables because the background-color is compiled into the button rule.

## 3. Live Site Link
* **Live URL:**
  - https://vcu-257.github.io/ugly-build-with-bootstrap-group-14/payment-success.html
  - https://vcu-257.github.io/ugly-build-with-bootstrap-group-14/payment-error.html
