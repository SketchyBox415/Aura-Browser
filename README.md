### Aura Browser

Aura is a modern, secure, and privacy-focused desktop web browser built with Electron and React. It features a sleek glassmorphic UI, native ad-blocking, built-in AI assistance, and robust local data security.

### Features

### 1\. Core Architecture & Security

*   **Secure IPC Bridge:** Utilizes a restricted `preload.js` script to context-isolate the React UI from direct Node.js access.
*   **Local Database Engine:** Powered by `better-sqlite3` to manage Bookmarks, History, Downloads, Passwords, and Settings locally.
*   **Encrypted Credentials:** Secures user passwords using industrial-grade AES-256-GCM encryption with a native system key.
*   **Network-Level Ad Blocker:** Integrates `@cliqz/adblocker-electron` to intercept network requests and filter out EasyList ads and trackers.
*   **Native Download Manager:** Hooks into Electron's session layer to safely intercept and route files to your local Downloads folder.

### 2\. Sleek UI (Dark Glassmorphism)

*   **Custom Title Bar:** A seamless, frameless window layout featuring custom navigation controls and the signature Aura gradient branding.
*   **Advanced Tab Strip:** Scrollable and dynamically resizable tab ecosystem supporting native context menus (Pin, Mute, Duplicate, and Close Others).
*   **Smart Omnibox:** A unified address and search bar featuring responsive, real-time dropdown suggestions pulled from your local history.
*   **Dynamic New Tab Page:** A minimalistic landing experience built around a beautiful gradient clock and quick-access shortcuts.
*   **Native Split View:** Enhances productivity by allowing users to dock and control two web sessions side-by-side.

### 3\. Integrated Sidebars & Utilities

*   **Unified Workspace Sidebars:** Quick-access panels to seamlessly manage your History, Bookmarks, and ongoing Downloads.
*   **Built-in AI Assistant:** A fully integrated sidebar chat experience utilizing OpenRouter to connect you with top-tier language models on the fly.
