# Dist

**Dist** is a lightweight and efficient distribution tool designed to simplify the process of distributing files, packages, or applications across multiple platforms. Whether you're a developer looking to distribute your software or a system administrator managing deployments, Dist provides a straightforward and reliable solution.

## Features

- **Cross-Platform Support**: Dist works seamlessly on Windows, macOS, and Linux.
- **Easy Configuration**: Simple configuration files to define distribution rules.
- **Fast and Efficient**: Optimized for speed, ensuring quick distribution of files.
- **Customizable**: Flexible options to tailor the distribution process to your needs.
- **Open Source**: Fully open-source, allowing you to modify and extend the tool as needed.

## Installation

To install Dist, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/astelicon/dist.git
   ```
2. Navigate to the project directory:
   ```bash
   cd dist
   ```
3. Install the required dependencies:
   ```bash
   npm install  # or yarn install, depending on your package manager
   ```
4. Build the project:
   ```bash
   npm run build  # or yarn build
   ```

## Usage

To use Dist, you can run the following command:

```bash
dist --config path/to/config.json
```

### Example Configuration

Here’s an example of a basic configuration file (`config.json`):

```json
{
  "source": "path/to/source",
  "destination": "path/to/destination",
  "options": {
    "recursive": true,
    "overwrite": false,
    "exclude": ["node_modules", ".git"]
  }
}
```

### Command Line Options

- `--config`: Path to the configuration file.
- `--help`: Display help information.
- `--version`: Display the current version of Dist.

