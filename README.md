# Legend Motion

Legend Motion is a declarative animations library for React Native, to make it easy to transition between styles without needing to manage animations.

`npm install @legendapp/motion` or `yarn add @legendapp/motion`

```jsx
import { Motion } from "@legendapp/motion"

<Motion.View
    initial={{ scale: 0.5 }}
    animate={{ scale: value ? 1 : 0.5 }}
 />
```

<a href="https://www.youtube.com/watch?v=cV8whnjLFFU"><img src="https://www.legendapp.com/img/legend-motion-video.png" width="300" /></a>


## Highlights

- ✨ Supports react-native and react-native-web
- ✨ API similar to Framer Motion for easy mixing of React Native Web with React
- ✨ Supports animating SVG and linear gradient
- ✨ Supports transformOrigin
- ✨ 0 dependencies using the built-in Animated
- ✨ Built for maximum performance
- ✨ Strongly typed with TypeScript

## 📖 Docs

The full documentation with live examples is on our [website](https://www.legendapp.com/dev/motion).

## 👩‍⚖️ License

[MIT](LICENSE)

---

Legend Motion is created and maintained by [Jay Meistrich](https://github.com/jmeistrich) with [Legend](https://www.legendapp.com) and [Bravely](https://www.bravely.io).

<p>
    <a href="https://www.legendapp.com"><img src="https://www.legendapp.com/img/LogoTextOnWhite.png" height="56" alt="Legend" /></a>
    <span>&nbsp;&nbsp;&nbsp;&nbsp;</span>
    <a href="https://www.bravely.io"><img src="https://www.legendapp.com/img/bravely-logo.png" height="56" alt="Bravely" /></a>
</p>
