# cicd-shell-server

Shell for fiddling with ci/cd: executing commands, pushing and pulling files.

# Using

```yaml
    - uses: mugiseyebrows/cicd-shell-server@v1
      with:
        host: your.public.server
        port: 8857
        secret: ${{ secrets.SERVER_SECRET }}
```

See [cicd-shell](https://github.com/mugiseyebrows/cicd-shell) for details.