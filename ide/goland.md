- proxy err:
    我的方法是编辑 IDEA 自定义的 VM Options，在 IDEA 中的 Help - Edit Custom VM Options 添加以下配置：
    ```
    -Dhttp.proxyHost
    -Dhttp.proxyPort
    -Dhttps.proxyHost
    -Dhttps.proxyPort
    -DsocksProxyHost
    -DsocksProxyPort
    ```