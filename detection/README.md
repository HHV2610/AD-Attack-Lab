# Detection and Mitigation

## Detection
- Monitor Event ID 4768 for Kerberos TGT requests using PKINIT
- Monitor Event ID 4886 and 4887 for abnormal certificate issuance
- Alert when certificate subject does not match the requester identity

## Mitigation
- Restrict certificate template enrollment permissions
- Disable 'Supply subject alternative name' where not required
- Regularly audit ADCS configurations
