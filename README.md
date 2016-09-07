# ansible-configure-ssh-with-github

Generate a local SSH key if necessary, add it to your Github account, and add your SSH keys from Github as known keys.

## Role Variables

`github_username` and `github_api_token` must be supplied or all tasks will be skipped.

## Example Playbook

```
  - hosts: all
    roles:
      - role: icopp.configure-ssh-with-github
        github_username: xxxxx
        github_api_token: xxxxx
```

## License

MIT
