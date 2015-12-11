# React Reorderable (forked)

Current fork adds few properties and makes it possible to nest ReactReorderable components

## Properties

- `handle` - a selector, which provides the handle element
- `mode` - `grid` or `list`, `list` will work in the general case but `grid` is eventually smarter for grid layout
- `itemClassName` - reorderable item class name (defaults to 'react-reorderable-item')
- `activeItemClassName` - active reorderable item class name (defaults to 'react-reorderable-item-active')

## Events

- `onDragStart`
- `onDrag`
- `onDrop`
- `onChange`

# License

MIT
