# Buttons

## **General guidelines**

* Button line height is 32px \(in the case of bordered buttons it includes top/bottom 1px\).
* Don't use multiple primary buttons in a single view.

## Spacing guidelines

![](../../.gitbook/assets/0%20%287%29.png)

* Buttons have left/right padding of 15px $medium-space \(except for link buttons, which have no padding\).
* Buttons contained in narrow spaces \(&gt;150px\) should fill 100% of the width available to them. This helps with cleaner alignment with other elements in that column, and also aligns multiple buttons when stacked.
* If multiple buttons are horizontally aligned, there should be a 20px margin separating them.

## **Animation**

* There is a subtle fade transition from normal to hover state on buttons.
* transition: all 0.2s;
* Loading animation inside the button corresponds to the loader definition

## **Disabled state**

* All button styles follow the same disabled state:
* No background color opacity, we use a color variable.
* All colors including text, border and any icon are @font-color-1 or @white

## **Content**

* An ideal button labeling has a {verb} + {noun} structure. A verb indicates the button is actionable while giving the idea about what to expect.
* Avoid generic labels like “OK”, “Cancel”, “Done” for buttons.

## Accessibility

* Use the ariaControls prop to add an aria-controls attribute to the button. Use the attribute to point to the unique id of the content that the button manages.
* Buttons use browser defaults for keyboard interactions.
* Give buttons keyboard focus with the tab key \(or shift + tab when tabbing backwards\)
* Activate buttons with the enter/return key or the space key

## Button types

## 

## Primary

![](../../.gitbook/assets/2%20%282%29.png)

![](../../.gitbook/assets/3%20%283%29.png)

Buttons call for action. We often use a primary button to draw attention to a page’s highest priority action.

* Text on buttons should always use the Semibold text style.
* You should only use one primary action per page.
*  If there isn’t any one clear primary action, then consider using one or a combination of the other button styles.

## Secondary

We have two secondary buttons in our design system today.

* Use borderless buttons on gray background.
* You should only use one primary action per page.
* If there isn’t any one clear primary action, then consider using one or a combination of the other button styles.

![](../../.gitbook/assets/4%20%284%29.png)

![](../../.gitbook/assets/5%20%283%29.png)

