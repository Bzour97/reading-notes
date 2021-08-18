# css

## CSS Transforms

The transform property allows you to visually manipulate an element by skewing, rotating, translating, or scaling:

    .element 
    {
    width: 20px;
    height: 20px;
    transform: scale(20);
    }

Giving this function two values will stretch it horizontally by the first and vertically by the second. In the example below the element will now be twice the width but half the height of the original element:

    .element 
    {
     transform: scale(2, .5);
    }

Or you can be more specific without using the shorthand function:

    transform: scaleX(2);
    transform: scaleY(.5);

## CSS transitions

CSS transitions provide a way to control animation speed when changing CSS properties. Instead of having property changes take effect immediately, you can cause the changes in a property to take place over a period of time. For example, if you change the color of an element from white to black, usually the change is instantaneous. With CSS transitions enabled, changes occur at time intervals that follow an acceleration curve, all of which can be customized.

## Which CSS properties can be transitioned?

The Web author can define which property has to be animated and in which way. This allows the creation of complex transitions. As it doesn't make sense to animate some properties, the list of animatable properties is limited to a finite set.

## Defining transitions

CSS Transitions are controlled using the shorthand transition property. This is the best way to configure transitions, as it makes it easier to avoid out of sync parameters, which can be very frustrating to have to spend lots of time debugging in CSS.

## CSS animations

CSS animations make it possible to animate transitions from one CSS style configuration to another. Animations consist of two components, a style describing the CSS animation and a set of keyframes that indicate the start and end states of the animation’s style, as well as possible intermediate waypoints.

There are three key advantages to CSS animations over traditional script-driven animation techniques:

- They’re easy to use for simple animations; you can create them without even having to know JavaScript.

- The animations run well, even under moderate system load. Simple animations can often perform poorly in JavaScript. The rendering engine can use frame-skipping and other techniques to keep the performance as smooth as possible.

- Letting the browser control the animation sequence lets the browser optimize performance and efficiency by, for example, reducing the update frequency of animations running in tabs that aren't currently visible.

## Defining the animation sequence using keyframes

Once you’ve configured the animation’s timing, you need to define the appearance of the animation. This is done by establishing two or more keyframes using the @keyframes at-rule. Each keyframe describes how the animated element should render at a given time during the animation sequence.

Since the timing of the animation is defined in the CSS style that configures the animation, keyframes use a < percentage > to indicate the time during the animation sequence at which they take place. 0% indicates the first moment of the animation sequence, while 100% indicates the final state of the animation. Because these two times are so important, they have special aliases: from and to. Both are optional. If from/0% or to/100% is not specified, the browser starts or finishes the animation using the computed values of all attributes.