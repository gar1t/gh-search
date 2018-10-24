# GitHub Search

```
usage: gh-search [-h] [-s SEARCH] [-o {stars,forks,updated}] [-p PAGES]
                 [-t ACCESS_TOKEN]

optional arguments:
  -h, --help            show this help message and exit
  -s SEARCH, --search SEARCH
                        Search term (default is 'tensorflow')
  -o {stars,forks,updated}, --order-by {stars,forks,updated}
                        How to order results (choices are 'stars', 'forks',
                        and 'updated'; default is 'stars')
  -p PAGES, --pages PAGES
                        Number of pages to process (default is 1)
  -t ACCESS_TOKEN, --access-token ACCESS_TOKEN
                        Access token (default is GITHUB_ACCESS_TOKEN env)
```

Script generates CSV output that can be redirected to a file:

    $ gh-search -p1 > results.csv
