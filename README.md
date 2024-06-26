<div align="center">
  <a href="https://splidejs.com" target="_blank">
      <img width="70" src="images/logo.svg">
  </a>
  <a href="https://reactjs.org/" target="_blank">
      <img width="70" src="images/react-logo.svg">
  </a>

  <h1>React Splide (Fork)</h1>
  <p><strong>***This is a fork of original react-splide exporting the types file***</strong></p>
  <p>
    React Splide is the React component for the
    <a href="https://github.com/Splidejs/splide">Splide</a> slider/carousel.
  </p>

  <p>
    <a href="https://splidejs.com/integration/react-splide/">Getting Started</a>
    <br>
    <a href="https://splidejs.com/">Demo</a>
    <br>
    <a href="https://github.com/Splidejs/splide/discussions">Discussions</a>
  </p>
</div>

## Quick Start

Get the latest version from NPM:

```
$ npm install react-splide-ts
```

Import CSS and components:

```jsx
import { Splide, SplideSlide } from "react-splide-ts";
import "react-splide-ts/css";

export function Slider() {
  return (
    <Splide options={{ rewind: true }} aria-label="React Splide Example">
      <SplideSlide>
        <img src="image1.jpg" alt="Image 1" />
      </SplideSlide>
      <SplideSlide>
        <img src="image2.jpg" alt="Image 2" />
      </SplideSlide>
    </Splide>
  );
}
```

Visit [here](https://splidejs.com/integration/react-splide/) for more details.

## Support Splide

Please support the project if you like it!

- [GitHub Sponsors](https://github.com/sponsors/NaotoshiFujita)

## License

React Splide and Splide are released under the MIT license.
© 2021 Naotoshi Fujita
