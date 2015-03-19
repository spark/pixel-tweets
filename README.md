sparklertweets
============
Stream tweet events and convert them to pixel data for a Spark Internet Button!

### Usage

1. Clone this repository and run `npm install` inside the root of the project directory.
2. Configure your Twitter API keys (see below).
3. Run `npm start`.

### Configuration

#### Keys & Secrets

You must create your own application to use the API. Please do so by going to the Twitter Application Management page.

* CONSUMER_KEY
* CONSUMER_SECRET
* ACCESS_TOKEN_KEY
* ACCESS_TOKEN_SECRET

You need all four of these to run the twitter stream included in `npm start`. Configuration options are detected via `nconf`, and you may specify them in your config.json file (placed at the root of the project directory):


#### Configuration file format
  ```js
  {
  	"consumer_key": "",
  	"consumer_secret": "",
  	"access_token_key": "",
  	"access_token_secret": "",
    "spark_username": "",
    "spark_password": ""
  }
  ```

  Once you've selected your