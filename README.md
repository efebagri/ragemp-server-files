# 💾 RAGEMP

<div align="center">
    <a href="https://rage.mp/"><img src="https://life-of-german.org/images/proxy/0b/0b33ce3075e0ea0468350a1c51087619095861d2.png" width="546" alt="ragemp" /></a>
</div>

![](https://img.shields.io/badge/Code-JavaScript-informational?style=flat&logo=javascript&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-CSharp-informational?style=flat&logo=csharp&logoColor=white&color=6aa6f8)
![visitors](https://visitor-badge.laobi.icu/badge?page_id=efebagri.ragemp-server-files)

# Set it up yourself

#### In the RAGEMP folder in the config.xml file, change the code to here:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<channel>prerelease_server</channel>
```

or the old version

```xml
<?xml version="1.0" encoding="UTF-8"?>
<channel>10_mNwuchuQ4ktWbR8d2N5jUzRt</channel>
```

# If you want to use C# as backend what you may need
#### settings.xml
```xml
<?xml version="1.0"?>
<config xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <resource src="Core"/>
  <acl_enabled>true</acl_enabled>
  <log_console>true</log_console>
  <log_chat>true</log_chat>
</config>
```

ore the old version

```xml
<config xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <resource src="Core"/>
    <acl_enabled>true</acl_enabled>
    <log_console>true</log_console>
    <log_chat>true</log_chat>
</config>
```
 
#### meta.xml
```xml
<meta>
    <info name="Core" description="Core Scripts" />
    <script src="Core.dll" />
</meta>
```
 
#### So that no unnecessary folder structures are created
```xml
<CopyLocalLockFileAssemblies>true</CopyLocalLockFileAssemblies>
<AppendTargetFrameworkToOutputPath>false</AppendTargetFrameworkToOutputPath>
```
