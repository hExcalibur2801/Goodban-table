# goodban table
Таблица блокировки всякой ботвы для pf

<h1>Как применять</h1>

<h3>Создаём каталог где удобно:</h3><br>
<b>cd /tmp && mkdir tazik && cd tazik
<br><br>
<h3>Клонируем репозиторий:</h3><br>
git clone https://github.com/hExcalibur2801/goodban.git
<br><br>
<h3>Добавляем таблицу в pf(pf.conf):</h3><br>
table &ltgoodban&gt persist file "/tmp/tazik/goodban/bantable.txt"

<h3>Добавляем первым фильтрующим правилом:</h3><br>
block drop in quick from <goodban>
<br><br><br>
Enjoy!
