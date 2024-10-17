# WeiboCommentCrawl
reference: https://github.com/SellWatermelonMan/WeiBoCrawler

## 安装依赖

```python
pip install -r requirements.txt
```

## 话题

话题需要用两个 `##` 间隔，例子如下

\#胖猫事件\#

## 类型

类型有 综合，实时，热门，高级 四种方式，对应微博的四种检索方式

## 具体运行方法
运行`main.ipynb` 查看输出结果

## Cookie 获取方法
以火狐浏览器为例，`F12`或者打开Web开发者工具（在右上角三条杠-更多工具-Web开发者工具），找到一个发送到`weibo.com`的Get请求，在请求头（Request headers）中下拉找到Cookie并复制
![image](https://github.com/user-attachments/assets/d096324b-04d7-43e7-bb66-6b5cd736bcb2)
