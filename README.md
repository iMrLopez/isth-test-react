# [IsthmusIT](https://isthmusit.com) - Frontend technical test

This test is a part of our hiring process at IsthmusIT for ReactJS frontend positions. It should take you between 3 and 12 hours depending on your experience.

**Feel free to apply! Drop us a line with your LinkedIn/GitHub/Twitter/AnySocialProfileWhereYouAreActive at jobs@isthmusit.com**


## Summary

The goal of this test is to make you code a small ReactJS app. We have scaffolded a skeleton app for you, but please change whatever you want (CSS files, HTML structure, JS structure...).

- Make sure to load the list of products at the beginning of the execution, it will change everytime you hit the API endpoint below
- The app can have as many components as you want.
- Any library of your choice can be used.
- The search should work and filter (prefereably in real time) the list of products by its SKU

Show us what you can do in 12 hours top!.


To give you an idea, here what your app could look like:


![app]()

## Installation

It should be as straight forward as:
```
npm install
npm start
```

## API documentation

### Routes

Here is the API address: https://fakemyapi.com/api/fake?id=1b35a44d-dfab-4182-aada-9632044912aa

- **GET** - https://fakemyapi.com/api/fake?id=1b35a44d-dfab-4182-aada-9632044912aa  Returns an array of products with the structure below, you should load this array of products at the beginning of the session as it is not static and a new random set will be generated everytime you request the endpoint

### Call object example

```
{
      "sku": 6605,
      "nombre": "Tasty Soft Gloves",
      "categoria": "Games",
      "estado": true,
      "tieneImpuestos": false,
      "marca": "Swift Inc",
      "inventario": 44494,
      "precios": {
        "moneda": "MNT",
        "precio": "330.00"
      },
      "imagenes": [
        "http://lorempixel.com/640/480/food",
        "http://lorempixel.com/640/480/food"
      ]
    }
```

## Submission

Fork this repository and send us an email to jobs@isthmusit.com with the link to your forked repository. We'll review it and get back to you in order to talk about your code!

Contact us at jobs@isthmusit.com if you need more details.
