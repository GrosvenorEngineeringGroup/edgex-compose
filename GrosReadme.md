# Links

`https://app.swaggerhub.com/apis-docs/EdgeXFoundry1/core-data/1.2.1`

# Device Random

`curl http://localhost:48080/api/v1/event/device/Random-Integer-Device/10`

# Bacnet discovery

`curl -X POST localhost:49980/api/v1/discovery`

# Add Bacnet device through API

`curl --request POST --url 'http://localhost:48081/api/v1/device' --header 'content-type: application/json' -d '@./AddDevice.json'`