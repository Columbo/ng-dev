# SimpleClass

Navigate to folder `\demos\samples\unit-tests`

Investigate `SimpleClass.ts` and `SimpleClass.spec.ts`

Find a list of matches at [Jasmine Docs](https://jasmine.github.io/api/edge/matchers.html)

Notice the First Test:

```typescript
it("contains 12 charactes", function() {
  expect(SimpleClass.sayHelloWorld().length).toEqual(12);
});
```

Run the Test using `ng test`

# VoucherValidator

Also investigate `voucher-validator.ts`:

There is an error in the implementation and one failing test. Find the error
