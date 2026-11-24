# Circuit-carft.2.1{
  "id": "ellt2302",
  "name": "First car build",
  "updatedAt": 1795363215459,
  "parts": [
    {
      "id": "1i6ilo75",
      "type": "battery",
      "name": "DC Battery",
      "x": 3,
      "z": -2,
      "rotation": 0,
      "value": 9,
      "enabled": true,
      "nodeA": "qq7jxfz3",
      "nodeB": "o9e2cbcr"
    },
    {
      "id": "kizygjhl",
      "type": "led",
      "name": "LED",
      "x": -3,
      "z": 0,
      "rotation": 0,
      "value": 220,
      "enabled": true,
      "nodeA": "lm9ebpcr",
      "nodeB": "4iad4ugd"
    },
    {
      "id": "at84sj6x",
      "type": "motor",
      "name": "DC Motor",
      "x": 0,
      "z": -1,
      "rotation": 0,
      "value": 12,
      "enabled": true,
      "nodeA": "bcitzf75",
      "nodeB": "9jbvu7o8"
    }
  ],
  "wires": [
    {
      "id": "23zeheag",
      "from": {
        "componentId": "at84sj6x",
        "port": "b"
      },
      "to": {
        "componentId": "kizygjhl",
        "port": "a"
      }
    }
  ]
}
