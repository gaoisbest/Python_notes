# Change user
`su -i root`
`su -i user1`

# Folder size
```
du -lh --max-depth=1
```
# Compress
```
# tar.gz
tar -czvf xx.tar.gz xx_folder
```
# Decompress
```
# zip
unzip file.zip

# gz
gunzip file.gz

# tar.gz
tar -zxvf xx.tar.gz

# tar.bz2
tar -jxvf xx.tar.bz2

```

# Find file
```
find ./ -name "*.c"
```

# Docker cp
```
docker cp container_name:path_to_file externel_folder_path
```
