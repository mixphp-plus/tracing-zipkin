## Mix Tracing Zipkin

Zipkin 调用链追踪库，基于 Opentracing 标准

## Usage

安装：

```
composer require mix-plus/tracing-zipkin
```

支持的 zipkin 版本：

- V3

# 使用
中间件直接引入
```php
$vega->use(\MixPlus\Tracing\Http\TracingWebServer::middleware());
```

文档：

- https://www.kancloud.cn/onanying/mixphp2-2/1712344

## License

Apache License Version 2.0, http://www.apache.org/licenses/
