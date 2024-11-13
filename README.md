# developers_best_practices

1. settings.py писать через pydantic_settings
https://docs.pydantic.dev/latest/concepts/pydantic_settings/#installation
2. requirements.txt заполнять вручную, а не через pip freeze, т.к. если нужно потом выпилить библиотеку, непонятно будет остались ли от нее зависимости, которые автоматом с ней устанавливались в дополнение.
3. Всегда, когда задачу можно решить итерацией (либо итерацией с использованием стека), следует делать выбор в пользу цикла for или while вместо рекурсии.
