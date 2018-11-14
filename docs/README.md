## Members

<dl>
<dt><a href="#getAll">getAll</a> ⇒ <code>*</code> | <code><a href="#Nothing">Nothing</a></code></dt>
<dd><p>Access all properties on object going through the given path,
returns <a href="#Nothing">Nothing</a> if it is not possible to fetch the value</p>
</dd>
<dt><a href="#isNothing">isNothing</a> ⇒ <code>Boolean</code></dt>
<dd><p>Checks if x is Nothing</p>
</dd>
</dl>

## Interfaces

<dl>
<dt><a href="#Nothing">Nothing</a></dt>
<dd><p>Represents an error in some accessing operation</p>
</dd>
</dl>

<a name="Nothing"></a>

## Nothing
Represents an error in some accessing operation

**Kind**: global interface  
**Properties**

| Name | Type |
| --- | --- |
| isNothing | <code>true</code> | 

<a name="getAll"></a>

## getAll ⇒ <code>\*</code> \| [<code>Nothing</code>](#Nothing)
Access all properties on object going through the given path,
returns [Nothing](#Nothing) if it is not possible to fetch the value

**Kind**: global variable  
**Returns**: <code>\*</code> \| [<code>Nothing</code>](#Nothing) - Final accessed property or nothing  

| Param | Type | Description |
| --- | --- | --- |
| obj | <code>Object</code> | Object to be accessed |
| path | <code>String</code> | Path to be accessed separated by . |

<a name="isNothing"></a>

## isNothing ⇒ <code>Boolean</code>
Checks if x is Nothing

**Kind**: global variable  
**Returns**: <code>Boolean</code> - whether it's equal or not  

| Param | Type | Description |
| --- | --- | --- |
| x | <code>\*</code> | Anything you want to test |
