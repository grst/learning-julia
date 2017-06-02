all: R python julia

%.html: %.ipynb
	jupyter nbconvert --ExecutePreprocessor.timeout=None --execute --to html $<

R: task1.R.html

python: task1.py.html

julia: task1.py.html
