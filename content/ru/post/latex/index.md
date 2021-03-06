---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Латекс"
subtitle: ""
summary: "Пост про Латекс"
authors: []
tags: []
categories: []
date: 2022-06-24T19:12:50+03:00
lastmod: 2022-06-24T19:12:50+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

![Latex_logo](latex.png)

## Обзор

LaTeX (/ˈlɑːtɛx/ LAH-tekh или /ˈleɪtɛx/ LAY-tekh) представляет собой программную систему для подготовки документов. При написании писатель использует обычный текст, а не форматированный текст, найденный в слове «What You See Is What You Get». такие процессоры, как Microsoft Word, LibreOffice Writer и Apple Pages.Писатель использует соглашения о тегах разметки, чтобы определить общую структуру документа, стилизовать текст по всему документу (например, выделить его полужирным шрифтом и курсивом), а также добавить цитаты и перекрестные ссылки. Распространение, такое как TeX Live или MiKTeX, используется для создания выходного файла (например, PDF или DVI), пригодного для печати или цифрового распространения.

LaTeX широко используется в научных кругах для обмена и публикации научных документов во многих областях, включая математику, информатику, инженерию, физику, химию, экономику, лингвистику, количественную психологию, философию и политологию. Он также играет заметную роль в подготовке и публикации книг и статей, содержащих сложные многоязычные материалы, такие как санскрит и греческий. LaTeX использует программу набора текста TeX для форматирования своего вывода и сам написан на языке макросов TeX.

## История

LaTeX был создан в начале 1980-х Лесли Лэмпортом, когда он работал в SRI. Ему нужно было написать макросы TeX для собственного использования, и он подумал, что, приложив немного дополнительных усилий, он сможет сделать общий пакет пригодным для использования другими. Питер Гордон, редактор Addison-Wesley, убедил его написать руководство пользователя LaTeX для публикации (Лэмпорт изначально скептически относился к тому, что кто-то будет платить за это деньги); он вышел в 1986 году и был продан сотнями тысяч копий. Тем временем Лэмпорт выпустил версии своих макросов LaTeX в 1984 и 1985 годах. 21 августа 1989 года на собрании группы пользователей TeX (TUG) в Стэнфорде Лэмпорт согласился передать обслуживание и разработку LaTeX Фрэнку Миттельбаху. Миттельбах вместе с Крисом Роули и Райнером Шопфом сформировал команду LaTeX3; в 1994 году они выпустили LaTeX2e, текущую стандартную версию. С тех пор сам LaTeX3 был отменен, а функции версии, предназначенные для этой версии, были перенесены в LaTeX 2e с 2018 года.

## Связанное программное обеспечение

В качестве пакета макросов LaTeX предоставляет набор макросов для интерпретации TeX. Существует много других пакетов макросов для TeX, включая Plain TeX, GNU Texinfo, AMSTeX и ConTeXt.

Когда TeX «компилирует» документ, он следует (с точки зрения пользователя) следующей последовательности обработки: Макросы → TeX → Драйвер → Вывод. Различные реализации каждого из этих шагов обычно доступны в дистрибутивах TeX. Традиционный TeX выводит файл DVI, который обычно преобразуется в файл PostScript. Совсем недавно Hàn Thế Thành и другие написали новую реализацию TeX под названием pdfTeX, которая также выводит в PDF и использует функции, доступные в этом формате. Механизм XeTeX, разработанный Джонатаном Кью, с другой стороны, объединяет современные технологии шрифтов и Unicode с TeX.

Шрифтом по умолчанию для LaTeX является Knuth's Computer Modern, который придает документам по умолчанию, созданным с помощью LaTeX, такой же отличительный вид, как и созданным с помощью простого TeX. XeTeX позволяет использовать шрифты OpenType и TrueType (то есть контурные) для выходных файлов.

Существует также множество редакторов для LaTeX, некоторые из которых являются автономными, основанными на исходном коде, а другие — онлайновыми, частично основанными на WYSIWYG. Подробнее см. в разделе Сравнение редакторов TeX.