# daily-life-hacks

## 1. Subscribe to all bank of america deals on the webpage
1. Go to Customer Deals browser page in your BofA account. https://secure.bankofamerica.com/customer-deals/
2. Go to "Console" tab in the developer tools of browser and paste the below
```js
document.querySelectorAll("#bamdAvailableDeals div.deal-logo-wrapper.top > a").forEach(function (item, index) {item.click()});
```
