# Facebook Crawler

Simple and light weighted crawler for Facebook Public Posts using Python and XPath

## Usage

```bash
python fb_crawler.py --page_id_file="page.tsv" --start_date="2020-06-20" --end_date="2020-06-30" --output_file="output.tsv"
```

page.tsv contains id of the pages you want to crawl. Its is a single column tsv file.

- 10376464573 is page id for ladygaga
- 8245623462 is page id for nba

Before crawling a Facebook  page you will new page ids for the
pages you want to crawl.

You can find out what is the id of a page by inspecting the
facebook page.

## References

- xpath selector: [https://docs.scrapy.org/en/latest/topics/selectors.html](https://docs.scrapy.org/en/latest/topics/selectors.html)

From the above link you will understand how to use xpath to parse and get required data from html.
- python request: [https://findwork.dev/blog/advanced-usage-python-requests-timeouts-retries-hooks/](https://findwork.dev/blog/advanced-usage-python-requests-timeouts-retries-hooks/)

From the above link you will understand how to use request library in python to get online html.
Also understand how to use the retry functionality when a request fails.



