# Xbox 360 Preservation Tool

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

## Feature Summary

### ✅ Ready Features

| Category             | Feature                                |
|----------------------|-----------------------------------------|
| File Comparison      | Folder comparison                       |
|                      | File hash/size diff                     |
|                      | XEX metadata extraction                 |
|                      | File preview/diff                       |
|                      | Recent folders                          |
| Neighborhood (XDK)   | File/folder browsing                    |
|                      | Upload/download (recursive)            |
|                      | Delete/create folders                   |
|                      | Manual XDK command support              |
| Debug Monitor        | Breakpoint set/remove                   |
|                      | Memory read/write/dump                  |
|                      | Gamepad automation                      |
| Build Database       | Fetch builds from remote DB             |
|                      | Local build scan                        |
|                      | Download/extract builds                 |
|                      | Upload builds to console                |
| Vault                | Mod list browsing                       |
| Settings & UX        | Dark mode                               |
|                      | Persistent settings (JSON)              |

---

### ❌ Not Ready Features

| Category             | Feature                                |
|----------------------|-----------------------------------------|
| File Comparison      | Binary or line-by-line diff             |
|                      | File merge support                      |
|                      | Detailed comparison export              |
| Neighborhood (XDK)   | Rename support                          |
|                      | Drag-and-drop file transfers            |
|                      | Progress bars for large ops             |
|                      | Robust error handling                   |
|                      | Multi-console management                |
| Debug Monitor        | Call stack / register display           |
|                      | Disassembly / source mapping            |
|                      | Symbol resolution                       |
|                      | Conditional / data breakpoints          |
|                      | Debug scripting                         |
| Build Database       | Mod/build integration                   |
|                      | Download resume / hash verification     |
| Vault                | Mod installation / management           |
| General              | User authentication                     |
|                      | Logging / auditing                      |
|                      | Localization / accessibility            |

