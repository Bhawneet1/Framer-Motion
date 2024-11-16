## Best for React Animation

# Search framer motion

# npm install motion

# Write in App.jsx
import {motion} from 'framer-motion'

# motion.element eg motion.div

# Code

``` JS
import React from 'react'
import {motion} from 'framer-motion'
const App = () => {
  
  return (
    <div>
      <motion.div
       initial={{
        x:300,
       }}
       animate={{//animation here
        x:1000,
        y:400,
        rotate:360,
       }}
       transition={{//time related things
        duration:2,
        delay:1,
        ease:"anticipate",
        repeat:Infinity,
       }}
       final={{
        x:400,
       }}
       
       id="box">

      </motion.div>
      <motion.h1></motion.h1>
    </div>
  )
}

export default App

```

# Code-2

``` Js
<div>
      <motion.div 
      drag//drag kar sakte hai
      dragConstraints={{
        top:0,
        left:0,
        //isi range mai rahega
        right:1000,
        bottom:300,
      }}
      dragDirectionLock='true'//ya x pae jaega ya y pae
      id="box"></motion.div>
    </div>

```

# code-3
