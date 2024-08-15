# HealthChecker

HealthChecker is a simple command-line tool to check if a specified website is up and running or down. It supports checking custom ports and provides quick feedback on the availability of the specified domain.

## Features

- Check the status of any domain.
- Specify a custom port to check for availability.
- Quick feedback with connection status.
  
## Requirements

- Go 1.23 or higher installed on your system.

## Installation

To get started with HealthChecker, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Shivangi10-10/go-projects.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd go-projects
   ```

3. **Install dependencies**:

   ```bash
   go mod tidy
   ```

## Usage

You can use the tool by running the following command:

```bash
go run . --domain <domain_name> [--port <port_number>]
```

- `--domain` or `-d`: Specifies the domain to check. This is a required parameter.
- `--port` or `-p`: Specifies the port to check. If not provided, it defaults to port 80.

### Examples

1. **Check if `pexels.com` is up on the default port (80)**:

   ```bash
   go run . --domain pexels.com
   ```

2. **Check if `pexels.com` is up on port 443**:

   ```bash
   go run . --domain pexels.com --port 443
   ```

## Output

After running the tool, the output will indicate whether the domain is up or down. Here are some examples:

### Example 1: Domain is Up

![Domain Up](https://github.com/user-attachments/assets/ae83fd0e-ff41-40f5-ad72-88c06cadeca4)

### Example 2: Domain is Down

![Domain Down](https://github.com/user-attachments/assets/ee12a32c-ed02-4483-9b3f-d10137a9130c)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue.

## Contact

For any questions or support, please contact [Shivangi Suyash](mailto:shivangi@example.com).
```
