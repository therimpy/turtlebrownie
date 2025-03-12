---
dg-publish: true
dg-homepage: true
banner: "![[one.jpg]]"
banner_y: 0.5
---
# <u>**TurtleBrownie**</u>
*<center>Comic (f)artist + illustrator</center>*

---
## <center><u>**Welcome to My Site!**</u></center>

>[!col]
>>[!todo] [[#<center><u>**Commission Queue**</u></center>|Commission Queue]]
>
>> [!tldr] [[My Characters]]

>[!col]
>>[!example] [[#<center><u>**My Brushes**</u></center>|My Brushes]]
>
>>[!faq] [[#<center><u>**FAQ**</u></center>|FAQ]]

>[!col]
>>[!abstract] Follow me here!
>> [Twitter/X](link)
>> [Instagram](link)
>> [Blue Sky](link)
>> [Art Fight](link)
>
>>[!summary] Support me here!
>> [Patreon](link)
>> [Gumroad](link)
>> [Discord](link)
>> [PayPal](link)

---
## <center><u>**Commission Queue**</u></center>
>[!col]
>>[!missing] [[What to Know|Commission Info]]
>
>>[!missing] [[Pricing and Examples]]
>
>>[!missing] [[Terms and Conditions]]

>[!col]
>> [!abstract] Accepted 
>>```dataview
>>LIST
>>FROM "Commissions"
>>WHERE status = start
>>SORT file.ctime ASC
>>```
>
>>[!example] In Progress
>>```dataview
>>LIST
>>FROM "Commissions" AND #comm
>>WHERE status = "pending"
>>SORT file.ctime ASC
>>```
>
>>[!help] Awaiting Review
>>```dataview
>>LIST
>>FROM "Commissions" AND #comm
>>WHERE status = "review"
>>SORT file.ctime ASC
>>```


>[!done] Completed
>```dataview
>LIST
>FROM "Commissions/Completed"
>SORT file.ctime ASC
>LIMIT 5
>```
---

## <center><u>**My Brushes**</u></center>
>[!col]
>>[!important] Paint's brush (no pen pressure)
>>![[pen1.jpg]]
>>![[GjgpuMFWEAAyu_a.jpg]]
>>![[GfFwZZnasAAWYzN.png]]
>>**Content ID:** *1806645*
>>Sketching & Lineart
>
>>[!important] Intoxicate Pencil Set
>>![[raefille2.jpg]]
>>![[sketch1.jpg]]
>>**Content ID:** *1740419*
>>Sketching & Rendering

>[!col]
>>[!important] HB mechanical pencil
>>![[Pasted image 20250312112428.png]]
>>![[Pasted image 20250312111703.png]]
>>![[figure study 2.png]]
>>**Content ID:** *2064870*
>>Sketching
>
>>[!important] softish paint brush
>>![[Pasted image 20250312112357.png]]
>>![[raefille.jpg]]
>>**Content ID:** *2026536*
>>Rendering

---

## <center><u>**FAQ**</u></center>
>[!col]
>>[!question] Question
>>Answer
>
>>[!question] Question
>>Answer
>
>>[!question] Question
>>Answer

>[!col]
>>[!question] Question
>>Answer
>
>>[!question] Question
>>Answer
>
>>[!question] Question
>>Answer