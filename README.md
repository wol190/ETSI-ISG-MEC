# ETSI-ISG-MEC
Github for the ETSI MEC ISG: http://www.etsi.org/technologies-clusters/technologies/multi-access-edge-computing

Copyright: Viavi Solutions, pending acceptance by the ETSI MEC ISG. Should that be the case then it would be expected that this repository would be moved to an official location.

License: Apache License (Version 2.0), but this is condition to the decision of the ETSI MEC ISG.

Repository Overview: This repository currently includes API descriptions for the Radio Network Information (RNI) API, Location API and UE Application Interface API. For each API a YAML & JSON OpenAPI Version 2.0 compliant description is provided (https://www.openapis.org/ and for the specification https://github.com/OAI/OpenAPI-Specification). The RNI directory also includes a protocol buffer interface file, based on version 3.0 (https://developers.google.com/protocol-buffers/docs/reference/proto3-spec). There is also a "Template" directory to support the process of creating OpenAPI description files for other ETSI MEC defined APIs.

Swagger Hub: The OpenAPI description files can be used as the basis server. For the Location API an example was provided at http://etsi-mec-location-api.azurewebsites.net/swagger/ui/index.html (site currently OFFLINE), whcih generated via the Swagger Editor: http://swagger.io/swagger-editor/.
