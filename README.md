# 🚀 GitHub Auto Commit

This repository features an automated GitHub Action workflow designed to regularly update the repository with scheduled, aesthetic commit messages.

## ✨ Features
- ⏰ **Automated Schedule:** Runs 4 times a day (`09:23`, `14:23`, `18:23`, and `21:23` WIB / UTC+7).
- 📜 **Poetic & Dynamic Commit Messages:** Rotates through a rich collection of Indonesian poetic and technical messages with live time-zone timestamps (`WIB`).
- ⚡ **Anti-Failure & Safe Loop Handling:** Includes automated diff checks to prevent empty commit errors and infinite build loops.
- ⚙️ **Manual Trigger:** Supports `workflow_dispatch` for manual execution anytime via the GitHub interface.

---

## 🛠️ How It Works

The workflow updates a timestamp in the `last_update` file and commits the changes automatically.

### Scheduled Execution Times (UTC+7 / WIB):
- 🌅 **09:23 WIB** (`02:23 UTC`)
- ☀️ **14:23 WIB** (`07:23 UTC`)
- 🌆 **18:23 WIB** (`11:23 UTC`)
- 🌙 **21:23 WIB** (`14:23 UTC`)

---

## 🚀 Setup & Usage

### 1. Enable GitHub Actions
1. Fork or clone this repository.
2. Go to the **Actions** tab in your GitHub repository and click **"I understand my workflows, go ahead and enable them"**.

### 2. Configure Write Permissions
To allow the workflow to push commits back to the repository:
1. Go to **Settings** $\rightarrow$ **Actions** $\rightarrow$ **General**.
2. Scroll down to **Workflow permissions**.
3. Select **"Read and write permissions"** and click **Save**.

### 3. Manual Test (Optional)
Navigate to **Actions** $\rightarrow$ **Auto commit** $\rightarrow$ click **Run workflow** to test it instantly without waiting for the scheduled cron time.

---

*Automated and maintained by **TangerangKota-CSIRT Commit Bot**.*
