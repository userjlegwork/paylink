# PayLink MUI

PayLink MUI is a fork from [Paylink](https://github.com/dlcastillop/paylink) using Material UI and some variation in concepts

## Live example

[https://userjlegwork.github.io/paylink/](https://userjlegwork.github.io/paylink/)

## How to use

PayLink uses React and Material UI to create pre-built components for your PayLink page. You only need to work in the **paylink.config.json** file.

### Hero section

The Hero section is going to have your photo, name and description. You can modify it in the **properties** object which has the following properties.

- name: your name
- description: your description
- alt: an alternative text for your photo
- hero: the path to your photo. We recommend to put it in the **images** folder.

For example:

    "properties": {
        "name": "Daniel Castillo",
        "description": "Frontend web developer",
        "alt": "Photo of Daniel Castillo",
        "hero": "./src/images/daniel-castillo.png"
    },

### Social media section

The Social Media section is going to have all your social media links. You can modify it in the **Social** array which has one object per social media. You only need to put your social media link in the **link** property within the corresponding object.

For example:

    "Social": [
        { "label": "Link", "type": "link", "link": "" },
        { "label": "GitHub", "type": "github", "link": "https://github.com/userjlegwork" },
        { "label": "Twitter", "type": "twitter", "link": "" },
        { "label": "LinkedIn", "type": "linkedin", "link": "" },
        { "label": "Instagram", "type": "instagram", "link": "" },
        { "label": "Discord", "type": "discord", "link": "" },
        { "label": "Facebook", "type": "facebook", "link": "" },
        { "label": "Medium", "type": "medium", "link": "" },
        { "label": "Pinterest", "type": "pinterest", "link": "" },
        { "label": "Snapchat", "type": "snapchat", "link": "" },
        { "label": "Telegram", "type": "telegram", "link": "" },
        { "label": "TikTok", "type": "tiktok", "link": "" },
        { "label": "Twitch", "type": "twitch", "link": "" },
        { "label": "Vimeo", "type": "vimeo", "link": "" },
        { "label": "WhatsApp", "type": "whatsapp", "link": "" },
        { "label": "YouTube", "type": "youtube", "link": "" },
        { "label": "Product Hunt", "type": "product-hunt", "link": "" }
    ],

The Social Media section supports Twitter, GitHub, LinkedIn, Instagram, a link, Discord, Facebook, Medium, Pinterest, Snapchat, Telegram, TikTok, Twitch, Vimeo, WhatsApp, YouTube and Product Hunt.

### Payment section

The Payment section is going to have all your payment methods. You can modify it in the **Payments** array which has one object per payment methods. You only need to put your payment method link in the **value** property within the corresponding object.

For example:

    "Payments": [
        {
            "id": "btc",
            "label": "Bitcoin",
            "value": "",
            "img": "./src/images/payments/btc.svg"
        },
        {
            "id": "busd",
            "label": "BinanceUSD",
            "value": "",
            "img": "./src/images/payments/busd.svg"
        },
        {
            "id": "matic",
            "label": "Matic",
            "value": "",
            "img": "./src/images/payments/matic.svg"
        },
        {
            "id": "doge",
            "label": "DogeCoin",
            "value": "",
            "img": "./src/images/payments/doge.svg"
        },
        {
            "id": "eth",
            "label": "Ethereum",
            "value": "",
            "img": "./src/images/payments/eth.svg"
        },
        {
            "id": "ltc",
            "label": "Litecoin",
            "value": "",
            "img": "./src/images/payments/ltc.svg"
        },
        {
            "id": "paypal",
            "label": "Paypal",
            "value": "",
            "img": "./src/images/payments/paypal.svg"
        },
        {
            "id": "usdt",
            "label": "USDT",
            "value": "",
            "img": "./src/images/payments/usdt.svg"
        },
        {
            "id": "qvapay",
            "label": "QvaPay",
            "value": "",
            "img": "./src/images/payments/qvapay.svg"
        },
        {
            "id": "sol",
            "label": "Solana",
            "value": "",
            "img": "./src/images/payments/sol.svg"
        },
        {
            "id": "ada",
            "label": "ADA",
            "value": "",
            "img": "./src/images/payments/ada.svg"
        },
        {
            "id": "trx",
            "label": "Tron",
            "value": "",
            "img": "./src/images/payments/trx.svg"
        },
        {
            "id": "xrp",
            "label": "XRP",
            "value": "",
            "img": "./src/images/payments/xrp.svg"
        },
        {
            "id": "card",
            "label": "Card",
            "value": "",
            "img": "./images/payments/card.svg"
        }
    ]

The Payment section supports Bitcoin, Binance USD, Matic, DogeCoin, Ethereum, Litecoin, PayPal, USDT, QvaPay, Solana, ADA, TRON, XRP and a card.

## How to deploy

### Deploy on GitHub Pages

1. Go to the repository settings, enable GitHub Pages and, select the `GitHub Actions` option as the source. For more info visit <https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-with-a-custom-github-actions-workflow>
2. Go to the `vite.config.js` and uncomment the `base` parameter. For more info read the comment in `vite.config.js`
3. After some seconds the deployment will be ready in `https://<username>.github.io/paylink`

## Special thanks

Many thanks to [Manuel Ernesto](https://twitter.com/manuelernestog), [Yoannis Sánchez](https://twitter.com/yossthedev), [Carlos Z. Bent](https://t.me/carloszbent_channel) and [Alex Navarro](https://twitter.com/Swordfest). PayLink is much better thanks to your work.

## Contributions

Suggestions and pull requests are welcomed!
