live site: https://julian-moncarz.github.io/tone-trainer/

I wanted to learn to sing as quickly as possible. I had claude do deep research, and it turns out the one of the most effective methods is visual pitch feedback training, so I built the minimal version of it :)

1. the site shows you a note
2. you sing it
3. it draws your  pitch against the target so you can train

Me on first using it:

https://github.com/user-attachments/assets/c62266e0-2185-457f-b491-e057686a1ecb

Me after 20 mins of practice:

https://github.com/user-attachments/assets/d7307023-5a76-4e6c-b854-43a454c2a69f

## Run it

```bash
python3 -m http.server 8000
# open localhost:8000
```

The mic needs `https://` or `localhost`, so double-clicking the file won't work. 
