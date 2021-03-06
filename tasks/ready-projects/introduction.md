# ready-projects

Не так важно, сколько книг по программированию вы прочли, сколько видео просмотрели и сколько подкастов прослушали, - если вы хотите стать разработчиком, вам нужно писать код.

Практиковаться можно как создавая свои собственные проекты, так и разбирая как пишут свои приложения другие разработчики. При этом простое копирование чужого кода результата не даст и ваш навык мастерства не поднимет. Постарайтесь разобраться, почему код пишется так, а не иначе, понять логику автора, не просто повторить готовую работу, но улучшить её, исправить замеченные ошибки и неточности, внести в неё что-то своё.

В предложенной подборке тасков вам предлагаются задания, в которых есть всё необходимое, чтобы начать программировать:
- демо приложения, чтобы посмотреть что должно получиться в итоге
- код приложения, чтобы сравнить то, что написали вы, с тем, что должно получиться, облегчить поиск ошибок в вашем коде
- видео автора приложения с пояснением как он пишет код
- дополнительные материалы, которые могут быть вам полезными

**Ваша задача** - используя предложенные материалы в качестве образца и руководства к действию **самостоятельно** написать своё собственное приложение. При этом html- и css-код с целью экономии времени можно скопировать полностью. Предполагается, что html и css вы уже знаете или выучите в ходе выполнения других заданий. Наша цель - научиться писать js-код. Его необходимо написать самостоятельно, весь полностью, от первого до последнего символа.

## Предполагаемая последовательность действий

- просмотрите видео с разбором кода полностью. Скорость просмотра видео можно увеличить, например, до 1.5х. Для видео на английском языке есть возможность включить субтитры и перевести их на русский язык. 
- оцените объём работы, определите последовательность действий, выделите основные этапы написания кода приложения
- при необходимости обратитесь к дополнительным материалам, возможно, там найдутся какие-то подсказки, которые облегчать работу над проектом, сделают её более осмысленной
- просматривайте видео по частям и пишите код вслед за автором. Старайтесь повторять код не строчка в строчку, а запоминать и воспроизводить логические фрагменты кода
- после того как вы полностью повторили авторский вариант приложения, первый этап работы над проектом закончен
- на втором этапе подумайте, как можно изменить/улучшить код приложения, какую дополнительную функциональность в него можно добавить
- объём и сложность дополнительной функциональности зависят от вашего опыта программирования и стремления выполнить задание максимально качественно. Это может быть добавление всего одной небольшой дополнительной функциональности, схожей с той, которая уже используется в приложении. Например, можно добавить в калькулятор функцию извлечения квадратного корня. Но изменения могут быть и более значительными, так, на основе простого калькулятора можно создать инженерный калькулятор с множеством функций
- когда работа над приложением закончена, временно, на период проверки, добавьте alert, в котором опишите всю добавленную вами дополнительную функциональность, чтобы проверяющим было удобнее проверять ваш проект. После проверки задания и выставления баллов, alert из кода приложения можно будет убрать.

## Требования к репозиторию

- для работы над проектом используйте свой собственный приватный репозиторий 
- название репозитория ready-projects, название веток, в которых ведётся разработка, соответствует названиям проектов, ветка master пустая, содержит только README.md
- история коммитов должна отображать процесс разработки приложения. [Требования к коммитам](https://docs.rs.school/#/git-convention)
- демо-версия приложения размещается на `https://www.netlify.com/`, либо на другом подобном хостинге. Для демоверсий, размещённых на netlify.com, название сайта даёте по схеме: имя гитхаб аккаунта - название таска.
- после окончания разработки или при наступлении дедлайна, создайте pull request из ветки разработки в ветку master. [Требования к pull request](https://docs.rs.school/#/stage2?id=Описание-pull-request-должно-содержать-следующую-информацию). Мержить pull request не нужно

## Проверка приложения

- приложение проверятся другими студентами (кросс-чек). Для этого до наступления дедлайна ссылку на демо-версию приложения добавьте в rs app https://app.rs.school/ вкладка Cross-Check: Submit
- для проверки приложения в ходе кросс-чека ссылки на проверяемые работы будут находиться в rs app вкладка Cross-Check: Review

## Технические требования

- работа приложения проверяется в браузере Google Chrome последней версии
- можно использовать [bootstrap](https://getbootstrap.com/), [material design](https://material.io/), css-фреймворки, html и css препроцессоры
- не разрешается использовать jQuery, другие js-библиотеки и фреймворки

## Критерии оценки

- Максимальный балл за задание указывается в самом задании
- 50% от максимального балла выставляются за повторение авторского варианта приложения. Если в авторском варианте приложения обнаружатся баги, повторять их нет необходимости 
- вторые 50% от максимального балла выставляются за реализацию студентом дополнительного функционала