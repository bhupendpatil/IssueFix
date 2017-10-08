# Visual Studio Validation Control Error Fix 
(works with Visual Studio 2017)

:boom:**Steps**
* Open .config file (Web.config)
* Paste the code below before ```</configuration>``` tag

  ```xml
  <appSettings>
      <add key="ValidationSettings:UnobtrusiveValidationMode" value="None"></add>
  </appSettings>
   ```

_May look like this_ 
:bow:
:point_down: 
![capture](https://user-images.githubusercontent.com/9783913/31308766-ee6b36f0-ab99-11e7-8ea9-ec1d11c8fb90.PNG)
