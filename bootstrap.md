# To get started...
1. install node.js
2. npm init -y
3. npm install --save-dev typescript
4. Update the tsconfig.json with
{
  "compilerOptions": {
    "module": "commonjs",
    "esModuleInterop": true,
    "target": "es6",
    "moduleResolution": "node",
    "sourceMap": true,
    "outDir": "dist"
  },
  "lib": ["es2015"]
}
