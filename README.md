# technomancy

Lux-powered site. Requires a Lux build with builtin `renderTemplate`.

```
cd /path/to/technomancy
lux webserver.lux
```

Templates live under `public/` (`index.tpl`, `oop-index.tpl`, includes). Context is a small `TplCtx` class in `webserver.lux`. Edit a `.tpl` then restart the server (includes are cached).
