---
cover: ../../.gitbook/assets/24.svg
coverY: 0
---

# 🧩 Product Metafields

## 🔎 What Are Shopify Product Metafields?

\
&#x20;  "_**Shopify metafields let you store additional, specialized information about your products—beyond what's available in the standard admin fields. They’re useful for showing things like material composition, potency, size details, or ingredient breakdowns**_."

⇒ DECO uses product metafields to generate dynamic labels and badges automatically<mark style="color:blue;">**—so all using the same design—just powered by different metafield values.**</mark>

## 🗂️ Common Use Cases

### 1. Show Values Of Product Meta Field Dynamically

#### 🌿 **Cannabis Products**

* Show **THCa flower potency** or **strain type** on product badges
* Display **CBD/THC ratios** dynamically

<figure><img src="../../.gitbook/assets/image (201).png" alt=""><figcaption></figcaption></figure>

#### 🕯️ **Handmade Goods**

* Highlight **soy wax percentage** for candles

<figure><img src="../../.gitbook/assets/image (202).png" alt=""><figcaption></figcaption></figure>

### 2. Show Exact Values Of Product Meta Field&#x20;

#### &#x20;🎀 Skincare Products

* Display the exact skin type that the product suits
* Based on what's written in-app

<figure><img src="../../.gitbook/assets/image (556).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (555).png" alt=""><figcaption></figcaption></figure>

## ✅ Preparations

Before starting, you need:

* [x] DECOPlan: Growth/Unlimited
* [x] Product metafields created in your Shopify admin
* [x] Metafield values assigned to your products

For example:&#x20;

<figure><img src="../../.gitbook/assets/image (544).png" alt=""><figcaption></figcaption></figure>

## ✨Step-by-step Setup

We'll walk through **two use cases**:

1. Show <mark style="color:blue;">**dynamic**</mark> metafield value if it exists
2. Show <mark style="color:blue;">**specific**</mark> metafield values only

## 🔁 Shared Steps for Both Use Cases

🔹 <mark style="color:blue;">**Step 1: Create or Select Badge**</mark>

* Open DECO app >> Navigate to: Labels & Badges then:

→ If you **don't have any badges** yet: Click _<mark style="color:blue;">**"Create badge"**</mark>_ >> Choose to create a _<mark style="color:blue;">**new Text Badge**</mark>_

→ If you **already have** badge(s): Click the _<mark style="color:blue;">**pencil icon**</mark>_ to edit an existing badge

<figure><img src="../../.gitbook/assets/image (670).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
This badge will act **as a dynamic template using metafield data**
{% endhint %}

<mark style="color:blue;">🔹</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Step 2: Connect Metafield with AutoText**</mark>

* &#x20;Go to Badge **Content** → Click **AutoText**
* In the popping list, scroll down & choose: **Product Metafields**&#x20;

<div><figure><img src="../../.gitbook/assets/image (668).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (669).png" alt=""><figcaption></figcaption></figure></div>

* Then a list of active meta fields will appear, _<mark style="color:blue;">**check the box**</mark>_ to select >> _<mark style="color:blue;">**Click "Select"**</mark>_ button to save the change.

<figure><img src="../../.gitbook/assets/image (672).png" alt=""><figcaption></figcaption></figure>

### 🎯 <mark style="color:blue;">Use Case 1: Show Values Of Product Meta Field Dynamically</mark>

#### 🔹 Step 3: Add Product Metafield

* Move to the "<mark style="color:blue;">**Products"**</mark> tab to select the metafield condition
* Scroll to the <mark style="color:blue;">**Metafield**</mark> >> Click <mark style="color:blue;">**+ Add Metafield**</mark>**&#x20;>>** _**Then, choose&#x20;**<mark style="color:blue;">**the same metafield name**</mark>**&#x20;as you selected in the last step**_**&#x20;>>** Hit on <mark style="color:blue;">**"Select"**</mark> button

<div><figure><img src="../../.gitbook/assets/image (673).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (674).png" alt=""><figcaption></figcaption></figure></div>

* After selecting your product metafield key >> <mark style="color:blue;">**Choose the option: "Exists"**</mark>&#x20;

<figure><img src="../../.gitbook/assets/image (675).png" alt=""><figcaption></figcaption></figure>

#### 🔹 Step 4: Preview & Verify&#x20;

* The app will <mark style="color:blue;">**automatically scan**</mark>**&#x20;your products&#x20;**<mark style="color:blue;">**and detect**</mark>**&#x20;which ones&#x20;**<mark style="color:blue;">**contain the keywords**</mark>**&#x20;related to the metafield key you selected.**\
  \
  👉 For those products, it will <mark style="color:blue;">**display the corresponding value**</mark>**&#x20;on the badge.**

**Example:**

* **Metafield Key:** care instruction
* **Condition:** _Exists_

<figure><img src="../../.gitbook/assets/image (676).png" alt=""><figcaption></figcaption></figure>

→ In this case, <mark style="color:blue;">**any product**</mark>**&#x20;that&#x20;**<mark style="color:blue;">**includes data in the "care instruction"**</mark>**&#x20;metafield will&#x20;**<mark style="color:blue;">**automatically show a badge with that value.**</mark>\
\
&#xNAN;_(See the image below for a visual example.)_

<figure><img src="../../.gitbook/assets/image (545).png" alt=""><figcaption></figcaption></figure>

### <mark style="color:blue;">🎲 Use Case 2: Show Exact Values Of Product Meta Field</mark>

#### 🔹 Step 3: Add Product Metafield&#x20;

* Move to the "<mark style="color:blue;">**Products"**</mark> tab to select the metafield condition
* Scroll to the <mark style="color:blue;">**Metafield**</mark> >> Click <mark style="color:blue;">**+ Add Metafield**</mark>**&#x20;>>** _**Then, choose&#x20;**<mark style="color:blue;">**the same metafield name**</mark>**&#x20;as you selected in the last step**_**&#x20;>>** Hit on <mark style="color:blue;">**"Select"**</mark> button

<div><figure><img src="../../.gitbook/assets/image (673).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (674).png" alt=""><figcaption></figcaption></figure></div>

* Choose the option: <mark style="color:blue;">**"Equal to"**</mark> >> Type in the <mark style="color:blue;">**Product metafield Value**</mark> in the white box

For example:

<figure><img src="../../.gitbook/assets/image (677).png" alt=""><figcaption></figcaption></figure>

#### 🔹 Step 4: Preview & Verify

* The app will **automatically find products that have the** <mark style="color:blue;">**exact metafield value**</mark> you entered.&#x20;

&#x20;        👉 **Then&#x20;**<mark style="color:blue;">**show that value**</mark>**&#x20;on the badge for those products**<mark style="color:blue;">**.**</mark>

**Example:**

* **Metafield Key:** _care instruction_
* **Value:** _sunlight prefer_
* **Condition:** _Equal To_

<figure><img src="../../.gitbook/assets/image (554).png" alt=""><figcaption></figcaption></figure>

→ In this case, <mark style="color:blue;">**any product(s)**</mark>**&#x20;that include the metafield value&#x20;**<mark style="color:blue;">**"sunlight prefer"**</mark>**&#x20;will&#x20;**<mark style="color:blue;">**automatically**</mark>**&#x20;show a badge&#x20;**<mark style="color:blue;">**with that value.**</mark>\
\
🖼️ _(See image below for example)_

<figure><img src="../../.gitbook/assets/image (553).png" alt=""><figcaption></figcaption></figure>

## ❗ Quick Troubleshooting

* **"No data"** → Double-check whether those <mark style="color:blue;">**products have the Product Metafield Value assigned yet OR**</mark> make sure the <mark style="color:blue;">**metafield key selected in AutoText matches**</mark> the one added in the <mark style="color:blue;">**Metafield section (under the Products tab).**</mark>
* **No display** → Notice <mark style="color:blue;">**Uppercase/ Lowercase letters**</mark> (e.g., `Linen` ≠ `linen`)

<figure><img src="../../.gitbook/assets/image (557).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
For the option <mark style="color:blue;">**"Exists"**</mark> →  Only type the product metafield <mark style="color:blue;">**KEY**</mark>

While with the <mark style="color:blue;">**"Equal to**</mark>" →  Only type the product metafield <mark style="color:blue;">**VALUE**</mark>
{% endhint %}

## 📞 Need Help?

If you’re stuck or need our experts to check your settings:

👉 Contact directly with the live-chat **DECO Support** team  and include:

* Your <mark style="color:blue;">**badge name**</mark>
* <mark style="color:blue;">**Screenshots**</mark> of your <mark style="color:blue;">**Shopify metafield setup**</mark>
* <mark style="color:blue;">**An example link**</mark> should have the badge to display on your website
