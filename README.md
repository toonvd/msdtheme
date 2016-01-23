# msdtheme

A theme for the new Magestackday website!

## Define theme
- open dev/tools/grunt/configs/themes.js
- add after luma block
```
    msd: {
        area: 'frontend',
        name: 'Msd/default',
        locale: 'en_US',
        files: [
            'css/styles-m',
            'css/styles-l'
        ],
        dsl: 'less'
    },
```

