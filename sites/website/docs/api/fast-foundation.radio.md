---
id: fast-foundation.radio
title: Radio class
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[@microsoft/fast-foundation](./fast-foundation.md) &gt; [Radio](./fast-foundation.radio.md)

## Radio class

<b>Signature:</b>

```typescript
export declare class Radio extends FormAssociated<HTMLInputElement> implements RadioControl 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)()](./fast-foundation.radio._constructor_.md) |  | Constructs a new instance of the <code>Radio</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [checked](./fast-foundation.radio.checked.md) |  | <code>boolean</code> | The checked state of the control |
|  [checkedAttribute](./fast-foundation.radio.checkedattribute.md) |  | <code>boolean</code> | Provides the default checkedness of the input element Passed down to proxy |
|  [clickHandler](./fast-foundation.radio.clickhandler.md) |  | <code>(e: MouseEvent) =&gt; void</code> |  |
|  [defaultChecked](./fast-foundation.radio.defaultchecked.md) |  | <code>boolean</code> | Initialized to the value of the checked attribute. Can be changed independently of the "checked" attribute, but changing the "checked" attribute always additionally sets this value. |
|  [defaultSlottedNodes](./fast-foundation.radio.defaultslottednodes.md) |  | <code>Node[]</code> |  |
|  [keypressHandler](./fast-foundation.radio.keypresshandler.md) |  | <code>(e: KeyboardEvent) =&gt; void</code> |  |
|  [name](./fast-foundation.radio.name.md) |  | <code>string</code> |  |
|  [proxy](./fast-foundation.radio.proxy.md) |  | <code>HTMLInputElement</code> |  |
|  [readOnly](./fast-foundation.radio.readonly.md) |  | <code>boolean</code> |  |
|  [value](./fast-foundation.radio.value.md) |  | <code>string</code> | The element's value to be included in form submission when checked. Default to "on" to reach parity with input\[type="radio"\] |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [connectedCallback()](./fast-foundation.radio.connectedcallback.md) |  |  |
|  [nameChanged()](./fast-foundation.radio.namechanged.md) |  |  |
