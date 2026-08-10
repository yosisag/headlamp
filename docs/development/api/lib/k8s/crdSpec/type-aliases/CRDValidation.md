# Type Alias: CRDValidation

```ts
type CRDValidation = 
  | {
  missing: [];
  ok: true;
  usableVersions: UsableCRDVersion[];
}
  | {
  missing: MissingFieldId[];
  ok: false;
  usableVersions: UsableCRDVersion[];
};
```

Defined in: [lib/k8s/crdSpec.ts:79](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/crdSpec.ts#L79)

Result returned by `validateCRDSpec`. Discriminated on `ok` so callers can
pattern-match without separately inspecting `missing.length`.
