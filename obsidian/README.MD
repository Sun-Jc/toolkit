### Obsidian

#### `.obsidian` Folder

- theme & snippets
- community-plugins
- core-plugins

#### Web Clipper

```ad-note
Credit: This script comes from (kepano/obsidian-web-clipper.js)[https://gist.github.com/kepano/90c05f162c37cf730abb8ff027987ca3].
Many thanks to @kepano for this script, and we shall follow this thread for updates!
```

1. Per [web-clipper.js](web-clipper.js), change `VAULT_NAME` to your target vault, the js snippet should be

```javascript
    /* Optional vault name */
    const vault = "VAULT_NAME";

    /* Optional folder name such as "Clippings/" */
    const folder = "Web-Clippings/";

    /* Optional tags  */
    const tags = "#webclip";
```

2. Add a new bookmark in your browser and paste the content of this script as the `url`.
3. Click this bookmark and you will find the clipped markdown file in your `Web-Clippings/` folder, with tag `#webclip`.

#### TODOs

- [ ] Wechat Official Account articles clipper;
- [ ] Bilibili & Youtube reference;
