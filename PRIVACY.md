# SimpleBOM privacy note

SimpleBOM keeps your bills of materials on your own computer. It goes online for two things only: a problem report that you choose to send, and a check for a newer version.

## Who reads it

The developer, **alextmad**, is the only person who reads what SimpleBOM sends.

SimpleBOM is shared by personal invitation, so reach me the same way you got yours. Inside SimpleBOM you can also use **Help > Report a problem**, which needs a valid key.

## A problem report

Nothing is sent until you press **Send**. The report dialog shows everything that will go, and you can untick most of it.

A report can hold:

- what you typed under **What happened?**
- the name or email in the contact box. It starts with the name on your key, or with what you typed there last time. You can clear it.
- SimpleBOM's log, ticked by default. File paths, which contain your Windows user name, and names you typed are replaced as the log is written. It records what SimpleBOM did, not what is in your projects.
- system info, ticked by default: the SimpleBOM version, the Windows version and the WebView2 version. No user name, computer name or folder.
- the last error, ticked by default when one has just happened
- screenshots, only the ones you add
- your project file, only if you tick it. It starts unticked and is marked confidential.
- your key's short id, always, so the report can be matched to your copy

Your key goes with the report so it can be checked. The key is not stored; only its short id is kept.

If a report cannot be sent, SimpleBOM keeps it on your computer and tries again the next time it starts. Once it is sent, the copy on your computer is deleted.

Reports are stored privately, and only I can read them.

## How long it is kept

- The files of a report (the log, screenshots, project file and the report's details) are deleted automatically after 90 days.
- A short summary (your description, contact, system info, key id and error code) stays while I work on the problem. Ask me and I will delete it sooner.

## The update check

The update check asks GitHub for the latest version number. It sends nothing about you: no key, no name, no project. The answer also lists keys that have been switched off.

It runs automatically only if you said **Yes** when SimpleBOM first asked. **Help > Check for updates** runs it whenever you choose. An update is checked for a valid signature before it installs.

## Internet addresses

GitHub (for the update check) and Cloudflare (for reports) see your computer's internet address, like any website you visit. SimpleBOM does not read or keep it.

## WebView2 and Windows

SimpleBOM shows its windows with WebView2, a part of Windows. What Windows sends to Microsoft is up to your Windows **Diagnostic data** setting, which SimpleBOM does not control.

## Nothing else

SimpleBOM sends nothing else. It has no analytics, no usage tracking and no account.

## Your rights

You can ask me to show, correct or delete what you sent. Tell me roughly when you sent it, or which key you used.
