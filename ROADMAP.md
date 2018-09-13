# Roadmap

1. Implement similar user-level config/dotfile-management to rcm
2. Implement way to separate files by security-level/user and safeguard them against modification by non-privileged users

## Sub-Roadmap

1. Implement storage format for meta-data that does not require non-standard tools like `jq`

### Folder structure of storage
$HOME/.configStore
    __META-$Filename.conf
    secureStore/
        __META-$Filename.conf

### Structure of __Meta-files
    FILENAME=name
    TARGETDIR=dir
    
