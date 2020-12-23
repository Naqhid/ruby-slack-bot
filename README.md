# Ruby Slack Bot Project- Globus-bot

This is a slack bot project created with ruby. I have created a slack ruby bot and called it 'globus-bot'. This bot is for showing capitals for every country. It can also check for a country's population

## Built With

- Ruby
- dotenv gem
- rack-test
- puma
- celluloid-io
- restcountry gem
- slack-ruby-bot gem

## Prerequisities

To get this project set up on your local machine, follow these simple steps:

## Installation

1. Open Terminal.
2. Navigate to your desired location to download the contents of this repository.
3. Copy and paste the following code into the Terminal: git clone `https://github.com/Naqhid/ruby-slack-bot`
4. Run `cd ruby-slack-bot`.
5. Run `bundle install` to get the necessary gems.
6. Create a new slack [workspace](https://slack.com/get-started#/create) and give it a name
7. Open [bot integration](http://slack.com/services/new/bot) link, and choose your created workspace from the top right corner, give a username for your bot and click on `Add bot integration` button.
8. Copy the given token, also you can change the bot username and give an avatar to your bot.
9. Click on `Save Integration` button.
10. Create .env file in your project folder, copy your TOKEN to that .env file and paste it as `SLACK_API_TOKEN = your-token-here`
11. Run `rackup` from your terminal window to start running the project.
12. Open the Slack and go to workspace page. Invite your bot to your page.To see available commands ask for @your_bot help.
13. Enjoy!

## List of available commands:

`@your_bot help` Shows information about bot commands <br>
`@your_bot countries` Shows a list of all available countries <br>
`@your_bot <country name>` Shows the capital of any particular country <br>
`@your_bot <country name> population` Shows the population of any particular country

## Author

👤 **Mohammed Naqhid**

- GitHub: [@Mohammed Naqhid ](https://github.com/Naqhid)
- Twitter: [@naqhid](https://twitter.com/naqhid)
- LinkedIn: [@Naqhid](https://www.linkedin.com/in/mohammed-naqhid-ab3080189/)

## Show your support

Give a ⭐️ if you like this project!
