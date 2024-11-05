Tool / Template for managing feature flags for your application.

UI should be created dynamically based on the structure returned from the APi
 - Add, remove, etc.
 - Users may want the ability to group their flags, or create some type of hierarchy.
 - UI might support dragging and dropping?
 - Support for either strings, or bools, nothing else.


_Should support the following endpoints_

 - GET /flags
 - POST /flags
 - GET /flags/:key
 - UPDATE /flags/:key
 - DELETE /flags/:key


