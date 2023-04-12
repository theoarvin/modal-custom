# TypeScript Components by Rupert

This repository was created as part of a guide to publishing TypeScript React components. You can read the guide over here: [Publishing TypeScript React components to NPM](https://fildon.hashnode.dev/publishing-typescript-react-components-to-npm)

## Getting Started

Install this package:

```shell
npm add typescript-components-by-rupert
```

Import the Counter component:

```js
import { Modal } from "modal-custom-theoab";
```

then you need to call the Modal component with two props <Modal openModal={openModal} setOpenModal={setOpenModal}/> . 

### openModal is a boolean that checks if the modal is open.

### setOpenModal is a function that modifies the value of openModal to close the Modal directly with a close in the component
