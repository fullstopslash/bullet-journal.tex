# Bullet journal
* [BuJo](BuJo.tex) - original [Bullet Journal](https://www.youtube.com/watch?v=fm15cmYU0IM)
* [Bujo-Addons](Bujo-Addons.tex) - User Created Plugins
* [Bujo-Addons-Legacy](Bujo-Addons-Legacy.tex) - As above but without extra depencies
	* Trackers:
		* [x] [Habit tracker](https://bulletjournal.com/blogs/bulletjournalist/intentional-habit-tracking)
		* [x] [Financial tracker](https://bulletjournal.com/blogs/bulletjournalist/finance-log-round-up)
		* [x] [Mood tracker](https://bulletjournal.com/blogs/bulletjournalist/5-ways-to-bullet-journal-to-benefit-your-mental-health)
		* [ ] Goal tracker
		* [X] Meal traker
		* [ ] TV show tracker
		* [ ] Chore chart
	* [ ] Title page
	* [ ] Books to read
	* [ ] Wish board
	* [ ] Quotes
	* [ ] Birthday list
	* [ ] Month Review
	* [ ] Daily/Weekly spread
	* [ ] Specialty planning
	* Other:
		* [ ] What have you learned?
		* [ ] Things to buy
		* [ ] Gratitute
	
# Prerequisites
##Original

LaTeX installed, and a LaTeX Editor, e.g. Vim, emacs

LaTeX packages used:
* ulem for Strikethrough text

Same for BuJo-Addond-Legacy

##BuJo-Addons

LateX packages used:
* Multirow - Merge Cells
* csvsimple - Finance

#PDF
latexmk -pdf -f -g -bibtex -deps -synctex=1 -interaction=nonstopmode -output-directory=BuJo.pdf 'BuJo.tex'

## License

This project is licensed under the GNU FDL License - see the [LICENSE.md](LICENSE.md) file for details
