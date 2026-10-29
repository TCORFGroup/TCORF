Version integrity. Each release is published with a file digest list at www.tcorf.com. A copy whose digest does not 
match the published list for its version is not the framework, whatever it is called. The list at the official source is 
authoritative. A digest list distributed inside a document set would authenticate nothing, since a modified set can carry 
a modified list — which is why it is published only on the site.  

Verify on any system: sha256sum <file> (Linux, macOS) or Get-FileHash <file> -Algorithm SHA256 (Windows).
