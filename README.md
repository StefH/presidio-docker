# presidio-docker

## analyzer

### Update 1
Includes extra language: **nl_core_news_lg**

```
docker run -d -p 5002:3000 sheyenrath/presidio-analyzer:latest
```

### Update 2
The default CreditCardRecognizer is also enabled for `nl`.

---

## anonymizer
```
docker run -d -p 5001:3001 sheyenrath/presidio-anonymizer:latest
```
