CC2530ZNP-Pro.hex - To be used with ZNP applications that do not use security. When using this image, the host processor
must register for specific ZDO callbacks using the ZDO_MSG_CB_REGISTER API, and will be notified of the response via
the ZDO_MSG_CB_INCOMING command. The included ZAP sample applications demonstrate this method of handling ZDO responses.

CC2530ZNP-Pro-Secure_Standard.hex - To be used with ZNP applications that use standard ZigBee security
join where the NWK key is sent in the clear or is pre-configured. When using this image, the host processor
must register for specific ZDO callbacks using the ZDO_MSG_CB_REGISTER API, and will be notified of the response via
the ZDO_MSG_CB_INCOMING command. The included ZAP applications demonstrate this method of handling ZDO responses.

CC2530ZNP-Pro-Secure_LinkKeyJoin.hex - To be used with ZNP applications that use the Pre-configured Trust Center Link Key 
method of joining where the pre-configured trust center link key is used to encrypt the APS tunnel command which contains the 
NWK key. When using this image, the host processor must register for specific ZDO callbacks using the ZDO_MSG_CB_REGISTER API, 
and will be notified of the response via the ZDO_MSG_CB_INCOMING command. The included ZAP applications demonstrate this method of 
handling ZDO responses.

CC2531ZNP-Pro.hex - Same functionality as the analogous .hex file above, except it is intended to be used with the CC2531 
USB dongle or a similar target device. When using this image, the host processor does not need to register for specific
ZDO callbacks and will receive ZDO responses as enumerated in the CC2530-ZNP Interface Specification for each corresponding
ZDO request that is sent.

CC2531ZNP-Pro-Secure_Standard.hex - Same functionality as the analogous .hex file above, except it is intended to be 
used with the CC2531 USB dongle or a similar target device. When using this image, the host processor does not need to 
register for specific ZDO callbacks and will receive ZDO responses as enumerated in the CC2530-ZNP Interface Specification
for each corresponding ZDO request that is sent.

CC2531ZNP-Pro-Secure_LinkKeyJoin.hex - Same functionality as the analogous .hex file above, except it is intended to be 
used with the CC2531 USB dongle or a similar target device. When using this image, the host processor does not need to 
register for specific ZDO callbacks and will receive ZDO responses as enumerated in the CC2530-ZNP Interface Specification
for each corresponding ZDO request that is sent. 

*****************************************************************************************
The serial boot loader is included in all images. Refer to the Z-stack user's guide for CC2530 ZigBee-PRO Network Processor 
- Sample Applications document for more information regarding the serial boot loader. 
*****************************************************************************************