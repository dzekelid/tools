{
  "info": {
    "name": "Zerigo Get the current public IPv4",
    "_postman_id": "e448ace2-fd41-4a0b-95f5-e535ba100d70",
    "description": "If you&#8217;re doing development or production behind NAT devices, it may be helpful to retrieve your current public IPv4 address.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tools",
      "item": [
        {
          "id": "799f55d7-ce67-4d9e-9b9b-2fe85adb3ae8",
          "name": "get-the-current-public-ipv4",
          "request": {
            "url": "http://example.com/api/api/1.1/tools/public_ipv4.xml",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "If you&#8217;re doing development or production behind NAT devices, it may be helpful to retrieve your current public IPv4 address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "255b61f1-3f56-4bd6-b2f1-19b6847292a8"
            }
          ]
        }
      ]
    }
  ]
}