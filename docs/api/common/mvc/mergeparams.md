
<header class="symbol-info-header"><h1 id="mergeparams">MergeParams</h1><label class="symbol-info-type-label decorator">Decorator</label><label class="api-type-label express" title="express">express</label></header>
<!-- summary -->
<section class="symbol-info"><table class="is-full-width"><tbody><tr><th>Module</th><td><div class="lang-typescript"><span class="token keyword">import</span> { MergeParams }&nbsp;<span class="token keyword">from</span>&nbsp;<span class="token string">"ts-express-decorators"</span></div></td></tr><tr><th>Source</th><td><a href="https://github.com/Romakita/ts-express-decorators/blob/v3.9.2/src//mvc/decorators/class/mergeParams.ts#L0-L0">/mvc/decorators/class/mergeParams.ts</a></td></tr></tbody></table></section>
<!-- overview -->


### Overview


<pre><code class="typescript-lang ">function <span class="token function">MergeParams</span><span class="token punctuation">(</span>mergeParams?<span class="token punctuation">:</span> <span class="token keyword">boolean</span><span class="token punctuation">)</span><span class="token punctuation">:</span> Function<span class="token punctuation">;</span></code></pre>


<!-- Parameters -->

<!-- Description -->


### Description

Specify the behavior of the router controller.

```typescript
@Controller("/")
@MergeParams(true)
class MyCtrl {

}
```

Property | Description | Default
---|---|---
CaseSensitive | Enable case sensitivity. | Disabled by default, treating “/Foo” and “/foo” as the same.
MergeParams | Preserve the req.params values from the parent router. If the parent and the child have conflicting param names, the child’s value take precedence. | false
Strict | Enable strict routing. | Disabled by default, “/foo” and “/foo/” are treated the same by the router.

<!-- Members -->

