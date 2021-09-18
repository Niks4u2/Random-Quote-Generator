# Random-Quote-Generator

## Getting started

Install JSON Server 

```
npm install -g json-server
```

Start JSON Server

```bash
json-server --watch quotes.json
```

Now if you go to [http://localhost:3000/quotes/1](http://localhost:3000/quotes/1), you'll get

```json
  { "id": 1, 
    "content": "There is nothing happens to any person but what was in his power to go through with.",
    "author": "Marcus Aurelius",
    "tags": ["famous-quotes"],
    "authorId": "zW_A5fM6XU-v",
    "authorSlug": "marcus-aurelius",
    "length": 84 }
```
### Alternative port

You can start JSON Server on other ports with the `--port` flag:

```bash
$ json-server --watch db.json --port 3004
```

---

Run `index.html` file on any live server.

