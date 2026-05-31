I wanted to learn to sing as quickly as possible. I had claude do deep research, and it turns out the one of the most effective methods is visual pitch feedback training, so I built the minimal version of it :)

1. the site shows you a note
2. you sing it
3. it draws your  pitch against the target so you can train

## Run it

```bash
python3 -m http.server 8000
# open localhost:8000
```

The mic needs `https://` or `localhost`, so double-clicking the file won't work. 
