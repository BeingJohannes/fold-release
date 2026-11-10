# Fold

All your tasks, one calm list. Fold brings together what's assigned to you in
Notion, Jira, GitLab and Microsoft To Do, your calendars, and its own tasks,
and sorts it all into **streams**: the big areas of your work and life. Free,
and everything stays on your computer.

## Download

| | |
| --- | --- |
| **Mac** (Apple Silicon: M1 or later) | [Download Fold for Mac](https://github.com/BeingJohannes/fold-release/releases/latest/download/Fold-mac-arm64.dmg) |
| **Windows 10/11** (most PCs: x64) | [Download Fold for Windows](https://github.com/BeingJohannes/fold-release/releases/latest/download/Fold-win-x64.exe) |
| **Windows on ARM** (e.g. Surface Pro X, Snapdragon laptops) | [Download Fold for Windows ARM](https://github.com/BeingJohannes/fold-release/releases/latest/download/Fold-win-arm64.exe) |

These links always give the newest version. Every version and what changed:
[Releases](https://github.com/BeingJohannes/fold-release/releases).

Not sure which Windows one you need? Open **Settings → System → About** and
look at **System type**: it says "x64" or "ARM".

## What it does

- **One view of your day.** Today, this week, this month or everything, as
  columns (one per stream) or a list. Overdue, today and soon stand out.
- **Brings in your tools.** Notion databases, Jira and GitLab issues,
  Microsoft To Do lists, and Google, Outlook or iCloud calendars. Switch a
  Notion database or a Jira/GitLab project to **two-way** and you can tick
  things off, change dates and priorities in Fold, and it saves back.
- **Your day's meetings** on a timeline across the top of Today.
- **Quick changes on a card.** Click the circle to tick it off (right-click
  for In progress, Blocked…), click the date or priority to change it, drag a
  task to another stream.
- **Search everything** with ⌘F, and add a task from anywhere with ⌥⇧Space.
- **Works with Claude.** One click in Settings lets Claude see your streams
  and plan with you.
- Light and dark, a slim sidebar mode, and keyboard shortcuts for most things.

## Installing

Fold isn't signed with a paid Apple or Microsoft certificate yet, so you'll see
a warning the first time you open it. You only do this once.

**Mac**

1. Open the downloaded `.dmg` and drag **Fold** to **Applications**.
2. Open Fold from Applications.
3. If macOS says it can't check Fold: open **System Settings → Privacy &
   Security**, scroll down and click **Open Anyway**.
4. When you connect a tool, macOS asks to let Fold use its Keychain item.
   Enter your Mac password and choose **Always Allow**.

**Windows**

1. Run the downloaded installer. Fold opens and adds itself to the Start menu.
2. If Windows says "Windows protected your PC": click **More info → Run anyway**.
3. If Windows Security removed Fold (a "Missing Shortcut" message): open
   **Windows Security → Virus & threat protection → Protection history**,
   choose Fold and click **Restore**.

## Updating

Fold tells you when a new version is out (a card in the sidebar, and
**Settings → General → App → Updates**). Download it from the same link and
install it over the top: your tasks and settings are kept.

On a Mac, the first update from version 0.5.1 onwards may ask for your password
once more; choose **Always Allow** and later updates won't ask again.

## Your data

Tasks, plans and settings are stored on your computer, not on a server.
Tokens and calendar links are kept in your Mac's Keychain or Windows
Credential Manager. Fold only changes things in your tools where you've
switched a database or project to two-way, never touches calendars or
Microsoft To Do, and never deletes or archives anything there.
