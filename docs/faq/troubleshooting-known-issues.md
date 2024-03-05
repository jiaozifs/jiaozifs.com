---
sidebar_position: 2
---

# Trobleshooting & Known Issues

## Trobleshooting

### Is my repository initialized for JiaoziFS?

After successfully executing `jiaozifs init`, you can view the configuration information in your `~/.jiaozifs` file and make corresponding modifications based on your configuration.

```
cat ~/.jiaozifs/config.toml

vim ~/.jiaozifs/config.toml
```

### After running Jiaozifs, where is the data stored?

+ Personal information data: In the `PostgreSQL database`.
+ Uploaded data: Depending on the upload method, the data is stored in different locations. By default, uploads are stored locally, and the data is saved in `~/.jiaozifs/blockstore`.

## Known Issues

TBD.