# Проект представляет собой внутреннюю биллинг систему, написанную на PHP. Разработка велась и ведется собсвтенными силами, поэтому проект является в некотором роде уникальным. 
# Модульные тесты имеют автоматизацию на уровне взаимодействия с БД: проверка целостность и непротиворечивость данных и т.п. Работоспособность самых используемых внутренних апи.
# Интеграционное тестирование не выполняется.
# UI тесты выполняются в процессе разработки новых фич, илбо исправления найденых багов. Тестирование ручное. Регрессионное тестирование отсутствует.
# Основным недостатком текущей ситуации являются:
# - отсутствие четкой формализации и ТЗ при постановке задач для разработки;
# - длительный процесс тестирования более-менее сложного функционала;
# - значительное количество багов выявляемое в ходе тестирования и большое количество итераций тестирования при разрабтке сложных фич.
# - отсутствие регрессионного тестирования, ввиду невозможности его организации при мануальном тестировании небольшими силами;
# Из предложений:
# - реализовать атоматизацию UI, поскольку большая часть багов выявляется именно здесь;
# - организовать регрессионное тестирование хотя бы критических функций.

