---
title: Set.prototype.add()
slug: Web/JavaScript/Reference/Global_Objects/Set/add
tags:
  - ECMAScript 2015
  - JavaScript
  - Method
  - Prototype
  - リファレンス
  - set
translation_of: Web/JavaScript/Reference/Global_Objects/Set/add
---
{{JSRef}}

**`add()`** メソッドは、特定の `value` をもつ新しい要素を `Set` オブジェクトの最後に追加します。

{{EmbedInteractiveExample("pages/js/set-prototype-add.html")}}

<div class="hidden">このデモのソースファイルは GitHub リポジトリに格納されています。デモプロジェクトに協力したい場合は、 <a href="https://github.com/mdn/interactive-examples">https://github.com/mdn/interactive-examples</a> をクローンしてプルリクエストを送信してください。</div>

<h2 id="Syntax" name="Syntax">構文</h2>

<pre class="syntaxbox notranslate"><var>mySet</var>.add(<var>value</var>);</pre>

<h3 id="Syntax" name="Syntax">引数</h3>

<dl>
 <dt>`<var>value</var>`</dt>
 <dd>`Set` オブジェクトに追加する要素の値です。</dd>
</dl>

<h3 id="Return_value" name="Return_value">返値</h3>

`Set` オブジェクトです。

<h2 id="Examples" name="Examples">例</h2>

<h3 id="Using_the_add_method" name="Using_the_add_method">add() メソッドの使用</h3>

<pre class="brush: js notranslate">var mySet = new Set();

mySet.add(1);
mySet.add(5).add('some text'); // メソッドチェーン

console.log(mySet);
// Set [1, 5, "some text"]
</pre>

<h2 id="Specifications" name="Specifications">仕様書</h2>

<table class="standard-table">
 <thead>
  <tr>
   <th scope="col">仕様書</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>{{SpecName('ESDraft', '#sec-set.prototype.add', 'Set.prototype.add')}}</td>
  </tr>
 </tbody>
</table>

<h2 id="Browser_compatibility" name="Browser_compatibility">ブラウザーの互換性</h2>

{{Compat("javascript.builtins.Set.add")}}

<h2 id="See_also" name="See_also">関連情報</h2>

<ul>
 <li>{{jsxref("Set")}}</li>
 <li>{{jsxref("Set.prototype.delete()")}}</li>
 <li>{{jsxref("Set.prototype.has()")}}</li>
</ul>