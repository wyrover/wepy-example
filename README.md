# wepy-example


```
npm install -g wepy-cli 
wepy init standard wepy-example
cd wepy-example
npm install
wepy build --watch
```

΢�ſ����߹���Ŀ¼ָ�� wepy-example������ָ�� wepy-example/dist


����Ȼ��Ԥ�����ֻ�΢��ɨ���ά�룬���ֻ���Ԥ��Ӧ��


vscode �� webpy-example ���Դ��Ŀ¼

wepy ��һ���� vue �Ŀ�ܣ����˽��ܵ���������


�ű��Ľṹ
``` js

import wepy from 'wepy'

@connect()

export default class Index extends wepy.page {
    config = {},            // ����ȫ�ֱ���
    components = {},        // ע�����
    mixins = {},            
    data = {},              // �ɰ�����
    computed = {},
    methods = {},           // ��Ӧ����
    events = {},            // �¼�
    onLoad() {              // ��ʼ��
    }
}

```