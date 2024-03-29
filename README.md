# Material Dark Pink Theme

[![Build Status](https://www.travis-ci.org/home-assistant-community-themes/material-dark-pink.svg?branch=master)](https://www.travis-ci.org/home-assistant-community-themes/material-dark-pink)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/hacs/integration)

> The Material Dark Pink Theme by GreenTurtwig

## Screenshots

### Overview

![Theme - Overview](https://raw.githubusercontent.com/home-assistant-community-themes/material-dark-pink/master/docs/theme-overview.png)

### Map

![Theme - Map](https://raw.githubusercontent.com/home-assistant-community-themes/material-dark-pink/master/docs/theme-map.png)

### Logbook

![Theme - Logbook](https://raw.githubusercontent.com/home-assistant-community-themes/material-dark-pink/master/docs/theme-logbook.png)

### History

![Theme - History](https://raw.githubusercontent.com/home-assistant-community-themes/material-dark-pink/master/docs/theme-history.png)

### Developer Tools

![Theme - Developer Tools](https://raw.githubusercontent.com/home-assistant-community-themes/material-dark-pink/master/docs/theme-developer-tools.png)

### Configuration

![Theme - Configuration](https://raw.githubusercontent.com/home-assistant-community-themes/material-dark-pink/master/docs/theme-configuration.png)

### Profile

![Theme - Profile](https://raw.githubusercontent.com/home-assistant-community-themes/material-dark-pink/master/docs/theme-profile.png)

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS

1. Go to the Community Store.
2. Search for `Material Dark Pink`.
3. Navigate to `Material Dark Pink` theme.
4. Press `Install`.
6. Go to services and trigger the `frontend.reload_themes` service.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/home-assistant-community-themes/material-dark-pink.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/home-assistant-community-themes/material-dark-pink.git
```
