测试
# PayDatePick

`import { TimeInfo } from '@tencent/wxpay-finance-component/types/PayDatePick.interface'`

## Props

<!-- @vuese:PayDatePick:props:start -->
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|defaultTime|默认时间|`String`|`false`|-|
|timepicker|兼容时间选择器|`boolean`|`false`|false|
|closeOnTimeSelect|选中日期后是否关闭弹框|`boolean`|`false`|false|
|format|日期格式|`string`|`false`|Y-m-d|

<!-- @vuese:PayDatePick:props:end -->


## Events

<!-- @vuese:PayDatePick:events:start -->
|Event Name|Description|Parameters|
|---|---|---|
|onDataPickChange|选中日期后触发|(val: TimeInfo)|

<!-- @vuese:PayDatePick:events:end -->


