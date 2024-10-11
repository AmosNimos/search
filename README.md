# search
A user-friendly CLI wrapper for the `find` command, providing flexible argument handling, simplified flag options, and default values for customizable file searches across specified directories with controlled depth.

## Features

- Simple usage with customizable search parameters
- Supports searching by file name, type, directory, and depth
- Default values for parameters to streamline searches

## Usage

```bash
search [name] [type] [directory] [depth]
```

### Arguments

- **name**      : Name pattern to search for (required)
- **type**      : Type of file to search for (default: `f` for file)
- **directory** : Starting directory for the search (default: current directory)
- **depth**     : Maximum search depth (default: `3`)

### Examples

1. Search for a specific file in the current directory:
   ```bash
   search myfile.txt
   ```

2. Search for directories only:
   ```bash
   search mydir d
   ```

3. Search for files in a specific directory with a custom depth:
   ```bash
   search myfile.txt f /home/user 2
   ```
   
## License

This project is licensed under the GPLV3 License - see the [LICENSE](LICENSE) file for details.
