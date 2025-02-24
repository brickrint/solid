# Солидбук

> Read [in English](./docs/en.md).

[Книга о принципах SOLID](https://ota-solid.vercel.app) и объектно-ориентированном дизайне программ.

## О чём это и для кого

Программировать — сложно.

Хороший код адекватно отражает систему, которую описывает, он устойчив к изменениям в этой системе. Плохой код запутанный, хрупкий и непонятный — он замедляет разработку.

Код становится плохим, когда он перестаёт соответствовать реальности — бизнес-требованиям, правилам поведения частей системы, их отношениям друг с другом. Бизнес-правила — это территория, код — карта этой территории. Чем точнее карта, тем проще справляться с изменениями в требованиях и даже предвидеть их.

В этой книге мы хотим рассказать и показать на примерах, как принципы объектно-ориентированного программирования могут помочь спроектировать устойчивую систему.

## О каких принципах пойдёт речь?

Мы рассмотрим 5 принципов SOLID, а именно:

- [принцип единственной ответственности](https://ota-solid.vercel.app/srp)
- [открытости и закрытости](https://ota-solid.vercel.app/ocp)
- [подстановки Барбары Лисков](https://ota-solid.vercel.app/lsp)
- [разделения интерфейса](https://ota-solid.vercel.app/isp)
- [инверсии зависимостей](https://ota-solid.vercel.app/dip)

Каждый из принципов — это лишь рекомендация, все они имеют область и границы применения. Но чтобы увидеть эти границы, необходимо понять, в чём польза и издержки каждого. Многие принципы вам покажутся чрезмерно абстрактными, неконкретными или вовсе надуманными. Отнеситесь к таким принципам, как к дзену Python — держите в голове, но проверяйте, насколько они полезны в конкретной ситуации.

Мы в этой книге предлагаем ещё одну из бесконечного числа интерпретаций этих принципов, попутно расписывая пользу и ограничения каждого. Зная пользу и ограничения, можно оценить, насколько конкретный принцип помогает решить задачу, стоящую перед вами.

## Об авторах

Эту книжку написали:

- [Саша Беспоясов](https://bespoyasov.ru) — разработчик в [0+X](https://0x.se), соавтор [Тяжеловато](https://fuckgrechka.ru/tzlvt/), бывший преподаватель в [Нетологии](https://netology.ru);
- [Артём Самофалов](https://github.com/dex157) — ведущий фронтенд-разработчик в [Social Discovery Ventures](https://sdventures.com), бывший преподаватель в [LoftSchool](https://loftschool.com).

...И [контрибьюторы проекта](https://github.com/open-tech-authors/solid/graphs/contributors) ❤️

## Лицензии

Текст и иллюстрации книги распространяются под лицензией [CC BY-NC-SA 4.0](./LICENSE-SA.md). Вы можете дополнять, менять и использовать их в проектах на некоммерческой основе при сохранении лицензии и указании авторов.

Исходный код проекта распространяется под лицензией [MIT](./LICENSE-MIT.md).
