# MFG Purchase Quick Count — UI/UX prototype (demo)

A **sanitized** build of the purchase-analytics UI/UX prototype, published so it
can be reviewed in a browser.

**All data in this build is synthetic.** Category names, SKU counts, stock and
purchase-order figures, warehouse provenance and operator names are invented for
the demo. No production or client data is present.

Two surfaces:
- **Mobile app** — exception list, purchase recap, recap history, profile
- **Backoffice portal** — claim queue, persons, devices, target (par) editor
- **Design language** — the token set, lane/stamp library and measured contrast

Deep links work, e.g. `?surface=mobile&screen=recap` or `?surface=portal&screen=par`.

This repository contains only build output. Source and the real dataset live in
the private repository.
