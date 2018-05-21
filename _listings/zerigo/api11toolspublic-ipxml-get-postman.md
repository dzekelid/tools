{
  "info": {
    "name": "Zerigo Get the current public IP",
    "_postman_id": "14163321-29a0-4a17-8889-4f353451fdf0",
    "description": "If you&#8217;re doing development or production behind NAT devices, it may be helpful to retrieve your current public IPv4/IPv6 address.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tools",
      "item": [
        {
          "id": "d77e11f7-81e9-430d-a4e1-1d188a077fd6",
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
              "id": "eb4b1b50-9e86-43e4-85c4-f2c3a5062771"
            }
          ]
        },
        {
          "id": "56cb9633-51d6-4534-b049-18d07b5342c9",
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
              "id": "c740d738-6574-43b7-9329-22989c4c9ad2"
            }
          ]
        },
        {
          "id": "d7cf3720-ede5-40c0-8f0b-1a3a6db75f04",
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
              "id": "b9c551ef-b3c7-47b0-8b9d-273a6d0fdb0e"
            }
          ]
        }
      ]
    }
  ]
}