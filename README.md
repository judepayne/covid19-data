
### Automated reconciliations of the different covid19 outbreak data sources.

Many people use Johns Hopkins data as a source for analytics. These reconciliations compare that dataset against wikipedia (community maintained) and worldometer (private).

These reconciliations are done at *country level only* at the moment.

Please note that in these reports:

`'jhu'`    = Johns Hopkins github [repository](https://github.com/CSSEGISandData/COVID-19)

`'wikipedia'` = the main Wikipedia coronavirus [webpage](https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic)

`'worldometer'` = the worldometer coronavirus [webpage](https://www.worldometers.info/coronavirus/)
<br/><br/>
> This reconciliation is run every two hours.
<br/><br/>
The full report is put into the reports/ folder as json.

A summary report which filters out countries that don't differ significantly is additionally posted as an [issue](https://github.com/judepayne/covid19-data/issues) at the same time.
