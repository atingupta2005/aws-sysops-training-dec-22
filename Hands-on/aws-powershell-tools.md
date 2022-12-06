```
Install-Module -Name AWSPowerShell.NetCore -AllowClobber
```

```
Import-Module AWSPowerShell.NetCore
```

```
Set-AWSCredential -AccessKey '' -SecretKey ''
```

```
New-S3Bucket -BucketName powershell-core-bucket-<random-number> -Region eu-west-1
```
