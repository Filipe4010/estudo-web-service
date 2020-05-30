# estudo-web-service | SOAP | REST API | XML | JSON |
Repositório destinado ao estudo de web service SOAP, REST API, XML &amp; JSON

# O SOAP Message tem a seguinte estrutura:
SOAP Envelope
SOAP Header
SOAP Body
# Exemplo:
<soap:Envelope
xmlns:soap="http://www.w3.org/2003/05/soap-envelope/"
soap:encodingStyle="http://www.w3.org/2003/05/soap-encoding">

<soap:Header>
...
</soap:Header>

<soap:Body>
...
  <soap:Fault>
  ...
  </soap:Fault>
</soap:Body>

</soap:Envelope>

# WSDL & XSD USANDO O PROGRAMA SOAP UI

TESTE USANDO SOAP UI http://soapclient.com/xml/soapresponder.wsdl

RETORNO: 

<SOAP-ENV:Envelope xmlns:SOAP-ENV="http://schemas.xmlsoap.org/soap/envelope/" xmlns:tns="http://www.SoapClient.com/xml/SoapResponder.wsdl" xmlns:xsd1="http://www.SoapClient.com/xml/SoapResponder.xsd" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:soap="http://schemas.xmlsoap.org/wsdl/soap/" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:SOAP-ENC="http://schemas.xmlsoap.org/soap/encoding/">
   <SOAP-ENV:Body>
      <mns:Method1Response SOAP-ENV:encodingStyle="http://schemas.xmlsoap.org/soap/encoding/" xmlns:mns="http://www.SoapClient.com/xml/SoapResponder.xsd">
         <bstrReturn xsi:type="xsd:string">Your input parameters are TESTE1 and TESTE2</bstrReturn>
      </mns:Method1Response>
   </SOAP-ENV:Body>
</SOAP-ENV:Envelope>
