# Islamic Clock Dashboard

A beautiful, feature-rich dashboard clock designed specifically for Muslims. This elegant timepiece combines essential daily tools with Islamic features to help you stay organized and connected to your faith throughout the day.

![Theme](https://img.shields.io/badge/theme-dark%2Flight-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Features

### Core Features
- **Real-time Clock** - Large, clear digital clock with seconds
- **Date Display** - Current date and ISO week number
- **Dual Theme Support** - Dark (default) and Light themes with smooth transitions
- **Auto Theme Detection** - Automatically follows system theme preferences

### Islamic Features
- **Prayer Times** - Accurate daily prayer times for your location
  - Supports multiple calculation methods (MWL, ISNA, Umm al-Qura, etc.)
  - Asr time calculation options (Shafi'i/Maliki/Hanbali or Hanafi)
  - Auto-detect location or manually set coordinates
  - Countdown timer to next prayer
- **Quran Audio Player** - Listen to all 114 Surahs
  - Full Surah library with Alafasy recitation
  - Loop mode for repeating current Surah
  - Auto-next mode for continuous playback
- **Daily Hadith** - Rotating collection of authentic hadiths
- **Location Display** - Shows detected or configured coordinates

### Productivity Features
- **Todo List** - Built-in task management
  - Add, edit, and delete tasks
  - Mark tasks as complete
  - Persistent storage (saved locally)
  - Task counter display
- **World Clocks** - Add multiple city clocks
  - Pre-configured major cities worldwide
  - Easy add/remove functionality
- **Quick Access Bookmarks** - Your favorite websites
  - Custom names and URLs
  - Emoji/icon support
  - One-click access

### UI/UX Features
- **Collapsible Sidebars** - Toggle left (Todo) and right (Prayer) panels
- **Responsive Design** - Works on desktop and tablets
- **Settings Modal** - Centralized configuration panel
- **Local Storage** - All preferences saved automatically

---

## Installation Guide

### Quick Start (Local Usage)
1. Download or clone this repository
2. Locate the `clock.html` file
3. Double-click to open in your default browser
4. For best experience, set as homepage using instructions below

---

## Setting as Browser Homepage

### Google Chrome

#### Method 1: Using Extension (Recommended for New Tab)
This method replaces the New Tab page with the clock dashboard.

1. Open Chrome Web Store
2. Search for **"New Tab Redirect"** extension or [click here](https://chrome.google.com/webstore/detail/new-tab-redirect/icpgjfneehieebagbmdbhnlpiopdcmfc)
3. Click **"Add to Chrome"** and confirm installation
4. Click the puzzle icon (Extensions) in the toolbar
5. Find **New Tab Redirect** and click the gear icon (Options)
6. In the **Redirect URL** field, enter the path to your file:
   - **Local file path** (macOS): `file:///Users/YOUR_USERNAME/Path/To/clock.html`
   - **Local file path** (Linux): `file:///home/YOUR_USERNAME/Path/To/clock.html`
   - **Local file path** (Windows): `file:///C:/Users/YOUR_USERNAME/Path/To/clock.html`
   - **Hosted URL**: `https://yourdomain.com/clock.html`
7. Click **Save**
8. Open a new tab to test - your clock should appear!

**Troubleshooting:** If you see an error about local files, you may need to grant the extension permission to access local files:
- Go to `chrome://extensions/`
- Find New Tab Redirect
- Enable **"Allow access to file URLs"**

#### Method 2: On Startup (Opens when Chrome launches)
1. Open Chrome Settings (click three dots ⋮ > Settings)
2. Go to **"On startup"** section in the left sidebar
3. Select **"Open a specific page or set of pages"**
4. Click **"Add a new page"**
5. Enter the file path:
   - macOS: `file:///Users/YOUR_USERNAME/Path/To/clock.html`
   - Windows: `file:///C:/Users/YOUR_USERNAME/Path/To/clock.html`
   - Linux: `file:///home/YOUR_USERNAME/Path/To/clock.html`
6. Click **Add**
7. Restart Chrome to test

**Note:** This method only opens the clock when Chrome starts, not on every new tab.

---

### Mozilla Firefox

#### Method 1: Using about:config (Advanced)
This method sets the homepage that loads when Firefox starts.

1. Open Firefox and type `about:config` in the address bar
2. Click **"Accept the Risk and Continue"**
3. In the search bar, type: `browser.startup.homepage`
4. Double-click the entry to edit it
5. Enter the full path to your file:
   - macOS: `file:///Users/YOUR_USERNAME/Path/To/clock.html`
   - Windows: `file:///C:/Users/YOUR_USERNAME/Path/To/clock.html`
   - Linux: `file:///home/YOUR_USERNAME/Path/To/clock.html`
6. Press **Enter** to save
7. Restart Firefox - your clock will load on startup

#### Method 2: Using Settings (Easier)
1. Open Firefox Settings:
   - Click the hamburger menu (☰) > **Settings**
   - Or type `about:preferences` in the address bar
2. Go to the **Home** section
3. Under **"Homepage and new windows"**, select **"Custom URLs..."** from the dropdown
4. Enter the path to your file:
   - `file:///Users/YOUR_USERNAME/Path/To/clock.html`
5. Close the settings tab - changes save automatically

#### Method 3: Using Extension (For New Tab Override)
To replace the New Tab page (not just homepage):

1. Open Firefox Add-ons:
   - Click the menu button > **Add-ons and themes**
   - Or visit [addons.mozilla.org](https://addons.mozilla.org)
2. Search for **"New Tab Override"**
3. Click **"Add to Firefox"** and confirm
4. After installation, click the extension icon in your toolbar
5. Select **"File"** tab
6. Click **"Select File"** and navigate to `clock.html`
7. Click **Open** to confirm
8. Your clock will now appear on every new tab

---

### Microsoft Edge

#### Method 1: On Startup
1. Open Edge Settings (three dots > Settings)
2. Go to **"Start, home, and new tabs"**
3. Under **"When Edge starts"**, select **"Open these pages"**
4. Click **"Add a new page"**
5. Enter: `file:///Users/YOUR_USERNAME/Path/To/clock.html`
6. Click **Add**

#### Method 2: Using Extension
1. Open Chrome Web Store (Edge supports Chrome extensions)
2. Install **"New Tab Redirect"**
3. Follow the same steps as Chrome Method 1

---

### Safari (macOS)

1. Open Safari
2. Go to **Safari > Preferences** (or press Cmd+,)
3. Click the **Tabs** tab
4. Set **"Homepage"** to your file path:
   - `file:///Users/YOUR_USERNAME/Path/To/clock.html`
5. Go to the **General** tab
6. Set **"Homepage"** field to the same URL
7. Set **"New windows open with"** to **Homepage**

**Note:** Safari may require you to host the file on a web server for full functionality.

---

### Opera

1. Open Opera Settings (gear icon or Alt+P)
2. Under **"On startup"**, select **"Open a specific page or set of pages"**
3. Click **"Add new page"**
4. Enter: `file:///Users/YOUR_USERNAME/Path/To/clock.html`
5. Click **Add**

---

## Usage Guide

### Todo List (Left Sidebar)
1. Click **"+ Add Task"** to create a new task
2. Enter task description, optional date and time
3. Click **"Save Task"**
4. Click on a task to mark it complete/incomplete
5. Click the **X** button to delete a task
6. Use the **▶/◀** button in the top-left to toggle the sidebar

### Prayer Times (Right Sidebar)
1. On first load, click **"Auto-Detect Location"** to set your coordinates
2. Or open Settings (⚙️) to manually enter latitude/longitude
3. Select your preferred **Calculation Method**
4. Choose **Asr Method** (Shafi'i or Hanafi)
5. Click **"Save Prayer Settings"**
6. View countdown to next prayer in the right sidebar

### Quran Audio
1. Select a Surah from the dropdown
2. Audio will start playing automatically
3. Use the audio controls (play/pause/volume)
4. Enable **Loop** to repeat the current Surah
5. Enable **Auto Next** to play Surahs sequentially

### World Clocks
1. Click the **"+"** button in the World Clocks section
2. Select a city from the dropdown
3. Click **"Add Clock"**
4. Hover over a clock and click **X** to remove it

### Bookmarks (Quick Access)
1. Click the **"+"** button in Quick Access section
2. Enter bookmark name (e.g., "Google")
3. Enter full URL (e.g., https://google.com)
4. Add an emoji or icon (optional)
5. Click **"Add"**
6. Click any bookmark to open the website

### Theme Settings
1. Click **⚙️ Settings** button
2. Under **Theme**, select:
   - **Auto** - Follows system preference
   - **Dark** - Dark theme (default)
   - **Light** - Light theme
3. Changes apply immediately

---

## Hosting Options

### Local File (No Hosting Required)
Simply open the file directly in your browser:
```bash
# macOS/Linux
open clock.html

# Windows
start clock.html
```

### GitHub Pages (Free Hosting)
1. Create a new repository on GitHub
2. Upload `clock.html`
3. Go to **Settings > Pages**
4. Select your branch and click **Save**
5. Your site will be live at `https://username.github.io/repo-name/clock.html`

### Netlify (Free Hosting)
1. Sign up at [Netlify](https://netlify.com)
2. Drag and drop the folder containing `clock.html`
3. Your site will be live instantly

### Vercel (Free Hosting)
1. Install Vercel CLI: `npm i -g vercel`
2. Navigate to the folder and run: `vercel`
3. Follow the prompts to deploy

---

## Technical Details

- **Single File** - Everything (HTML, CSS, JavaScript) is contained in one file
- **No Dependencies** - No external libraries required
- **Local Storage** - All data saved to browser's localStorage
- **APIs Used**:
  - Aladhan API for prayer times
  - Islamic Network / MP3Quran for Quran audio
  - Browser Geolocation API for location detection

### Browser Compatibility
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### Privacy
- All data is stored locally in your browser
- No data is sent to external servers except:
  - Prayer times API (coordinates sent for calculation)
  - Quran audio streams (audio requests)

---

## Customization

### Changing Accent Color
Edit the CSS variables in the `<style>` section:
```css
:root {
    --accent-color: #5a6c7d;  /* Change this */
    --accent-hover: #4a5a6a;  /* Change this */
}
```

### Adding World Clock Cities
Find the `worldClockModal` section and add new options:
```html
<option value="Timezone/City">City, Country</option>
```

### Changing Default Theme
Modify the initialization in the JavaScript:
```javascript
function getPreferredTheme() {
    return 'dark'; // Change from 'auto' to 'dark' or 'light'
}
```

---

## License

MIT License - Feel free to use, modify, and distribute.

---

## Support

If you encounter any issues or have suggestions for improvements, feel free to:
- Open an issue on GitHub
- Submit a pull request
- Share with others who might benefit

---

**Enjoy your Islamic Clock Dashboard!** 🕌 ⏰
