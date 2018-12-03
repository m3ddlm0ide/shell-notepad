### init archive.is fetching via shell-curl

```
curl -v -A "Mozilla/5.0 (Windows NT 6.1; Win64; x64; rv:59.0) Gecko/20100101 Firefox/59.0" --request POST --data-urlencode "url=https://randompage.tld" --data-urlencode "submitid=$(cat /dev/urandom | tr -cd 'a-f0-9' | head -c 8)" --data-urlencode "submit=" https://archive.is/submit/
```
