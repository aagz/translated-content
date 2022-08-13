---
title: Server
slug: Web/HTTP/Headers/Server
tags:
  - 安全
  - 服务器
  - 软件
  - 首部
translation_of: Web/HTTP/Headers/Server
---
<div>{{HTTPSidebar}}</div>

<p><code><strong>Server</strong></code> 首部包含了处理请求的源头服务器所用到的软件相关信息。</p>

<p>应该避免使用过长或者过于详细的描述作为 Server 的值，因为这有可能泄露服务器的内部实现细节，有利于攻击者找到或者探测已知的安全漏洞。</p>

<table class="properties">
 <tbody>
  <tr>
   <th scope="row">Header type</th>
   <td>{{Glossary("Response header")}}</td>
  </tr>
  <tr>
   <th scope="row">{{Glossary("Forbidden header name")}}</th>
   <td>no</td>
  </tr>
 </tbody>
</table>

<h2 id="语法">语法</h2>

<pre class="syntaxbox">Server: &lt;product&gt;
</pre>

<h2 id="指令">指令</h2>

<dl>
 <dt>&lt;product&gt;</dt>
 <dd>处理请求的软件或者产品（或组件产品）的名称。</dd>
</dl>

<h2 id="示例">示例</h2>

<pre>Server: Apache/2.4.1 (Unix)</pre>

<h2 id="规范">规范</h2>

{{Specifications}}

<h2 id="浏览器兼容性">浏览器兼容性</h2>

<p>{{Compat}}</p>

<h2 id="相关内容">相关内容</h2>

<ul>
 <li>{{HTTPHeader("Allow")}}</li>
</ul>