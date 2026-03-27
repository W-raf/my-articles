
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<title>Eisenhower Matrix for Obsidian</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
    margin: 0;
    background: #0a0f14;
    font-family: "Inter", sans-serif;
    color: #e6f7ff;
    line-height: 1.6;
}

.container {
    max-width: 900px;
    margin: 40px auto;
    padding: 32px;
    background: #0d141c;
    border-radius: 16px;
    border: 1px solid rgba(0,255,255,0.15);
    box-shadow: 0 0 25px rgba(0,255,255,0.1);
}

h1 {
    font-size: 2.6rem;
    color: #00eaff;
    text-shadow: 0 0 12px #00eaff;
}

h2 {
    color: #00eaff;
    border-left: 4px solid #00eaff;
    padding-left: 10px;
    margin-top: 40px;
}

.neon-box {
    background: rgba(0,255,255,0.05);
    border: 1px solid rgba(0,255,255,0.2);
    padding: 16px;
    border-radius: 12px;
    margin: 20px 0;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin: 16px 0;
}

table th, table td {
    border: 1px solid rgba(0,255,255,0.2);
    padding: 10px;
}

table th {
    background: rgba(0,255,255,0.1);
    color: #00eaff;
}

code {
    background: rgba(0,255,255,0.1);
    padding: 4px 6px;
    border-radius: 6px;
    color: #7deaff;
}

pre {
    background: rgba(0,255,255,0.05);
    border: 1px solid rgba(0,255,255,0.15);
    padding: 16px;
    border-radius: 12px;
    overflow-x: auto;
}
</style>
</head>

<body>
<div class="container">

<h1>🎛️ Eisenhower Matrix for Obsidian</h1>
<p>Интерактивная матрица Эйзенхауэра с Dataview + TRON‑стилизацией</p>

<div class="neon-box">
Этот проект добавляет в Obsidian динамическую матрицу Эйзенхауэра, которая автоматически собирает задачи из всех заметок, сортирует их по важности/срочности и отображает в виде аккуратных цветных блоков с анимацией.
</div>

<h2>📌 Возможности</h2>
<div class="neon-box">
<ul>
<li>Автоматический сбор задач из всех заметок</li>
<li>Приоритизация по тегам <code>#raf_i</code> — <code>#raf_vi</code></li>
<li>4 квадранта матрицы Эйзенхауэра</li>
<li>Подсветка просроченных задач</li>
<li>Отдельный блок выполненных задач</li>
<li>TRON‑стиль: неон, тёмная тема, анимации</li>
</ul>
</div>

<h2>🧭 Теги приоритизации</h2>

<table>
<tr><th>Тег</th><th>Значение</th><th>Действие</th></tr>
<tr><td>#raf_i</td><td>Срочно и важно</td><td>Делать сейчас</td></tr>
<tr><td>#raf_ii</td><td>Несрочно, но важно</td><td>Планировать</td></tr>
<tr><td>#raf_iii</td><td>Срочно, но не важно</td><td>Делегировать</td></tr>
<tr><td>#raf_vi</td><td>Несрочно и не важно</td><td>Минимизировать</td></tr>
</table>

<h2>📝 Пример использования</h2>

<pre><code>- [ ] #raf_i Подписать договор
- [ ] #raf_vi Купить вариатор, если будет время
</code></pre>

</div>
</body>
</html>
