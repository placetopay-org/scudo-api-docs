# Kount 


Datos de petición requeridos para una correcta ejecución de la regla 

```json
{
  ...
  "instrument": {
    "card": {
      "pan_hash": "D21B10C0ABF0E02D9C279D13878AFB8424D961E1",
      "expiration_date": "12/22",
      "bin": "530691",
      "last_4": "5293"
    },
    "kount" :{
        "session" : "abcdefg12345abababab123456789012"
    }
    ...
  }
  "ip_address" : "127.0.0.1"
}
```


## Documentación relacionada 

* [Device Data Collector](https://developer.kount.com/hc/en-us/articles/6731598562836-How-to-Integrate-the-Kount-Web-Client-for-Device-Data-Collection-into-Your-Website)
* [Como generar id de sesión para el device data collector](https://developer.kount.com/hc/en-us/articles/4411121644820-How-to-Create-a-Session-ID-for-the-Device-Data-Collector-DDC-)