<h3>Основные функции</h3>
<p>В папке src (потом в папке main/java/org/example) в файле main.java находятся функции _min, _max, _sum, _mult, которые ищут минимум, максимум, сумму и произведение чисел во входном файле (числа должны быть введены через пробел) 
<br/>На вход нужно ввести путь до файла с числами, чтобы протестировать работу программы</p>
<h3>Тесты</h3>
<ol>
<li>Также есть тесты, которые проверяют работу программы, тесты находятся в папке scr (потом test/java) в файле tests.java, первые 2 теста (Base_tests_1 и Base_tests_2) проверяют корректность работы функций</li>
<li>Следующие 2 теста (Time_test_1 и Time_test_2) проверяют скорость работы функций (они должны работать не больше, чем за 100 милисекунд)</li>
<li>Последний тест (Memory_test) проверяет память, которая используется при запуске программы (не должна превышать 5000 Мб)</li>
</ol>
<h3>График</h3>
<p>Также в репозитории лежит файл png с зависимостью времени работы программы от количества цифр в файле в млн</p>
<h3>Github Actions</h3>
<p>В репозитории есть файл pom.xml и main.yml, благодаря которым при каждом коммите запускается автоматическое тестирование программы, также можно вручную запустить тесты через Github Actions</p>
<h3>Telegram</h3>
При запуске тестов в Github Actions отправляется уведомление в группу Telegram https://https://t.me/+Pl-ELFieGb83MjRi
