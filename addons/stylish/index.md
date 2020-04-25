# Stylish - Custom themes for any website

> https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=en

When working with different tabs in the browser for the development site `DEV`, the test site `UAT` and the production site `PROD`, it can quickly become confusing to know which tab corresponds to which environment. Especially when you do something dangerous such as deleting records, launching batches, ...

Are you really sure that the site displayed is that of the test site? Even when the URL is just an IP?

Thanks to [Stylish](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=en)

![Sample](./images/sample.png)

The configuration is just CSS so, f.i., for the UAT sites (regex based on the URL), we can define something like:

```css
body {
    background: #FFE400;
}

body::before {
    content: "=== USER ACCEPTANCE SITE ===";
}
```

Same for PROD URLs.
