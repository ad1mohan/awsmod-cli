# 🚀 awsmod - AWS Profile Manager

`awsmod` is a simple and fun command-line tool to manage your AWS credentials and configurations stored in `~/.aws/config` and `~/.aws/credentials`. 🎯

## 📥 Installation

1. Clone this repository: 🖥️
   ```sh
   git clone https://github.com/your-username/awsmod-cli.git
   cd awsmod-cli
   ```
2. Make the script executable: 🔧
   ```sh
   chmod +x awsmod
   ```
3. Move it to a directory in your `PATH` (e.g., `/usr/local/bin`): 🚀
   ```sh
   sudo mv awsmod /usr/local/bin/
   ```
4. Verify the installation: ✅
   ```sh
   awsmod help
   ```

## 🛠️ Usage

### 🔹 Available Commands:

#### ✅ Check if `awsmod` is working
```sh
awsmod check
```
_Print a test message to verify installation._

#### ✨ Add a new AWS profile
```sh
awsmod add-profile
```
_Prompts for AWS credentials and adds a new profile._

#### 🔄 Set an existing profile as the default
```sh
awsmod set-default
```
_Prompts for a profile name and sets it as the default._

#### 📋 List all AWS profiles
```sh
awsmod list-profiles
```
_Displays a list of available profiles._

#### 🗑️ Clear all AWS configurations
```sh
awsmod clear
```
_Deletes both `~/.aws/config` and `~/.aws/credentials`._

#### 📖 Show help
```sh
awsmod help
```
_Displays available commands and usage information._

## 📜 License
This project is licensed under the MIT License. 📝

## 🤝 Contributing
Found a bug? Have an idea? Feel free to open an issue or submit a pull request! 🚀

