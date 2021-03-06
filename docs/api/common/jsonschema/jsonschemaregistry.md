
<header class="symbol-info-header"><h1 id="jsonschemaregistry">JsonSchemaRegistry</h1><label class="symbol-info-type-label class">Class</label><label class="api-type-label private" title="private">private</label></header>
<!-- summary -->
<section class="symbol-info"><table class="is-full-width"><tbody><tr><th>Module</th><td><div class="lang-typescript"><span class="token keyword">import</span> { JsonSchemaRegistry }&nbsp;<span class="token keyword">from</span>&nbsp;<span class="token string">"ts-express-decorators/lib/jsonschema/registries/JsonSchemesRegistry"</span></div></td></tr><tr><th>Source</th><td><a href="https://github.com/Romakita/ts-express-decorators/blob/v3.9.2/src//jsonschema/registries/JsonSchemesRegistry.ts#L0-L0">/jsonschema/registries/JsonSchemesRegistry.ts</a></td></tr></tbody></table></section>
<!-- overview -->


### Overview


<pre><code class="typescript-lang "><span class="token keyword">class</span> JsonSchemaRegistry <span class="token keyword">extends</span> <a href="#api/common/core/registry"><span class="token">Registry</span></a><<span class="token keyword">any</span><span class="token punctuation">,</span> Partial<<a href="#api/common/jsonschema/jsonschema"><span class="token">JsonSchema</span></a>>> <span class="token punctuation">{</span>
    <span class="token function">property</span><span class="token punctuation">(</span>target<span class="token punctuation">:</span> <a href="#api/common/core/type"><span class="token">Type</span></a><<span class="token keyword">any</span>><span class="token punctuation">,</span> propertyKey<span class="token punctuation">:</span> <span class="token keyword">string</span><span class="token punctuation">,</span> type<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">,</span> collectionType?<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">)</span><span class="token punctuation">:</span> <a href="#api/common/jsonschema/jsonschema"><span class="token">JsonSchema</span></a><span class="token punctuation">;</span>
    <span class="token function">required</span><span class="token punctuation">(</span>target<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">,</span> propertyKey<span class="token punctuation">:</span> <span class="token keyword">string</span><span class="token punctuation">,</span> value?<span class="token punctuation">:</span> <span class="token keyword">boolean</span><span class="token punctuation">)</span><span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">;</span>
    <span class="token function">getSchemaDefinition</span><span class="token punctuation">(</span>target<span class="token punctuation">:</span> <a href="#api/common/core/type"><span class="token">Type</span></a><<span class="token keyword">any</span>><span class="token punctuation">)</span><span class="token punctuation">:</span> JSONSchema6<span class="token punctuation">;</span>
<span class="token punctuation">}</span></code></pre>


<!-- Parameters -->

<!-- Description -->

<!-- Members -->







### Members



<div class="method-overview">
<pre><code class="typescript-lang "><span class="token function">property</span><span class="token punctuation">(</span>target<span class="token punctuation">:</span> <a href="#api/common/core/type"><span class="token">Type</span></a><<span class="token keyword">any</span>><span class="token punctuation">,</span> propertyKey<span class="token punctuation">:</span> <span class="token keyword">string</span><span class="token punctuation">,</span> type<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">,</span> collectionType?<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">)</span><span class="token punctuation">:</span> <a href="#api/common/jsonschema/jsonschema"><span class="token">JsonSchema</span></a></code></pre>
</div>




<hr/>



<div class="method-overview">
<pre><code class="typescript-lang "><span class="token function">required</span><span class="token punctuation">(</span>target<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">,</span> propertyKey<span class="token punctuation">:</span> <span class="token keyword">string</span><span class="token punctuation">,</span> value?<span class="token punctuation">:</span> <span class="token keyword">boolean</span><span class="token punctuation">)</span><span class="token punctuation">:</span> <span class="token keyword">any</span></code></pre>
</div>




<hr/>



<div class="method-overview">
<pre><code class="typescript-lang "><span class="token function">getSchemaDefinition</span><span class="token punctuation">(</span>target<span class="token punctuation">:</span> <a href="#api/common/core/type"><span class="token">Type</span></a><<span class="token keyword">any</span>><span class="token punctuation">)</span><span class="token punctuation">:</span> JSONSchema6</code></pre>
</div>








