# aws-profile
Wrapper script to generate &amp; pass AWS AssumeRole keys to other scripts

If the role you're switching to requires MFA, add
```
mfa = true
```

to the relevent `~/.aws/config` block
