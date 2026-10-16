# HTTP and HTTPS
# Objective
To understand secure web communication and the security benefits of TLS.

# HTTP vs HTTPS
HTTP: Data is transmitted without built-in encryption.
HTTPS: Uses TLS to secure communication.
Encryption: Protects data from being read.
Authentication: Verifies server identity using certificates.
Integrity: Helps detect data modification.
# Tools
Web Browser
Developer Tools
# Deployment
HTTPS should use a valid TLS certificate and redirect HTTP traffic to HTTPS where appropriate.

# Rollback
Restore the previous working configuration if deployment fails and verify service functionality.

# Conclusion
HTTPS provides encryption, authentication, and integrity, making it safer than HTTP for sensitive data.

# Interview Questions
What is HTTPS? HTTP secured using TLS.
What is TLS? A protocol that secures network communication.
Why is HTTP insecure? Data is not encrypted by default.
