# inbox-bash

Bash client for [Inbox](https://github.com/san650/inbox-server).

## Configuration

Add a `INBOX_URL` environment variable with your inbox-server URL.

e.g. Add the following to your `bashrc` configuration file

```
INBOX_URL=https://username:password@example.com:port/
```

*Don't forget to end the URL with `/`*

Remember that `inbox-server` uses HTTP BASIC Authentication

## Usage

### Add a resource

```
$ inbox add http://www.wikipedia.org/
```

### List all resources

Return all resources

```
$ inbox list
```

Return resources filtered by tags

```
$ inbox list shell web ~host
```

Note that by prefixing the tag with `~` it will exclude resources that contains
said tag.


## License

inbox-bash is licensed under the MIT license.

See [LICENSE](./LICENSE) for the full license text.
