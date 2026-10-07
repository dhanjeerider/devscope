
  <h1>DevScope – Privacy Policy</h1>
  <p class="subtitle">Last updated: October 2026</p>

  <div class="highlight">
    <strong>TL;DR:</strong> DevScope collects zero data. No analytics, no tracking, no accounts, no servers. Everything stays on your device.
  </div>

  <h2>1. Data Collection</h2>
  <p>DevScope does <strong>not</strong> collect, store, or transmit any personal data, browsing history, or page content to any external server. All inspection data is processed locally in your browser and is never uploaded anywhere.</p>
  <ul>
    <li>No analytics or tracking scripts</li>
    <li>No user accounts or authentication</li>
    <li>No external server communication (except when you explicitly open external tools)</li>
    <li>No browsing history collection</li>
    <li>No personal information requested or stored</li>
  </ul>

  <h2>2. Local Data Storage</h2>
  <p>DevScope stores the following data locally using Chrome's <code>chrome.storage.local</code> API:</p>
  <ul>
    <li><strong>Site profiles:</strong> Custom CSS rules and class modifications you save per website</li>
    <li><strong>Global CSS:</strong> Custom CSS you choose to apply on all websites</li>
    <li><strong>Preferences:</strong> Theme selection, blocked domains list, tool settings</li>
    <li><strong>Tool states:</strong> Per-tool enable/disable preferences</li>
  </ul>
  <p>All this data remains on your device and can be exported or deleted at any time through the extension settings.</p>

  <h2>3. Permissions Usage</h2>
  <p>DevScope requests the minimum permissions necessary to function:</p>
  <ul>
    <li><strong>activeTab:</strong> Access the current tab when you open the popup</li>
    <li><strong>scripting:</strong> Inject CSS and run inspection scripts on pages you choose</li>
    <li><strong>storage:</strong> Save your settings, CSS profiles, and preferences locally</li>
    <li><strong>tabs:</strong> Read the current tab's URL and title for display and tool functions</li>
    <li><strong>contextMenus:</strong> Provide right-click menu options for quick tool access</li>
    <li><strong>commands:</strong> Enable keyboard shortcuts for common actions</li>
    <li><strong>cookies:</strong> Read site cookies for the Storage inspector tool</li>
    <li><strong>webNavigation:</strong> Apply saved persistent CSS when pages load</li>
    <li><strong>host_permissions (http/https):</strong> Enable persistent CSS injection across all websites you visit</li>
  </ul>

  <h2>4. External Services</h2>
  <p>DevScope includes links to external tools (PageSpeed Insights, GTmetrix, W3C Validator, etc.). When you click these links, the current page URL is sent to that external service. This is entirely optional and under your control.</p>
  <p>DevScope uses <code>html.lr7.workers.dev</code> as a CORS proxy to fetch page source HTML for Meta and SEO inspection. Only the URL of the page you're inspecting is sent to this proxy to retrieve the HTML content. No other data is transmitted.</p>

  <h2>5. Third-Party Services</h2>
  <p>DevScope does not integrate with or send data to any third-party analytics, advertising, or tracking services.</p>

  <h2>6. Data Deletion</h2>
  <p>You can delete all DevScope data at any time by:</p>
  <ul>
    <li>Using the "Clear All Data" button in the extension's Options page</li>
    <li>Uninstalling the extension (all local storage is automatically removed)</li>
  </ul>

  <h2>7. Children's Privacy</h2>
  <p>DevScope does not knowingly collect any data from anyone, including children under the age of 13.</p>

  <h2>8. Changes to This Policy</h2>
  <p>Any updates to this privacy policy will be reflected in the "Last updated" date at the top of this page.</p>

  <h2>9. Contact</h2>
  <p>For questions about this privacy policy or DevScope's data practices, please contact the developer through the Chrome Web Store listing.</p>

  <div class="footer">
    <p>DevScope v1.1.0 • Manifest V3 • Open Source Friendly</p>
    <p>© 2026 DevScope. All rights reserved.</p>
  </div>
