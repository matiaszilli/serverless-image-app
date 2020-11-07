---
name: Bug report
about: Let us know about an unexpected error, a crash, or an incorrect behavior.

---

<!--
Hi there,

Thank you for opening an issue. Please note that we try to keep the issue tracker reserved for bug reports and feature requests. For general usage questions, please see the documentation.

-->

### Current Terraform Version
<!---
Run `terraform version` to show the version, and paste the result between the ``` marks below.

If you are not running the latest version of Terraform, please try upgrading because your issue may have already been fixed.
-->

```
...
```

### Terraform Configuration Files
<!--
Paste the relevant parts of your Terraform configuration between the ``` marks below.

For large Terraform configs, please use a service like Onedrive and share a link to the ZIP file. For security, you can also encrypt the files using our GPG public key.
-->

```terraform
...
```

### Debug Output
<!--
Full debug output can be obtained by running Terraform with the environment variable `TF_LOG=trace`. Please create a GitHub Gist containing the debug output. Please do _not_ paste the debug output in the issue, since debug output is long.

Debug output may contain sensitive information. Please review it before posting publicly, and if you are concerned feel free to encrypt the files using our GPG public key.
-->

### Expected Behavior
<!--
What should have happened?
-->

### Actual Behavior
<!--
What actually happened?
-->

### Steps to Reproduce
<!--
Please list the full steps required to reproduce the issue, for example:
1. `terraform init`
2. `terraform apply`
-->

### Additional Context
<!--
Are there anything atypical about your situation that we should know? For example: is Terraform running in a wrapper script or in a CI system? Are you passing any unusual command line options or environment variables to opt-in to non-default behavior?
-->

### References
<!--
Are there any other GitHub issues (open or closed) or Pull Requests that should be linked here? For example:

- #6017

-->