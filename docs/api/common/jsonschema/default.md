
<header class="symbol-info-header"><h1 id="default">Default</h1><label class="symbol-info-type-label decorator">Decorator</label><label class="api-type-label ajv" title="ajv">ajv</label><label class="api-type-label jsonschema" title="jsonschema">jsonschema</label></header>
<!-- summary -->
<section class="symbol-info"><table class="is-full-width"><tbody><tr><th>Module</th><td><div class="lang-typescript"><span class="token keyword">import</span> { Default }&nbsp;<span class="token keyword">from</span>&nbsp;<span class="token string">"ts-express-decorators"</span></div></td></tr><tr><th>Source</th><td><a href="https://github.com/Romakita/ts-express-decorators/blob/v3.9.2/src//jsonschema/decorators/default.ts#L0-L0">/jsonschema/decorators/default.ts</a></td></tr></tbody></table></section>
<!-- overview -->


### Overview


<pre><code class="typescript-lang ">function <span class="token function">Default</span><span class="token punctuation">(</span>defaultValue<span class="token punctuation">:</span> <span class="token keyword">string</span> | <span class="token keyword">number</span> | <span class="token keyword">boolean</span> | <span class="token punctuation">{</span><span class="token punctuation">}</span><span class="token punctuation">)</span><span class="token punctuation">:</span> <span class="token punctuation">(</span>...parameters<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">[</span><span class="token punctuation">]</span><span class="token punctuation">)</span> => <span class="token keyword">any</span><span class="token punctuation">;</span></code></pre>


<!-- Parameters -->

<!-- Description -->


### Description

There are no restrictions placed on the value of this keyword.

This keyword can be used to supply a default JSON value associated with a particular schema.
It is RECOMMENDED that a default value be valid against the associated schema.

## Example

```typescript
class Model {
   @Default("10")
   property: string = "10";
}
```

Will produce:

```json
{
  "type": "object",
  "properties": {
    "property": {
      "type": "string",
      "default": "10"
    }
  }
}
```

<!-- Members -->

