<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<h3>Установка:</h3>
<ol>
	<li>Для подключения к бд - изменить .env и указать свою бд</li>
	<li>Для загрузки таблиц - с консоля зайти в репозиторий прописать php artisan migrate</li>
	<li>Для загрузки заполнений - с консоля зайти в репозиторий прописать php artisan db:seed</li>
	<li>Для сохранения картинок - с консоля зайти в репозиторий прописать php artisan storage:link</li>
	<li>Для активации - с консоля зайти в репозиторий прописать php artisan serve</li>
</ol>

<h3>Функционал</h3>

<h4>Модели</h4>
<ol>
	<li>Article(Статья)</li>
	<li>Category(Категория)</li>
	<li>Commet(Коментарий)</li>
	<li>User(Пользователь)</li>
	<li>Role(Роль пользователя)</li>
</ol>

<h4>Views</h4>
<ol>
	<li>article - index, show</li>	
	<li>ctegory - index, show</li>	
	<li>blogger - articles(index, create ,edit)</li>	
</ol>

<p>Не авторизованиый пользователь:</p>
<ul>
	<li>Просмотр главной страницы - страницы всех статей</li>
	<li>Просмотр определенной страницы</li>
</ul>
<p>Авторизованиый пользователь:</p>
<ul>
	<li>Может напсать статью указав навзвание, оипсание, определить категорию, добавить изображение </li>
	<li>Осавить коментрий на другие статьи</li>
	<li>Всесь фунцкионал не авторизованного пользователя</li>
</ul>

<h4>БД</h4>

<img src="http://joxi.ru/J2bKL0EhXj17KA.jpg">