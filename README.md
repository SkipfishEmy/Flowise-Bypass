# Flowise-Bypass
Flowise 1.6.5 - Authentication Bypass
puts authentication middleware for all the endpoints with path /api/v1
except a few whitelisted endpoints. But the code does check for the case
sensitivity hence only checks for lowercase /api/v1 . Anyone modifying the
endpoints to uppercase like /API/V1 can bypass the authentication.
