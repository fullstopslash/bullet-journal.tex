THIS REPO IS ARCHIVED. If you really want move your analog buJo to digital, use emacs org mode.

# Bullet journal
* [BuJo](BuJo.tex) - original [Bullet Journal](https://www.youtube.com/watch?v=fm15cmYU0IM)
* [Bujo-Addons](Bujo-Addons.tex) - User Created Plugins
	* Trackers:
		* [X] Books to read
		* [X] What have you learned?
		* [X] [Mood tracker](https://bulletjournal.com/blogs/bulletjournalist/5-ways-to-bullet-journal-to-benefit-your-mental-health)
		* [X] [Habit tracker](https://bulletjournal.com/blogs/bulletjournalist/intentional-habit-tracking)
		* [X] [Financial tracker](https://bulletjournal.com/blogs/bulletjournalist/finance-log-round-up)
		* [X] Meal traker
		* [X] Chore chart
		* [X] TV show tracker
		* [ ] Goal tracker
	* Lists
		* [X] Quotes
		* [ ] Wish board
		* [ ] Things to buy
	* [X] Title page
	* [ ] Month Review
	* [ ] Daily/Weekly spread
	* [ ] Specialty planning
	* Other:
		* [ ] Gratitute
* [Bujo-Addons-Legacy](Bujo-Addons-Legacy.tex) - As above but without extra depencies
	
# Prerequisites
## Original

LaTeX installed, and a LaTeX Editor, e.g. Vim, emacs

LaTeX packages used:
* ulem for Strikethrough text

Same for BuJo-Addons-Legacy

## BuJo-Addons

* LateX packages used (based on debian packages):
	* texlive-pictures
		* csvsimple - Finance
	* texlive-latex-extra
		* tikz - dot grid bullet journal background
* Other
	* .ics - iCalendar format for... calendar view ;)
	* .csv - For tracking
	* .opml - For subscriptions
	* .vcf - For contacts
	* .html - For website bookmarks 

# PDF
latexmk -pdf -f -g -bibtex -deps -synctex=1 -interaction=nonstopmode -output-directory=BuJo.pdf 'BuJo.tex'

# TODO
* dot grid background paper

## License

This project is licensed under the GNU FDL License - see the [LICENSE.md](LICENSE.md) file for details
