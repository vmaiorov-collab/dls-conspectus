# Конспекты курса Deep Learning School

Подробные автономные конспекты видео курса **Deep Learning School** ([плейлист на YouTube](https://www.youtube.com/playlist?list=PL0Ks75aof3Tiru-UvOvYmXzD1tU0NrR8V), 62 видео). Каждый конспект — один HTML-файл с формулами, кодом, схемами и таймкодами, ведущими в нужный момент видео. Читается офлайн.

## Сайт

**[vmaiorov-collab.github.io/dls-conspectus](https://vmaiorov-collab.github.io/dls-conspectus/)** — список всех видео по темам. Видео без конспекта помечены «скоро».

## Структура

- `index.html` — начальная страница; список видео лежит в массиве `DATA` (у готового конспекта есть поле `href`).
- `lessons/NN-слаг.html` — конспекты, где `NN` — номер видео в плейлисте.
- `assets/site.css` — стили начальной страницы.
- `scripts/paper-style.py` — приводит конспект к единому оформлению, добавляет пейджер и обновляет поиск по разделам на главной:
  `python3 scripts/paper-style.py lessons/<файл>.html`
