# WordPress User Enumeration Exploit

## Description

This project aims to exploit the User Enumeration vulnerability in various WordPress versions, up to and including the latest release, version 6.4.3, as of the time of this document. User Enumeration is a technique for identifying valid usernames by analyzing a web application's responses to specific requests. Although WordPress does not officially recognize this as a vulnerability, comprehending its mechanics is essential for improving website security.

## Setup and Configuration

Here are detailed steps to set up a safe and controlled environment for testing and studying the User Enumeration exploit without impacting any live websites.

1. **Python Dependencies Installation**: Execute the following command to install the required Python dependencies: `pip3 install -r requirements.txt`
2. **User File**: Modify or add to the `usernames.txt` file as needed.
3. **Set the URL in the Code**: Adjust the code to point to the target URL for testing.

## Mitigation Strategies 💡

We propose several techniques and configurations to help prevent or mitigate the risks associated with User Enumeration, including:

- Customizing error messages to be less informative about the existence or non-existence of user accounts.
- Restricting access to user information via the `functions.php` file in WordPress themes.
