# Typescript
In the nextJS section - we looked at a basic nextJS app that was specifically Javascript. Lets build the same app again, but with Typescript support 

```
  npx create-next-app@latest --ts --no-eslint --no-tailwind  --app --import-alias "@/*" --src-dir 07-typescript 07-typescript
```

Now explore the files that are generated - note the different extensions. ts and tsx.

Typescript needs to know about some config - so you will have a file called tsconfig.json - Usually you wont need to touch anything as as once it is setup its good to go (usually). the nextJS wizard sets it up for you. 


Lets talk about types!

Open layout.tsx, and inspect the metadata variable - compare how it is different between the 06-nextjs version and the 07-typescript version. in the typescript verison, there is an extra bit of definition `Metadata` this indicates the type.i.e. the type of `metadata` is `Metadata` 

While not a requirement, it is a convention that type definitions have 

