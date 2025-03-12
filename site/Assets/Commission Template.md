---
status:
- start
- pending
- review
- complete

type:
- Sketch
- Render
- Illustration
size:
- Portrait
- Halfbody
- Fullbody
colour:
- Yes
- No

name: name
client: name
tier:
- Large
- Medium
- Small
- Free
where:
- Email
- Discord
contact: "email or discord"
timeAccepted: 00/2025
timeComplete: 00/2025

ref: 
other: "desc"

### for price calculating
price: 0
surcharge: 0
---
# <u>**`=this.name`**</u>
## <center>*`=this.file.name`*</center>
---
>[!col]
>>[!note] Type
>>`=this.type`
>
>>[!note] Size
>>`=this.size`
>
>>[!note] Colour
>>`=this.colour`
>
>>[!note] Price
>>$ _`=this.price*((this.surcharge + 100)/100)`_ USD 

>[!missing] Information
>|%%t%%|%%t%%|
>|-|-|
>|*Client:*|`=this.client`, `=this.tier` Tier|
>|*Contact:*|`=this.where`,`=this.contact`|
>|*Started:*|`=this.timeAccepted`|
>|*Completed:*|`=this.timeComplete`|
>|*Paid:*|<input type="checkbox" unchecked><input type="checkbox" unchecked>|
>
>>[!todo] Notes
>>- ?

>[!cite] Reference(s)
>`=this.ref`

>[!summary] Description
>`=this.other`