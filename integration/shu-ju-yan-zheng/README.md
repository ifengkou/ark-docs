---
description: >-
  数据正确性和准确性是所有数据类产品的基础，没有这个基础，后续所有的分析功能都会大打折扣，甚至完全无法使用。另外，当您需要从原有系统迁移到易观方舟，或者您希望将易观方舟的数据同您原有的数据仓库的数据进行比对校验时，也常会遇到和自己所期望的数据结果不一致的情况。如果您遇到这些情况，请不要着急，这些问题非常正常，本文会提供一些步骤帮助您更快地找到问题的原因。
---

# 数据验证

{% hint style="info" %}
如果你正在使用易观方舟任何一个商业版本，并且遇到了数据不准的情况，请立即联系您的专属客户服务专家。我们非常重视客户数据的准确性问题，用户成功专家会全程协助您解决。
{% endhint %}

如果您倾向于自主验证数据，可参考以下5步来进行：

**第一步：**[**客户端埋点检查**](sdk-verification.md)\*\*\*\*

很多的数据问题都是因为客户端埋点不正确引起的。所以首先应该从源头触发进行检查。主要检查点为：

1. 是否覆盖了所有涉及到的页面
2. 是否覆盖了位于不同页面的相同事件
3. 数据是否能正常发送
4. 是否因为页面跳转导致有些事件不能完全上报
5. 是否包含了更适合在服务端上报的事件

**第二步：来源一致性检查**

在同原有数据分析平台或数据仓库对比数据时常会遇到某些指标偏差很大的情况。这时我们首先应检查两个数据平台的数据来源是否一致。大多数时候方舟的数据都来自于客户端的用户行为，如果其它平台的数据来源和易观方舟不一致，那么很可能两边得到的统计结果也不同。如果您正巧遇到了这种情况，建议您采用相同的数据上报方式。

**第三步：统计口径检查**

在同

**第四步：数据入库检查**



**第五步：基本指标检查**


