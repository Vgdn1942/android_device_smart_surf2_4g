## [ROM][UNOFFICIAL][7.1.1] LineageOS 14 for MTC Smart Surf2 4G
(c) **Decker**, [http://www.decker.su](http://www.decker.su)

![LineageOS / Decker.SU](https://3.bp.blogspot.com/-beayt9o83QA/WKoDpc1PFoI/AAAAAAAAL-U/8NskvXvUNtI6ONDwmmB8jCojRD_XqGn6wCLcB/s1600/lineage_os_decker_su_478x269.jpg  "LineageOS / Decker.SU")

На данный момент в прошивке работает:

- RIL (связь) на первой и второй SIM-карте.
- Передача данных через мобильную сеть.
- WiFi (устанавливается связь с точкой доступа, работает передача данных)
- GPS (полномасштабный тест не проводился, но в GPS Test'е, а также YGPS, который теперь встроен в прошивку местоположение определятся).
- Камера (основная и фронтальная камеры работают, в том числе работает и ***съемка видео***).
- Аппаратные OMX кодеки (!), кодирование / декодирование видео осуществляется аппаратными кодеками.
- Светодиод вспышки.
- Звук
- Live Display
- Запись экрана (screen recording)
- Запись с микрофона (sound recording)
- Bluetooth (проверялась только передача / прием файлов между двумя аппаратами, работа с другими профилями, например, гарнитурой и т.п. не тестировалась)
- WiFi AP (создание точки доступа WiFi)
- Запись разговора с линии штатными средствами ОС
- Вибрация аппаратных клавиш BACK, HOME, MENU.

Если что-то не работает - создавайте соответствующий Issue.

###История изменений:

- Добавлены необходимые разрешения в приложение Камера (Snap), теперь помимо HD 720p, HD 1080p доступны также другие разрешения поддерживаемые смартфоном.
- Исправлена работа фронтальной камеры. Теперь запись с нее ведется в поддерживаемых сенсором разрешениях, никаких артефактов на видео записанном с фронтальной камеры нет.
- Исправлено декодирование видео аппаратным [VP9 кодеком](https://xakep.ru/2015/04/07/vp9-youtube/)  в приложении Youtube. Как известно, Yotube с некоторого времени стал выдавать видеопоток пожатый именно этим кодеком, для аппаратов которые его поддерживают. Теперь на данной прошивке подобные видео смотрятся без проблем (кстати, для справки, во встроенном приложении YouTube на стоке поток отдается не в VP9)

Заметки к сборке лежат в **NOTES.md** ... если вы хотите собрать на основе этого дерева прошивку для своего девайса, настоятельно рекомендуется их прочитать.

###Поддержка проекта:

http://donate.decker.su/ 

