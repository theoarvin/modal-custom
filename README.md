# Modal Components by theo arvin


## Getting Started

Install this package:

```shell
npm install modal-theoab
```

Import the Counter component:

```js
import { Modal } from "modal-theoab";
```

then you need to call the Modal component with two props  . 

```js
<Modal openModal={openModal} setOpenModal={setOpenModal}/>
```

- openModal is a boolean that checks if the modal is open.

- setOpenModal is a function that modifies the value of openModal to close the Modal directly with a close in the component
