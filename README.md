# TARA-Go

TARA Client in Go language

Package `tara` provides a client for authenticating with the [TARA authentication
service](https://e-gov.github.io/TARA-Doku/).

`tara` wraps an OpenID Connect client with some specific choices and
adjustments made by TARA.

Uses packages `log` and `internal/session` (not provided here at present time). If you use TARA-Go, then implement these yourself. 
