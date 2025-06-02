# XenScope - Xbox 360 Preservation Tool

![newbackground](https://github.com/user-attachments/assets/3a6ff2ee-94f9-477e-b4d0-d186d371d29a)


## What the Tool Does

### 1. File Comparison and Analysis
- **Compare Folders**: Add multiple folders (e.g., game builds) and compare their contents.
- **File Hashing**: Computes MD5 hashes and sizes, highlighting differences and missing files.
- **XEX Metadata Extraction**: Uses xextool to extract and display metadata from `.xex` files.
- **Filtering**: Filter by file type (XEX, DDS, XMA, XML, etc.) and text.
- **Preview and Diff**: Preview files and launch external diff tools (e.g., WinMerge).
- **Recent Folders**: Remembers recently compared folders.

### 2. Xbox Neighborhood Pro (XDK File Manager)
- **Connect to Xbox 360 Dev/Test Kits** using XBDM protocol (via IP).
- **Browse, upload, download, and delete** files/folders on the console.
- **Recursive Upload/Download** support.
- **Drive Info**: Show free space on console drives.
- **Raw XDK Commands** and view responses.
- **Debug Monitor Integration**: Launches a live debugging monitor.

### 3. Debug Monitor
- **System Info**: Threads, modules, memory regions, etc.
- **Live Debug Events**: Breaks, exceptions, debug strings.
- **Breakpoints**: Set and remove at specific addresses.
- **Memory**: Read/write memory and dump regions to a file.
- **Gamepad Automation**: Simulate input on the console.

### 4. Build Database
- **Fetch Builds** from a remote JSON database.
- **Track Owned Builds**: Scan local folders.
- **Download/Extract** with progress.
- **Upload to Console** after extraction.

### 5. James 2452’s Vault
- View a curated list of Xbox 360 mods with search and download links.

### 6. Settings
- Configure paths for `xenia.exe`, `xextool.exe`.
- Set default console IP/port.
- Dark mode + JSON-based settings persistence.

---

## What the Tool Does *Not* Do Yet

### File Comparison
- ❌ No binary/line-by-line diff.
- ❌ No file merge support.
- ❌ No detailed comparison export.

### Xbox Neighborhood Pro
- ❌ No rename support.
- ❌ No drag-and-drop transfers.
- ❌ No progress bars for large folder ops.
- ❌ No robust error handling.
- ❌ No multi-console support.

### Debug Monitor
- ❌ No call stack/register display.
- ❌ No disassembly/source mapping.
- ❌ No symbol resolution.
- ❌ No conditional/data breakpoints.
- ❌ No debug scripting.

### Build Database
- ❌ No mod/build integration.
- ❌ No download resume or hash verification.

### Vault
- ❌ No mod management or user uploads.

### General
- ❌ No user auth, logging, multi-user, localization, or accessibility.

---

## Summary Table

| Feature                         | Status |
|----------------------------------|--------|
| Folder comparison                | ✅ Yes |
| File hash/size diff              | ✅ Yes |
| XEX metadata extraction          | ✅ Yes |
| File preview/diff                | ✅ Yes |
| Recent folders                   | ✅ Yes |
| XDK file/folder browse           | ✅ Yes |
| Upload/download (recursive)      | ✅ Yes |
| Delete/create folders            | ✅ Yes |
| Rename files/folders             | ❌ No  |
| Drag-and-drop transfers          | ❌ No  |
| Progress bars (folders)          | ❌ No  |
| Manual XDK commands              | ✅ Yes |
| Debug monitor (basic)            | ✅ Yes |
| Set/remove breakpoints           | ✅ Yes |
| Read/write/dump memory           | ✅ Yes |
| Call stack/registers/disasm      | ❌ No  |
| Symbol/source mapping            | ❌ No  |
| Gamepad automation               | ✅ Yes |
| Build DB fetch/scan              | ✅ Yes |
| Download/extract/upload builds   | ✅ Yes |
| Download resume/integrity check  | ❌ No  |
| Mod database (Vault)             | ✅ Yes |
| Mod install/management           | ❌ No  |
| User authentication              | ❌ No  |
| Logging/audit                    | ❌ No  |
| Multi-console support            | ❌ No  |
| Settings persistence             | ✅ Yes |
| Dark mode                        | ✅ Yes |
