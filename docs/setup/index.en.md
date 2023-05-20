---
title: Setup
description: Get a clou on your personal settings on coaster.cloud app.
icon: material/cog

hide:
    - navigation
---

## Register account

After installing our app, you _can_ create an account. The account is used to login to the **app** and **website**.

<figure markdown>
[Register account: coaster.cloud](https://coaster.cloud/account/register){:target="_blank" .md-button }
</figure>

## Premium features

As a registered user we can offer you premium features like this:

<figure markdown>
![Profile Setup](../assets/images/setup/setup_features_dark.png#only-dark)
![Profile Setup](../assets/images/setup/setup_features_light.png#only-light)

Screenshot App
</figure>

<div class="grid cards" markdown>

- :material-chart-bar-stacked: Get your own statistics

    ---
    From the registration of park visits and attractions ridden, we create extraordinary statistics.

- :fontawesome-brands-fort-awesome: Count visits

    ---
    Every park visit that is recorded can be tracked by you and counted for the statistics. This results in awesome statistics.

- :material-counter: Count rides

    ---
    We love statistics. That's why we `count` our rides. This results in crazy statistics.

- :material-heart-plus: Favoriten festlegen

    ---
    Set your favorite parks or attractions, to get a faster access.

- :material-image-plus: Upload images

    ---
    Upload photos of objects (It's not a family album) and let other users rate your photos :material-thumb-up-outline:. By the way, the most beautiful and rated photos are often available as cover images.

- :material-source-pull: Contribution

    ---
    With your profile you can contribute to our `coaster.cloud` database. How this works? See it [here](../contribute/).

- :fontawesome-solid-users: Groups function [^1]

    ---
    Users can be grouped together by entering a code. You will now see the `counts` of the others. [BETA][^1]

</div>

## Multilingual

Our coaster.cloud app is available in several languages. The multilingual translations are also contributed by our community. With the help of [crowdin.com](https://crowdin.com/project/coastercloud) we can work together on a translation. The biggest challenge here is the special terms we use in this industry. You can also help with the translation.

As a translator, you can activate the language you support at [crowdin.com](https://crowdin.com/project/coastercloud). The base language is British English. In a very simple "left / right" table and with AI support, you can now translate as much as you have time for.

The highlight of [crowdin.com](https://crowdin.com/project/coastercloud) : After translating, your translation is in a "review mode". This means that the translation does not go live immediately, but is checked by another person. If you see a translation by someone else and find it suitable - just put a tick on it. The reviewer will notice more quickly that this translation is correct.

``` mermaid
graph LR
  A[translation] --> B{is reviewd};
  B -->|no| C[need translation];
  C --> D[review];
  D --> B;
  B ---->|yes| E[go live!];
```

### Supported languages in our app

* :flag_gb: English (source)
* :flag_de: German
* :flag_nl: Dutch
* :flag_fr: French
* :flag_it: Italian
* :flag_es: Spanish
* :flag_pt: Portuguese

<figure markdown>
  ![CrowdIn.com activity](../assets/images/setup/crowdin_activity.en.png)
  <figcaption>CrowdIn.com activity</figcaption>
</figure>

[^1]: The group feature is currently only available to BETA testers and selected partners.
