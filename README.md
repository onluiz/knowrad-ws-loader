# knowrad-wsloader
Knowrad websocket loader is an structure to load DICOM files via websocket.

1 - Client ask for DICOM to an web java app in server;

2 - Server ask DICOM for DCM4CHEE via dcm API and returns the DICOM for the app in server;

3 - App returns the DICOM for client via websockets (previously opened).
