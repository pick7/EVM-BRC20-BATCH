### 在各种 evm 链上打铭文的脚本工具
#### 让不会写代码的人也能批量打铭文, 再一次站在同一起跑线上.
使用以下命令格式来执行二进制文件：


```shell
./对应的二进制文件 "换成你的节点" "换成你的私钥" '铭文的格式' "换成你要改的 gas,单位是 wei" "换成你要打的总量" "换成休息的间隔,单位是毫秒"
```

#### 使用步骤

1. clone 或者 下载 [本仓库](/0xJayShen/EVM-BRC20-BATCH/archive/refs/heads/main.zip)
2. 使用对应的二进制文件运行
   - mac 用户
    ```shell
    ./mac https://rpc.ankr.com/bsc/2eac989010412c2411daf2a 64431432344y4460dsfsdaf2d6c2f 'data:,{"p":"bsc-20","op":"mint","tick":"bsci","amt":"1000"}' 6000000000 1 1
    
    ```
   - windows 用户(待测试)
   ```shell
   ./windows.exe https://rpc.ankr.com/bsc/2eac989010412c2411daf2a 64431432344y4460dsfsdaf2d6c2f 'data:,{"p":"bsc-20","op":"mint","tick":"bsci","amt":"1000"}' 6000000000 1 1

    ```