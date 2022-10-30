Bondage Club Auto React (BCAR)
====================  
This Extension lets your Character react automatically to Actions done to them.  

Example Picture:  
![ExamplePicture](https://user-images.githubusercontent.com/115511728/196439657-cfb098f1-093a-4b5d-8d6b-df0a755e1335.png)  

The ears can wiggle and the tail wag too. To change the ears wiggle and the tail wag animation see "Commands of BCAR" down below. You can add the script via Tampermonkey [here](https://github.com/DrBranestawm/BCAR/raw/main/script/bcarLoader.user.js)  
or add it as Bookmark any of your devices. To do that save  
<code>javascript:(()=>{fetch('https://drbranestawm.github.io/BCAR/script/bcar.js').then(r=>r.text()).then(r=>eval(r));})();</code>  
as a bookmark on your devices.


Commands of BCAR
----------------------
Help Menu
----
  - /bcar help : To opnen the help menu window

The only way to change the ears and tail types is to use chat commands. The set ears and tails will be saved and will be loaded even after relogging. 
  
Ears
----
  - /bcar ear1 : To save your current ears as the primary ears.

Switch your ear to the one you want the secondary ear to be.

  - /bcar ear2 : To save the secondary ears. 
  
  - /bcar earson : To turn the ear wiggling on.
  - /bcar earsoff : To turn the ear wiggling off.
  
  
Tail
----
  - /bcar tail1 : To save your current ears as the primary tail.

Switch your tail to the one you want the secondary tail to be.

  - /bcar tail2 : To save the secondary tail.  
  
  - /bcar tailon : To turn the tail wagging on.
  - /bcar tailoff : To turn the tail wagging off.
  
  
Settings reset
---
  - /bcarreset : To reset the set ears and tails to the default settings  


# BCE Expressions for BCAR 
[BCE Expressions for BCAR](https://github.com/DrBranestawm/BCAR/raw/main/bceExpressionsForBCAR/scriptLoader.user.js)  
<code>javascript:(()=>{fetch('https://drbranestawm.github.io/BCAR/bceExpressionsForBCAR/script.js').then(r=>r.text()).then(r=>eval(r));})();</code>

# BCAR Beta
Use the beta at own risk!  
You can add the beta script via Tampermonkey [here](https://github.com/DrBranestawm/BCAR/raw/main/script/bcarBetaLoader.user.js)  
or add it as Bookmark any of your devices. To do that save  
<code>javascript:(()=>{fetch('https://drbranestawm.github.io/BCAR/script/bcarBeta.js').then(r=>r.text()).then(r=>eval(r));})();</code>  
as a bookmark on your devices.


Special Thanks
----------------

 - Angela
    - Privoviding the main script
 - Julia ([@agicitag](https://github.com/agicitag))
    - Providing general help
    - Permission to use their save and load settings feature
 - Haruhi ([@crimsontropy](https://github.com/crimsontropy))
    - Clean up the if-else for actions
    - Their tail wag script on which the ear wiggle is based
    - Implementing the save and load settings feature
 - Utsumi
    - Help with an issue with the activityDictionary
