# Proof of concept code for client-side vulnerabilities

Basic HTML proof of concepts for issues such as:

- Clickjacking
- insecure CORS settings
- CSRF
- Tabnapping
- XSSI
- postMessage issues

Most of these are pretty basic, but having them all in one place avoids writing the same things over and over again.

Two things that are a bit more interesting:

- clickjacking_full.html: an advanced clickjacking script for real-world multi-click Clickjacking exploitation. 
- csrf-multi.html: automatically send multiple CSRF requests (for example when bruteforcing a small value - such as an IP when performing CSRF against internal networks -, or for multi-stage CSRF attacks where the order of requests dosn't matter, or requests can be performed multiple times).


