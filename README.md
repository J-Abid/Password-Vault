🛡️ SecureVault: Client-Side Password Management Engine

<img width="535" height="566" alt="Screenshot 2025-12-05 124801" src="https://github.com/user-attachments/assets/a756ad6e-cd9e-4a1d-903b-cb1d102a07d3" />

🔗 Live Demonstration: https://j-abid.github.io/Password-Vault/

SecureVault is a robust, privacy-focused password management solution engineered entirely within a single HTML file. By leveraging the Web Crypto API and LocalStorage, it offers a secure, offline-capable vault for managing sensitive credentials without reliance on external servers, cloud databases, or complex build steps.

Designed with a modern Glassmorphism UI using Tailwind CSS, it combines aesthetic elegance with functional utility. It features a proprietary encryption routine that ensures data remains accessible only to the holder of the Master Password, providing a "Zero-Knowledge" architecture where no data ever leaves the user's browser.

✨ Key Features & Capabilities

🔐 Zero-Knowledge Security Architecture

Client-Side Hashing: Utilizes SHA-256 via the Web Crypto API to hash the Master Password, ensuring the key is never stored in plain text.

Local Persistence: All credential data is encrypted and stored locally within the browser's LocalStorage. No data is transmitted over the network.

Auto-Lock Mechanism: Features a secure lock screen that restricts access to the dashboard until the correct Master Password is verified.

🎨 Modern Glassmorphism UI

Responsive Dashboard: Built with Tailwind CSS, featuring a frosted-glass aesthetic (backdrop-filter) that adapts seamlessly to desktop and mobile viewports.

Visual Categorization: automatically organizes credentials into color-coded categories (Social, Finance, Work, etc.) with intuitive iconography.

Interactive Feedback: Includes toast notifications, animated transitions, and dynamic empty states for a polished user experience.

🛠️ Integrated Utility Suite

Cryptographic Generator: A built-in, configurable password generator capable of creating high-entropy strings (up to 64 chars) with toggles for symbols, numbers, and casing.

Strength Analyzer: Real-time visual strength meter that evaluates password complexity as you type, providing immediate feedback on credential security.

Smart Search & Filter: Instantly filter the vault by category or search through titles and usernames with zero latency.

💾 Data Portability

Export Capabilities: proprietary export engine allows users to download their entire vault as encrypted JSON (for backup) or CSV (for interoperability with other managers).

One-Click Copy: fast-action buttons to copy usernames or passwords to the clipboard securely.

🛠️ Technical Stack

🧱 HTML5: The entire application resides in a single semantic file.

⚡ JavaScript (ES6+): Vanilla JS handling logic, DOM manipulation, and cryptography.

🎨 Tailwind CSS: Loaded via CDN for utility-first, rapid UI styling.

🔐 Web Crypto API: Native browser API used for hashing and security operations.

💾 LocalStorage API: Used for persistent, client-side data storage.

🚀 Deployment & Usage
This project utilizes a Serverless / Build-less Architecture.
To deploy or run locally, simply open the index.html file in any modern web browser. No npm install, webpack, or backend servers are required.
Open the file in a browser.
Create a Master Password on the first run.
Manage your credentials securely offline.

** Designed by M. Junaid Abid for privacy, speed, and simplicity. **
