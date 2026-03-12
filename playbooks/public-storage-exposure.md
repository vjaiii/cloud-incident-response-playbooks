# Public Storage Exposure Playbook

## Scenario

A bucket, object store, or cloud storage resource is found to be publicly accessible.

## Initial indicators

- Security alert or CSPM finding
- External report
- Public URL access confirmed
- Unexpected data download patterns

## Immediate response steps

- Remove public access immediately if safe to do so
- Preserve access logs and metadata
- Identify affected data and sensitivity
- Validate whether exposure was intentional or accidental

## Investigation focus

- Who changed the access settings
- When the resource became public
- Which objects were exposed
- Whether external access occurred
- Whether similar resources have the same issue

## Containment

- Block public access
- Review IAM and bucket policies
- Review organization-level guardrails
- Search for similar misconfigurations

## Recovery

- Notify stakeholders if sensitive data was exposed
- Strengthen preventive controls
- Add alerts and guardrails for future exposure
