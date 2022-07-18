# Install package

```sh
npm install
```

# Run 1 scenario

```sh
./node_modules/.bin/cucumber-js -p default -p html_report --tags "@TC_M70"
./node_modules/.bin/cucumber-js -p bantheme -p html_report --tags "@TC_M70"
```


# Run all
```sh
npm test
```

# Change enviroment in .env 
```
DEFAULT_TIMEOUT=60000
PLATFORM="chrome"
ENVIRONMENT="bantheme"
DEBUG="false"
```