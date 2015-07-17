# Paydunk Front End Plugin

<img alt="Paydunk" src="http://paydunk.com/wp-content/themes/paydunk/images/footr_logo.png" />

### Usage:

Add this div to your web page where you would like the paydunk button to appear:

```html
<div id="paydunkButton"></div>
```

Request API access and register applications at https://developers.paydunk.com. Check in the Applications tab to view all of your apps. You'll see each of your apps are given an App ID. Update the code below with your App ID and price:

```js
<script type="text/javascript" src="jquery.paydunk.js"></script> 
<script>
$('#paydunkButton').paydunk({
    appID        : '7k2f9w57LmFfzU7eP3AQEZW19H5qj8XRwEE73VfB', //your App ID goes here - required!!
    price        : 20, //required!!
    order_number : 1,
    tax          : 0,
    shipping     : 0
});
</script>
```

Order number, tax and shipping are optional. Be sure to include jquery on your page as well!
