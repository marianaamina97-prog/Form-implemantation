# Form-implemantation
## Introduction
A form is container used to collect user input and send it to the serve.it is also a semantic element because it explains itself. Forms are essiantial for things like search bars,login pages ,surveys and contact forms.
## Form Sections And Their Purpose 
A form is created with the < form > element.A form is made up of four main parts which include:

**Legend** This is an element used inside a fielset to give a description for the group of forms control.It improves accessibility for the screen readers to announce the legend so the users know what the fields are grouped under.
It helps organize forms visually and logically.

**Fieldset** A fieldset is used to group related form  elements together.It usually has a border that groups the inputs.Inputs in fieldset include :
<ul>
  <li>text</li>
  <li>email</li>
  <li>checkbox</li>
  <li>radio</li>
  <li>website</li>
  <li>button</li>
  <li>numbers</li>
  and many more.
</ul>

**Labels** The < label > element is used to define caption for an input element.This improves usability and accessibility.It is advisiable to always associate labels with inputs for easy accessibility.

## Form Implemantation
For a form to be functional it has to have all its features.For example a "Registration form" this has a fieldset,inside the fieldset the form has it first legend as "personal information" This groups everything about you like name ,phone number,email and gender in one fieldset.
Inside the fieldset there are labels and inputs for easy readability.Different legends groups different inputs and labels in one fieldset.Each fiedset and legend makes a border classifying different fieldset from each other .

## CSS Styling
This project uses a component-based, mobile-first CSS approach with flexbox layouts and consistent spacing via the gap property.
<ul>
<li>The universal box-sizing: border-box ensures predictable element sizing.</li>

<li>Forms and fieldsets use flexbox for alignment and responsiveness.</li>

<li>Media queries adjust layout widths for screens under 640px.</li>

<li>Typography uses a clean sans-serif hierarchy ('Poppins' and Arial) for readability and visual consistency.</li>
</ul>

## 🎨 Color Palette
<ul>
<li>Primary Button : Accent	Blue</li>	
<li>Primary Hover:	Deep Blue	</li>
<li>>Secondary Accent:	Blueviolet</li>	
<li>Secondary Hover:	Violet</li>	
<li>Background:	Light Gray</li>	
<li>Text:	Dark Gray</li>	
<li>Border:	Cool Gray</li>
</ul>

## ⚙️ Features Implemented
<ul>
<li>Flexbox Layouts: Used in forms, button rows, and checkbox alignment.</li>

<li>Hover Transitions: Smooth animations on buttons and inputs using transform, scale, and box-shadow.</li>

<li>Focus States: Accessible outlines for keyboard navigation.</li>

<li>Box Shadows & Border Radius: Provide depth and a modern, soft appearance.</li>

<li>Responsive Design: Adjusts layout for mobile via @media (max-width: 640px).</li>

<li>Custom Buttons: Unified .btn, .primary, and .secondary classes for consistent CTA design.</li>
</ul>

## 🌐 Browser Compatibility

Tested and optimized for modern browsers:

✅ Chrome (latest)

✅ Firefox (latest)

✅ Edge (latest)

## Reference
https://github.com/marianaamina97-prog/Form-implemantation


