# Azure Sphere MQTT client with MQTT-C

## Generate test.mosquitto.org TLC client certificate

NOTE - IT'S IMPORTANT TO POINT OUT THAT THE CERTS INCLUDED WILL LIKELY HAVE EXPIRED

[Generate a TLS client certificate for test.mosquitto.org](https://test.mosquitto.org/ssl)

The certificates are valid for 90 days from time of creation

I think we should delete the client.key and cert.crt files

and emphasis that they need to be called client.key and client.crt


The mosquitto.org.crt

I think we should get the dev to download the mosquitto.org.crt as it too will eventually expire.

**They need to download the PEM Format**

It can be downloaded from  https://test.mosquitto.org/

The encrypted ports support TLS v1.3, v1.2 or v1.1 with x509 certificates and require client support to connect. For ports 8883 and 8884 you should use the certificate authority file [mosquitto.org.crt (PEM format)](https://test.mosquitto.org/ssl/mosquitto.org.crt)

---

 or mosquitto.org.der (DER format)) to verify the server connection. Port 8081 has a Lets Encrypt certificate, so you should use your system CA certificates or the appropriate Lets Encrypt CA certificate for verification.



