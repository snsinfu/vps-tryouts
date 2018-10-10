# VPS tryouts

## Amazon EC2

Set credentials in `~/.aws/credentials`:

```
[default]
aws_access_key_id = ...
aws_secret_access_key = ...
```

And run these commands:

```
cd amazon
make
make ssh
make clean
```

## Hetzner Cloud

Set these environment variables:

- HCLOUD\_TOKEN
- TF\_VAR\_location (optional)
- TF\_VAR\_type (optional)
- TF\_VAR\_os (optional)

And run these commands:

```
cd hetzner
make
make ssh
make clean
```
