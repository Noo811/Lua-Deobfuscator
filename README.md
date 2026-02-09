# Lua-Deobfuscator
AI overview.
Lua Deobfuscation Tool
This is a web-based tool for deobfuscating Lua/Roblox scripts. It takes obfuscated, jumbled code and transforms it into clean, readable format with proper indentation, spacing, and line breaks.

Features:
Deobfuscation Engine: Automatically formats jumbled Lua code with proper indentation and spacing

Comment Removal: Strips out both single-line (--) and multi-line (--[[ ]]) comments

Smart Line Breaking: Adds line breaks after semicolons, keywords, and operators

Truncated Display: Output shows only first 6 lines with "..." for large scripts (click to expand)

Live Statistics: Shows character and line counts

One-Click Operations: Deobfuscate, clear, copy, and load example functions

Dark Theme: Developer-friendly dark interface with syntax-friendly colors

How It Works:
Paste obfuscated Lua/Roblox code into the input box

Click "Deobfuscate" to process the code

View clean, formatted output in the results panel

Copy or further analyze the deobfuscated code

Technical Details:
Pure HTML/CSS/JavaScript - no external dependencies

Uses regex patterns to identify and reformat code structures

Implements proper Lua indentation logic (4 spaces per level)

Handles common obfuscation patterns found in Roblox scripts

Responsive design that works on desktop and mobile

Use Cases:
Analyzing obfuscated game scripts

Learning Lua/Roblox script structure

Educational purposes for understanding code obfuscation techniques

Preparing scripts for debugging or modification
