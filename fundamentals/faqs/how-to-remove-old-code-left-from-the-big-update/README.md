---
description: >-
  The instructions to completely delete leftover DECO codes from your theme ( if
  you don't find those code files, it means all DECO codes no longer to exist in
  your store)
icon: trash-can
---

# How to remove old code left from the big update?

{% hint style="info" %}
After upgrading the app using the Polaris 12 gallery of Shopify, all of DECO codes are moved into the DECO theme app extension, not existing in your theme.\
\
But, sometimes, there will be some files left in your theme. They do not impact your theme elements, or other factors such as loading speed, or SEO in any way. However, to remove them completely, please follow this instruction:
{% endhint %}



1. Go to **Themes** > **Edit codes**

<figure><img src="../../../.gitbook/assets/image (484).png" alt=""><figcaption></figcaption></figure>

2. Delete "**\{% include 'scm-product-label-head' %\}**" in file "**theme.liquid**"

* In the search bar, you search for "**theme.liquid**", then click to open the file. Next in the code, you search for "**scm**", then find the line "**\{% include 'scm-product-label-head' %\}**" to delete.

<figure><img src="../../../.gitbook/assets/image (491).png" alt=""><figcaption></figcaption></figure>

* If this file has "**\<!--Product-Label script. Don't modify or delete-- >**" below the code "**\{% include 'scm-product-label-head' %\}"**, you will also delete all that part or kindly contact us to delete those files for you more easily!

3. Remove all the file(s) that has **"scm"** in the title.

* In the search bar, you search for "**scm**", then find all the file with "**scm**" > click those files starting with "**scm**" > click this button ![](<../../../.gitbook/assets/image (489).png>)

<figure><img src="../../../.gitbook/assets/image (486).png" alt=""><figcaption></figcaption></figure>

4. Remove all the file that has **"sma-deco-label.css"** in the title.

* In the search bar, you search for "**sma-deco-label.css**", then find the file to delete.

<figure><img src="../../../.gitbook/assets/image (490).png" alt=""><figcaption></figcaption></figure>
