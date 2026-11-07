# J.A.R.V.I.S. — Personal AI Operating System (`arceas71/jarvis`)

A futuristic, minimalist **J.A.R.V.I.S.** AI Operating System crafted with an Obsidian & Charcoal palette (`#17191D`, `#25252D`), Deep Royal Purple (`#6841A5`) accents, and Titanium Silver (`#AAB8C8`) structure.

Works on **both Phone (native Android APK + mobile web)** and **Laptop (desktop browser + GitHub Actions)**.

---

## 🚀 Quick Start: How to Deploy to `arceas71/jarvis`

1. Extract this zip archive and push all files to your [`arceas71/jarvis`](https://github.com/arceas71/jarvis) repository on GitHub.
2. Open your repository on GitHub and click the **Actions** tab at the top.
3. You will see two ready-to-run workflows:
   - **📱 `Build JARVIS Android APK & Deploy Web OS`** (`build-apk.yml`):
     - Click **Run workflow**.
     - GitHub's cloud runner automatically builds the Capacitor Android project and packages `app-debug.apk`.
     - When the run finishes (~2 minutes), scroll down to **Artifacts** at the bottom of the workflow summary and click **`jarvis-android-apk`** to download the APK to your phone!
   - **🤖 `JARVIS Autonomous AI Agent (GitHub Models)`** (`jarvis-agent.yml`):
     - Click **Run workflow**, enter any task prompt, choose your free **GitHub Models** brain (`gpt-4o-mini`, `gpt-4o`, `Llama-3.3-70B-Instruct`, or `Phi-4`), and click **Run**.
     - Uses your built-in `GITHUB_TOKEN` (with `models: read` permission) to run autonomous file inspection and code generation right inside the Actions tab.

---

## 💻 Running on Phone vs. Laptop

| Device | How It Works |
| :--- | :--- |
| **Android Phone** | Download `jarvis-android-apk` from the **Actions** tab Artifacts and install the native APK, or open the GitHub Pages URL in Chrome/Brave. |
| **Laptop / Desktop** | Open `index.html` directly in any browser, or enable **GitHub Pages** (`Settings -> Pages -> Deploy from main branch`) for an always-online URL. |
| **iPhone / iPad** | Open the GitHub Pages URL in Safari and tap **Share -> Add to Home Screen** for a full-screen standalone app. |
