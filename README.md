# Starling Workflow Demo

This is a browser-based prototype of a technician work-order workflow.

## Demo flow
1. Open index.html.
2. Choose a work order.
3. Read the current instructions.
4. Click "Mark Step Done".
5. The next step unlocks.
6. Return to the Work Orders page to see progress and the manager overview.

## Important
This version is a front-end demo. Progress is stored in the browser using localStorage. It is NOT yet a multi-user/server-backed production system.

## Publish
The easiest free option is GitHub Pages:
1. Create a GitHub account.
2. Create a new public repository, e.g. `starling-workflow-demo`.
3. Upload `index.html` and `README.md`.
4. Open repository Settings -> Pages.
5. Set Source to "Deploy from a branch".
6. Select the `main` branch and `/ (root)`.
7. Save.
8. GitHub will provide a public URL.

For a real product, replace localStorage with authentication + a database/API so multiple phones and managers share the same records.
