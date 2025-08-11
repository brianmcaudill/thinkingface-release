# Release Notes - v0.17.1

## Release Date: 2025-08-11

## Overview
This release focuses on fixing and improving the Claude Code IDE integration in ThinkingFace editor, ensuring it works properly as an LLM provider alongside other models.

## Key Features & Improvements

### Claude Code Integration Fixes
- **Fixed path duplication issue**: App paths were being incorrectly doubled (e.g., `C:\Users\...\thinkingface-apps\C:\Users\...\thinkingface-apps\...`). Now correctly handles absolute paths.
- **Improved stream management**: Fixed "stream already active" errors that occurred when retrying after failures. Added automatic cleanup of old streams.
- **Enhanced Windows execution**: Switched from batch files to PowerShell scripts for better output handling and reliability on Windows.
- **Better output visibility**: Added `--output-format text --verbose` flags to ensure Claude Code output is properly displayed in the chat interface.

### Technical Improvements
- Added comprehensive logging throughout the Claude Code execution pipeline for better debugging
- Implemented proper cleanup with `finally` blocks to prevent resource leaks
- Fixed npm package name references (corrected to `@anthropic-ai/claude-code`)
- Improved error messages to be more helpful when Claude Code is not installed

## Bug Fixes
- Fixed working directory path duplication that prevented Claude Code from running in the correct app directory
- Resolved stream cleanup issues that caused "stream already active" errors
- Fixed PowerShell execution for better Windows compatibility
- Corrected package name in error messages

## Installation Requirements
- Claude Code must be installed globally: `npm install -g @anthropic-ai/claude-code`
- Windows users need PowerShell available (included by default)

## Known Issues
- Squirrel installer build currently failing (ZIP distribution available as alternative)
- WiX installer may have icon extraction warnings

## Download
- Windows x64: `ThinkingFace-win32-x64-0.17.1.zip`

## Documentation
- Added comprehensive technical documentation for Claude Code integration
- Created flow diagrams showing the complete execution pipeline
- Updated integration architecture documentation

## Contributors
- Brian