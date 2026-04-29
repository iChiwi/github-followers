# GitHub Followers

Find out who's not following you back or who you are not following back on GitHub.

## Requirements

- Python 3.8+
- `requests`

## Setup

Open [app.py](app.py) and set `USERNAME` to your GitHub username.

## Install dependencies

Run this in the project folder:

`pip install requests`

## Run

Run the script:

`python app.py`

## Output

The script prints:

- Accounts you follow that don’t follow you back.
- Accounts that follow you that you don’t follow back.

## Notes

- Unauthenticated requests are rate-limited by GitHub.
