# Route your S3-served static HTMLs beautifully

If you host your static website in AWS S3, you can set up some redirect rules which allows you to request a page without specifying the `.html` postfix after every page request.
You users will be able to request your `products.page` like this `/products`. Check the `aws/redirections_rules` for more info.
