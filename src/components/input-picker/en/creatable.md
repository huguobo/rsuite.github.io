### Creatable

<!--start-code-->

```js
/**
 * import data from
 * https://github.com/rsuite/rsuite.github.io/blob/master/src/resources/data/users.js
 */

const instance = (
  <div>
    <InputPicker creatable data={data} style={{ width: 224 }} />
    <hr />
    <InputPicker
      creatable
      data={data}
      style={{ width: 224 }}
      groupBy="role"
      placeholder="Group Select"
    />
  </div>
);
ReactDOM.render(instance);
```

<!--end-code-->
