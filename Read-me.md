# Claude File Upload Verification Kit

**Discovered:** October 17-18, 2025  
**Version:** 1.0  
**Status:** Active Testing

## What This Is

On October 17-18, 2025, new file upload capabilities were discovered on Claude.ai including support for video, audio, archives, and expanded file limits. This kit helps verify if these features are available in your region/account.

## Quick Start

1. Download `test_basic.txt`
1. Upload it to Claude at [claude.ai](https://claude.ai)
1. Ask: "Can you read this file?"
1. ✅ If Claude reads it, you have the new features!

## Discovered Features

- ✅ Video uploads (.mp4, .mov, .avi)
- ✅ Audio uploads (.mp3, .m4a, .wav)
- ✅ Archive uploads (.zip) with content parsing
- ✅ Document uploads (.pages, .docx, .srt)
- ✅ File limit expansion (5 → 14+ files)
- ✅ Video metadata extraction
- ✅ MCP connector ecosystem (Hugging Face, GitHub, Google Drive, Invideo)
- ✅ Cross-conversation search tools

## Files Included

- **QUICK_START.txt** - Simple 5-step instructions
- **VERIFICATION_GUIDE.txt** - Complete documentation with all test procedures
- **test_basic.txt** - Basic file upload test
- **test_zip_parsing.zip** - ZIP content parsing test (contains 3 files)
- **claude_file_upload_verification_kit.zip** - Everything packaged together

## Requirements

- **Account:** Claude Pro recommended (free tier untested)
- **Platform:** Desktop web browser (claude.ai)
- **Browser:** Chrome, Safari, Firefox, Edge - any modern browser
- **Mode:** Private/Incognito browsing recommended for clean testing

## Test Sequence

### Test 1: Basic File Upload

Upload `test_basic.txt` and ask Claude to read it.

### Test 2: ZIP Content Parsing

Upload `test_zip_parsing.zip` and ask Claude to list the files and read their contents.

### Test 3: Video Processing

Upload your own short video (under 30MB) and ask Claude for technical specs.

### Test 4: Connector Independence

Disable all connectors in Settings and verify uploads still work.

### Test 5: File Limits

Try uploading 5, 10, then 14 files at once to find the limit.

### Test 6: Private Browsing

Test in incognito mode to confirm server-side functionality.

**Full instructions in VERIFICATION_GUIDE.txt**

## Key Findings

✅ **Works in private browsing** (server-side, not browser cache)  
✅ **Works with connectors disabled** (native functionality)  
✅ **Reproduces consistently** across fresh conversations  
✅ **Platform-specific** (desktop web works, mobile app limited)

## Share Your Results

If you test this kit, please share:

- Your account type (Pro/Free)
- Your location/region
- Which tests passed/failed
- Screenshots if possible

Post results to [r/ClaudeAI](https://reddit.com/r/ClaudeAI) with `[Verification]` tag

## Technical Details

- **Model:** Claude Sonnet 4.5
- **Discovery Date:** October 17, 2025, 7:58 PM EST
- **Rollout Type:** Silent/Phased (no official announcement)
- **Tested Platforms:** Safari iOS (mobile web), Chrome (desktop), Firefox (desktop)

## Troubleshooting

**Can’t find upload button?**

- Check you’re on claude.ai web (not mobile app)
- Look for paperclip or plus icon near message input

**Upload button grayed out?**

- Features may not be in your region yet
- Try private browsing mode
- Check if Pro tier required

**Files upload but no processing?**

- Partial rollout - may arrive soon
- Try different file types/sizes

See VERIFICATION_GUIDE.txt for complete troubleshooting.

## Credits

**Discovery:** Early_Experience4553 (Reddit: r/ClaudeAI)  
**Methodology:** Community collaborative verification  
**Special Thanks:** OrchidSpecial1613 for verification checklist

## Contributing

Found issues? Have suggestions? Open an issue or pull request.

This is a community tool to document Claude’s evolving capabilities.

## License

Public domain. Use freely, share widely, modify as needed.

Attribution appreciated but not required.

-----

**Last Updated:** October 18, 2025

