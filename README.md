# Onos_Openflow_Rules

|Author|Chieh-Ting Chung|
|---|---
|E-mail|sksksk1748@gmail.com

## Memo

* SDN 拓樸實作，並執行 host1 ping host2

## Algorithm
* 請搭配 【HackMD】Lab 1 : ONOS OpenFlow Controller 安裝 Java, curl, ONOS, mininet 及下 command
* 各個 Switch port 要設定好

## Your `~/onos-2.4.0/` folder should look like this
```
onos-2.4.0
├── apache-karaf-4.2.8/
│   └── ...
├── apps/ 
│   └── ...
├── bin/
│   └── ...
└── init/ 
│   └── ...
└── switchRule/ 
│   └── ...
└── topology/ 
    └── ...

```

## Topic

* 產生有兩條路徑的topology
* h1 ping h2
* 讓ping packet走較長的路徑( S1 --> S3 --> S2 ) 
    * Switch S3的forwarding table
    * Ping 成功的畫面
    * ONOS GUI中的topology

## Result

* Switch S3的forwarding table
![](https://i.imgur.com/jSPzurs.png)
* Ping 成功的畫面
![](https://i.imgur.com/OkdWbkd.png)
* ONOS GUI中的topology
![](https://i.imgur.com/gsuNxmx.png)

## Reference

* NTUST , SHAN-HSIANG SHEN PROFESSOR
