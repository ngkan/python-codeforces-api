# python-codeforces-api

More friendly inferface to Codeforces API.

Basically convert every Codeforces object to a coressponding class.

Use arguments similarly to the API.

I don't translate user.friends method since it needs authorization.

## Example
```
status, user = get_user_info('tourist')
print(user.handle)
print(user.rank)
print(user.rating)
```

## License
MIT