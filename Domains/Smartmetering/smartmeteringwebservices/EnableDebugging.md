## EnableDebugging request

### Description
Enable debugging for a device. Communication with the device will be logged and made available through [FindMessageLogs](./FindMessageLogs.md),

All requests have similar response behaviour which is described in [ResponseMessages](./ResponseMessages.md).

[GetEnableDebuggingResponse](./GetEnableDebuggingResponse.md) returns the result status. The response contains the DeviceIdentification and CorrelationUid which is received from the GetEnableDebuggingRequest request.

### References

XSD: [sm-adhoc.xsd](https://github.com/OSGP/Shared/blob/development/osgp-ws-smartmetering/src/main/resources/schemas/sm-adhoc.xsd)

WSDL: [SmartMeteringAdhoc.wsdl](https://github.com/OSGP/Shared/blob/development/osgp-ws-smartmetering/src/main/resources/SmartMeteringAdhoc.wsdl)

