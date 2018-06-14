# PyLadies Meetup @ Metis June 13, 2018

## Set up
```
git clone git@github.com:parsing-science/metis_june_2018.git
cd metis_june_2018
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Present slides
```
jupyter nbconvert --SlidesExporter.reveal_scroll=True --template slides_reveal.tpl --to slides Talk.ipynb --post serve
```
