<p align="center">
  <img src="tocas-og.png">
</p>

&nbsp;

# Tocas UI 2

Tocas UI 是基於 SASS 和 CSS3 的元件框架，可快速建立大型或小型網站的介面，

其用法與 Bootstrap 差異甚多，Tocas UI 以不雜亂，有意義為主。

**可至：https://tocas-ui.com/ 觀看教學文件。**

&nbsp;

# 特色

1. 更簡潔，沒有像 Bootstrap 那樣**雜亂**的樣式名稱。（如：`.m-l-1`, `.p-x-2`, `.p-a-3`）

2. 以**意義**為樣式命名的主要精神。 

3. 以支援行動裝置為**優先**。

4. 更**加彈性的格線系統**，並達到 16 格線。 

5. 據有**回饋力**的動畫。

6. 元件之間可交互使用。

7. 模塊**不需要 jQuery**（耶！）。

&nbsp;

# 安裝

透過 `git` 安裝最新（測試版）。

```
$ git clone https://github.com/TeaMeow/TocasUI.git
```

透過 `git` 安裝正式版。

```
$ git clone https://github.com/TeaMeow/TocasUI.git
$ git fetch --tags
$ git tag -l
> v2.0.2
$ git checkout tags/v2.0.2
```

&nbsp;

# 範例

Tocas UI 的樣式命名方式來自於 Semantic UI 的精神，以意義為主。

```html
<!-- Tocas 大的 主要 按鈕 -->
<button class="ts big primary button"></button>
```

讓我們看看 Bootstrap 的樣式命名方式。

```html
<!-- 按鈕 按鈕-大的 按鈕-主要 -->
<button class="btn btn-lg btn-primary"></button>
```

&nbsp;

# 簡短，而且更有意義

讓我們展示一些更進階的用法，讓你清楚了解 Tocas UI 和 Bootstrap 之間的差異。

```html
<div class="ts menu">
    <a class="header item">商標</a>
    <a class="active item">首頁</a>
    <a class="item">特色</a>
    <a class="item">價格</a>
    <a class="item">關於</a>
</div>
```

而這是 Bootstrap。

```html
<nav class="navbar navbar-light bg-faded">
    <a class="navbar-brand">商標</a>
    <ul class="nav navbar-nav">
        <li class="nav-item active">
            <a class="nav-link">首頁</a>
        </li>
        <li class="nav-item">
            <a class="nav-link">特色</a>
        </li>
        <li class="nav-item">
            <a class="nav-link">價格</a>
        </li>
        <li class="nav-item">
            <a class="nav-link">關於</a>
        </li>
    </ul>
</nav>
```

&nbsp;

# 社群

## Pull Request

我們很高興接受任何 Pull Request（如果是新功能的話要符合相關理念 :D），

Commit 可以是英文或是中文（English is allowed :D），有時間就會去檢查。

&nbsp;

## 功能需求

可以開啟 Issue 來回報自己要的功能，最後會被標上可行或是不可行的標籤，

如果最終不可行的話還敬請見諒，但不要因此而停止提出建議喔 :D。

&nbsp;

## Bug 回報

一樣可以開啟 Issue 然後稍微敘述一下問題，有空就會去檢查。

&nbsp;

# 可參考文件

這裡是幾個可能會啟發你創意，或是更能讓你了解這類東西的連結。

[Amaze UI | 中国首个开源 HTML5 跨屏前端框架](http://amazeui.org/)

[Semantic UI](http://semantic-ui.com/)

[Bulma: a modern CSS framework based on Flexbox](http://bulma.io/)

[Bootstrap·The world's most popular mobile-first and responsive front-end framework.](http://v4-alpha.getbootstrap.com/)

[Kule Lazy 3](http://www.kule.tw/)

[Ant Design - 一个 UI 设计语言](http://ant.design/)

[Tapestry](http://tapestry.wisembly.com/)

[Kube](https://imperavi.com/kube/)

[BassCss](http://www.basscss.com/)

[Pure](http://purecss.io/)

[Milligram](https://milligram.github.io/)

[Element](http://element.eleme.io/)