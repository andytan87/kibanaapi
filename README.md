# kibanaapi

``` bash
curl -X PUT http://Allegro_Kibana_API:testing@192.168.1.40:5601/api/saved_objects/search/88d17440-412c-11f0-abee-6d217f4ebfe6 \
  -H "Content-Type: application/json" \
  -H "kbn-xsrf: true" \
  -d '{
    "attributes": {
      "title": "test",
      "kibanaSavedObjectMeta": {
        "searchSourceJSON": "{\"index\":\"816afcd0-6e9c-11ee-bab2-8b3443d1bd64\",\"query\":{\"query\":\"status:404\",\"language\":\"kuery\"},\"filter\":[]}"
      }
    }
  }'
```
