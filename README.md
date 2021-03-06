# Tracking code for Criteo
Template is implemnted as one-tag executed on all pages, dynamic variables can be submitted.


## Configuration
![GTM template for Criteo](https://github.com/House-of-Rezac/criteo/blob/master/criteo.PNG?raw=true)


### Parameters
* *Partner ID* - ID, expected numeric value like 111111
* *User Email* - user email if known. Note: add this value only with GDPR consent
* *Page Type* - see below
* *Device Type* - possible values are mobile, desktop or tablet
* *Currency Code* - currency code according ISO 4217, e.g. EUR, USD, CZK etc.
* *Products* - array of products relevant in given context (purchase content, cart content, product detail or impressions)
* *Transaction ID* - ID of order, needed only on thank you page
* *Checkout Step* - step of checkout (1 = cart)

### Page Types
On different pages use this values (case insensitive) for "Page Type" field:
* `home` or `homepage`
* `category`, `list`, `product.list` or `searchresults` - list of products
* `product`, `detail` or `product.detail` - detail of product
* `cart` or `checkout` - view of basket
* `purchase` - thank you page
