# testmarketplace

A Claude Code plugin marketplace for distributing plugins across teams and communities.

## Adding this marketplace

Add the marketplace to Claude Code (replace `owner/repo` with your GitHub username and repo name):

```
/plugin marketplace add owner/repo
```

Example:

```
/plugin marketplace add ganeshdipdumbare/testmarketplace
```

## Installing plugins

After adding the marketplace, install individual plugins:

```
/plugin install <plugin-name>@testmarketplace
```

## Available plugins

| Plugin | Description |
|--------|-------------|
| **review-plugin** | Adds a `/review` skill for quick code reviews (bugs, security, performance, readability) |

## Updating

Refresh your local copy of the marketplace:

```
/plugin marketplace update
```
