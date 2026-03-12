# IAM Compromise Playbook

## Scenario

Potential compromise of a user account, administrator identity, or service account in a cloud environment.

## Initial indicators

- Unusual login location or device
- Unexpected API activity
- Privilege escalation
- New keys, tokens, or service accounts created
- Access to sensitive resources outside normal patterns

## Immediate response steps

- Disable or suspend the affected identity if appropriate
- Revoke active sessions, keys, or tokens
- Review recent IAM changes
- Check for newly assigned roles or permissions
- Validate whether related service accounts were used

## Investigation focus

- Authentication logs
- Audit logs
- Resource access history
- Privilege changes
- Network and workload activity tied to the identity

## Containment

- Remove unauthorized permissions
- Rotate credentials
- Review related secrets or workloads
- Increase monitoring for follow-on activity

## Recovery

- Restore access using least privilege
- Confirm no persistence remains
- Document timeline, affected resources, and lessons learned
