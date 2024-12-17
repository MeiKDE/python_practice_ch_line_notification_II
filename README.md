# Specter: Automated LINE Notify Messaging

This script sends an automated message to a LINE group or individual using the LINE Notify API. The message includes the current date in the format MM/DD and prompts recipients to reply with specific items.

## Prerequisites

- Python 3.x
- `requests` library (can be installed using `pip install requests`)
- A valid **LINE Notify** token

## How It Works

1. The script retrieves the current date and formats it in `MM/DD` format.
2. A pre-defined message is created, incorporating the formatted date and a custom message (e.g., reminders or action items).
3. The script sends the message to LINE Notify using the API.

## Configuration

To use this script, you need to set your **LINE Notify** access token as an environment variable:

```bash
export ACCESS_TOKEN="your_line_notify_access_token"
