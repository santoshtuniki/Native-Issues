#### no babel config file detected for index.js. either disable config file checking with requireconfigfile: false, or configure babel so that it can find the config files

##### Add in .eslintrc file

        parser: '@babel/eslint-parser',

        parserOptions: {
            requireConfigFile: false,
        }