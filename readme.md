# RocketBotRoyale Bonus Collector

⚠️️ For Educational Use Only!

<img align="left" style="width: 100px; height: auto;" src="https://i.ibb.co/mhxJDdx/image.png">

Automates bonus collection and crate purchases for RocketBotRoyale, using our Unofficial Python Client for Rocket Bot Royale Game API available at [GitHub](https://github.com/Rocket-Bot-Royale/api). It logs in with provided credentials or prompts for them, collects timed bonuses, checks coin balance, and optionally opens crates if sufficient coins are available.


## Installation

Ensure you have Python 3 installed. You can install the required library using pip:

```bash
pip install rbrapi    # RocketBotRoyale API client library
```

## Usage

Run the script with Python, providing necessary arguments:

```bash
python main.py --email "your_email" --password "your_password" [--no-logging] [--auto-open-crates]
```

### Command-line Arguments

- `--email`: Email address for your RocketBotRoyale account.
- `--password`: Password for your RocketBotRoyale account.
- `--no-logging`: (Optional) Disable logging. By default, logging is enabled unless this flag is specified.
- `--auto-open-crates`: (Optional) Automatically open crates if available and if coins are sufficient.

If you omit `--email` or `--password`, the script will prompt you to enter them interactively.

## Example

To run the script with logging enabled and auto-open crates:

```bash
python main.py --email "your_email" --password "your_password" --auto-open-crates
```

To run the script without logging and with auto-open crates:

```bash
python main.py --email "your_email" --password "your_password" --no-logging --auto-open-crates
```
