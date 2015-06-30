# Shocker

Manage docker containers with ssh-access
that serves http under a subdomain.

```
shocker <command> [-h|--help]

commands:
  create   Create container for subdomain
  destroy  Destroy container for subdomain

Usage: shocker create <subdomain>
  Create a container that serves http under <subdomain>
  and echo the port on which it listens to ssh

  Example: shocker create myapp

Usage: shocker destroy <subdomain>
  Destroy the container running under <subdomain> and
  delete it for all eternity

  Example: shocker destroy myapp
```