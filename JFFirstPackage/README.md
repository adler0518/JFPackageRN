## Qunar React Native 基础组件

`react-native-jf-extension` 在 `react-native` 的基础上，新增和修改了许多基础组件和API。

### 使用

想要使用 `react-native-jf-extension` 提供的组件或API，方法如下：

```
import React, {Toast, Button, View, Text, AppRegistry} from 'react-native-jf-extension';
```

想要使用 `react-native` 提供的组件或API，方法如下：

```
import React, {Toast, Button, View, Text, AppRegistry} from 'react-native';
```

**当然，`react-native-jf-extension` 是基于 `react-native` 的，所以包含所有 `react-native` 提供的组件和API。所以，我们推荐大家直接使用 `react-native-jf-extension`。**

### 说明
react-native-jf-extension 是package中定义的名字。在index定义的别名jf-react-native `@providesModule jf-react-native`，引用的时候会找不到。

`providesModule` 是Facebook弄的一个东西 加了这个就可以直接import了，这个是Facebook自己弄的  所以自己写的node模块就不能这样写。


### 资料
https://reactnatve.wordpress.com/2016/06/16/alias-in-react-native/

