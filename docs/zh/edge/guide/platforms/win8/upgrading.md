---

license: Licensed to the Apache Software Foundation (ASF) under one or more contributor license agreements. See the NOTICE file distributed with this work for additional information regarding copyright ownership. The ASF licenses this file to you under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

           http://www.apache.org/licenses/LICENSE-2.0
    
         Unless required by applicable law or agreed to in writing,
         software distributed under the License is distributed on an
         "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
         KIND, either express or implied.  See the License for the
         specific language governing permissions and limitations
    

   under the License.
---

# 升級 Windows 8

本指南演示如何修改 Windows 8 專案從科爾多瓦的舊版本進行升級。 大多數這些說明適用于與舊集的前面的命令列工具創建的專案 `cordova` CLI 實用程式。 命令列介面資訊，請參閱如何更新的 CLI 版本。

## 從 2.8.0 升級到 2.9.0

下面的命令應當從內進行 Visual Studio 可以肯定任何專案引用是更新刪除。

1.  刪除 `cordova-2.8.0.js` 從專案的 `www` 目錄。

2.  添加 `cordova.js` 檔從源到專案中的 `www` 目錄。（請注意該檔不再包含在檔案名中的版本號）。

3.  生成和測試 ！

## 從 2.7.0 升級到 2.8.0

下面的命令應當從內進行 Visual Studio 可以肯定任何專案引用是更新刪除。

1.  刪除 `cordova-2.7.0.js` 從專案的 `www` 目錄。

2.  添加 `cordova.js` 檔從源到專案中的 `www` 目錄。（請注意該檔不再包含在檔案名中的版本號）。

3.  生成和測試 ！