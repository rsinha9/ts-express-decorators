
<header class="symbol-info-header"><h1 id="httpserver">HttpServer</h1><label class="symbol-info-type-label decorator">Decorator</label></header>
<!-- summary -->
<section class="symbol-info"><table class="is-full-width"><tbody><tr><th>Module</th><td><div class="lang-typescript"><span class="token keyword">import</span> { HttpServer }&nbsp;<span class="token keyword">from</span>&nbsp;<span class="token string">"ts-express-decorators"</span></div></td></tr><tr><th>Source</th><td><a href="https://github.com/Romakita/ts-express-decorators/blob/v3.9.2/src//server/decorators/httpServer.ts#L0-L0">/server/decorators/httpServer.ts</a></td></tr></tbody></table></section>
<!-- overview -->


### Overview


<pre><code class="typescript-lang ">type HttpServer = Http.Server & <a href="#api/common/server/ihttpfactory"><span class="token">IHttpFactory</span></a><span class="token punctuation">;</span>
function <span class="token function">HttpServer</span><span class="token punctuation">(</span>target<span class="token punctuation">:</span> <a href="#api/common/core/type"><span class="token">Type</span></a><<span class="token keyword">any</span>><span class="token punctuation">,</span> targetKey<span class="token punctuation">:</span> <span class="token keyword">string</span><span class="token punctuation">,</span> descriptor<span class="token punctuation">:</span> TypedPropertyDescriptor<Function> | <span class="token keyword">number</span><span class="token punctuation">)</span><span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">;</span></code></pre>


<!-- Parameters -->

<!-- Description -->


### Description

Inject the Http.Server instance.

### Example

```typescript
import {HttpServer, Service} from "ts-express-decorators";

@Service()
export default class OtherService {
   constructor(@HttpServer httpServer: HttpServer) {}
}
```

> Note: TypeScript transform and store `ExpressApplication` as `Function` type in the metadata. So to inject a factory, you must use the `@Inject(type)` decorator.

<!-- Members -->

