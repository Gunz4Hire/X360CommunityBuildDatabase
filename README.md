# Xbox 360 Preservation Tool - User Guide
## Overview
This Unity-based tool helps with Xbox 360 game preservation by providing several key features:

* Folder comparison to analyze differences between builds

* XEX metadata extraction

* Build database integration

* Devkit exploration tools

## Main Features
### 1. Folder Comparison
* Compare contents of multiple folders containing Xbox 360 game files

* Shows file matches/differences with MD5 hashes and sizes

* Displays visual indicators for matching (green) and different (yellow) files

* Filter and sort files by name, size, or type

* Preview files directly in the tool (supports PNG, TXT, LUA)

### 2. XEX Metadata Analysis
* Extract metadata from XEX files including:

> Original PE name

> Filetime (with date conversion)

> Title ID

> Version information

> Base version

* Compare timestamps between different XEX builds

* Launch XEX files directly in Xenia emulator

### 3. Build Database
* Fetch and view the community build database from GitHub

* Search and filter builds by title, date, version or notes

* View detailed information about specific builds

* Toggle between raw JSON view and formatted table view

### 4. Devkit Explorer
* Basic interface for exploring Xbox 360 devkit modules

* View module versions and information

* (Note: This section appears to be a placeholder for future expansion)

## How to Use
### Basic Workflow:
1. **Add Folders:** Click "Add Folder" to select folders containing Xbox 360 game files

2. **Configure Paths:**

> Set path to Xenia emulator (for direct XEX launching)

> Set path to xextool.exe (for XEX metadata extraction)

3. **Run Comparison:** Click "Run Comparison" to analyze the folders

4. Review Results:

> View XEX metadata in the top section

> See file differences in the comparison table

> Click on files to preview them

## Build Database Usage:
1. Enter the GitHub JSON URL (default is pre-filled)

2. Click "Fetch" to load the database

3. Search or browse through builds

4. Click on entries to view detailed information

## Previewing Files:
* Click any filename in the comparison table

* A popup will show the file contents (for supported types)

* Use tabs to view different versions of the file from each folder

## Requirements
* Unity (for the editor version)

* xextool.exe for XEX metadata extraction

* Xenia emulator (optional, for direct XEX launching)

## GitHub Integration
The tool can directly fetch and display build information from:

> https://github.com/Gunz4Hire/X360CommunityBuildDatabase/blob/main/X360CommunityBuildDatabase.json
## Tips
* The tool remembers your Xenia and xextool paths between sessions

* Use the filter to quickly find specific files

* Sort by size to identify large differences between builds

* The "Current Folder Only" toggle helps focus on one build at a time

## Limitations
* Currently only previews PNG, TXT and LUA files

* Some features require specific tool paths to be set

* Devkit Explorer is currently a basic placeholder

This tool is designed to assist in Xbox 360 game preservation efforts by making it easier to compare different builds and analyze their contents.
