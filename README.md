# PAI-AUTOPOST

## Social Media Auto Posting with Ziggy

This script enables you to automatically schedule and post to LinkedIn, Twitter, Facebook, and Instagram using Ziggy, your Personal AI. It fetches a random viral topic from Ziggy and generates content for each social media platform. The posts are scheduled and include the hashtags #ziggy #easytrain.ai #vdtl #ve7ltx.tech.

## Prerequisites

To use this script, you need:

- Python 3.6+

- The following Python libraries: `requests`, `linkedin-api`, `tweepy`, `facebook-sdk`, `InstagramAPI`, `schedule`

Install the required dependencies using pip:

```bash

pip install requests linkedin-api tweepy facebook-sdk InstagramAPI schedule

```

## Usage

1. Clone this repository to your local machine:

```bash

git clone https://github.com/your-username/social-media-auto-posting.git

```

2. Replace the placeholder API credentials in the script with your actual API credentials for Twitter, Facebook, and Instagram.

3. Run the script:

```bash

python social_media_auto_posting.py

```

The script will continuously fetch a new viral topic from Ziggy, generate content with the desired hashtags, and schedule social media posts every 5 minutes.

## Notes

- Make sure you have the necessary permissions and rights to post on behalf of users or accounts on each social media platform.

- Posting to LinkedIn requires the `linkedin-api` library, which is not an official LinkedIn library. Make sure to install it from a trusted source or adapt the code to use an alternative library if desired.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.



