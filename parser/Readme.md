#### Parsing error: This experimental syntax requires enabling one of the following parser plugin(s): "jsx", "flow", "typescript".

1) Install in dev dependencies

        npm i --save-dev @babel/preset-react

2) Add in .eslintrc file

        "parser": "@babel/eslint-parser",
        "parserOptions": {
            "babelOptions": {
                "presets": ["@babel/preset-react"]
            },
        }
