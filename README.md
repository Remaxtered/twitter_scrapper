# Twitter_scrapper

This script is created to scrap tweets from the specified link in the last 7 days.

## Usage
To run this script run:

    python twitter-scraper.py -f FILENAME
  
Flags:
  
  -f (required): name of the input file that contains twitter URLs (1 per line) in the following format: 
  
  > https://twitter.com/<SCREEN_NAME>/status/<ID>
  
  -s: csv output; useful to diff content between different iterations of the script
  
## Requirements
You have to register twitter developer account and get API keys here: 
  
    https://developer.twitter.com/en/docs/basics/authentication/guides/access-tokens.html
    
## Dependences

    twitter
    pytz
to install run: 
    
    pip install python-twitter
    pip install pytz

### Enjoy playing!
    
 
