Usage:
=======

This small PHP Tool allows you to minify backups, by scaling all images down and replacing PDFs with small dummy files.

This can be useful if you want to setup development or staging environment and dont want to waste time and space to deal with all the big assets.

Usage:

```
    php Bin/minfiy.php --source=/assetbackup/production --target=/assetbackup/minified_production
```

Optional Parameters:

```
   --skipExistingFiles=0		By default existing files are not copied to target anymore.
   --quietMode=1			No output of log infos.
```

Todo:
=======
* Replace Videos as well
