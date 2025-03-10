# svelte-maplibre

## 0.3.5

### Patch Changes

- [#54](https://github.com/dimfeld/svelte-maplibre/pull/54) [`e5d8a09`](https://github.com/dimfeld/svelte-maplibre/commit/e5d8a0957c0b73ff65ed7b4a91d77d79a6b057c8) Avoid clobbering MapLibre's added classes on Marker elements

- [#54](https://github.com/dimfeld/svelte-maplibre/pull/54) [`e5d8a09`](https://github.com/dimfeld/svelte-maplibre/commit/e5d8a0957c0b73ff65ed7b4a91d77d79a6b057c8) Support `draggable` and drag events on MarkerLayer

- [#55](https://github.com/dimfeld/svelte-maplibre/pull/55) [`7b94240`](https://github.com/dimfeld/svelte-maplibre/commit/7b9424077c4797386b9f6adbd3e2dcc61b48b6b6) Allow disabling zoom on double click

- [#55](https://github.com/dimfeld/svelte-maplibre/pull/55) [`7b94240`](https://github.com/dimfeld/svelte-maplibre/commit/7b9424077c4797386b9f6adbd3e2dcc61b48b6b6) Support dblclick and contextmenu events on layesrs and markers

- [#56](https://github.com/dimfeld/svelte-maplibre/pull/56) [`3cec7bf`](https://github.com/dimfeld/svelte-maplibre/commit/3cec7bf9441a6dfb7d2d648a5b27b456d9fd2837) Handle updates to the MapLibre component's `style` prop

## 0.3.4

- Support 2-way binding for `latLng` on draggable markers.
- Add `eventsIfTopMost` to Layers, to only fire mouse events if the layer is the top-most layer under the mouse pointer.

## 0.3.3

- Support `draggable` on `Marker`

## 0.3.2

- Properly manage hover state on features with ID `0`

## 0.3.1

- Lazily load deck.gl library so that the rest of the package can be used without including it.

## 0.3.0

- Support Svelte 4
- Upgrade to fully-released version of MapLibre GL 3.0

## 0.2.2

- Support `transformRequest` property on Map component.

## 0.2.1

- Fix layers not removing while data sources elsewhere in the map are loading
