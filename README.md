# Кастомный mailer для WordPress

Мэйлер отправляет письма на почту с фложениями.
Проверка на бота reCaptcha V2

## Структура файлов в WordPress

<pre>
`[wp-content]
 |--[themes]
    |--[yourtheme]
        |--[functions]
            |--enqueue.php
        |--[mailer]
        |--[partials]
           |--partial-form.php
         index.php
         functions.php`
</pre>
index.php - <br>`<?php get_template_part( 'partials/partial-form'); ?>` <br><br>
functions.php - <br>`require get_template_directory() . '/functions/enqueue.php';` <br><br>