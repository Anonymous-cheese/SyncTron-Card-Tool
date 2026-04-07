# SyncTron Card Tool

A desktop tool for converting card game assets into Tabletop Simulator (TTS)-ready decks and print-ready exports.

## Features

- Resize card images to standard card dimensions (Pokémon ratio)
- Automatically generate TTS card sheets (4096px safe limit)
- Support for multiple decks
- Board/playmat export support
- Print-ready PNG and PDF export with bleed
- Dark mode UI with red accents

## Usage

1. Launch the application
2. Assign folders to each deck
3. (Optional) Select card back images
4. Click **Process Assets**

## Output

The tool generates:
- Resized card assets
- TTS-ready sheet images
- Print-ready exports (PNG + PDF)
- Logs and diagnostics

## Requirements

- Windows 11
- Python (for development builds)

## Build

To build the executable:

build_windows_exe.bat

## Notes

- Keep all card images consistent in aspect ratio
- Avoid extremely large images to prevent TTS compression
- Delete app state if startup issues occur:

C:\Users\<your-user>\.synctron_card_tool\app_state.json

## License

Private project / personal use
