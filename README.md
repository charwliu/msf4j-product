# msf4j-product
This will install the msf4j and other required features to the kernel and build up a product.
You can find the product in the target directory

Go to the target/wso2msf4j-<version>/bin directory
Then run the following command to start the MSF4J server.

```
./carbon.sh
```

If you wanna configure the transport you can use the netty-transports.yml file.
```
./carbon.sh -Dtransports.netty.conf=netty-transports.yml
```
