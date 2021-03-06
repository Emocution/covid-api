# covid-api
APIs to track COVID-19 cases globally

# Source
Data regulary extracted from https://github.com/CSSEGISandData/COVID-19

# API
## All countries

GET: https://xpowery.github.io/covid-api/v1/timeseries.json

## Format

```json
{
  "version": "0.1",
  "description": "COVID-19 report from CSSEGISandData",
  "data": {
    "mainland-china": {
      "2020-04-12": {
        "anhui": [
          0,
          0,
          0
        ],
        "beijing": [
          0,
          0,
          0
        ]
      }
    },
    "japan": {
      "2020-04-12": {
        "all": [
          0,
          0,
          0
        ],
      }
    }
  }
}

```

## Specific country

GET: https://xpowery.github.io/covid-api/v1/timeseries-[country-name].json

## Example

GET: https://xpowery.github.io/covid-api/v1/timeseries-india.json

```json
{
  "version": "0.1",
  "description": "COVID-19 report from CSSEGISandData",
  "data": {
    "2020-02-08": {
      "all": [
        3,
        0,
        0
      ]
    },
    "2020-03-13": {
      "all": [
        82,
        4,
        2
      ]
    },
    "2020-05-07": {
      "all": [
        52987,
        15331,
        1785
      ]
    }
  }
}

```

## US Stats[CLEAN DATA]
GET: https://xpowery.github.io/covid-api/v1/timeseries-usa.json

## Format

```json
{
  "version": "0.1",
  "description": "COVID-19 report from CSSEGISandData",
  "data": {
    "2020-04-12": {
      "alabama": [
        3563,
        0,
        93
      ],
      "alaska": [
        272,
        66,
        8
      ]
    }
  }
}

```

## Other Stats
https://xpowery.github.io/covid-api/v1/timeseries.json

# Format


# Explanation
```json
"STATE_NAME": [
  "CONFIRMED_CASES",
  "RECOVERED_CASES",
  "DEATH_CASES"
]
```

# Terms
Check terms here https://github.com/CSSEGISandData/COVID-19
