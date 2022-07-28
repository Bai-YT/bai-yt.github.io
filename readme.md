The jemdoc.css file should be stored in the same location as the html files to maintain proper formatting.

To generate an html file from a jemdoc file, for example, home.jemdoc, run python on the following:

jemdoc -c mysite.conf home.jemdoc

To generate an html file from a local file index.jemdoc and save the result in a folder called html, run python on the following:

jemdoc -c mysite.conf -o html/ index

To generate an html file from a local file index.jemdoc and save the result in the folder up, run python on the following:

jemdoc -c mysite.conf -o ../ index