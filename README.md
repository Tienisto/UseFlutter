# UseFlutter.dev Repository

This repository contains human-verified information about apps.

[UseFlutter.dev](https://useflutter.dev) prefers this over the auto-generated information.

## Schema

### ➤ blacklist.csv

A list of `<android package name>, <app name>` pairs that should not be included on the website
because they are not Flutter apps.

### ➤ apps.json

A list of apps that will be displayed on the website.

```json
{
  "LocalSend": {
    "homepage": "https://localsend.org",
    "source": "https://github.com/localsend/localsend",
    "android": "org.localsend.localsend_app",
    "ios": "1661733229",
    "windows": "https://localsend.org/download",
    "macos": "1661733229",
    "linux": "https://localsend.org/download",
    "libraries": {
      "State Management": [
        "refena"
      ],
      "Persistence": [
        "shared_preferences"
      ],
      "Networking": [
        "dio"
      ]
    }
  }
}
```

### ➤ libraries.json

Libraries that will be displayed on the website to indicate which libraries are used by the apps.
