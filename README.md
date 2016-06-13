# CSRF-PoC-Genorator
This is a simple CSRF Proof of Concept generator that supports multiple form encodings and methods

## How to use?
Fill out the form information with the request payload, encoding type, method, and URL, and download the POC file. You can then host the file with your web server of choice

```
python -m SimpleHTTPServer
```

It is recommended that the file is hosted rather than opened directly, in the chance that the target URI is checking referer headers.

## Does it support JSON?
No
