# Donate3

This is an example component.

```jsx
import { Donate3 } from 'donate3-sdk';

const config = {
  type: 'embed', // 0 Float mode，1 Normal mode float\embed
  color: "#666",
  title: "0xhardman",
  toAddress: "0xb15115A15d5992A756D003AE74C0b832918fAb75",
  demo:false
}
export default () => <Donate3 config={...config}/>
// const renderDonate3 = (domElement: HTMLElement | null, config: Props) => {
//   if (!domElement) throw new Error("Your DOM id is incorrect");

//   const root = ReactDOM.createRoot(domElement as HTMLElement);
//   root.render(<UFO config={config} />);
// };

// (window as any).renderDonate3 = renderDonate3;

// renderDonate3(document.getElementById("donate3_root"), config);
```
