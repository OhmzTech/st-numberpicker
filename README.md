st-numberpicker
===================

Numberpicker field for Sencha Touch 2.3+ that uses slot picker functionality, similiar to datefield. Range is set via minValue and maxValue, and component height is calculated to determine fadeout (opacity) to be set on individual items.

Uses placeHolder attribute for field display prefix and (custom) units attribute for suffix. Both require custom .scss file for handling before and after pseudoelement content via attr. 

Initial (rough) version. 

Usage Example:<br/>
<pre>
Ext.create('Ext.ux.field.NumberPicker', {
    minValue: 0, // Required
    maxValue: 100, // Required
    name: 'myNumberField', // Form field name for form methods (getValues, etc)
    placeHolder: 'Ratio', // Prefix label - optional
    units: '%', // Suffice label - optional
    value: 50 // Initially set value - optional
});
</pre>