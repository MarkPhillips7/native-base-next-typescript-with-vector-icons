# native-base-next-typescript-with-vector-icons

This repo demonstrates that an error occurs trying to use react-native-vector-icons in a Next.js app created from [this NativeBase template](https://github.com/GeekyAnts/nativebase-templates/tree/master/nextjs-with-native-base-typescript).

## How this repo got here

```bash
npx create-next-app -example https://github.com/GeekyAnts/nativebase-templates/tree/master/nextjs-with-native-base-typescript
cd native-base-next-typescript-with-vector-icons
npm install react-native-vector-icons --save
npm install @types/react-native-vector-icons --save-dev

```

Added a MaterialIcons icon in pages/index.tsx and got this error:

```bash
error - ./node_modules/react-native-vector-icons/lib/create-icon-set.js
Module parse failed: Unexpected token (91:8)
You may need an appropriate loader to handle this file type, currently no loaders are configured to process this file. See https://webpack.js.org/concepts#loaders
| 
|       return (
>         <Text {...props}>
|           {glyph}
|           {children}
```
