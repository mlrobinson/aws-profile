# aws-profile
Wrapper script to generate &amp; pass AWS AssumeRole keys to other scripts

If the role you're switching to requires MFA, add your MFA device arn  (e.g.)
```
mfa_serial = arn:aws:iam::500000000000:mfa/simonvc
```

to the relevent `~/.aws/config` block
