# STAT!

https://github.com/user-attachments/assets/51c63a57-2462-4d9f-b52b-6d3f91f65388


A drag-and-drop to-do board for Windows. Keep School, Work and Personal in their own workspaces, drag cards from **To Do** to **In Progress** to **Done**, and rename or add columns to fit how you work.

- Type `- ` for bullets, or use the toolbar for checklists, numbered lists, **bold**, *italic*, <ins>underline</ins> and ~~strikethrough~~
- Expand a card's notes to a full page when you have a lot to write
- Attach, paste or drop images on a card. The first one becomes the card's cover, and you can view, download or copy any of them full size
- Add due dates, priorities and links to any card
- Color whole cards in pastel shades
- Light, dark or automatic theme
- Every change saves the moment you make it

## Download

Get the latest version from the [**Releases page**](https://github.com/Nej2005/stat-app/releases/latest). There are two versions to choose from:

| File | What it is |
|---|---|
| **[STAT-Setup-0.8.1.exe](https://github.com/Nej2005/stat-app/releases/latest/download/STAT-Setup-0.8.1.exe)** | Installer (recommended). Adds STAT! to the Start menu and desktop, and can be uninstalled from Windows Settings. |
| **[STAT-Portable-0.8.1.exe](https://github.com/Nej2005/stat-app/releases/latest/download/STAT-Portable-0.8.1.exe)** | Single file, no install. Just double-click to run. |

Requires Windows 10 or 11 (64-bit). Already have an older version? Install the new one over it; your tasks are kept.

### "Windows protected your PC"

STAT! isn't code-signed yet, so the first time you run it Windows SmartScreen may show this warning. Click **More info**, then **Run anyway**. You only need to do this once.

## Your data

Your boards, including the images on them, are stored only on your own PC, at `%APPDATA%\STAT!\stat.db`. STAT! runs a small local server on `127.0.0.1` that only your PC can reach. There's no account to make and nothing is uploaded. The installer and the portable version share the same data.

To back up your tasks, close STAT! and copy that folder. Uninstalling the app keeps your data. Delete the folder yourself if you want it gone.
