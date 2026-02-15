**Your Personal Film Diary**

Log4Film-Buffs is a self-contained, browser-based film tracking application designed for cinema enthusiasts who want to keep a detailed record of their viewing journey.
No external databases, no sign-ups, no internet required after initial download—just pure, local film logging.

---

## Features

### Comprehensive Film Logging
- **Track watched films** with detailed information:
  - Film title
  - Director
  - Release year
  - Genre (15 categories available)
  - Runtime in minutes
  - Date watched
  - Personal rating (1-5 stars with interactive star selector)
  - Written review/notes

### Watchlist Management
- Maintain a separate watchlist for films you want to see
- Easily move films from watchlist to watched with a single click
- Search and filter your watchlist

### Statistics Dashboard
- **Real-time statistics** including:
  - Total films watched
  - Average rating across all films
  - Total hours of film watched
  - Watchlist count
- **Genre breakdown** showing distribution of films by genre
- **Top 5 rated films** display with full details

### Advanced Filtering & Search
- Search films by title or director
- Filter by genre
- Sort by:
  - Recently watched
  - Highest rated
  - Title (alphabetical)
  - Year of release

### Data Management
- **Export your data** to JSON format for backups
- **Import data** to restore from previous backups
- All data stored locally in your browser's localStorage

---

## How to Use

### Installation

1. Download the `log4film-buffs.html` file
2. Save it anywhere on your computer
3. Double-click the file to open it in your default web browser
4. That's it! No installation or setup required

### Getting Started

#### Adding a Film

1. Click on the **"Add Film"** tab (default view)
2. Fill in the film details:
   - **Film Title** (required)
   - **Director** (optional)
   - **Year** (optional)
   - **Genre** (optional - select from dropdown)
   - **Runtime** (optional - in minutes)
   - **Date Watched** (auto-filled with today's date)
   - **Rating** (required - click on stars to rate 1-5)
   - **Review** (optional - your thoughts on the film)
3. Check **"Add to watchlist instead of watched"** if you haven't seen it yet
4. Click **"Save Film"**

#### Viewing Your Watched Films

1. Click on the **"Watched"** tab
2. Use the search bar to find specific films by title or director
3. Filter by genre using the dropdown menu
4. Sort your collection using the sort dropdown:
   - Recently Watched (default)
   - Highest Rated
   - Title (A-Z)
   - Year

#### Managing Your Watchlist

1. Click on the **"Watchlist"** tab
2. View all films you want to watch
3. Use the search bar to find specific entries
4. Click **"Mark as Watched"** to move a film to your watched list
   - You'll be prompted to enter the date watched and rating
5. Click **"Remove"** to delete from watchlist

#### Viewing Statistics

1. Click on the **"Statistics"** tab
2. View your film-watching insights:
   - Total films watched
   - Average rating
   - Total hours watched
   - Genre distribution
   - Your top 5 rated films

---

## Data Management

### Exporting Your Data

Your film data is valuable! Create backups regularly:

1. Go to the **"Statistics"** tab
2. Click **"Export Data (JSON)"**
3. A file named `log4film-buffs-backup-YYYY-MM-DD.json` will download
4. Store this file safely (cloud storage, external drive, etc.)

### Importing Data

Restore from a backup or transfer data to another device:

1. Go to the **"Statistics"** tab
2. Click **"Import Data"**
3. Select your JSON backup file
4. Confirm the import (this will replace current data)
5. Your data will be restored

---

## Technical Details

### Data Storage

Log4Film-Buffs uses **browser localStorage** to save your data:
- All data is stored locally on your device
- No data is sent to external servers
- Data persists between browser sessions
- Data is specific to the browser being used

**Important Notes:**
- Clearing browser data/cache will delete your films
- Different browsers have separate storage (Chrome data ≠ Firefox data)
- Private/Incognito mode may not persist data after closing
- Always keep backups using the Export function

### Browser Compatibility

Works with all modern browsers:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

Requires JavaScript enabled.

### File Size

The application is a single HTML file (~50KB) containing:
- HTML structure
- CSS styling (embedded)
- JavaScript functionality (embedded)

No external dependencies or internet connection required after download.

---

## Tips for Film Buffs

### Best Practices

1. **Log films immediately** after watching while details are fresh
2. **Write meaningful reviews** to remember your impressions years later
3. **Export data monthly** to maintain current backups
4. **Use the watchlist** to plan your viewing schedule
5. **Rate honestly** to make statistics more meaningful

### Organization Ideas

- Use the **genre filter** to explore patterns in your viewing habits
- Check your **average rating** to see if you're becoming more critical over time
- Review **total hours watched** to track your film-watching commitment
- Sort by **year** to discover gaps in film history you haven't explored

### Power User Tips

- The date field auto-fills with today, but you can log past films by changing the date
- Reviews support line breaks - press Enter to create paragraphs
- Use consistent director name spelling for accurate search results
- Runtime tracking helps calculate total viewing time
- Export before major browser updates or system changes

---

## Frequently Asked Questions

**Q: Can I use this on my phone?**  
A: Yes! The interface is responsive and works on mobile browsers. Save the HTML file to your device or access it via cloud storage.

**Q: What happens if I lose my data?**  
A: If you haven't exported a backup, the data may be unrecoverable. Always maintain regular backups.

**Q: Can I share my film list with friends?**  
A: Yes! Export your data and send them the JSON file. They can import it into their own Log4Film-Buffs.

**Q: Can I customize the genres?**  
A: Currently, genres are fixed in the code. If you're comfortable with HTML, you can edit the genre dropdown in the source code.

**Q: Is there a limit to how many films I can log?**  
A: localStorage typically allows 5-10MB per domain, which can store thousands of film entries with reviews.

**Q: Can I access my data on multiple devices?**  
A: Use the Export/Import feature to transfer data between devices. Cloud storage of the HTML file and JSON backups is recommended.

**Q: Does this work offline?**  
A: Yes! Once you have the HTML file, it works completely offline.

**Q: Can I edit a film after adding it?**  
A: Currently, you would need to delete and re-add the film. Future versions may include edit functionality.

---

## Troubleshooting

### Data Not Saving
- Ensure JavaScript is enabled in your browser
- Check if you're in Private/Incognito mode (data may not persist)
- Verify sufficient localStorage space isn't exceeded
- Try a different browser

### Film Cards Not Appearing
- Check if any filters are active
- Try clearing the search bar
- Ensure films were saved to the correct list (Watched vs Watchlist)

### Import/Export Issues
- Ensure JSON file is properly formatted
- Check file isn't corrupted
- Try exporting again and comparing files
- Make sure file extension is .json

---

## Support & Feedback

This is a standalone application without official support channels. However, you can:
- Keep regular backups of your data
- Document any issues you encounter
- Share with fellow film buffs
- Customize the code to suit your needs (it's a single HTML file!)

---

## Version Information

**Current Version:** 1.0  
**Release Date:** February 2026  

---

## License & Usage

This application is provided as-is for personal use. Feel free to:
- Use it to track your films
- Share it with friends
- Modify it for personal needs
- Create backups and variations

---

## Final Notes

Log4Film-Buffs is designed for film enthusiasts who value simplicity, privacy, and complete control over their data. No accounts, no tracking, 
no cloud dependency—just you and your cinema journey.


---

**Remember:** Export your data regularly! Your film journey is worth preserving.
