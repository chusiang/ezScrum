# ezScrum

## Setting

### Edit ezScrum_FTPServer_Config.txt

- Rename ezScrum_FTPServer_Config_default.txt to ezScrum_FTPServer_Config.txt
- File location: ``ezScrum/ezScrum_FTPServer_Config.txt``
- Modify it.

        ezScrum.FTP.site.ip
        ezScrum.FTP.site.username
        ezScrum.FTP.site.password

### Edit its_config.txt

- Rename its_config_default.txt to its_config.txt
- File location: ``ezScrum/WebContent/Workspace/_metadata/its_config.txt``
- Modify it.

        serverURL
        Account
        Password

### Edit TestConfig.properties

- Rename TestConfig_default.properties to TestConfig.properties
- File location: ``ezScrum/TestData/TestConfig.properties``
- Modify it.

        serverURL
        serverAccount
        serverpwd
        DB_name
        Appserv_UseID
        Appserv_pwd

### Manually create table

- File location: ``ezScrum/WebContent/Workspace/_metadata/initail_bk.sql``
- Take this sql file all sql statement copy to your My SQL to create table

### Use it.

- Access the link like [http://serverURL/ezScrum/logon.do](http://serverURL/ezScrum/logon.do)
