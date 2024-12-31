
###  <em> A simple script to automatically send LinkedIn connection requests. </em>

## How to Use

### Step 1: Search on LinkedIn
1. Go to LinkedIn
2. Search for people you want to connect with (like "DevOps Engineer", "Tech Recruiter", etc.)
3. Filter results if needed (location, company, etc.)

### Step 2: Run the Script
1. Press `F12` on your keyboard (opens Developer Tools)
2. Click on "Console" tab
3. Copy all the code from [script.js](https://raw.githubusercontent.com/muhiris/autoconnect-linkedin/main/script.js).
4. Paste it in the console
5. Press Enter

### Step 3: Watch it Work!
- The script will start sending connection requests
- It scrolls through pages automatically
- You'll see status messages in the console

## ⚙️ Settings You Can Change

At the top of the script, you'll find these settings:

```javascript
config: {
    scrollDelay: 3000,        // How long to wait between scrolls
    actionDelay: 2000,        // How long to wait between actions
    nextPageDelay: 5000,      // How long to wait before next page
    maxRequests: -1,          // How many requests to send (-1 means unlimited)
    addNote: false,           // true = send with note, false = send without note
    note: "Hey {{name}}, I'm looking forward to connecting with you!"  // Your custom note
}
```

Just change these numbers as needed!

## 🛑 Important Notes

- Don't set delays too low - it might look suspicious
- LinkedIn has daily connection request limits (usually 100-150 per week)
- Better to send 20-30 requests per day to look natural
- The script works best with modern browsers (Chrome, Firefox, Edge)

## ⚠️ Be Careful!

- Using automation scripts might go against LinkedIn's terms
- Use this responsibly and at your own risk
- Don't send too many requests too quickly
- Try to connect with relevant people only

## 🐛 Common Problems & Solutions

### Script stops working?
- Refresh the page
- Run the script again

### Not sending requests?
- Check if you're on the right LinkedIn search page
- Make sure you're logged in
- Try increasing the delay times

### Getting errors?
- Clear your browser console
- Refresh the page
- Try again

Need help? Feel free to open an issue!