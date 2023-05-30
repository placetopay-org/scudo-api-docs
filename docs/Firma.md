---
stoplight-id: 6ccbf9a0d4ab5
---

# Firma

Para la creación de una firma en los encabezados HTTP se debe tener los siguientes datos:

**Llave Secreta:** Llave secreta proporcionada por Evertec Placetopay
**Seed:** Estampa de tiempo. 
**URL:** Url del hebhook

## Ejemplo de calculo en PHP

````php

$url = 'https://client-url/notification';
$seed = now()->timestamp; // 1648159035
$secretKey = 'thisIsAnExampleOfSecretKey';

$signature = hash_hmac('SHA256', $url . $seed, $secretKey)

````