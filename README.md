# inbox.sh

Bash client for [Inbox](https://github.com/san650/inbox-server).

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

inbox.sh is licensed under the MIT license.

See [LICENSE](./LICENSE) for the full license text.
