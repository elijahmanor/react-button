# React Button
This repository is the code demo from my "Building Design Systems With React" talk I will give at [ReactJS Girls London](https://reactjsgirls.com/#speakers). I will link the deck once the talk has been given.

You can view the live site [here](react-button.netlify.com).

## Design

### Light Theme
![Buttons Light](https://user-images.githubusercontent.com/7671983/56490131-6d43ed00-64e4-11e9-8073-569517a1c5e9.jpg)

### Dark Theme
![Buttons Dark](https://user-images.githubusercontent.com/7671983/56490130-6d43ed00-64e4-11e9-906e-72ba20cfbf86.jpg)


## Properties
| Property        | Description                        | Type          | Required   |
| -------------   | :----------------------------------| :------------ | :--------- |
| `disabled`      | Sets the button to a disabled state| `boolean`     | false      |
| `icon    `      | Adds an icon to the button         | `IconType`    | false      |
| `label    `     | The button text                    | `string`      | true       |
| `onClickHandler`| The action to be dispatched onClick| `function`    | true       |
| `size`          | The size of the button             | `ButtonSizes` | false      |
| `theme`         | The theme for the button           | `ButtonThemes`| false      |
| `type`          | The type of button                 | `ButtonTypes` | false      |

## Types
| Type            | Values                           | Default      |
| -------------   | :--------------------------------| :----------- |
| `ButtonSizes`   | `SMALL` `MEDIUM` `LARGE`         | `MEDIUM`     |
| `ButtonThemes`  | `LIGHT` `DARK`                   | `LIGHT `     |
| `ButtonTypes`   | `PRIMARY` `SECONDARY` `TERTIARY` | `PRIMARY `   |
