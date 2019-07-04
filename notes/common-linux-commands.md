# 常用 Linux 命令

## 显示当前目录

```
➜  ~ pwd
/Users/kevin
```

***

## 查看目录内容

```
➜  flutter git:(stable) ll
total 136
-rw-r--r--   1 kevin  staff   1.5K May 10 12:00 AUTHORS
-rw-r--r--@  1 kevin  staff   2.6K Feb 27 01:17 CODE_OF_CONDUCT.md
-rw-r--r--   1 kevin  staff   3.4K May 10 12:00 CONTRIBUTING.md
-rw-r--r--@  1 kevin  staff   1.5K Feb 27 01:17 LICENSE
-rw-r--r--@  1 kevin  staff   1.1K Feb 27 01:17 PATENTS
-rw-r--r--   1 kevin  staff   4.2K May 10 12:00 README.md
-rw-r--r--@  1 kevin  staff   7.9K Feb 27 01:17 analysis_options.yaml
drwxr-xr-x@  6 kevin  staff   192B May 10 12:00 bin
-rw-r--r--@  1 kevin  staff   607B Feb 27 01:17 dartdoc_options.yaml
drwxr-xr-x@ 14 kevin  staff   448B Feb 27 01:17 dev
drwxr-xr-x@ 12 kevin  staff   384B May 10 12:00 examples
-rw-r--r--   1 kevin  staff   6.1K May 11 13:34 flutter_01.log
-rw-r--r--   1 kevin  staff   6.1K May 17 14:47 flutter_02.log
-rw-r--r--   1 kevin  staff   1.7K May 10 12:00 flutter_console.bat
-rw-r--r--@  1 kevin  staff   296B Feb 27 01:17 flutter_root.iml
drwxr-xr-x@ 12 kevin  staff   384B Feb 27 01:17 packages
-rw-r--r--   1 kevin  staff    14B Jul  2 20:14 version
```

列表中的内容有目录和文件，权限描述例如：
* -rw-r--r-- 为文件，权限为 644
* drwxr-xr-x 为目录，权限为 755

***
