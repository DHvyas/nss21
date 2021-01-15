# NSS DTU

This is the NSS DTU 2021 website

## Installation

Use the npm package manager to install node modules.

```bash
npm install # installs backend node modules
cd client # switch to frontend client directory
npm install # installs frontend node modules
cd .. # return to project root directory
```

## Add configurations

Update the two `.json` configuration files in the `config` directory, and save them as `default.json` and `production.json`

The configuration files should contain the following:

```bash
{
  "mongoURI": #Your MongoDB connection URI wrapped in double-quotes
  "jwtSecret": #Any string as your JSON web token secret
}
```

## Usage

In the project root directory, run this command:

```bash
npm run dev
```

## Heroku Deployment

In the project root directory, run this command:

```bash
heroku create #Create your app on Heroku
git push heroku master #Deploy your app to Heroku

```