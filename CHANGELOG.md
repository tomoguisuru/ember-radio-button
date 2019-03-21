### 2.0.0
- Updates to  Ember CLI 3.4.4
- Removes support for Ember CLI < 2.18

### 1.3.0
 - adds support for passing a closure action to the `changed` property


### 1.2.4
 - adds `aria-checked` attribute binding

### 1.2.3
 - adds `checkedClass` to override the default "checked" classname on the label when it is checked

### 1.2.2
 - adds `ariaDescribedby`

### 1.2.1
 - adds `ariaLabelledby`

### 1.2.0
 - README overhaul
 - adds `tabindex` and `autofocus`
 - use `Ember.isEqual` for comparison
 - updated examples in the test application to be implemented with components
 - fix for ember engine support

### 1.1.1
 - adds support for engines
 - Potential Breaking Change: The addon now uses templates from the addon folder.
   If you were supplying your own templates at the previous location
   (`app/templates/components/radio-button.hbs` for example)
   You will need to instead extend the provided component and explicitly
   supply your own template.

### 1.0.7

 - adds a `radioClass` property to put any classes you want on the input element
 - adds a `radioId` property to specify an id for the input element, allows
   associating non-wrapping label elements

### 1.0.6

 - Use `hasBlock` internally and remove deprecation warnings from
   accessing the component's `template` property

### 1.0.5

 - Improve IE8 Support

### 1.0.4

 - Fix putting additional classNames on the label

### 1.0.3

 - Put additional classNames on the label

### 1.0.2

 - Add `ember-radio-button` class to the label when used as a block

### 1.0.1

 - Put a `checked` classname on the label element when a block form
   radio-button is checked

### 1.0.0

 - Update to htmlbars
 - Rely on the `change` event, not `click`
 - Only `label` and `input` elements emitted, no more `span`

### 0.1.3

 - Add `required` and `name` bound attributes

### 0.1.2

 - Add `disabled` bound attribute
