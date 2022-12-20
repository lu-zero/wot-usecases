# Use case coverage - Gaps to consider for next WG charter

## Geolocation

* vocabulary
* geofencing
* static geolocation
* dynamic geolocation
* proximity; ad-hoc, e.g. bluetooth device identifies user is at home
* semantic location format, e.g. (BiM)  / additional ontologies + data format/historical data
* topology
* indoor/outdoor geolocation
* FoI; feature of interest (as in SSN);
* semantic query
* geopose - orientation

## Protocol Bindings

### other IOT standards and ecosystems
* BACnet
* KNX
* Modbus
* ECHONET Lite Web API Binding
* OPC-UA Binding Template
* Hybridcast Binding
* emerging standards, e.g. Matter

### Low level protocols and connection mechanisms
* LPWAN and SDI 12 usage in WoT
* websocket or SSE since a dashboard on a browser would be limited if we only have HTTP
* multicast

## Onboarding, Security and Trust
* IoT trust ontology
* access control; roles/scopes; onboarding
* more implementation needed for different flows
* emerging standards, e.g. DID, SSI
* key distribution
* encryption on isolated networks

## Complex Interactions
* orchestration / aggregation / automation rules
* behavior description

## Thing Relationships
* service interconnection
* links between TDs (see also Digital Twins)
* Groups of devices and linking (virtual compositions)

## Digital Twins
* device shadow
* connected & disconnected status 
* time series
* historical data 
* links between TDs (see also Thing Relationship)
* service interconnection

- reviewed until here on Dec 20th

## Metrics/Ontologies
data-based; trust metrics; (indoor) geolocation; semantic query
data-driven; latency/metric ranking
additional ontologies for location / temperature
relative values/precision
/units/battery level

## UI
hint for UI elements / geolocation / timestamps
hint for UI elements / indoor location
hint for UI elements /geolocation
ui preference description

## Accessibility
sensory modalities
alternative I/O


## Video
video streaming
video streaming protocol binding template
"Video streaming binding/email and sms binding, image payload formats"

## Onboarding
onboarding; registration

## Miscellaneous
Usage cycle description
embedding of application-specific metadata 
presence; context
roles/scopes; onboarding
sensory modalities
simple rules/automatic onboarding/configuration