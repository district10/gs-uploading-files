## Easy File Uploader

You need java. Then goto release page to download [the jar file: gs-uploading-files-0.1.0.jar (21.4 MB)](https://github.com/district10/gs-uploading-files/releases/download/v2.0/gs-uploading-files-0.1.0.jar).

Then run it like:

```
$ java -jar -Dspring.http.multipart.max-file-size=100MB -Dspring.http.multipart.max-request-size=100MB gs-uploading-files-0.1.0.jar
```

文件上传. 类似于 npm 的 http-server 的兄弟.
