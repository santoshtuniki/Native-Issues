### At each folder, define "name" in a package.json file

#### Inside screens folder in src:

    {
        "name": "@Screen"
    }

### Add the same to tsconfig.json

    {
        "compilerOptions": {
            "baseUrl": "./src",
            "paths": {
                "@Screen/*": ["screens/*"]
            }
        }
    }

### In metro.config.js

    const config = {
        resolver: {
            enableGlobalPackages: true,
        },
    };