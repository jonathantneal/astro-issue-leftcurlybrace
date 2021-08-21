```js
// There is,
//      .cjs - Common JS Module
//      .mjs - Modern ES Module
//      .js - UMD
import { Manager } from "@okikio/manager";
import { Manager } from "https://unpkg.com/@okikio/manager";
import { Manager } from "https://cdn.jsdelivr.net/npm/@okikio/manager";
// Or
import { Manager } from "https://cdn.skypack.dev/@okikio/manager";

// Via script tag
<script src="https://unpkg.com/@okikio/manager/lib/api.js"></script>
// Do note, on the web you need to do this, if you installed it via the script tag:
const { Manager, methodCall } = window.manager;
// or
const { default: Manager, methodCall } = window.manager;
```
