When using ZNP hex images, the host processor must register for specific ZDO
callbacks of interest using the ZDO_MSG_CB_REGISTER API, and will be notified
of the response via the ZDO_MSG_CB_INCOMING command. The ZAP applications
incuded with this release demonstrate this method of handling ZDO responses.

For use with SPI serial interface -
 CC2538ZNP-SPI-Pro.hex -
  To be used with ZNP applications that do not use security.

 CC2538ZNP-SPI-Pro-Secure_Standard.hex -
  To be used with ZNP applications that use standard ZigBee security joining
  where the NWK key is sent in the clear or is pre-configured.

 CC2538ZNP-SPI-Pro-Secure_LinkKeyJoin.hex -
  To be used with ZNP applications that use the Pre-configured Trust Center
  Link Key method of joining where the pre-configured trust center link key
  is used to encrypt the APS tunnel command which contains the NWK key.

For use with UART serial interface -
 CC2538ZNP-UART-Pro.hex -
  To be used with ZNP applications that do not use security.

 CC2538ZNP-UART-Pro-Secure_Standard.hex -
  To be used with ZNP applications that use standard ZigBee security joining
  where the NWK key is sent in the clear or is pre-configured.

 CC2538ZNP-UART-Pro-Secure_LinkKeyJoin.hex -
  To be used with ZNP applications that use the Pre-configured Trust Center
  Link Key method of joining where the pre-configured trust center link key
  is used to encrypt the APS tunnel command which contains the NWK key.
