Based on the information gathered, here's the draft for the `README.md` file for the `proxy` project:

```markdown
# Proxy Project

## Overview

The `proxy` project is designed to provide a robust and efficient proxy server solution with customizable configurations. It integrates with NGINX and utilizes MariaDB as the main storage backend. The project supports containerized deployment and offers flexibility for network and environment configurations.

## Features

- **NGINX Customizations**: Advanced configurations to tailor proxy behavior.
- **MariaDB Integration**: Acts as the primary backend storage for the proxy server.
- **Environment Flexibility**: Includes environment variable support for seamless configuration.
- **Containerized Deployment**: Streamlined setup using Docker, making it portable and easy to deploy.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Akhaladze/proxy.git
   cd proxy
   ```

2. Set up the environment variables:
   - Create an `.env` file based on the example provided.
   - Configure the necessary variables for the proxy and database services.

3. Bring up the services:
   ```bash
   docker-compose up -d
   ```

## Usage

- Ensure all services are running:
  ```bash
  docker ps
  ```
- Access the proxy server at the configured address and port.
- Customize NGINX configurations as needed in the provided configuration files.

## Contribution

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your changes:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to your fork.
4. Submit a pull request.

## Recent Updates

- **Added NGINX customizations** ([Commit](https://github.com/Akhaladze/proxy/commit/751bd043d1b561bf009d945aee3ec4ab76d1621c))
- **Integrated database to the same network as the proxy** ([Commit](https://github.com/Akhaladze/proxy/commit/5ee836d81de1f25e0e72675e87450128358b49ab))
- **Added MariaDB as the storage backend** ([Commit](https://github.com/Akhaladze/proxy/commit/10c4ea34c4d0e475fa7fe6cdf6e3cdb48b3e678b))

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

If you have further questions or require additional details to enhance the `README.md`, feel free to let me know!
