# school-choice
Data analysis for education's school choice in Indiana project

Assumptions
-----------

The following things are assumed to be true in this documentation.

* You are running OSX.
* You are using Python 2.7. (Probably the version that came OSX.)
* You have [virtualenv](https://pypi.python.org/pypi/virtualenv) and [virtualenvwrapper](https://pypi.python.org/pypi/virtualenvwrapper) installed and working.
* You have NPR's AWS credentials stored as environment variables locally.

For more details on the technology stack used with the app-template, see our [development environment blog post](http://blog.apps.npr.org/2013/06/06/how-to-setup-a-developers-environment.html).


Bootstrap the project
---------------------

```
cd school-choice
mkvirtualenv school-choice
pip install -r requirements.txt
```

**Problems installing requirements?** You may need to run the pip command as ``ARCHFLAGS=-Wno-error=unused-command-line-argument-hard-error-in-future pip install -r requirements.txt`` to work around an issue with OSX.

Run the notebook
---------------

`
jupyter notebook
`

The homepage of the notebook should open automatically in your preferred browser. Notebooks generally run on `localhost:8888` if it is the sole notebook running.


Data sources
---------------

Choice Scholarship program annual report: [2014](http://indianapublicmedia.org/stateimpact/files/2014/01/Choice-Scholarship-Program-Annual-Report-012714.pdf), [2016](http://www.doe.in.gov/sites/default/files/news/2015-2016-choice-scholarship-program-report-final-april2016.pdf), [2017](http://www.doe.in.gov/sites/default/files/choice/2016-2017-choice-scholarship-program-report-feb24-final.pdf)