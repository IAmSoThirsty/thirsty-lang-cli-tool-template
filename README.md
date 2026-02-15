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
