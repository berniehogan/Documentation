---
layout: default
title: Forms
parent: Key Concepts
---

## Overview

Forms are one of the primary ways that that you will assign values to your variables in Network Canvas. They work by associating each **variable** with an **input control**, a **question prompt** and **validation options**, to form a **field**. Each form can have as many fields as you wish, and in any order.

{% include nc-image src="assets/img/key-concepts/forms/preview.png" %}

When using Architect to design your study you will encounter several places where you are able to build a form - particularly when creating stages that use Interfaces such as the Name Generator, the Per-alter Form, and the Ego Form.

## Constructing a Form

Forms are comprised of one or more 'fields', which can be re-ordered to appear in any sequence. The sequence they appear in Architect is the same sequence that they will be shown in Network Canvas. To begin creating a form, locate the form section within the interface you are configuring.

{% include nc-image src="assets/img/key-concepts/forms/form.png" caption="The form section of a name generator interface" %}

Set the form heading, and then create fields for each of the variables you wish to capture on this form, by clicking the "create new" button.

When creating a new field, you will first either create a new variable or select an existing one to use from the variable chooser. Next, you will type the question prompt to be shown next to the input control.

Next you must decide which [input control](../input-controls) to use, which for new variables will determine the type that this variable will be set to.

{% include tip-caution.md content="Remember that once a variable type has been set, such as by choosing its input type when it is first used, it cannot be changed later. You may still adjust the specific input control on your form even once the type is set, as long as the input control is compatible with the variable type." %}

After setting the input control, set any [variable specific options](../variable-types) and configure the [validation options](../validation) you require.

{% include nc-image src="assets/img/key-concepts/forms/field.png" caption="Interface for creating a form field" %}

## Considerations

When designing forms, there are a few things that you should keep in mind:

- Although it may be tempting to create long and elaborate forms, as is typical within other more traditional survey software, we encourage researchers to consider the burden of overloaded forms on participants and data quality. For example, while it is possible to capture categorical data within a form, you might elect to use the Categorical Bin interface instead. Network Canvas is not intended to replace existing survey methods.
- Making strategic use of forms allows you to capture attribute data systematically, however, you lose the interactive qualities (e.g. dragging and dropping) of other interfaces that may improve the interview experience for participants and potentially render higher quality data.
- If you use the same variable in multiple places in your interview (for example in different forms), any changes you make to the input control or validation options will apply to _all_ uses of the variable.
