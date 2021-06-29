# pushgateway-functions

[![Build Status](https://drone.osshelp.ru/api/badges/ansible/pushgateway-functions/status.svg)](https://drone.osshelp.ru/ansible/pushgateway-functions)

The role which installs [pushgateway-functions](https://github.com/OSSHelp/pushgateway-functions).

## Deploy example

```yaml
    roles:
      - role: pushgateway-functions
```

## Available parameters

### Main

| Param | Default | Description |
| -------- | -------- | -------- |
| `pushgateway_version` | `1-latest` | Library version to install. Format is `N-latest` where `N` is major version of needed release.  |

## FAQ

None

## Useful links

- [Library itself](https://github.com/OSSHelp/pushgateway-functions)
- [Official documentation for pushgateway](https://github.com/prometheus/pushgateway)

## TODO

None, so far.

## License

GPL3

## Author

OSSHelp Team, see <https://oss.help>
