MQTT Variants used for different test with certificates ...

Create server on local ip : 192.168.2.110 - privately val.itdbcks.net was pointed to that local ip 
created ssl CA and Client Certificates for server for CN=val.itdbcks.net and clients to used to 

certificates can be used either for HTTPS either for MQTT (on ip address 192.168.2.110)..

 Description | App | Type | use on
------------ | ------------ | ------------- | -------------
MqttNetDB | Broker | .NET Framework 4.7+ | Windows
MqttNetClient | Client | .NET Framework 4.7+ | Windows
MQTTm2m | Client | .NET Framework 4.7+ | Windows
NF.ESP32.Cert| Client | nanoFramework 1.5.x | embbeded ESP32
TinyCLRMqtt| Client | TinyCLR OS 2.x | embbeded STM32F743
 
