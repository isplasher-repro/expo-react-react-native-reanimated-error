These steps were taken to create this repro:
1. Install expo as per their docs
2. Install the package as per docs
3. Add `components/Header.tsx` that uses the package
4. Use component in `app/(tabs)/index`

Everything else is left as default.

Running `npm start -- --reset-cache` will result in the following error:
```
TypeError: Cannot assign to read only property 'message' of object 'SyntaxError: unknown: Support for the experimental syntax 'jsx' isn't currently enabled (13:14)
