# AlienTech42 Unraid Templates

This repository contains Unraid Docker templates used in my videos.

These templates allow you to quickly install containers without manually entering all settings.

---

## Available Templates

### Homelab Hub

* Manual install shown in video
* Template available for quick setup

👉 [Open Homelab Hub Template](./homelab-hub/)

---

## How to Use

1. Download the `.xml` file
2. Place it in:

   ```
   /boot/config/plugins/dockerMan/templates-user/
   ```
3. Go to:
   Docker → Add Container → Select Template

---

## Notes

* You may need to adjust ports depending on your setup
* Appdata path assumes:

  ```
  /mnt/user/appdata/
  ```
