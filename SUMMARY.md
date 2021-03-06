# Table of contents

* [序言](README.md)

## 简介 <a id="summary"></a>

* [Knative 简介](summary/knative-concept.md)

## 1. 安装部署 <a id="01deploy"></a>

* [kubernetes 安装](01deploy/k8s-install.md)
* [isito 安装](01deploy/isito-install.md)
* [Knative 安装](01deploy/knative-install.md)
* [Nats 安装（选装）](01deploy/nats-an-zhuang-xuan-zhuang.md)

## 2. 用户指南 <a id="user-guide"></a>

* [cli 工具](user-guide/untitled.md)
* [Knative 商业化版本](user-guide/knative-shang-ye-hua-ban-ben.md)
* [Knative Serving 用户指南](user-guide/knative-serving-pei-zhi-zhi-nan/README.md)
  * [第一个 Serving 用例 Hello world](user-guide/knative-serving-pei-zhi-zhi-nan/di-yi-ge-yong-li.md)
  * [为 Knative Service 配置私有镜像仓库](user-guide/knative-serving-pei-zhi-zhi-nan/wei-knative-service-pei-zhi-si-you-jing-xiang-cang-ku.md)

## 2. Serving <a id="02serving"></a>

* [功能及配置](02serving/config.md)
* [自动扩缩容 KPA 配置](02serving/zi-dong-kuo-suo-rong-kpa-pei-zhi/README.md)
  * [基于流量请求数实现服务自动扩缩容](02serving/zi-dong-kuo-suo-rong-kpa-pei-zhi/ji-yu-liu-liang-qing-qiu-shu-shi-xian-fu-wu-zi-dong-kuo-suo-rong.md)
  * [在Knative中使用HPA](02serving/zi-dong-kuo-suo-rong-kpa-pei-zhi/zai-knative-zhong-shi-yong-hpa.md)
* [核心组件](02serving/component/README.md)
  * [autoscaler](02serving/component/autoscaler.md)
  * [activator](02serving/component/activator.md)
  * [controller](02serving/component/controller.md)
  * [webhook](02serving/component/webhook.md)
  * [networking-certmanager](02serving/component/networking-certmanager.md)
  * [networking-istio](02serving/component/networking-istio.md)
* [资源对象](02serving/resource.md)

## 3. Eventing <a id="03eventing"></a>

* [CloudEvents](03eventing/cloudevents.md)
* [功能及配置](03eventing/gong-neng-ji-pei-zhi.md)
* [核心组件](03eventing/he-xin-zu-jian.md)
* [资源对象](03eventing/zi-yuan-dui-xiang.md)

## 4. knative 可观测性 <a id="04observe"></a>

* [Untitled](04observe/untitled.md)

## 5. 性能测试 <a id="xing-neng-ce-shi"></a>

* [Untitled](xing-neng-ce-shi/untitled.md)

## 6. 源码解读 <a id="05code-read"></a>

* [activator](05code-read/untitled-1.md)

## 7.进阶开发 <a id="advanced-development"></a>

* [如何基于 Knative 开发 自定义controller](advanced-development/custom-controller.md)
* [如何利用 Google 开源工具 Ko 在 kubernetes 上构建并部署 Go 应用](advanced-development/ko-dev.md)

## 8. knative 实践案例 <a id="06practice"></a>

* [GRPC示例](06practice/untitled.md)

