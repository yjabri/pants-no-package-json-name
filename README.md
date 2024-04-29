Running `pants tailor ::`

populates `foo/BUILD` with 

```

package_json()
```

Running `pants tailor ::` again results in

```
$ pants tailor ::
14:56:17.68 [ERROR] 1 Exception encountered:

Engine traceback:
  in `tailor` goal

KeyError: 'name'
```