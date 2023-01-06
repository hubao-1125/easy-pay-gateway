
# easy-pay-gateway
`带*的为真正的服务`

## epg-common-utils(支付公用model或工具类)

---

## epg-core(支付核心，所有对接支付相关实现都在这里)

---

## epg-pay(支付、退款、撤单等行为)
### 1、epg-pay-common(model)
### 2、epg-pay-api(dubbo接口)
### 3、epg-pay-service(具体实现)
#### 0、epg-pay-service-base(支付具体实现服务基础版，所有请求都会打到这个服务)*
#### 1、epg-pay-service-wx(微信支付具体实现服务，限定V2XML)*
#### 2、epg-pay-service-wxv3(微信支付具体实现服务，限定V3JSON)*
#### 3、epg-pay-service-alipay(支付宝支付具体实现服务)*
#### 4、epg-pay-service-union(银联支付具体实现服务)*
#### 5、epg-pay-service-icbc(工行支付具体实现服务)*
#### 6、epg-pay-service-dg(汇付天下-斗拱支付具体实现服务)*
### 4、epg-pay-data(支付相关操作数据库)

---

## epg-config(通道配置相关)
### 1、epg-config-common(model)
### 2、epg-config-api(dubbo接口)
### 3、epg-config-service(具体实现)
#### 1、epg-config-service-get(获取支付、分账等具体通道配置服务)*
#### 2、epg-config-service-operation(CRUD支付通道配置服务)*
### 4、epg-config-data(通道配置相关操作数据库)

---

## epg-order(支付订单)
### 1、epg-order-common(model)
### 2、epg-order-api(dubbo接口)
### 3、epg-order-service(具体实现)
#### 1、epg-order-service-ext(对外吐出查询订单服务，PS：有老业务系统的可通过http查询订单判断业务逻辑)*
#### 2、epg-order-service-internal(对内提供查询订单服务)*
#### 3、epg-order-service-page(页面订单查询服务)*

---

## epg-share(分账订单)
### 1、epg-share-common(model)
### 2、epg-share-api(dubbo接口)
### 3、epg-share-service(具体实现)
#### 0、epg-share-service-base(支付具体实现服务基础版，所有请求都会打到这个服务)*
#### 1、epg-share-service-wx(微信支付具体实现服务，限定V2XML)*
#### 2、epg-share-service-wxv3(微信支付具体实现服务，限定V3JSON)*
#### 3、epg-share-service-alipay(支付宝支付具体实现服务)*
#### 4、epg-share-service-unionpay(银联支付具体实现服务)*
#### 5、epg-share-service-icbc(工行支付具体实现服务)*
#### 6、epg-share-service-dg(汇付天下-斗拱支付具体实现服务)*

---

## epg-front
### 1、epg-front-pay(支付对外服务，对外吐出http支付等接口)*
### 2、epg-front-receive(支付对外接收支付通知服务)*
### 3、epg-front-config(支付通道配置服务)*
### 4、epg-front-order(支付订单服务)*
### 5、epg-front-order-page(页面订单查询服务)*

---