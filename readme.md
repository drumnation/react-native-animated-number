# react-native-animated-number [![Travis Build Status](https://img.shields.io/travis/drumnation/react-native-animated-number.svg?style=flat-square)](https://travis-ci.org/drumnation/react-native-animated-number) [![David](https://img.shields.io/david/dev/drumnation/react-native-animated-number.svg?style=flat-square)](https://david-dm.org/drumnation/react-native-animated-number?type=dev) [![npm](https://img.shields.io/npm/dt/react-native-animated-number.svg?style=flat-square)](https://www.npmjs.com/package/react-native-animated-number)

> Animates numbers

## Install
```bash
$ npm install react-native-animated-number --save
```

## Usage
1. Add an import to the top of yur file
    ```js
    import AnimatedNumber from 'react-native-animated-number';
    ```
2. Declare the component in the render method of your component
    ```jsx
    render() {
        return (
            <AnimatedNumber
              hello={'Hello world!'}
             />
        )
    }
    ```
3. Take a look at the [example app](/tree/master/example).

## Component Props
| Property | Type     | Description             | Example     |
|----------|----------|-------------------------|-------------|
| hello    | `string` | The hello world message | `Hello 🦄!` |

## License
MIT © [drumnation](https://github.com/drumnation/react-native-animated-number)

---
# Generator Notes
👋🏽 Hello and thanks for using, [`generator-rnc`](https://github.com/brh55/generator-rnc)! <br>
Please feel free to report [bugs](https://github.com/brh55/generator-rnc/issues) or contribute useful features to the generator to help others.

Also, don't forget to include example an application for users to test out and use your component.

1. `react-native init example`

> 🗒 P.S: Don't forget to delete this note :)
