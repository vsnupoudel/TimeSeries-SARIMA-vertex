# TimeSeries-SARIMA-vertex
```
{
  "targetColumn": "Close_Price",
  "timeSeriesIdentifierColumn": "Week_Number",
  "timeColumn": "Close_Time",
  "optimizationObjective": "minimize-rmse",
  "trainBudgetMilliNodeHours": "2000",
  "unavailableAtForecastColumns": [
    "Close_Price"
  ],
  "availableAtForecastColumns": [
    "Close_Time"
  ],
  "dataGranularity": {
    "unit": "minute",
    "quantity": "5"
  },
  "forecastHorizon": "30",
  "contextWindow": "120",
  "windowConfig": {
    "strideLength": "6"
  },
  "modelDisplayName": "bitcoin_02_05"
}
```
