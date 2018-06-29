---
layout: post
title:  "Accounts package"
date:   2018-06-29 18:30:00 +0800
categories: EthereumCore
tags: golang Ethereum accounts
author: blc.study.grp
---

## Account
높은 수준의 이더리움 계정 관리 구현

### 하위 패키지 설명
* abi 
  * Ethereum ABI (Application Binary Interface)를 구현
* abi/bind
  * Ethereum contract Go binding 생성
* abi/bind/backends (냉무)
* keystore
  * secp256k1 개인키로 암호화된 storage 구현
* subwallert
  * USB 하드웨어 wallert 지원
* usbwallert/internal/trezor
  * wire protocol wrapper를 포함
  
### 주요 type
#### Account
