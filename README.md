## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Opens [http://localhost:3000] to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm install`

Installs all dependencies required to run the app.



## Standards

### BEM modified for SCSS

We apply the use of BEM modified for SCSS when writing stylesheet. Example:

```
.class {
  &__nested {
    &__deep {
      width: 100%;
      height: 100%;
      
      &--modifier {
        background-color: green;
      }
    }
  }
}
```

For further reading, check [https://www.joeforshaw.com/blog/writing-scss-with-bem] or [http://getbem.com/introduction/] for documentation.
