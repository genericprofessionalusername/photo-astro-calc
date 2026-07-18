# Contributing to Photo-Astro-Calc

Thank you for your interest in improving this project! Because this is a monolithic application (everything lives in `index.html`), contributing is straightforward and requires no local server setup.

## How to Contribute

### 1. Report Bugs or Request Features
* Check the **Issues** tab to see if your topic is already being discussed.
* If not, open a new issue describing the bug or feature request clearly.

### 2. Make Code Changes
Since the entire application is contained in a single file, follow these steps to propose changes:

1. **Fork the Repository:** Click the "Fork" button at the top right of this page to create your own copy.
2. **Create a Branch:** Create a new branch in your fork for your changes (e.g., `fix-exposure-calc`).
3. **Edit the File:** Modify the `index.html` file. 
   * Keep the embedded CSS inside the `<style>` tags organized.
   * Keep JavaScript functions clean and documented inside the `<script>` tags.
4. **Test Locally:** Open your modified `index.html` file directly in any web browser to test your changes. Ensure no console errors appear.
5. **Commit & Push:** Commit your changes with a clear, descriptive commit message.

### 3. Submit a Pull Request (PR)
* Open a Pull Request from your branch back to our `main` branch.
* In your PR description, explain **what** you changed and **why**.
* If your PR fixes an open issue, include `Fixes #IssueNumber` in the description.

## Code Guidelines
* **Keep it Vanilla:** Use standard HTML5, CSS3, and modern, plain JavaScript. Avoid adding external framework dependencies (like React or Vue) to keep the project lightweight.
* **Format:** Maintain consistent indentation (2 or 4 spaces) to keep the single-file architecture readable.
* **Performance:** Keep mathematical formulas optimized since all calculations run client-side in the user's browser.

## Other
* If you think thare are meaningful improvements going away from a single page I'm all ears, but I'm also lazy.
