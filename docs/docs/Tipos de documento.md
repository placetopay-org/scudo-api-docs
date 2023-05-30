# Tipos de documento

Al crear una sesión, si usa una de las estructuras `payer`, `buyer`, or `shipping`, debe usar el atributo document_type para enviar los siguientes códigos, según el país:


### Estados Unidos (PR)

Code| Type of Document | Validation Rule
---------|---------- |----------
 SSN | US Social Security Number  | `'/^\d{9}$/'`
 EIN | US Federal Tax ID | `'/^\d{9}$/'`


### Colombia (CO)

Code| Type of Document | Validation Rule
---------|---------- |----------
 CC | Cédula de ciudadanía  | `'/^[1-9][0-9]{3,9}$/'`
 CE | Cédula de extranjería | `'/^([a-zA-Z]{1,5})?[1-9][0-9]{3,7}$/'`
 TI | Tarjeta de identidad| `'/^[1-9][0-9]{4,11}$/'`
 NIT | Número de Identificación Tributaria| `/^[1-9]\d{6,9}$/'`
 RUT | Registro único tributario| `'/^[1-9]\d{6,9}$/'`
 
### Ecuador (EC)
Code| Type of Document| Validation Rule
---------|----------|---------
 CI | Cédula de identidad|`'/^\d{10}$/'`
 RUC | Registro Único de Contribuyentes|`'/^\d{13}$/'`
 

### Costa Rica (CR)

Code| Type of Document| Validation Rule
---------|----------|------------
 CRCPF | Cédula personal física |`'/^[1-9][0-9]{8}$/'`
 CPJ | Cédula personal juridica |`'/^[1-9][0-9]{9}$/'`
 DIMEX | DIMEX- Docuemnto de identificación de Migración y Extranjería|`'/^[1-9][0-9]{10,11}$/'`
 DIDI | DIDI - Docuemnto de identificación de diplomáticos|`'/^[1-9][0-9]{10,11}$/'`


### Chile (CL)

Code| Type of Document| Validation Rule
---------|----------|------------
 CLRUT | Cédula personal física |`'/^(\d{1,2}(?:\.?\d{1,3}){2}-[\dkK])$/'`


### Panamá (PA)

Code| Type of Document| Validation Rule
---------|----------|------------
 CIP | Cédula de identidad personal| `'/^(N,E,PE\d+)?\d{2,6}\d{2,6}$/'`


 ### Brasil (BR)

 Code| Type of Document| Validation Rule
---------|----------|------------
 CPF | Cadastro de Pessoas Físicas|`'/^\d{10,11}$/'`
 CNPJ | Cadastro Nacional da Pessoa Jurídica | `/^\w{14}$/`


 ### Perú (PE)

  Code| Type of Document| Validation Rule
---------|----------|------------
 DNI | DNI|`'/^\d{8}$/'`
 RUC | Registro Único de Contribuyente | `'/^\d{13,14}$/'`


### México (MX)

  Code| Type of Document| Validation Rule
---------|----------|------------
  RFC | Registro Federal de Contribuyente | `'/^\w{12,13}$/'`


### España (ES)

Code| Type of Document| Validation Rule
---------|----------|------------
  NIF | Número de Identificación Fiscal | `'/^(\d{7,8})([A-HJ-NP-TV-Z])$/'`


### Argentina (ES)

Code| Type of Document| Validation Rule
---------|----------|------------
CUIT | Clave Única de Identificación Tributaria | `'/^(\d{7,8})([A-HJ-NP-TV-Z])$/'`