# notion2google-calendar

## file info

```
credentials.json: OAuth2 credentials file from google OAuth2
secrets.yaml: NotionAPI Key and database ID
eventinfo.csv: calendar event database csv file
```

## How to use:

```
crontab -e
```

```
PATH=$PATH:$PWD
python ./main.py > $PWD/log.txt
```