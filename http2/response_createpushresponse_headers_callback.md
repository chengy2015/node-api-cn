<!-- YAML
added: v8.4.0
-->

Call [`http2stream.pushStream()`][] with the given headers, and wraps the
given newly created [`Http2Stream`] on `Http2ServerResponse`.

The callback will be called with an error with code `ERR_HTTP2_INVALID_STREAM`
if the stream is closed.

