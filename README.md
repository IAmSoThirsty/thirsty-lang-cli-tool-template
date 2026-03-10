<div align="right">
  <img src="https://img.shields.io/badge/Date-2026--03--10-blue?style=for-the-badge" alt="Date" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/Tier-Master-gold?style=for-the-badge" alt="Tier" />
</div>

# Thirsty-lang CLI Tool Template 💧

Build command-line applications with Thirsty-lang.

## Features

- Argument parsing
- Subcommands
- Configuration files
- Progress bars
- Interactive prompts with sip

## Example

```thirsty
glass main() {
  drink args = parseArgs()
  
  thirsty args.command == "process"
    processFiles(args.files)
  hydrated thirsty args.command == "help"
    showHelp()
}
```

## Commands

- `mytool process <files>` - Process files
- `mytool config` - Show configuration
- `mytool help` - Show help

## License

MIT
