# Github Actions example

This actions example is simple on purpose. The action only echoes a string so you don't get
confused with the action complexity when understanding the composite action and workflow system.

- Use environment (dev/prod) where you can define different secrets and force them to run on some specific branches
- Uses composite action to reuse code
- Uses 3 workflows: PR, push to main and release on main
