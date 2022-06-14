# **TypeMarkup**

TypeMarkup is a beautiful and simple language for web documents.

## **Preview**

```TypeMarkup
*html :: lang es

&html head
  meta :: charset UTF-8

  :: http-equiv X-UA-Compatible
  :: content IE-edge
  meta

  :: content width=device-width, initial-scale=1.0
  :: name viewport
  meta

&html body
  p >> what!?

  :: src templates/header
  Header

  :: src templates/main
  Main

  :: src templates/footer
  Footer
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## LICENSE
[Apache-2.0](https://www.apache.org/licenses/)
