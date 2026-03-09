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

| Plugin | Version | Description |
|--------|---------|-------------|
| **joke-plugin** | 1.1.0 | Adds a `/joke` skill for programming jokes |

## Versioning

Plugins are versioned so you can track updates. After updating the marketplace (`/plugin marketplace update`), reinstall a plugin to get the latest version:

```
/plugin install joke-plugin@testmarketplace
```

## Updating

Refresh your local copy of the marketplace:

```
/plugin marketplace update
```
