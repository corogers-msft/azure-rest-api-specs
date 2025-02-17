# Customer Lockbox
    
> see https://aka.ms/autorest

This is the AutoRest configuration file for Customer Lockbox.



---
## Getting Started 
To build the SDK for Customer Lockbox, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`
---

## Configuration



### Basic Information 
These are the global settings for the Customer Lockbox API.

``` yaml
openapi-type: arm
tag: package-2018-02-preview
```

### Tag: package-2018-02-preview

These settings apply only when `--tag=package-2018-02-preview` is specified on the command line.

``` yaml $(tag) == 'package-2018-02-preview'
input-file:
- Microsoft.CustomerLockbox/preview/2018-02-28-preview/customerlockbox.json
```

---
# Code Generation


---
## C# 

These settings apply only when `--csharp` is specified on the command line.
Please also specify `--csharp-sdks-folder=<path to "SDKs" directory of your azure-sdk-for-net clone>`.

``` yaml $(csharp)
csharp:
  azure-arm: true
  license-header: MICROSOFT_MIT_NO_VERSION
  namespace: Microsoft.Azure.Security.CustomerLockbox
  output-folder: $(csharp-sdks-folder)/customerlockbox/Microsoft.Azure.Security.CustomerLockbox/src/Generated
  clear-output-folder: true
```


