

ZPyODBCDA is a Zope Database Adapter based on Python's pyodbc moudle (http://pyodbc.sourceforge.net). It links the Zope server to ODBC data sources. It is distributed under the GPL licence.

The reason I wrote a new Zope ODBC Database Adapter and didn't simply use the existing "New ZODBC DA" on zope.org is that I felt the underlying Pywin32's ODBC module which the "New ZODBC DA" depended on was not stable enough, and occasionally crashed my Python programs.

The another mxODBCDA is a commercial product which is not free.

The ZPyODBCDA product is modified from the codes of Thierry MICHEL's GPL licensed ZPoPyDA product, which links Zope to PostgreSQL and seems to be very mature.

ZPyODBCDA requires Python 2.4 or higher.

If your Zope runs on the win32 platform, you probably don't need any other moudules, as I already included pyodbc's binary code (pyodbc.pyd) in the package folder; for other platform like Linux, you may first need to install the pyodbc moudule for your Python instance.

I hope this product can provide a more reliable free Zope/ODBC connec solution to you.

Have fun.

Henry Zhou

Jiangwen365 °® gmail µã com


