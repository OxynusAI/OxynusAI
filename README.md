```bash
curl -s 'https://raw.githubusercontent.com/OxynusAI/OxynusAI/refs/heads/main/README.md' | grep -oP '(?<=<input[^>]*x-data="curl-me"[^>]*value=")[^"]*'
```

<input x-data="curl-me" type="hidden" value="Hello"> 
