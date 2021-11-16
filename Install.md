## Installation
Update Nodejs by typing this command line.
```sh
npm install
```

Install the necessary package with this command.
```sh
npm install -g sass
```

## Compiler
After each modification of the sass file, it is necessary to input this line.
```sh
sass scss/style.scss:css/style.css
```

## File Watcher
If you want to avoid typing the command every time, 
you can use a file watcher that will do it **automatically** for you.
> Select your sass program which is usually located in `C:\Users\{User}\AppData\Roaming\npm`

Put as argument the path of your destination css file.
```sh
$FileName$:$ProjectFileDir$/css/$FileNameWithoutExtension$.css
```
You can also put the path of your destination css map file.
```sh
$ProjectFileDir$/css/$FileNameWithoutExtension$.css:$FileNameWithoutExtension$.css.map
```

### All that remains is to discover the language and train yourself on your own projects. 

## Documentation
> [Read more](https://sass-lang.com/documentation/syntax) about Scss language

## Licence
MIT