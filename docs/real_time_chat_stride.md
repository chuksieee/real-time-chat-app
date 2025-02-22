
# 🔐 STRIDE Threat Model: Real-Time Chat Application

| Threat | Description                         | Mitigation                            |
|--------|-------------------------------------|---------------------------------------|
| **S**poofing | Fake user identities accessing chats | Firebase Auth for verified sign-in    |
| **T**ampering | Unauthorized message modification | Secure Realtime Database Rules       |
| **R**epudiation | Users denying message history    | Message logs stored with timestamps  |
| **I**nformation Disclosure | Unintended data leaks           | Encrypted data transfer via HTTPS    |
| **D**enial of Service | Spam messages flooding chat    | Rate limiting and CAPTCHAs          |
| **E**levation of Privilege | Gaining admin rights              | Role-based access control           |
