# qb-contract

1. Документация https://sortlyapi.docs.apiary.io/#
2. Custom attributes https://app.sortly.com/manage-custom-attributes/node

Используемые запросы

#### PUT https://api.sortly.co/api/v1/items/${folderId}
Body

1/
{\"custom_attribute_values\": [ {\"custom_attribute_id\": 207377, \"value\": \"https://https://storage.yandexcloud.net/qb-receipts/2ead823fb06d92aaacca89c079bec1e3.pdf\"}, {\"custom_attribute_id\": 186587, \"value\": \"0\"}, {\"custom_attribute_id\": 236287, \"value\": \"0\"}, {\"custom_attribute_id\": 217019, \"value\": \"8330\"}]}

2/
{\"notes\": \"ПОДПИСАНО\"}

3/
{\"custom_attribute_values\": [{\"custom_attribute_id\": 239296, \"value\": 0},{\"custom_attribute_id\": 221743, \"value\": 2.35}]}

#### GET https://api.sortly.co/api/v1/items?per_page=1000&page=1&folder_id=${folderId}&include=custom_attributes

#### GET https://api.sortly.co/api/v1/items/${folderId}?include=custom_attributes
