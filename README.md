# Bullet journal
* [BuJo](BuJo.tex) - original [Bullet Journal](https://www.youtube.com/watch?v=fm15cmYU0IM)
* [Bujo-Addons](Bujo-Addons.tex) - User Created Plugins
	* Trackers:
		* [X] Books to read
		* [X] What have you learned?
		* [x] [Mood tracker](https://bulletjournal.com/blogs/bulletjournalist/5-ways-to-bullet-journal-to-benefit-your-mental-health)
		* [x] [Habit tracker](https://bulletjournal.com/blogs/bulletjournalist/intentional-habit-tracking)
		* [x] [Financial tracker](https://bulletjournal.com/blogs/bulletjournalist/finance-log-round-up)
		* [X] Meal traker
		* [X] Chore chart
		* [ ] Goal tracker
		* [ ] TV show tracker
	* [ ] Title page
	* [ ] Wish board
	* [ ] Quotes
	* [ ] Month Review
	* [ ] Daily/Weekly spread
	* [ ] Specialty planning
	* Other:
		* [X] Birthday list
		* [ ] Things to buy
		* [ ] Gratitute
* [Bujo-Addons-Legacy](Bujo-Addons-Legacy.tex) - As above but without extra depencies
	
# Prerequisites
## Original

LaTeX installed, and a LaTeX Editor, e.g. Vim, emacs

LaTeX packages used:
* ulem for Strikethrough text

Same for BuJo-Addons-Legacy

## BuJo-Addons

LateX packages used (based on debian packages):
* texlive-pictures
	* csvsimple - Finance
* texlive-latex-extra
	* tikz - dot grid bullet journal background

In debian: apt install texlive-latex-extra texlive-pictures

# PDF
latexmk -pdf -f -g -bibtex -deps -synctex=1 -interaction=nonstopmode -output-directory=BuJo.pdf 'BuJo.tex'

# TODO
* dot grid background paper

## License

This project is licensed under the GNU FDL License - see the [LICENSE.md](LICENSE.md) file for details
