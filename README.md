# Madi Baimuratov

I review AI generated code and repository changes using reproducible checks. I document what was tested and what the evidence leaves unresolved.

This work follows METHOD. Project page on [Astana Hub](ССЫЛКА), contact via [Telegram @Madbai](https://t.me/Madbai).

For a review request, open an [issue in this repository](https://github.com/XtReL/XtReL/issues) with a public repository link and the change or claim you want checked. Please keep private code and credentials out of public issues.

## Example review

[Read the json-flatten report in English](https://github.com/user-attachments/files/33626715/json-flatten-review.pdf) and the [public discussion](https://github.com/simonw/json-flatten/pull/10#issuecomment-6249090234).

The review covers commit `78c2835bf3b7b7cf068fca04a6cf341347dfa2bc`. It includes a key collision that silently loses a value and an empty key that changes a dictionary into a scalar. It was an unsolicited review assisted by AI, without a commission or approval from the maintainer. Existing overlapping PRs are acknowledged in the report. Those PR implementations were not tested.

## По-русски

Проверяю код, созданный с помощью ИИ, и изменения в репозиториях воспроизводимыми проверками. В отчёте показываю, что проверено и какие вопросы остаются без подтверждения.

Работа ведётся по METHOD. Страница проекта на [Astana Hub](ССЫЛКА), связь в [Telegram @Madbai](https://t.me/Madbai).

Для запроса проверки откройте [обращение в этом репозитории](https://github.com/XtReL/XtReL/issues), укажите публичный репозиторий и изменение или утверждение, которое нужно проверить. Закрытый код и ключи доступа в публичное обращение не добавляйте.

В [отчёте по json-flatten](https://github.com/user-attachments/files/33626715/json-flatten-review.pdf) разобрана потеря значения при совпадении путей ключей и превращение словаря с пустым ключом в скаляр. Проверен коммит `78c2835bf3b7b7cf068fca04a6cf341347dfa2bc`. Проверка выполнена по моей инициативе с помощью ИИ, без заказа или одобрения автора. Пересечения с существующими PR отмечены, сами исправления из этих PR не проверялись.

Пилотная проверка Trust Core по METHOD 0.3.3 не подтвердила приёмку по записанным требованиям.

## Projects

[Trust Core](https://github.com/XtReL/trust-core) is an experimental signed evidence log. Its pilot review under METHOD 0.3.3 did not establish acceptance under the recorded requirements.

[DevSecOps Gatekeeper](https://github.com/XtReL/devsecops-gatekeeper) is an early secret scanning prototype. Its README records the limits and the cloud mode acceptance result.

Trust Core представляет собой экспериментальный журнал подписанных свидетельств. Пилотная проверка не подтвердила приёмку по записанным требованиям. DevSecOps Gatekeeper остаётся ранним прототипом сканера секретов, ограничения и результат приёмки облачного режима указаны в README.

## Writing

[dev.to](https://dev.to/xtrel)

