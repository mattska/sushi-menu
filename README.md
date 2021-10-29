# Sushi Menu
## API
_Base URL_: https://my-json-server.typicode.com/mattska/sushi-menu

### Lista delle categorie di prodotto
**GET** /categories
````
{
  "id": "categories-0001",
  "name": "Uramaki"
}
````
### Lista dei prodotti a menù
**GET** /products
````
{
  "id": "product-0001",
  "name": "Salmon Flambe",
  "image": "",
  "price": 2.50,
  "category": "categories-0001",
  "ingredients": [
    "ingredients-0001",
    "ingredients-0002"
  ]
}
````
### Lista degli ingredienti di menù
**GET** /ingredients
````
{
  "id": "ingredients-0001",
  "name": "Riso"
}
````
