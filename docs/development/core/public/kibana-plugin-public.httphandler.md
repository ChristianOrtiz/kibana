<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-public](./kibana-plugin-public.md) &gt; [HttpHandler](./kibana-plugin-public.httphandler.md)

## HttpHandler type

A function for making an HTTP requests to Kibana's backend. See [HttpFetchOptions](./kibana-plugin-public.httpfetchoptions.md) for options and [HttpBody](./kibana-plugin-public.httpbody.md) for the response.

<b>Signature:</b>

```typescript
export declare type HttpHandler = (path: string, options?: HttpFetchOptions) => Promise<HttpBody>;
```