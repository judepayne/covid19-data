
### Automated reconciliations of the different covid19 outbreak data sources.

The Johns Hopkins covid19 outbreak data is broadly used for analytics.

The reconciliations here compare that dataset against wikipedia (community maintained) and worldometer (private) at *country level only* at the moment.

Please note that in these reports:

`'jhu'`    = Johns Hopkins github [repository](https://github.com/CSSEGISandData/COVID-19)

`'wikipedia'` = the main Wikipedia coronavirus [webpage](https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic)

`'worldometer'` = the worldometer coronavirus [webpage](https://www.worldometers.info/coronavirus/)
<br/><br/>
> This reconciliation is run every four hours.

> An additional daily reconciliation is run at 00:20 UTC (Just after the jhu daily run completes).
<br/>

The full reconciliation report is put into the reports/ folder as json.

Human readable summaries of the 4-hourly run and daily run are posted as [issues](https://github.com/judepayne/covid19-data/issues) as the full reports are generated.

