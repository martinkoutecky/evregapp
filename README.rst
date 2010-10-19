========
evregapp
========

Currently in a planning/design phase. What do we want it to do? And what is out
of the scope of this project?

Features
========

+	Form designer (be able to create forms without coding).

	+	Maybe reuse some widget library, like `ToscaWidgets
	<http://toscawidgets.org/>`_?
+	Form reuse (be able to clone existing forms and edit them).
+	Get user information from an existing database (e.g. a website CMS
	database). Probably use `SQLAlchemy <http://www.sqlalchemy.org/>`_?
+	Participant list generation (xls, pdf, ...)
+	Generate bank transfer information and verify that the transfer occured;
	this obviously has to be a plugin to allow the use of various banks etc.
	
Design
======

We need to agree on the features first, but after that we'll probably have to
pick a framework (`Pylons <http://pylonshq.com/>`_? Or something else?) and
maybe something else.


