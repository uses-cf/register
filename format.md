You must add atleast one record type.
`description` and `repo` are not required, they are for documentational purposes only.
If you are not comfortable sharing your email in public, please add your [discord user id](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-).
Create a new file in `domains` directory like `domains/subdomain.json` with the following content and replace the placeholders accordingly.
```json
{
    "owner": {
        "username": "gh-username",
        "email": "email@address.tld",
        "discord": "userid"
    },
    "repo": "https://github.com/gh-username/repo",
    "description": "What the subdomain is being used for",
    "record": {
       "CNAME": "",
       "A": [],
       "AAAA": [],
       "MX": [],
       "TXT": ""
    }
}
```
