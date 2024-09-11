# WhatsApp-Spammer

# WA-Spam

## Description

**WA-Spam** is a Python-based tool designed to send spam messages on WhatsApp. It provides a terminal-based interface for choosing between sending user-typed messages or auto-generated messages. The script allows flexible options for message spamming with features like random message generation, counting, and more.

> ⚠️ **Disclaimer**: This tool is for educational purposes only. Spamming others without their consent is illegal and unethical. Use responsibly and respect others' privacy.

## Installation

To set up **WA-Spam**, follow these steps:

### Clone the Repository
```bash
git clone https://github.com/sh1vam.03/WhatsApp-Spammer.git

cd WhatsApp-Spammer
```

### Install Modules

Ensure you have Python 3.x installed. Install the required Modules from `requirements.txt`:

```bash
pip install -r requirements.txt
```

### Requirements

- Python 3.x
- The required modules listed in `requirements.txt`

## Usage

After installing the required packages, you can run the tool as follows:

```bash
python wa-spam.py
```

### Terminal Interface

Once you run the tool, you'll be presented with the following options:

```
 __        ___        ____
 \ \      / / \      / ___| _ __   __ _ _ __ ___  
  \ \ /\ / / _ \ ____\___ \| '_ \ / _` | '_ ` _ \ 
   \ V  V / ___ \_____|__) | |_) | (_| | | | | | |
    \_/\_/_/   \_\   |____/| .__/ \__,_|_| |_| |_|
                           |_|   
                                        -sh1vam.03
```

#### Main Menu:
```
Choose an option from the following:
[1] User typed message
[2] Auto typed message
[0] Quit
[+] Enter Option -> 1
```

#### User Typed Message (Option 1):
```
[*] User typed message <SELECTED>
[N] How many messages do you have?
[0] Enter 0 to quit and exit tool.
[+] Enter Number of Messages (Default: 1) -> 
```

#### Auto Typed Message (Option 2):
```
[*] Auto typed message <SELECTED>
Choose an option from the following:
[1] Message with counting
[2] Random Message Generator
[3] Meaningless Message Generator
[0] Quit
[+] Enter Option -> 
```

### Features

- **User-Typed Message**: Allow to user type some messages manually and tool mechanism send these messages repeatedly.
- **Auto-Typed Message**: Offers different automated message-sending options:
  - **Message with Counting**: Sends messages with a counting mechanism (e.g., "Message 1", "Message 2").
  - **Random Message Generator**: Sends randomly generated words of sentence as message.
  - **Meaningless Message Generator**: Sends random, nonsensical words of sentence as message.
  
## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue if you have suggestions or improvements.

## License
This project is licensed under the [MIT License](./LICENSE).

