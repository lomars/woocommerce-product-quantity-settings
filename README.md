# WooCommerce product quantity settings
### Set quantity min max and step at product level in Woocommerce

In WooCommerce admin product pages general settings, a checkbox enable or disable some additional quantity setting fields that handle minimum, maximun and step arguments at product level (showing or hiding the setting fields dynamically):

**When checkbox is unchecked, quantity setting fields are not visible and disabled:**

<img src="https://i.stack.imgur.com/yy21r.png" />

**When checkbox is checked, quantity setting fields are visible and enabled for the current product:**

<img src="https://i.stack.imgur.com/v24yh.png" />

**Note:** All settings are merged in a unique custom field as an indexed array of values, to improve performance.

> Also this works nicely on "Ajax add to cart" for simple products, for product variations from variable products and also on the cart quantity input field.
