# vertical-marquee-view
A react-native marquee(vertical) label component. 



## Anchors

1. [Desc](#desc)
2. [Install](#install)
3. [Usage](#usage)
4. [Props](#props)
5. [Update Log](#update-log)


## Desc

[Skip this part, go to **#Install**](#install)

This is a **vertical** marquee label. 
<!-- 
If you need a **horizontal** one, please use [react-native-lahk-marquee-label](https://github.com/cheng-kang/react-native-lahk-marquee-label). -->

Please refer to [vertical-marquee-view](https://github.com/kishor98100/vertical-marquee-view) for more detailed descrition.

**Note:**

- In Andorid, you can use both `width` or `flex` to layout the view.
- In iOS, use `width` to layout the view. `flex` layout is not supported.


## Install

```sh
npm install --save vertical-marquee-view 
```

## Usage

1. Import

```js
import VerticalMarqueeView from 'vertical-marquee-view ';
```

2. Use

```js
<VerticalMarqueeView
  duration={8000}
  text={'This is a Marquee Label.'}
  textStyle={{ fontSize: 13, color: 'white' }}
/>
```

or

```js
<VerticalMarqueeView
  speed={250}
  textStyle={{ fontSize: 13, color: 'white' }}
>
  This is a Marquee Label.
</VerticalMarqueeView>
```

## Props

- `children`: string, the text to show in the marquee. Alternative to `text`.
- `text`: string, the text to show in the marquee. Alternative to `children`.
- `duration`: number(unit: millisecond), the duration for the marquee to run one round. e.g. 6000 (for 6 seconds a round). Alternative to `speed`.
- `speed`: number(unit: px/s, px per second), the speed of the marquee. Alternative to `duration`.
- `bgViewStyle`: stylesheet object, background view component custom styles.
- `textStyle`: stylesheet object, text component custom styles.

## Update Log

### 2019.08.16 `Version 1.0.0`

- Dynamic Text Support: now you can use dynamic text with this component :D


