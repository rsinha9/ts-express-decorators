
<header class="symbol-info-header"><h1 id="setconverter">SetConverter</h1><label class="symbol-info-type-label class">Class</label><label class="api-type-label private" title="private">private</label><label class="api-type-label converters" title="converters">converters</label><label class="api-type-label component" title="component">component</label></header>
<!-- summary -->
<section class="symbol-info"><table class="is-full-width"><tbody><tr><th>Module</th><td><div class="lang-typescript"><span class="token keyword">import</span> { SetConverter }&nbsp;<span class="token keyword">from</span>&nbsp;<span class="token string">"ts-express-decorators/lib/converters/components/SetConverter"</span></div></td></tr><tr><th>Source</th><td><a href="https://github.com/Romakita/ts-express-decorators/blob/v3.9.2/src//converters/components/SetConverter.ts#L0-L0">/converters/components/SetConverter.ts</a></td></tr></tbody></table></section>
<!-- overview -->


### Overview


<pre><code class="typescript-lang "><span class="token keyword">class</span> SetConverter <span class="token keyword">implements</span> <a href="#api/common/converters/iconverter"><span class="token">IConverter</span></a> <span class="token punctuation">{</span>
    <span class="token keyword">constructor</span><span class="token punctuation">(</span>converterService<span class="token punctuation">:</span> <a href="#api/common/converters/converterservice"><span class="token">ConverterService</span></a><span class="token punctuation">)</span><span class="token punctuation">;</span>
    deserialize<T><span class="token punctuation">(</span>data<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">,</span> target<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">,</span> baseType<span class="token punctuation">:</span> T<span class="token punctuation">,</span> deserializer<span class="token punctuation">:</span> <a href="#api/common/converters/ideserializer"><span class="token">IDeserializer</span></a><span class="token punctuation">)</span><span class="token punctuation">:</span> Set<T><span class="token punctuation">;</span>
    serialize<T><span class="token punctuation">(</span>data<span class="token punctuation">:</span> Set<T><span class="token punctuation">,</span> serializer<span class="token punctuation">:</span> <a href="#api/common/converters/iserializer"><span class="token">ISerializer</span></a><span class="token punctuation">)</span><span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">[</span><span class="token punctuation">]</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span></code></pre>


<!-- Parameters -->

<!-- Description -->


### Description

Converter component for the `Set` Type.

<!-- Members -->







### Members



<div class="method-overview">
<pre><code class="typescript-lang ">deserialize<T><span class="token punctuation">(</span>data<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">,</span> target<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">,</span> baseType<span class="token punctuation">:</span> T<span class="token punctuation">,</span> deserializer<span class="token punctuation">:</span> <a href="#api/common/converters/ideserializer"><span class="token">IDeserializer</span></a><span class="token punctuation">)</span><span class="token punctuation">:</span> Set<T></code></pre>
</div>




<hr/>



<div class="method-overview">
<pre><code class="typescript-lang ">serialize<T><span class="token punctuation">(</span>data<span class="token punctuation">:</span> Set<T><span class="token punctuation">,</span> serializer<span class="token punctuation">:</span> <a href="#api/common/converters/iserializer"><span class="token">ISerializer</span></a><span class="token punctuation">)</span><span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">[</span><span class="token punctuation">]</span></code></pre>
</div>








