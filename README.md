st-numberpicker
===================

Number picker field for Sencha Touch 2.3+ that uses slot picker functionality, similiar to datefield. Range is set via minValue and maxValue.  

Uses placeHolder attribute for field display prefix and (custom) units attribute for suffix. Both require custom .scss file for handling before and after pseudoelement content via attr. 

Initial (rough) version. 

Usage Example:<br/>
<pre>
Ext.create('Ext.ux.field.NumberPicker', {
    minValue: 0,
    maxValue: 100,
    name: 'myNumberField',
    placeHolder: '%',
    value: 50
});
</pre>