# DoguinhoHotel-NLW

<p align="center">
  <img alt="OriginSix" src="https://github.com/gessic22/DoguinhoHotel-NLW/blob/e6f95470d57f5992d1c19673e2b83b23aebe2776/DOGUINHOHOTEL.PNG" width="100%">
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- HTML
- CSS
- JavaScript

Bibliotecas

- [Google Fonts](https://fonts.google.com/)
- [SwipeJS](https://github.com/nolimits4web/Swiper)
- [ScrollRevel](https://scrollrevealjs.org)

Utilitários

- [randomuser.me](https://randomuser.me/photos)
- [IconMoon](https://icomoon.io/app/#/select)

## 💻 Projeto

DoguinhoHotel é uma página institucional no formato One Page, responsiva, para usar em diversos tipos de micro, pequena e média empresas. Contém as seguintes seções: Header, Navigation, Home, Sobre, Serviços, Depoimentos, Contato e Footer

## ⏫ Updates

Bug do Scroll x no slider de depoimentos (resolvido por @erikfritas):
- Para remover este bug, foi necessário apenas modificar o #testimonials, adicionando mais duas linhas:
```css
#testimonials{
  ...
  width: 100%;
  overflow-x: hidden;
}
```

