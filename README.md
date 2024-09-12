# Read JSON from an external URL in WordPress

This is a simple guidelines and script that reads an external JSON file and displays an offer to the WordPress admin dashboard.

# Create a JSON file to the remote server.

Our initial plan is to create an offer notification message to inform admin users about a discount. This message will display only the admin area. So, create a JSON file, and copy this JSON code.

```JSON
{
  "msg": "Celebrate with us and save 15%. Hop into egg-citing deals and enjoy the season: <a href='https://bluewindlab.net'>Start shopping now</a>!",
  "offer_starts": "11.09.2024",
  "offer_ends": "13.09.2024",
  "offer_id": "bnm_11092024_12092024"
}
```
