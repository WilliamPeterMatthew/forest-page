# forest-page
A webpage for the Forest App.

## Errorpage
For Nginx users, use the following code.
```nginx
error_page 404 /errorpage/404.html;
error_page 502 /errorpage/502.html;
```

For Apache users, use the following code.
```apache
ErrorDocument 404 /errorpage/404.html
ErrorDocument 502 /errorpage/502.html
```

If you are using another static webpage service, you need to copy all files under the folder `errorpage` to the root directory.

If you don't need to use the errorpage, you can find the [v1.0 tag](https://github.com/WilliamPeterMatthew/forest-page/tree/v1.0) code to use in the release page.