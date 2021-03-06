---
title: ftp recv
description: Reference topic for **** - 

ms.prod: windows-server


ms.technology: manage-windows-commands

ms.topic: article
ms.assetid: f249ce61-247d-421b-9b93-48bce5108800 vhorne
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017
---
# ftp: recv

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Copies a remote file to the local computer using the current file transfer type.   
## Syntax  
```  
recv <remoteFile> [<LocalFile>]  
```  
#### Parameters  

|   Parameter   |                   Description                    |
|---------------|--------------------------------------------------|
| <remoteFile>  |        Specifies the remote file to copy.        |
| [<LocalFile>] | Specifies the name to use on the local computer. |

## Remarks  
- The **recv** command is identical to the **get** command.  
- if *LocalFile* is not specified, the file is given the *remoteFile* name.  
  ## Examples  
  copy **test.txt** to the local computer using the current file transfer type.  
  ```  
  recv test.txt  
  ```  
  copy **test.txt** to the local computer as **test1.txt** using the current file transfer type.  
  ```  
  recv test.txt test1.txt  
  ```  
  ## Additional References  
- [ftp: ascii](ftp-ascii.md)  
- [ftp: binary](ftp-binary.md)  
- [ftp: get](ftp-get.md)  
- - [Command-Line Syntax Key](command-line-syntax-key.md)  
