Tuchuzy Crawler
================

About
-----

Scrapy Spider to crawl Tuchuzy.com

<a name="setup" />
Setup A Local Instance
----------------------

1.  Make and enter a virtualenv with Python 3.4+

    ```
    virtualenv env/
    source env/bin/activate
    ```

2.  Install all crawler requirements:

    ```
    pip install -r requirements.txt
    ```

3. Run Scrapy crawl command:
    ```
    cd tuchuzy_crawler && scrapy crawl tuchuzy -o tuchuzy.csv --logfile tuchuzy.log
    ```

- In case of debugging crawler or parsing, prefer to use `HTTPCACHE_ENABLED = True` to avoid re-visiting pages during testing