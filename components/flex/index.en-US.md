---
category: Components
group: Layout
title: Flex
description: A flex layout container for alignment.
cover: https://mdn.alipayobjects.com/huamei_7uahnr/afts/img/A*SMzgSJZE_AwAAAAAAAAAAAAADrJ8AQ/original
coverDark: https://mdn.alipayobjects.com/huamei_7uahnr/afts/img/A*8yArQ43EGccAAAAAAAAAAAAADrJ8AQ/original
tag: 5.10.0
---

## When To Use

- Good for setting spacing between elements.
- Suitable for setting various horizontal and vertical alignments.

### Difference with Space component

- Space is used to set the spacing between inline elements. It will add a wrapper element for each child element for inline alignment. Suitable for equidistant arrangement of multiple child elements in rows and columns.
- Flex is used to set the layout of block-level elements. It does not add a wrapper element. Suitable for layout of child elements in vertical or horizontal direction, providing more flexibility and control.

## Examples

<!-- prettier-ignore -->
<code src="./demo/basic.tsx">Basic</code>
<code src="./demo/align.tsx">Align</code>
<code src="./demo/gap.tsx">Gap</code>
<code src="./demo/wrap.tsx">Wrap</code>
<code src="./demo/combination.tsx">Combination</code>
<code src="./demo/debug.tsx" debug>Debug</code>

## API

> This component is available since `antd@5.10.0`. The default behavior of Flex in horizontal mode is to align upward. In vertical mode, it aligns to stretch. You can adjust this via properties.

Common props ref: [Common props](/docs/react/common-props)

| Property  | Description                                                                 | Type                                                                 | Default  | Version |
|-----------|-----------------------------------------------------------------------------|----------------------------------------------------------------------|----------|---------|
| vertical  | Is direction of the flex vertical, use `flex-direction: column`             | boolean                                                              | `false`  |         |
| wrap      | Sets whether the child elements wrap onto multiple lines or stay on a single line | [flex-wrap](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-wrap) \| boolean | `nowrap` | 5.17.0  |
| justify   | Sets the alignment of elements in the direction of the main axis            | [justify-content](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content) | `normal` |         |
| align     | Sets the alignment of elements in the direction of the cross axis           | [align-items](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items) | `normal` |         |
| flex      | Flex CSS shorthand properties                                               | [flex](https://developer.mozilla.org/en-US/docs/Web/CSS/flex)         | `normal` |         |
| gap       | Sets the gap between grids                                                  | `small` \| `middle` \| `large` \| string \| number                    | -        |         |
| component | Custom element type                                                         | React.ComponentType                                                  | `div`    |         |

## Design Token

<ComponentTokenTable component="Flex"></ComponentTokenTable>
