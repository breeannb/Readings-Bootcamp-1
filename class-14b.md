# [Lesson 7 Transforms ](https://learn.shayhowe.com/advanced-html-css/css-transforms/)
> * Transform property -  alternative ways to size, position, and change elements
> * The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.
> * Transform Syntax - 
>   ``````div { -webkit-transform: scale(1.5 -moz-transform: scale(1.5); -o-transform: scale(1.5);transform: scale(1.5); }`````
> * 2D Transforms - Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes
>   * 2D Rotate - The rotate value provides the ability to rotate an element from 0 to 360 degrees.
>   *  Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. 
>   * The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically. Later we will discuss how you can change this default point of rotation.
> * 2D Scale  - Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.
>   * It is possible to scale only the height or width of an element using the scaleX and scaleY values.
> * 2D Translate - The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.
>   * Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.
>   * As with the scale value, to set both the x and y axis values at once, use the translate value and declare the x axis value first, followed by a comma, and then the y axis value.
> * 2D Skew - The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both.
> * Combining Transforms
>   * It is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time for example. In this event multiple transforms can be combined together. To combine transforms, list the transform values within the transform property one after the other without the use of commas.
> * Transform Origin
>   * The transform-origin property can accept one or two values. When only one value is specified, that value is used for both the horizontal and vertical axes. If two values are specified, the first is used for the horizontal axis and the second is used for the vertical axis.
>   * 
> * Perspective
>   * The perspective of an element can be set in two different ways. One way includes using the perspective value within the transform property on individual elements, while the other includes using the perspective property on the parent element residing over child elements being transformed.
> * Perspective Depth Value - The perspective value can be set as none or a length measurement. The none value turns off any perspective, while the length value will set the depth of the perspective.
> * Perspective Origin
>   * As with setting a transform-origin you can also set a perspective-origin. The same values used for the transform-origin property may also be used with the perspective-origin property, and maintain the same relationship to the element.
> * 3D Transforms
>   * 3D Rotate
>   * 3D Scale
>   * 3D Translate
>   * 3D Skew
>   * Shorthand 3D Transforms
>   * Transform Style
>   * Backface Visibility


# [Lesson 8 Transitions & Animations](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)

> * Transitions - an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.
>   * Transitional Propert - he transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties.
>   * It is important to note, not all properties may be transitioned, only properties that have an identifiable halfway point. Colors, font sizes, and the alike may be transitioned from one value to another as they have recognizable values in-between one another. 
>   * Transition Duration - The duration in which a transition takes place is set using the transition-duration property.
>   * Transition Timing - The transition-timing-function property is used to set the speed in which a transition will move.
>   * Transition Delay - On top of declaring the transition property, duration, and timing function, you can also set a delay with the transition-delay property.
> * Shorthand Transitions 
> * Animations
>   * Animations Keyframes -  The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.
>   * Animation Name - the animation-name property is used with the animation name, identified from the @keyframes rule, as the property value. The animation-name declaration is applied to the element in which the animation is to be applied to.
>   * Animation Duration, Timing Function, & Delay 
>   * Once you have declared the animation-name property on an element, animations behave similarly to transitions. 
>  * Customizing Animations
>      * Animation Iteration
>      * Animation Direction - Values for the animation-direction property include normal, reverse, alternate, and alternate-reverse
>       * Animation Play State - The animation-play-state property allows an animation to be played or paused using the running and paused keyword values respectively. 
>   * Animation Fill Mode - The animation-fill-mode property identifies how an element should be styled either before, after, or before and after an animation is run.

# [8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users/)
> * 1. Fade in -  
```
.fade
{
        opacity:0.5;
}
.fade:hover
{
        opacity:1;
}
```
> * 2. Change color
```
.color:hover
{
        background:#53a7ea;
}
```

> * Grow & Shrink
```
.grow:hover
{
        -webkit-transform: scale(1.3);
        -ms-transform: scale(1.3);
        transform: scale(1.3);
}
```

> * Rotate elements
```
.rotate:hover
{
        -webkit-transform: rotateZ(-30deg);
        -ms-transform: rotateZ(-30deg);
        transform: rotateZ(-30deg);
}
```
> * Square to circle
```
.circle:hover
{
        border-radius:50%;
}
```

> * 3D shadow
```
.threed:hover
{
        box-shadow:
                1px 1px #53a7ea,
                2px 2px #53a7ea,
                3px 3px #53a7ea;
        -webkit-transform: translateX(-3px);
        transform: translateX(-3px);
}
```
> * Swing
```
```
> * Inset border
```
.border:hover
{
        box-shadow: inset 0 0 0 25px #53a7ea;
}
```
> * Inset border
```
.border:hover
{
        box-shadow: inset 0 0 0 25px #53a7ea;
}
```

# [6 Buttons Animated](https://codepen.io/retyui/pen/ByoaXV)


# [CSS3 Keyframes Animation](https://codepen.io/akshaychauhan/pen/oAfae)



# [404](https://codepen.io/kieranfivestars/pen/MYdQxX?__cf_chl_captcha_tk__=48979f2092570554f2934379147124706251262a-1586965433-0-AXdIMFz84TWvrC_EW2v9FJSm805ZUK2eG5WAhsQ9V3qT18DJopyvpPdIGcj6QWiPjxX8cbhl_3ncj1U7DoX1LOVYme2ULsGq9zW7LoHUwkBU2LvanMXzuGBtCjV6xkSooZPFjo8Ku5x7oHL5SpchwTpaSP_MF9OipMpu8ok39KKF8EDe-DiJS5JYhvk_PAtJOs5UnI3ZUpX347EqeIX2lE29ZJpjssXgQDQWdKwUe0sdaKRVvqWqb_rvGEzHwR9G9Y1hVgVvJTSRy5qxlqMQAqVn6CHURjdMAXuWxwlFRCMqI9VfjNjY91zJpU2OTKYuqIWK-PEZGfDAXeplho3XX5PIntcH1ZoImtxhf3EnFKiRmfjK2oQ1t-9v2KyWzq6TalC7nPiBgvf5bxCLlzsGw9W6OZSPACp7HRYgbSrlYBwSIJ7JjfGH8YJtFiQrwQ_Xf4mBJGGjzBr_xsFE9Vc80wQrseDueVK_0cpxRNODf9ngFJihSs_f_tjC26HTbuX18yn3XNaq7gf1FNGjKOsm8V0JKgxZaU4qBkudwm4gX5XrX1_geQNitT3iFXIFvsuE8g)


# [Pure CSS Bounce Animation](https://codepen.io/dp_lewis/pen/gCfBv?__cf_chl_captcha_tk__=10f640e315bb8c38f0555c667f687734eb02a650-1586965434-0-AdnxQYZPCaan9rKIykVYc0e9u4H8eX1Jtv57utVflyujGxmKTixINuDEbx1iCAvI2A27GeCTYdLP_SkBN0JnWGDhaEgAnqwjFzJ_-ODAk89QbQ6gGnoJJ64t-uaAcHRuyp3BluVkrVr9xdqa_0mbYYfSjZ9lAZK_l7DFwZkDCPOZRBCVhZjLcG5xU7sIMOyVyv28e2yOCf1EBPOs_-t_8KiSj1OjLGxN3sjMX-3aWxjQbH-XEJSiW6DOPBkGR7ENFMkh8Al0XxMbMpUi7s-lWCEW172ghXsNJQIQb25BcnPIlt6UmdWDNohrop12CMBiQhXPSz4WpuYNsrS18t85FBRKqAl4PHDyX_4-i3iqBxqHN2eRfLenjPtg6sKiqVCs2czhbkGSaZc-iHjepFKZKnJStiUq66OfvH0VwlDfrpxsBYRY9l3EyLt4o9L_IvWVcOZ7ubhOzlvUTCw-sYH3FLvw_Bg44LmzAcVCk2udxo3tNQCA5oYGl1kaqHBcloofxdSuEj23WtCFF47xcvShube12Tnsve8ACRclPpt9TRwf)
