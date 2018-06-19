# vue-district-picker

## install

npm install --save vue-district-picker

## Use

```
import VueDistrictPicer from 'vue-district-picker';

Vue.use(VueDistrictPicer)

<vue-district-picker :show.sync="show" @confirm="confirm" :citydata="citydata"></vue-district-picker>
```


## props

```
{
    // 省市区数据
    citydata: {
      type: Object
    },
    // 双向绑定显示隐藏
    show: {
      type: Boolean,
      default: false
    },
    zIndex: [Number],

    //初始化数据（对应省市区数据ID）
    areaData: {
      type: Array,
      default: () => {
        return ["340000", "340100", "340103"]
      }
}
```


