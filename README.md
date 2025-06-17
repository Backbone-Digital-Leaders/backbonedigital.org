# Backbone static website

https://backbonedigital.org/

## Development

### Setup instructions

Prerequisites:
- Python 3

1. Clone this repo
1. `cd public`
1. Serve the static files: `python3 -m http.server 8080`
1. Visit http://localhost:8080/

## Production

### Deploying

Eventually this will likely be hosted on WordPress. Until then:

1. Push files to our static server: `rsync -azP -e ssh public/* root@104.248.118.195:/var/www/backbone-digital/`
