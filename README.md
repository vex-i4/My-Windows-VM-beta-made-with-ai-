# 🕹️ My Cloud Desktop & Steam

This repo lets you run a full Linux Desktop in your browser so you can use Steam on an iPad, Quest 2, or phone. **No PC needed!**

## 🚀 How to Start

1. Open the **Terminal** in your GitHub Codespace.
2. Paste this command to start the desktop:
```bash
docker run -d --name=webtop -p 3000:3000 linuxserver/webtop:amd64-ubuntu-mate

```


3. Go to the **Ports** tab, find **3000**, change it to **Public**, and click the link.

## 🛠️ How to Install Steam

Once you are inside the desktop, open the **Terminal icon** and run these 3 steps:

**Step 1: Unlock the tools**

```bash
sudo apt update && sudo apt install software-properties-common -y

```

**Step 2: Install Steam**

```bash
sudo apt install steam -y

```

**Step 3: Open Steam (Best for Browsers)**

```bash
steam -vgui

```

## 💡 Tips

* **Keyboard:** If you are on an iPad, use the side menu arrow to find the "On-Screen Keyboard."
* **Permission Denied?** If a file won't open, type `chmod +x filename`.

---

### 💬 Support

**Add me on discord at Enko_WZ** if you have questions!
