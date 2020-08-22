![One Yellow UI](https://ibb.co/10Z0mxt)

> bulit on top of one Drark (https://github.com/atom/atom/tree/master/packages/one-dark-ui).


### Install

This theme comes bundled with Atom and can be activated by going to the __Settings > Themes__ section and selecting "One Dark" from the __UI Themes__ drop-down menu.


### Settings

In the theme settings you can:

- Change the __Font Size__ to scale the whole UI up or down.
- Choose between 3 __Tab Sizing__ modes.
- Hide the  __dock buttons__.

To make changes, go to `Settings > Themes > One Dark UI > Settings` or the cog icon next to the theme picker.


### Customize

It's also possible to resize only certain areas by adding the following to your `styles.less` (Use DevTools to find the right selectors):

```css
.theme-one-dark-ui {
  .tab-bar { font-size: 18px; }
  .tree-view { font-size: 14px; }
  .status-bar { font-size: 12px; }
}
```



