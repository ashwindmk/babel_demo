# Babel CLI

### Pre-requisite

NPM


### Steps

**1. Install Babel**
```
npm install @babel/core @babel/preset-env @babel/cli --save-dev
```

**2. Set Babel Presets**

Create `/.babelrc` file.

```
{
    "presets": ["@babel/env"]
}
```

**3. Add Script**

Add script in `package.json` file.

```javascript
...
"scripts": {
    ...,
    "build": "babel src -d dist"
}
...
```

**4. Build**
```
npm run build
```
