# Bullet journal
* [BuJo](BuJo.tex) - original [Bullet Journal](https://www.youtube.com/watch?v=fm15cmYU0IM)

* [Bujo-Addons](Bujo-Addons.tex) - implement ideas such as:
	* [x] [Habit tracker](https://bulletjournal.com/blogs/bulletjournalist/intentional-habit-tracking)
	* [x] [Financial tracker](https://bulletjournal.com/blogs/bulletjournalist/finance-log-round-up)
	* [x] [Mental Health](https://bulletjournal.com/blogs/bulletjournalist/5-ways-to-bullet-journal-to-benefit-your-mental-health)
	* [ ] And whatever you want! Anyone can edit, send issue or pull request
	
# Prerequisites
LaTeX installed, and a LaTeX Editor, e.g. Vim, emacs

LaTeX packages used:
* ulem for Strikethrough text

OPTIONAL: i use latexmk to convert to PDF:

latexmk -pdf -f -g -bibtex -deps -synctex=1 -interaction=nonstopmode -output-directory=BuJo.pdf 'BuJo.tex'

## License

This project is licensed under the GNU FDL License - see the [LICENSE.md](LICENSE.md) file for details
