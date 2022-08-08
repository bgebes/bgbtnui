# bgbtnui

> Made with create-react-library

[![NPM](https://img.shields.io/npm/v/bgbtnui.svg)](https://www.npmjs.com/package/bgbtnui) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save bgbtnui
```

## Usage

```jsx
import React, { Component } from 'react'

import { Button } from 'bgbtnui'
import 'bgbtnui/dist/index.css'

class Example extends Component {
  render() {
    return (
      <>
        <Button type='b-primary'>Primary Button</Button>
        <Button type='b-default'>Default Button</Button>
        <Button type='b-dashed'>Dashed Button</Button>
        <br />
        <Button type='b-text'>Text Button</Button>
        <Button type='b-link' href='...'>
          Link Button
        </Button>
      </>
    )
  }
}
```

## License

MIT © [bgebes](https://github.com/bgebes)
