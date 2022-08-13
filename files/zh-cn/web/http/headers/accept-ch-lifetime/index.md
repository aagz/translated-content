---
title: Accept-CH-Lifetime
slug: Web/HTTP/Headers/Accept-CH-Lifetime
translation_of: Web/HTTP/Headers/Accept-CH-Lifetime
---
<div>{{HTTPSidebar}}{{securecontext_header}}{{SeeCompatTable}}</div>

<p>服务器设置<code><strong>Accept-CH-Lifetime</strong></code>标头以指定{{HTTPHeader("Accept-CH")}}标头值的持久性，该值指定客户端应在后续请求中包括哪些<a href="https://developer.mozilla.org/en-US/docs/Glossary/Client_hints">Client Hints</a>标头。</p>

<table class="properties">
 <tbody>
  <tr>
   <th scope="row">Header type</th>
   <td>{{Glossary("Response header")}}</td>
  </tr>
  <tr>
   <th scope="row">{{Glossary("Forbidden header name")}}</th>
   <td>?</td>
  </tr>
 </tbody>
</table>

<div class="blockIndicator note">
<p><strong>注意：</strong> <a href="https://developer.mozilla.org/en-US/docs/Glossary/Client_hints">Client Hints</a>只能在安全源（通过 TLS）上访问。所有安全的请求都应该持久化 Accept-CH 和 Accept-CH-Lifetime 头，以确保<a href="https://developer.mozilla.org/en-US/docs/Glossary/Client_hints">Client Hints</a>可靠地发送。</p>
</div>

<h2 id="语法">语法</h2>

<pre class="syntaxbox">Accept-CH-Lifetime: &lt;age&gt;
</pre>

<h2 id="示例">示例</h2>

<pre>Accept-CH: Viewport-Width, DPR
Accept-CH-Lifetime: 86400
</pre>

<h2 id="浏览器兼容性">浏览器兼容性</h2>

<p>{{Compat("http.headers.Accept-CH-Lifetime")}}</p>

<h2 id="参见">参见</h2>

<ul>
 <li>{{HTTPHeader("Accept-CH")}}</li>
 <li>{{HTTPHeader("Vary")}}</li>
</ul>