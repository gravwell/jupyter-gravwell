# Gravwell in Jupyter notebooks

To query a Gravwell system in your Jupyter notebooks, copy `gravwell-lib.ipynb` to the same directory as your notebook, then add the following cell to the top of your notebook:

	%run gravwell-lib.ipynb

By default, requests will be sent to a demo Gravwell server. To use your own server, change the `GravwellToken` and `GravwellServer` variables in `gravwell-lib.ipynb`.

Check out `example.ipynb` for examples of how you might use the library. The `query` function returns a [pandas](https://pandas.pydata.org/) `DataFrame` object, which can be used in a variety of ways (displayed as tables, charted, etc.)
