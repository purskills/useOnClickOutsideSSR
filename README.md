# What is this?

useOutside Click Event on React JS projects and also NextJS project(for SSR)

# Install

`npm i use-onclickoutside-ssr --save`

Then ...

```
import React, { useRef } from "react";
import useOnClickOutsideSSR from "use-onclickoutside-ssr";

const App = () => {
    const ref = useRef();
    useOnClickOutside(ref, () => console.log("clicked outside"));

    return (
        <div ref={ref}>
            Hello World
        </div>
    )
}
```
