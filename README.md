# ansible-configure-ssh-with-github

Add your local SSH key to your Github account, and add your SSH keys from Github as known keys.

## Role Variables

`github_username` and `github_api_token` must be supplied or all tasks will be skipped.

## Dependencies

* [icopp.configure-ssh-key](https://github.com/icopp/ansible-configure-ssh-key)

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
