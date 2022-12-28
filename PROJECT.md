
# easy-pay-gateway
`带*的为真正的服务`

## epg-common-utils(支付公用model或工具类)

## epg-pay(支付、退款、撤单等行为)
### 1、epg-pay-common(model)
### 2、epg-pay-api(dubbo接口)
### 3、epg-pay-service(具体实现)*
### 4、epg-pay-data(支付相关操作数据库)

---

## epg-config(通道配置相关)
### 1、epg-config-common(model)
### 2、epg-config-api(dubbo接口)
### 3、epg-config-service(具体实现)*
### 4、epg-config-data(通道配置相关操作数据库)

---

## epg-order(支付订单)
### 1、epg-order-common(model)
### 2、epg-order-api(dubbo接口)
### 3、epg-order-service(具体实现)*

---

## epg-share(分账订单，待定)
### 1、epg-share-common(model)
### 2、epg-share-api(dubbo接口)
### 3、epg-share-service(具体实现)*

---

## epg-front
### 1、epg-front-pay(支付对外服务，对外吐出http支付等接口)*
### 2、epg-front-receive(支付对外接收支付通知服务)*
### 3、epg-front-config(支付通道配置服务)*
### 4、epg-front-order(支付订单服务)*

---