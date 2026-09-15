# 이미지 / 마스크 처리

모든 오브젝트는 가려지거나 잘린 곳 없는 '완전한 형태'여야 고품질 결과물이 나옵니다.

#### **✅ DO**

▶ 잘린 단면이 없는 온전한 이미지 소스를 사용하세요.

{% columns %}
{% column %}
<figure><img src="../../.gitbook/assets/image (104).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column %}
<figure><img src="../../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}
{% endcolumns %}

#### **❌ DON'T**

▶ AI가 잘린 신체나 제품의 일부를 스스로 그려주지는 않습니다.

{% columns %}
{% column %}
<figure><img src="../../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column %}
<figure><img src="../../.gitbook/assets/image (107).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}
{% endcolumns %}



#### **✅ DO**

▶ 배너 끝에 맞닿아 있는 이미지는 정확히 잘라내야(Attach) 합니다.

{% columns %}
{% column %}
<figure><img src="../../.gitbook/assets/image (108).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column %}
<figure><img src="../../.gitbook/assets/image (109).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}
{% endcolumns %}

#### **❌ DON'T**

▶ 잘린 이미지를 다른 요소로 덮어서 가릴 경우, 리사이즈 과정에서 가려졌던 잘린 단면이 그대로 노출될 수 있습니다.

{% columns %}
{% column %}
<figure><img src="../../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column %}
<figure><img src="../../.gitbook/assets/image (111).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}
{% endcolumns %}

{% hint style="warning" %}
그룹 마스크 주의: 여러 요소를 하나의 마스크로 묶으면 개별 이동이 불가능해집니다.
{% endhint %}

#### **✅ DO**

▶ 효과가 필요할 땐 레이어별 개별 마스크를 활용하세요.

{% columns %}
{% column %}
<figure><img src="../../.gitbook/assets/image (112).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column %}
<figure><img src="../../.gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}
{% endcolumns %}

#### **❌ DON'T**

▶ 배너 전체를 덮는 전역 마스크나 복잡한 그룹 마스크를 사용하지 마세요.\
리사이즈 시 마스크 위치가 어긋나 디자인이 깨질 수 있습니다.

{% columns %}
{% column %}
<figure><img src="../../.gitbook/assets/image (114).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column %}
<figure><img src="../../.gitbook/assets/image (115).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}
{% endcolumns %}
