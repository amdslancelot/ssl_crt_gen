# ssl_crt_gen

## Usage
chmod +x ssl_crt_gen
./ssl_crt_gen <domain_name>


## Concept
#### Certificate Authority(CA) side
1. Root CA key (rootCA.key)
2. Root CA Certificate (rootCA.crt)

#### Server side
1. Server Private Key (server.key)
2. Certificate Signing Request (csr)

#### Signing
1. server.key -> server.csr
2. server.csr + rootCA.key + rootCA.crt = server.crt


