Yahtzee Logic System v10.0
A Professional-Grade, Multi-Player Digital Scorecard

This is a standalone, browser-based Yahtzee management system designed for high-efficiency data entry, strategic tracking, and multi-user competitive play. Built with a "Clean Slate" architecture, it allows for total customization of player sets and visual environments.

🚀 Core Features
🛠 Technical Architecture
Zero-Footprint Hosting: Single-file HTML5/CSS3/JavaScript solution. No server-side database required.
Local State Persistence: Utilizes localStorage to ensure game data and theme preferences survive browser refreshes or accidental tab closures.
Responsive Dashboard: Optimized for both desktop and mobile (landscape/portrait) viewing.
Clean Input Logic: Custom CSS overrides to remove distracting browser "spinners" (incremental arrows) for a pure data-entry experience.

📊 Advanced Scoring Engine
Binary Toggle System: Lower section categories (Full House, Straights, Yahtzee) use a three-state toggle (Scored / Zeroed / Clear) to eliminate manual typing.
Strategic Delta Tracking: Dynamic "Points Needed" indicator for the Upper Section to help players track the 35-point bonus threshold in real-time.
Yahtzee Bonus Validation: Intelligent logic prevents "Yahtzee Bonus" (+100) checks unless a primary Yahtzee (50) is recorded, ensuring adherence to official rules.
Leader Detection: Real-time CSS highlighting (Gold Border) automatically identifies the current point leader across all columns.

🎨 User Experience (UX)
Dynamic Column Management: Ability to add or remove players on the fly.
Theme Engine: 9 distinct visual modes including:
Midnight: Modern dark mode.
PLM Dashboard: Professional high-contrast light mode.
Matrix Terminal: Retro-hacker aesthetic.
Cyberpunk: High-energy neon.
Nordic Frost: Clean, minimal aesthetic.
Hard Reset Functionality: Separate "Clear Scores" (keep players) and "Hard Reset" (wipe all system data) options.

🛠 Usage Instructions
Add Players: Click the + Add Player button and enter the names (e.g., You, Rachel, Kaleb, Landen).
Enter Scores: * Type numbers into the Upper Section or Chance boxes.
Click the buttons for Straights/Full House/Yahtzee to toggle between the set score and a zero.
Track the Bonus: Watch the "X more needed" text under the Upper Subtotal to gauge your progress toward the 35-point bonus.
Manage Themes: Use the dropdown menu to switch themes instantly based on your environment.

📁 Installation
Clone this repository or download the index.html file.
Open index.html in any modern web browser.
(Optional) Deploy to GitHub Pages for a private, shareable mobile link.
Developed for the analytical strategist.
