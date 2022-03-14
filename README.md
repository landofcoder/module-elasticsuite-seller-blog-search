# ElasticSuite Blog search for Lof Magento 2 Seller Blog


This module connecting between each other [ElasticSuite](https://github.com/Smile-SA/elasticsuite) search extension and [Landofcoder](https://landofcoder.com/magento/magento-2-extensions.html) [Magento 2 Seller Blog extension](https://landofcoder.com/magento-2-marketplace-blog.html/)

It allows to index Magento 2 Blog posts into the search engine and display them into the autocomplete results, and also on the search result page.

### Requirements

* For version 1.x.x: Magento Community Edition 2.3.* - 2.4.* or Magento Enterprise Edition 2.3.* - 2.4.*

The module requires :

- [ElasticSuite](https://github.com/Smile-SA/elasticsuite)
- [Seller Blog](https://landofcoder.com/magento-2-marketplace-blog.html/)

### How to use

1. Enable it

``` bin/magento module:enable Lof_ElasticsuiteSellerBlog ```

3. Install the module and rebuild the DI cache

``` bin/magento setup:upgrade ```

4. Process a full reindex of the Blog Post search index

``` bin/magento index:reindex elasticsuite_sellerblog_fulltext ```

Forked from Repo: [ComWrap ElasticsuiteBlog](https://github.com/comwrap/Comwrap_ElasticsuiteBlog)
