# Homelab Hub (Unraid Template)

This template installs Homelab Hub on Unraid.

## Template Includes

* Repository: `raidowl/homelab-hub:latest`
* WebUI configured
* Appdata path set
* Port mapped

---

## Installation

### Option 1 (Recommended)

Follow the full setup in the video:
👉 [Watch Video](#)

### Option 2 (Quick Install)

1. Download `my-homelab-hub.xml`
2. Place it in:

   ```
   /boot/config/plugins/dockerMan/templates-user/
   ```
3. Go to:
   Docker → Add Container
4. Select `homelab-hub`

---

## Notes

* Default port: `8000`
* Container port: `8000`
* You may need to adjust port if already in use

---

## Icon

The template includes a default icon for convenience.
