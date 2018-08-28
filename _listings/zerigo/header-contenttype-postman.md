{
  "info": {
    "name": "Zerigo Single page version",
    "_postman_id": "8f606f4f-f9a2-4e28-8c2e-093fb49f275f",
    "description": "Zerigo DNS supports a fairly standard REST API for full creation, modification, and deletion of domain (zone) and host records. It is easy and straightforward to work with.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tools",
      "item": [
        {
          "id": "428285c7-7edb-417a-80eb-b6d223417487",
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
              "id": "304ecad6-ea7b-49ad-b853-5437c4cc9024"
            }
          ]
        },
        {
          "id": "7dd40972-42a3-4b71-9407-8d4174646bab",
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
              "id": "deee5256-2d14-49ce-9de5-6d60c3645de4"
            }
          ]
        },
        {
          "id": "11ed20e4-8956-4e56-88c1-0d1ba7870b17",
          "name": "get-the-current-public-ip",
          "request": {
            "url": "http://example.com/api/api/1.1/tools/public_ip.xml",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "If you&#8217;re doing development or production behind NAT devices, it may be helpful to retrieve your current public IPv4/IPv6 address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b72b1d42-81e7-465d-a776-9f9761faa1ba"
            }
          ]
        }
      ]
    }
  ]
}