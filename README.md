# µgolfjax

A pretty small ajax js library.

## Usage

```
µ(method, url, form, success, error)
```

<dl>
  <dt>method</dt><dd>HTTP verb, i.e. `'GET'`, `'POST'`, etc.</dd>
  <dt>url</dt><dd>The url to access.</dd>
  <dt>form</dt><dd>A form containing data to submit</dd>
  <dt>success</dt><dd>A callback that contains the returned data, which gets called on success.</dd>
  <dt>error</dt><dd>A callback that contains the returned data, which gets called on error.</dd>
</dl>
