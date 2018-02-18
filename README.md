# Metadata Scraper

## Description
Program that creates a title based on a present NFO file and embed that into the MKV metadata. If the file is not MKV the option exists to convert it.

This requires a Kodi formatted NFO file with the same filename as the video file.

## Usage

The **-s, --scraper** Default option. Scrapes the metadata title from the NFO file and adds it to the associated MKV file.  
The **-c --convert** This converts any other video file format to MKV. (WARNING: Currently this script relies on mkvmerge to successfully reject non-video files that aren't NFO and JPG)

## Requirements
- xmllint
- mkvtoolnix
- A Kodi NFO file creator
- options.bash - This needs to be installed in the same folder as the script.
