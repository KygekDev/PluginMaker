# PluginMaker

<!-- TODO: Add description in README.md -->

## Prerequisites

- Git installed to your PATH.
- PHP 7.3 or 7.4 installed to your PATH with YAML extension installled and enabled.
- PHP binary with built-in web server capabilities (apparently PocketMine-MP's doesn't have this feature compiled).
- [Optional] Composer PHAR or installer (Get from https://getcomposer.org).

## How to Run

1. Open your preferred terminal (on Windows use Git Bash).
2. Clone the repository using Git:
```bash
$ git clone https://github.com/KygekDev/PluginMaker
```
3. Change directory to the `public` directory inside the repository:
```bash
$ cd PluginMaker/public
```
4. Start the built-in PHP web server:
```bash
# Format: <hostname_or_ip_address>:<port>
$ php -S 0.0.0.0:8000
```

**Optional:** Run `php composer.phar install` inside the root directory of the repository to install the latest compatible dependencies and synchronize autoload.

## Issues or Pull Requests?

Feel free to submit any in https://github.com/KygekDev/PluginMaker/issues or in https://github.com/KygekDev/PluginMaker/pulls.
