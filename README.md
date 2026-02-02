Outlook Mail Tracker Board
iOS-optimized email tracking application for Outlook/Office 365
📱 Live Demo
Once deployed to GitHub Pages, your app will be available at:
https://YOUR-USERNAME.github.io/outlook-mail-tracker/
🚀 Quick Deploy to GitHub Pages
Step 1: Create GitHub Repository

Go to GitHub.com and sign in
Click the "+" icon (top right) → "New repository"
Name it: outlook-mail-tracker
Make it Public
Click "Create repository"

Step 2: Upload Files
Option A: Upload via Web Interface

On your new repository page, click "uploading an existing file"
Drag and drop the index.html file
Click "Commit changes"

Option B: Use Git Command Line
bashgit clone https://github.com/YOUR-USERNAME/outlook-mail-tracker.git
cd outlook-mail-tracker
# Copy index.html into this folder
git add index.html
git commit -m "Initial commit"
git push origin main
Step 3: Enable GitHub Pages

Go to repository Settings
Scroll to "Pages" (left sidebar)
Under "Source", select "main" branch
Click "Save"
Wait 1-2 minutes for deployment

Step 4: Access Your App
Your app will be live at:
https://YOUR-USERNAME.github.io/outlook-mail-tracker/
✅ Microsoft OAuth Setup
The app uses Microsoft's public Graph Explorer client ID (d3590ed6-52b3-4102-aeff-aad2292ab01c), which allows:

✅ Read emails
✅ Read user profile
✅ Read mailbox settings
✅ Works immediately without Azure AD setup

If You Want Your Own Client ID

Go to Azure Portal
Navigate to Azure Active Directory → App registrations
Click "New registration"
Set redirect URI to your GitHub Pages URL
Grant permissions: User.Read, Mail.Read
Replace CLIENT_ID in index.html

📧 Features

🔐 Secure OAuth - Microsoft authentication
📁 Folder Selection - Choose which folders to track
🔄 Real-time Sync - Get latest emails
📝 Custom Tracking - Status, Priority, Owner, Notes
🔍 Search & Filter - Find emails quickly
💾 CSV Export - Download tracking data
📱 iOS Optimized - Perfect for iPhone

🔒 Privacy & Security

✅ All data stays in your browser (localStorage)
✅ No server-side storage
✅ Direct connection to Microsoft Graph API
✅ Tokens expire after 1 hour
✅ Read-only access to emails

💡 Usage

Connect - Sign in with your Outlook account
Select Folders - Choose which folders to track
Track - Add status, priority, and notes to emails
Sync - Refresh to get new emails
Export - Download your tracking data

🆘 Troubleshooting
"HTTPS required" error:

Make sure you're accessing via GitHub Pages URL (https://)
Don't open the file directly from your phone

Login issues:

Clear browser cache and try again
Make sure you're using Safari or Chrome
Check that cookies are enabled

No emails loading:

Select folders in the "Folders" menu
Check your internet connection
Try disconnecting and reconnecting

📄 License
MIT License - Free to use and modify
👨‍💻 Customization
To change the pre-filled email address, edit line 240 in index.html:
javascriptlet userEmail = 'your-email@company.com';
🔗 Repository URL
https://github.com/YOUR-USERNAME/outlook-mail-tracker
Replace YOUR-USERNAME with your GitHub username after creating the repository.
