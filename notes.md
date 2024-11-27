###TS

#### READONLY 

```
type User = {
  readonly _id: string;
}
```
Em casos de array:

```readonly scores : readonly numbers[]```

ou usando o ReadonlyArray<T>

```let a: ReadonlyArray<number> = [1, 2, 3];```

#### Optional

Torna aquela variável opcional

type User = {
  _id: string;
  name?: string;
}