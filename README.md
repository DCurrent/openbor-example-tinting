# openbor-example-tinting
How to apply tint effects to OpenBOR entities for special effects.

This is a technical demonstrator of applying tints to create color effects on entities. Please note that nearly every other aspect of this module is derived from the original Beats of Rage. It is therefore severely out of date and should not be used as a module authoring example in any way.

# Why Tints?

The simplest example of tints is dealing with special effects when hit by elemental attacks, like fire. That is what this module will demonstate. Typically, an “I’m on fire!” reaction is created with a generic set of burning sprites shared by every model (think Final Fight or early versions of Street Fighter). Another common technique is to change the entity’s current colors to a pre-existing “Burn” palette and then adding some fire themed particle effects.

The latter is far more visually appealing, but tinting is even better! Here’s why.
-	It’s a huge time saver. Set the tinting script up, get some particle effects going and you’re done. There’s no need to bother with making and keeping track of alternate palettes and attributes for special effects. The script takes care of everything automatically.
-	The visual effect is far more dynamic. Instead of reverting to a static effect palette, the entity appears frozen, on fire, or whatever else while still retaining its unique look. If the entity was wearing a green shirt, they are still wearing a green shirt – just on fire.
-	Tints are adjustable on the fly. You could have varying intensities of burn for example, or as is demonstrated in this module, a gradual effect based on time. The possibilities are endless.

# Instructions

## Demo

1.	Open the module and play as normal.
    1.	To try out the freeze effect, pick Kula and use her Forward, Forward, Attack command. Leave an enemy frozen until the effect expires and you’ll notice they will visually “thaw out” over time.
    2.	To try out burn, choose Maxima and use Forward, Forward, Attack or Special.

## Installation 

The module contains a plug and play script. To activate it, take the following steps:
1.	Copy the contents of this module’s script folder to your own.
2.	If you have preexisting fmap settings or scripted palette changes for burn, shock, etc. in your module, make sure to remove them.
3.	The script is already set up for burn and freeze. You will find there is full documentation inside on how to add more effects (shock, poison, etc.), adjust the colors, and so on.

# Notes
- This example is only for color tints. You’ll still want to bind some visual flash effects like flames or sparks to really sell it. That is material for another tutorial.
- If your module already has scripts in it you may need to make some adjustments. This will vary module to module, but is usually a very simple task.


