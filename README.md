<h1>📒 TCG Binder Planner</h1>

<p class="cta-link">
        <a href="https://biglax.github.io/virtualbinder/">🔗 Launch TCG Binder Planner</a>
    </p>

<p>A web-based tool for planning Pokémon TCG binder layouts. Designed specifically for collectors to visualize their <strong>Snorlax</strong> and <strong>Blastoise</strong> collections before sleeving them up.</p>

<h2>✨ Features</h2>

<ul>
        <li><strong>📖 Virtual Binder Interface:</strong> Realistic binder simulation with a central spine and side-by-side page spreads.</li>
        <li><strong>🔄 Dual Collection Support:</strong> Toggle between <strong>Snorlax</strong> and <strong>Blastoise</strong> card databases.</li>
        <li><strong>📐 Adjustable Layouts:</strong> Switch between <strong>4-Pocket</strong> (2x2) and <strong>9-Pocket</strong> (3x3) binder sizes.</li>
        <li><strong>🖼️ Biglax Method Support:</strong> Special logic for custom "Wide Art" (spanning two pockets). Drop wide art in the left or center columns to visually bridge the gap between slots.</li>
        <li><strong>💰 Pricing Engine:</strong>
            <ul>
                <li><strong>📊 Custom Database:</strong> Pre-loaded AUD pricing for specific cards.</li>
                <li><strong>✏️ Manual Override:</strong> Double-click any card to set your own specific price.</li>
                <li><strong>💵 Live Total:</strong> Running tally of your collection's total value in the header.</li>
            </ul>
        </li>
        <li><strong>💾 Persistence:</strong> Your layout, custom uploads, and manual prices are saved automatically to your browser's local storage.</li>
    </ul>

<h2>🚀 How to Use</h2>

<ol>
        <li><strong>➕ Add Pages:</strong> Click the <code>+</code> button in the top right to add a new spread of pages.</li>
        <li><strong>🃏 Add Cards:</strong> Drag and drop cards from the sidebar into any empty slot.</li>
        <li><strong>🎨 Biglax Method:</strong> Go to the "Custom" tab to upload wide artwork. These images require two adjacent horizontal slots (Left+Right or Center+Right).</li>
        <li><strong>🗑️ Remove Cards:</strong> Right-click a card to remove it instantly.</li>
        <li><strong>🏷️ Edit Prices:</strong> Double-click a card to enter a custom price value.</li>
    </ol>

<h2>🛠️ Installation / Hosting</h2>

<h3>🏠 Run Locally</h3>
    <p>Simply download the <code>index.html</code> file and open it in any modern web browser (Chrome, Firefox, Safari). No installation or server required.</p>

<h3>☁️ Host on GitHub Pages</h3>
    <ol>
        <li>Upload <code>index.html</code> to a GitHub repository.</li>
        <li>Go to <strong>Settings</strong> &gt; <strong>Pages</strong>.</li>
        <li>Set the <strong>Source</strong> to <code>main</code> branch and save.</li>
        <li>Your planner will be live at <code>https://your-username.github.io/repo-name</code>.</li>
    </ol>

<h2>💻 Tech Stack</h2>

<ul>
        <li>⚛️ <strong>React:</strong> For UI logic and state management.</li>
        <li>🌬️ <strong>Tailwind CSS:</strong> For styling and responsive design.</li>
        <li>🔦 <strong>Lucide React:</strong> For iconography.</li>
        <li>🐠 <strong>Babel:</strong> For in-browser JSX compilation.</li>
        <li>🗃️ <strong>TCGDex API:</strong> For fetching official card data and images.</li>
    </ul>

<hr>

<footer>Built for the ultimate Snorlax/Blastoise collector.</footer>
