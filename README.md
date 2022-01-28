# Bullet journal
* [BuJo](BuJo.tex) - original [Bullet Journal](https://www.youtube.com/watch?v=fm15cmYU0IM)
* [Bujo-Addons](Bujo-Addons.tex) - implement ideas such as:
	* [Habit tracker](https://bulletjournal.com/blogs/bulletjournalist/intentional-habit-tracking)
	* [Financial tracker](https://bulletjournal.com/blogs/bulletjournalist/finance-log-round-up)
	* [Mental Health](https://bulletjournal.com/blogs/bulletjournalist/5-ways-to-bullet-journal-to-benefit-your-mental-health)

i use latexmk to convert to PDF:

latexmk -pdf -f -g -bibtex -deps -synctex=1 -interaction=nonstopmode -output-directory=BuJo.pdf 'BuJo.tex'
