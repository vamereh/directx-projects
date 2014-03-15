C++ и DirectX 9
================

Разные инсталляции 3D анимаций на C++ и DirectX 9 (2007г.), которые я готовил для практической части своей [дипломной работы по нейросетям](https://github.com/vamereh/neural-network).

## Что нужно, чтобы посмотреть?

Windows и поддержку DirectX 9. Да и еще архиватор, который может распаковать zip архив.

## Как запустить и посмотреть?

```shell
git clone git@github.com:vamereh/directx-projects.git
```
Затем извлекайте из архива то, что понравилось. Переходите в извлеченную папку, затем в папку Debug и ищите там exe файл. Запускайте.

## Что внутри?

Все архивы - это проекты среды Visual С++, т.е. можно посмотреть реализацию.

* betty_run - идущая battle girl; качественная модель, анимация, текстуры.
* pauk_run - идущий моб Паук.
* pauks_zoo - ограниченная площадь, где разворачивается визуализация работы простейшей нейросети (перцептрон). Главные герои паучки, которые бегают, добывают еду, сражаясь со своими конкурентами. У каждого паучка своя нейронная сеть. Все нейронные сети инициализируются при запуске приложения с разными исходными данными. В результате каждый паучок приобретает свой характер, специфичное поведение и просто похож на живое существо. Этот инсталляция интересна еще и тем, что паучки ходят по не ровной поверхности, а еда сбрасываемая им падает под действием силы тяжести (только нет ускорения).
* pauk_zoo_light - то же самое, что вверху только в обрезанном варианте.

## Есть вопросы?

Кузнецов Алексей.
Пишите: vamereh@gmail.com
