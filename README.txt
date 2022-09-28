endpoints:
  POST - https://zf6zo9puz6.execute-api.us-east-2.amazonaws.com/dev/setDataDynamoApi/{Id}
  GET - https://zf6zo9puz6.execute-api.us-east-2.amazonaws.com/dev/getStarwarsApi
  GET - https://zf6zo9puz6.execute-api.us-east-2.amazonaws.com/dev/getStarwarsApi/{id}
  GET - https://zf6zo9puz6.execute-api.us-east-2.amazonaws.com/dev/getDynamoApi
  GET - https://zf6zo9puz6.execute-api.us-east-2.amazonaws.com/dev/getDynamoApi/{Id}
functions:
  setDataDynamoApi: renatogamonal-dev-setDataDynamoApi
  getStarwarsApi: renatogamonal-dev-getStarwarsApi
  getDynamoApi: renatogamonal-dev-getDynamoApi