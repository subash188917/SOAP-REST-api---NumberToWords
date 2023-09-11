
# SOAP & REST api - NumberToWords

Welcome to the NumberToWords API Integration project! This GitHub repository hosts a comprehensive solution for integrating the SOAP and REST APIs provided by the NumberConversion.wso web service. The primary goal of this project is to automate the conversion of numerical values into their corresponding words, allowing you to leverage this functionality in your applications and systems.




### Features:


SOAP and REST API integration

Automated testing suite

Clear documentation

Open for contributions


### Get Started :
Download a postman collection file and import it in postman
Or
Add manually api in API Tool as given below content required
```
```
## POST SOAP - NumberToWords

##### URL
https://www.dataaccess.com/webservicesserver/NumberConversion.wso

```
```

##### Request Headers
```
Content-Type:text/xml; charset=utf-8

Content-Length:length

```
```
```
##### Body raw (xml)

```
<?xml version="1.0" encoding="utf-8"?>
<soap12:Envelope xmlns:soap12="http://www.w3.org/2003/05/soap-envelope">
  <soap12:Body>
    <NumberToWords xmlns="http://www.dataaccess.com/webservicesserver/">
      <ubiNum>444</ubiNum>
    </NumberToWords>
  </soap12:Body>
</soap12:Envelope>

```


## POST REST api - NumberToWords

##### URL
https://www.dataaccess.com/webservicesserver/NumberConversion.wso/NumberToWords

```
```

##### Request Headers
```
Content-Type:application/json

Content-Length:length

```
```
```
##### Body raw (text)

```
{
   "ubiNum": "44"
}

```
## Documentation

[SOAP api Test cases](https://github.com/KareenaKambaliya/SOAP-REST-api---NumberToWords/blob/main/SOAP%20api%20atc.xlsx)# SOAP-REST-api---NumberToWords
