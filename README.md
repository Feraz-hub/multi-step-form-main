# Multi-Step Subscription Form

A subscription selection interface built with HTML, CSS and vanilla JavaScript. The flow takes a user from personal details through plan selection and add-ons to an order summary and confirmation screen.

![Subscription form screenshot](<Screenshot (105).png>)

## Interface and interactions

- Step-by-step navigation with a progress indicator.
- Required-field checks for personal details.
- Arcade, Advanced and Pro subscription choices.
- Monthly and yearly billing options.
- Optional add-ons and a calculated summary.
- A confirmation screen after the final step.

## Stack

HTML · CSS · JavaScript · DOM events

## Run locally

No package installation or build step is required. With Python 3 installed:

```bash
git clone https://github.com/Feraz-hub/multi-step-form-main.git
cd multi-step-form-main
python -m http.server 8000
```

Open [localhost:8000](http://localhost:8000). On Windows, use `py -m http.server 8000` if `python` is not available.

## Project map

| File | Purpose |
| --- | --- |
| `index.html` | Form steps and summary markup |
| `app.js` | Navigation, selections and pricing logic |
| `style.css` | Layout, step visibility and visual states |
| `assets/` | Fonts and interface assets |

## Scope

A frontend practice implementation: it does not create accounts, charge customers or submit subscriptions to a backend. More thorough input validation, billing edge cases and accessibility checks are suitable next improvements.

## Attribution

Built from the [Frontend Mentor multi-step form challenge](https://www.frontendmentor.io/challenges/multistep-form-YVAnSdqQBJ). Supplied design assets remain credited to their original owners.

## Author

[Feranmi Adenaya](https://feraz-hub.github.io/) · [GitHub](https://github.com/Feraz-hub)
