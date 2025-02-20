<img src="./banner.png">
<h1 align="center">PixelGAN</h1>
<div align="center">
  <a href="https://github.com/K1rsN7/BusinessLunchGAN/issues">
		<img src="https://img.shields.io/github/issues/K1rsN7/BusinessLunchGAN?color=4A73DF&labelColor=1C2325&style=for-the-badge">
	</a>
	<a href="https://github.com/K1rsN7/BusinessLunchGAN/stargazers">
		<img src="https://img.shields.io/github/stars/K1rsN7/BusinessLunchGAN?color=4A73DF&labelColor=1C2325&style=for-the-badge">
	</a>
	<a href="./LICENSE">
		<img src="https://img.shields.io/badge/Licence-CC%20BY--NC%204.0-4A73DF?style=for-the-badge&labelColor=1C2325" alt="Лицензия CC BY-NC 4.0">
	</a>
</div>

<p>Инструмент разработанный для улучшения качества фото и видео. В нем используется алгоритм генеративно-состязательной сети.</p>

<h2 align="center">Установка и использование</h2>
<p>Для начала требуется установить PyTorch с официального сайта.</p>
<pre><code>Устанавливаем зависимости <code>pip install -r requirements.txt</code></code></pre>

<p>Откройте (или создайте, если его нет) файл <code>.env</code> и запишите туда <code>INPUT_PATH=your_path_to_file</code>, где <code>your_path_to_file</code> это путь до вашего файла. Для удобства вы можете располагать файлы в дирректории <code>General/input</code>. Если папки <code>input</code> не существует, вы можете ее создать.</p>

<p>Так-же в этом файле создайте еще одну переменную <code>COLLECTION_OF_MANY_FILES=False</code>. Если значение установлено <code>False</code>, то обрабатываться будет только один файл, указанный в <code>INPUT_PATH</code>. Если же установлено значение <code>True</code>, то вместо пути до файла в переменной <code>INPUT_PATH</code> вам нужно указать путь до папки, в которой лежит множество фото/видео.</p>

<p><strong>ВАЖНО:</strong> файлы принимаются только с расширениями (jpg, jpeg, png, mp4, avi, mov)</p>

<p>После всех действий выше вы можете запускать файл <code>app.py</code>. Результаты выполнения вы обнаружите в папке <code>General/results</code>. Если вы обрабатывали видео, в этой папке появятся отдельные кадры видео, а в самом конце файл видео с вашим названием и расширением.</p>

<h2 align="center">Уникальность нашего проекта</h2>
<p>Уникальность продукта обеспечивается использованием объектно-ориентированного программирования (ООП), которое позволяет структурировать код в виде взаимодействующих объектов, повышая его модульность, гибкость и упрощая разработку, тестирование и сопровождение.</p>

<p>Важным фактором является применение Генеративно-состязательной сети (GAN) в качестве алгоритма. GAN способна эффективно обучаться на больших объемах данных и улучшать результаты с каждой новой итерацией обучения, обеспечивая высокую точность и качество генерации изображений.</p>

<p>Наш продукт обладает мультифункциональностью, предоставляя возможность обработки как отдельных изображений/видео, так и целых папок.</p>

<h2 align="center">Задачи на будущее</h2>
<ol align="center">
    <li>Подбор весов моделей для более качественной обработки видео</li>
    <li>Построение более легковесной архитектуры</li>
    <li>Добавление генеративной модели для улучшения лиц на видео</li>
    <li>Ускорение работы алгоритма</li>
    <li><strong>Непрерывное совершенствование:</strong> Постоянно обновлять и совершенствовать модель искусственного интеллекта, периодически обновляя ее новыми данными и учитывая отзывы пользователей. Быть в курсе последних исследований в области методов улучшения качества видео, чтобы внедрять любые новые подходы или достижения.</li>
</ol>

<h2 align="center">Результат работы алгоритма</h2>
<p><strong>До обработки | После обработки</strong></p>
<div align='center'>
    <img height="250px" src="original image.png" alt="До обработки" />
    <a></a>
    <img height="250px" src="processed image.png" alt="После обработки" />
</div>

<h2 align="center">Итоги Хакатона</h2>
<div align='center'>
    <img src="https://github.com/DIMFLIX-HACKATONS/PixelGAN/blob/55581e863a63e96100c9a8a3c3a4a19c47e0b00f/%D1%81%D0%B5%D1%80%D1%82%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%82.png" alt="" />
</div>
<h2 align="center"> Star History</h2>
<div align="center">
<a href="https://star-history.com/#K1rsN7/BusinessLunchGAN&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=K1rsN7/BusinessLunchGAN&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=K1rsN7/BusinessLunchGAN&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=K1rsN7/SubManage&type=Date" />
 </picture>
</a>
</div>
