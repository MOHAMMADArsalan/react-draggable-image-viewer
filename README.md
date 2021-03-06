# react-draggable-image-viewer

**React Draggable image zoom component**
A slack like image viewer for react.

<p align="center">
  <img src="https://raw.githubusercontent.com/MOHAMMADArsalan/react-draggable-image-viewer/master/Assets/demo1.png" width=600 alt="Demo 1">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/MOHAMMADArsalan/react-draggable-image-viewer/master/Assets/demo2.png" width=600 alt="Demo 2">
</p>

## Usage

Install the package using NPM:

```
npm install react-draggable-image-viewer --save
```

Add the component to your React application:

```jsx
import ImageView from "react-draggable-image-viewer";
import yourImage from "./path/to/image";

export default function ExampleComponent() {
  return <ImageView src=[yourImage] width={500} />;
}
```

## Configuration

| Prop             | Type          | Default    | Description                                                                                                                                                      |
| ---------------- | ------------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `images` (required) | Array of String | []          | URL/path of the large image                                                                                                                                      |
| `onHide`         | Function | `function() {}`   |   call when user click on close icon                                                                                                           |
| `isActive`          | Boolean| `false`   | will show and hide image view component                                                                                                                |
| `Draggable`      | Boolean        | `false`       | allow to drag image
| `activePhotoIndex`      | Number        | `0`       | start displaying image from given index
| `maxWidth`      | Number        | `300`       | max Width will be use for calculate image aspect ratio
| `maxHeight`      | Number        | `300`       | max Height will be use for calculate image aspect ratio


## Development

Requirements: Node.js, Yarn

1. Clone this repository: `git clone [repo-url]`
2. Install all dependencies: `yarn install`
3. Run `yarn start` to generate the library bundle using [Webpack](https://webpack.js.org/)

Suggestions and contributions are always welcome! Please first discuss changes via issue before submitting a pull request.
