# Lavide landing

A one-page site for a specialist who sells targeting, landing pages, and chat bots. The page introduces the offer, the cases, and a way to write.

## Problem

The offer was being explained in direct messages. There was no single URL that showed the three services, a few results, and a contact path in the same voice as the person selling them.

## What was built

`index.html` is the whole site. The document title is “Олена Стратієвська — Таргет · Лендінги · Чат-боти”. Styles and the small scripts live in the same file so the page can be hosted as one document. Photos and icons sit next to it.

## How it works

A visitor scrolls from the headline through the services and the examples to the contact block. There is no application server in this repository. Links and the form action are whatever was pasted into the HTML at the time of the case.

## Stack

HTML, CSS, JavaScript.

## Run locally

```bash
python3 -m http.server 8080
```

Open `http://127.0.0.1:8080`.
