# patriqcs Unraid Community Applications Templates

XML templates for applications published to the
[Unraid Community Applications] store.

Each `.xml` here is a standalone Docker-container template. The container
source code lives in a separate repository linked from each template's
`<Project>` tag.

## Templates

| Template | Container Image | Source Repo |
|---|---|---|
| [mosbot.xml](./mosbot.xml) | `ghcr.io/patriqcs/mosbot` | [patriqcs/mosbot](https://github.com/patriqcs/mosbot) |

## Manual install (without CA)

In Unraid: **Apps -> Add Container -> Template URL**, paste the raw URL of
the desired template, e.g.

```
https://raw.githubusercontent.com/patriqcs/unraid-templates/main/mosbot.xml
```

## License

MIT
