<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [tough-cookie](./tough-cookie.md) &gt; [Store](./tough-cookie.store.md) &gt; [removeCookie](./tough-cookie.store.removecookie_1.md)

## Store.removeCookie() method

Remove a cookie from the store (see notes on `findCookie` about the uniqueness constraint).

**Signature:**

```typescript
removeCookie(domain: Nullable<string>, path: Nullable<string>, key: Nullable<string>, callback: ErrorCallback): void;
```

## Parameters

<table><thead><tr><th>

Parameter


</th><th>

Type


</th><th>

Description


</th></tr></thead>
<tbody><tr><td>

domain


</td><td>

[Nullable](./tough-cookie.nullable.md)<!-- -->&lt;string&gt;


</td><td>

The cookie domain to match against.


</td></tr>
<tr><td>

path


</td><td>

[Nullable](./tough-cookie.nullable.md)<!-- -->&lt;string&gt;


</td><td>

The cookie path to match against.


</td></tr>
<tr><td>

key


</td><td>

[Nullable](./tough-cookie.nullable.md)<!-- -->&lt;string&gt;


</td><td>

The cookie name to match against.


</td></tr>
<tr><td>

callback


</td><td>

[ErrorCallback](./tough-cookie.errorcallback.md)


</td><td>

A function to call when the cookie has been removed or an error occurs.


</td></tr>
</tbody></table>
**Returns:**

void
