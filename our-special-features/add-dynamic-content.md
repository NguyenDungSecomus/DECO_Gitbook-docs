---
description: >-
  Select an automatic text option to display dynamic details of each product.
  Specifically, it'll automatically calculate % discount, Remaining stock, Day
  release, etc of each products.
cover: ../.gitbook/assets/Screenshot_1 (6).png
coverY: 0
---

# 💡 Add Dynamic Content

## GUIDELINE VIDEO

{% hint style="info" %}
This function is only available for **TEXT LABEL/BADGE**
{% endhint %}

{% embed url="https://www.youtube.com/watch?v=qOxhsr4z750" %}

## DETAILED DOCS



* First, on your app dashboard, click on "Create label":

<figure><img src="../.gitbook/assets/image (298).png" alt=""><figcaption></figcaption></figure>

* Then, you will see this screen, please choose "Text label":

<figure><img src="../.gitbook/assets/image (299).png" alt=""><figcaption></figcaption></figure>

* After that, click on "Add discount" button, then choose 1 of your preffered&#x20;

<figure><img src="../.gitbook/assets/image (300).png" alt=""><figcaption></figcaption></figure>

<details>

<summary>This feature will base on your available settings in your Shopify Admin to automatically calculate and display dynamic values of your products</summary>



</details>

{% hint style="info" %}
5 types of variables:&#x20;
{% endhint %}

<figure><img src="../.gitbook/assets/image (463).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="136">Types</th><th align="center">Code </th><th>Usage</th><th>Example</th><th data-hidden></th></tr></thead><tbody><tr><td><strong>Discount %</strong></td><td align="center">SAVE {SAVE_PERCENT}%</td><td>It will use this formula<strong>: </strong><mark style="background-color:green;"><strong>[(Compare-at price - price)/ compare-at price]*100</strong></mark> in your Shopify admin to automatically display the sale percentage</td><td><ul><li>Price: $399</li><li>Compare-at price: $499</li></ul><p>-> Formula: <mark style="background-color:orange;"><strong>[(499-399)/499]*100</strong></mark> </p><p>-> The sale percentage displayed on label: SAVE 20%</p></td><td></td></tr><tr><td><strong>Discount amount</strong></td><td align="center">SAVE {SAVE_AMOUNT} NOW</td><td>It will use this formula:  <mark style="background-color:green;"><strong>(Compare-at price - Price)</strong></mark> in Shopify admin to automatically display the sale amount</td><td><ul><li>Price: $350</li><li>Compare-at price: $560</li></ul><p>-> Result: SAVE 210 NOW</p></td><td></td></tr><tr><td><strong>Price</strong></td><td align="center">ONLY {PRICE}$</td><td>It will <mark style="background-color:green;"><strong>base on the Price of your products</strong></mark> to display on your label</td><td><ul><li>Price: $350</li></ul><p>-> Result: ONLY 350$</p></td><td></td></tr><tr><td><strong>Day release</strong></td><td align="center">NEW IN {NEW_FOR}</td><td>It will <mark style="background-color:green;"><strong>base on the publish date of your products</strong></mark> to automatically calculate how many days left to display on your label</td><td><ul><li>The created date: July 1, 2024</li><li>The current date: July 10, 2024<br><br>-> Result: NEW IN 10<br></li></ul></td><td></td></tr><tr><td><strong>Remaining stock</strong></td><td align="center">ONLY {STOCK} LEFT</td><td>It will <mark style="background-color:green;"><strong>base on the total of available stock in Inventory</strong></mark> to automatically display on your label</td><td><ul><li>Available: 19 </li></ul><p>-> Result: ONLY 19 LEFT</p></td><td></td></tr></tbody></table>

**NOTE:**&#x20;

1\. If you want your text will be in another lines: Insert \</br> into the text box&#x20;

2\. All content in the text box should be written in 1 line, please don't press "enter" on your keyboard

3\. This mark " is a special character, instead of using it, please use this mark '
