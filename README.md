esa-cli
=======

# Commands

## view

CLI application to view posts (default)

```
$ esa view [team]
```

![img](https://raw.githubusercontent.com/ksss/esa-cli/master/demo.gif)

### Key

- j: Down
- k: Up
- l: Next page
- h: Back page
- Enter: Show a post body
- q: Quit

## api

request to esa API and print json response

```
$ esa api posts "q=category:2016/06 title:日報"
{...}
```

# Env

- ESA_ACCESS_TOKEN: Your esa access token
