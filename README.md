# 99managers.org
99 Managers simple landing page visible at [99managers.org](https://99managers.org/)

Available on [Codeberg](https://codeberg.org/dulvui/99managers.org) and [Github](https://github.com/dulvui/99managers.org).

# Build
To build the site locally please install first [zola](https://www.getzola.org/).
```
cd src
zola build
```

# Deploy
This deployment is specific for my infrastructure, but it works with any caddy server or other http server.
```
rsync -vra public/ floresta:/var/www/html/99managers.org/ --delete
```

# Licenses
The website itself is licensed under the [GNU AGPL v3.0](LICENSE) license.  
All content made by myself is licensed under the [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/) license.

[Simple-icons](https://github.com/simple-icons/simple-icons) are used in the footer. They are [CC0-1.0](https://github.com/simple-icons/simple-icons/blob/develop/LICENSE.md) licensed
