{
  "info": {
    "name": "Zerigo Get the current public IPv6",
    "_postman_id": "8f2e55ac-bf46-4607-90fa-7affd4ebe6fa",
    "description": "If you&#8217;re doing development or production with IPv6, it may be helpful to check if IPv6 works for you.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tools",
      "item": [
        {
          "id": "511e20c3-4201-4d5a-9747-6a178f57c06d",
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
              "id": "d7f6c7ad-4e96-4e5f-9288-1bb858a6960f"
            }
          ]
        },
        {
          "id": "9d8a702a-8211-43a7-a631-cb358f8adb57",
          "name": "get-the-current-public-ipv6",
          "request": {
            "url": "http://example.com/api/api/1.1/tools/public_ipv6.xml",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "If you&#8217;re doing development or production with IPv6, it may be helpful to check if IPv6 works for you."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6735f010-7a03-40b1-8524-2d5468f92edf"
            }
          ]
        }
      ]
    }
  ]
}