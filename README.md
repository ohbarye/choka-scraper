# Choka Scraper

This is a script to fetch catches of fishing by scraping https://www.fishing-v.jp/.

## Requirement

- [Docker](https://www.docker.com/)

That's it!

## Usage

Just run the command below on your terminal.

```shell
$ docker run -it -v $PWD:/app -w /app python bash -c "pip install -r requirements.txt && python scraper.py"
```
