# sftp_config_file
SFTP配置文件（Sublime Text 3 、VS Code）



VS Code 的版本

```json
{   
    "host": "120.01.01.111",
    "port": 22,
    "username": "root",
    "password": "123456",
    "protocol": "sftp",
    "agent": null,
    "privateKeyPath": null,
    "passphrase": null,
    "passive": false,
    "interactiveAuth": true,
    "remotePath": "/www/wwwroot/web.1111.com/",
    "uploadOnSave": false,
    "syncMode": "update",
    "ignore": [
        "**/.vscode/**",
        "**/.git/**",
        "**/.DS_Store"
    ],
    "watcher": {
        "files": "glob",
        "autoUpload": true,
        "autoDelete": true
    }

}
```

Sublime Text 的版本

```json
{
    // The tab key will cycle through the settings when first created
    // Visit http://wbond.net/sublime_packages/sftp/settings for help
    
    // sftp, ftp or ftps
    "type": "sftp",

    "save_before_upload": true,
    "upload_on_save": true,
    "sync_down_on_open": true,
    "sync_skip_deletes": false,
    "sync_same_age": true,
    "confirm_downloads": false,
    "confirm_sync": true,
    "confirm_overwrite_newer": false,
    
    "host": "120.01.01.111",
    "user": "root",
    "password": "123456",
    "port": "22",
    
    "remote_path": "/www/wwwroot/www.11111.com/",
    "ignore_regexes": [
        "\\.sublime-(project|workspace)", "sftp-config(-alt\\d?)?\\.json",
        "sftp-settings\\.json", "/venv/", "\\.svn/", "\\.hg/", "\\.git/",
        "\\.bzr", "_darcs", "CVS", "\\.DS_Store", "Thumbs\\.db", "desktop\\.ini"
    ],
    "file_permissions": "777",
    "dir_permissions": "777",
    
    //"extra_list_connections": 0,

    "connect_timeout": 30,
    "keepalive": 10,
    //"ftp_passive_mode": true,
    //"ftp_obey_passive_host": false,
    //"ssh_key_file": "~/.ssh/id_rsa",
    //"sftp_flags": ["-F", "/path/to/ssh_config"],
    
    //"preserve_modification_times": false,
    //"remote_time_offset_in_hours": 0,
    //"remote_encoding": "utf-8",
    //"remote_locale": "C",
    //"allow_config_upload": false,
}
```
