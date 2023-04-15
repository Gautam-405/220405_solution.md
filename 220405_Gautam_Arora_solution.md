# Details

Rename this file in the format `yourRollNumber_solution.md` (example, `220000_solution.md`) and create a pull request in the parent repository on github.


## Your zeroth approach below

Reasoning - %%% Just follwed the steps to download linux terminal on windows. ththen run the given file whose output state that"The answer of this challenge is output
of "man" when run on the terminal, copy the exact output"
then ran "man" command on temrinal whose output is- %%%

```
%%% What manual page do you want?
For example, try 'man man'. %%%
```

---

## Your first approach below (first.txt)

Reasoning - %%% Given code is an example of rotation encyption in which a letter is replaced by a letter 19 places ahead of it. For ex- 'a' is shifted to 's' %%%

```
%%% AFTER DECRYPTING- noicee you did crack a rotation encyption on your own.The following is a clue for the next puzzle. CLASS of that INPUT. %%%
```

---

## Your second approach below (strings.txt)

Reasoning -
After understanding that we hve to use linux terminal and after downloading the lamp_stack_task zip 
Applied ffollowing commands to retrieve information about strings.txt
gautam@LAPTOP-AE2SA9A9:/mnt/d$ ls
'$MfeDeepRem'  '$RECYCLE.BIN'   Lamp_Stack_Task.zip   Lamp_Stack_task  'System Volume Information'   rtr8A1E.tmp
gautam@LAPTOP-AE2SA9A9:/mnt/d$ cd Lamp_Stack_task
gautam@LAPTOP-AE2SA9A9:/mnt/d/Lamp_Stack_task$ find . -name strings.txt
./question_mark/Lamp_Stack/1/5/0/3/strings.txt
gautam@LAPTOP-AE2SA9A9:/mnt/d/Lamp_Stack_task$ cd question_mark/Lamp_Stack/1/5/0/3
gautam@LAPTOP-AE2SA9A9:/mnt/d/Lamp_Stack_task/question_mark/Lamp_Stack/1/5/0/3$ ls
strings.txt
gautam@LAPTOP-AE2SA9A9:/mnt/d/Lamp_Stack_task/question_mark/Lamp_Stack/1/5/0/3$ cat strings.txt
kw4QLNylm2inErX
DabAWF1UenBD2W
kPVEQPc6ZN8x2jn
g4JoMqFZyat9vd5
ORNwuwGtKDLydge
TqMuGims7vlJtno
8dc2evcCSSc4kUy (password)



## Your third approach below (fourth.zip)

Reasoning - %%% as 8dc2evcCSSc4kUy (password) does not open up fourth file
And after seeing other txt file containg similar passwords in it.
I ran the command
gautam@LAPTOP-AE2SA9A9:/mnt/d/Lamp_Stack_task/question_mark/Lamp_Stack$ grep -r "8dc2evcCSSc4kUy"
1/5/0/3/strings.txt:8dc2evcCSSc4kUy (password)
eleven.txt:8dc2evcCSSc4kUy
final.txt:8dc2evcCSSc4kUy
tells us that same string is also contained in final as well as eleven.txt

where eleven.txt is required password for fourth.zip 
after unzipping fourth.zip
gautam@LAPTOP-AE2SA9A9:/mnt/d$ ls
'$MfeDeepRem'  '$RECYCLE.BIN'   Lamp_Stack_Task.zip   Lamp_Stack_task  'System Volume Information'   fourth.zip   get_in   rtr8A1E.tmp
gautam@LAPTOP-AE2SA9A9:/mnt/d$ cd get_in
gautam@LAPTOP-AE2SA9A9:/mnt/d/get_in$ grep -r DevOps{
4/2_inner/0.txt:DevOps{y0ur3_4w350m3_4nd_0ne_5t3p_c1053r}%%%

```
%%% DevOps{y0ur3_4w350m3_4nd_0ne_5t3p_c1053r}%%%
```

---


- Name : Gautam Arora
- Roll :220405
- GitHub username:Gautam-405
- Discord username:220405_Gautam_Arora#2469


## Do not tamper below this line

---

Q29yZSB0ZWFtIGtvIGZha2UgZG8=
