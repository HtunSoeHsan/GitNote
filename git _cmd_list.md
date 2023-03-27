
# git and git hub

> ### git areas <br>
>  
![enter image description here](https://github.com/HtunSoeHsan/GitNote/blob/main/img/gitarea.PNG?raw=true)

> ###  git workflow<br>
>  
![enter image description here](https://github.com/HtunSoeHsan/GitNote/blob/main/img/git-workflow.png?raw=true)

git မှာ area ၃ ခု ရှိပါတယ်
1. working directory( အလုပ်လုပ်နေသောနေရာ )
2. staging area (ပြောင်းလဲမှုတွေကိုယာယီသိမ်းပေးပြီးမှတ်တမ်းတင်ပေးတဲ့နေရာ)
3. repository (မှတ်တမ်းတင်ထားတဲ့ ပြောင်းလဲမှုတွေကို စုစည်းသိမ်းဆည်းတဲ့နေရာ)
> ### git cmd lists<br>
>
- `git init `- git ကို project folder ထဲတွင် စတင်သည်။
- `git add file_name` - working directory မှ file ကို staging area သို့ ပို့သည်။
- `git add . `- working directory မှ file အားလုံး ကို  staging area သို့ ပို့သည်။
- `git commit -m "commit note"`- ပြောင်းလဲမှု မှတ်တမ်းတင်(ပုံရိုက်ထားလိုက်)သည်။
- `git commit -am "commit note"`- `git add .` နှင့် `git commit -m "commit note"` ကို တစ် ပြိုင်တည်းလုပ်သည်။
- `git status` - working dir နဲ့ staging area မှာ ရှိ သော file အခြေနေကိုကြည့်သည်။(file က working dir မှာ ရှိရင် အနီရောင် နဲ့ ပြပြီး staging area မှာ ရှိရင် အစိမ်းရောင်နဲ့ ပြပါတယ်)
- `git log`- commit တွေကိုကြည့်(ဘယ်နှစ်ခုရှိ၊ဘယ်သူလုပ်၊ဘယ်ချိန်လုပ်etc...)
- `git log --oneline`- commit တွေကို တစ် line တည်းနဲ့ကြည့်(only commit id and message)
- `git checkout commit_id` - မှတ်တမ်းတင်ထားတဲ့ commit မှာ ဘာတွေဖြစ်ခဲ့လဲ သွာကြည့်။



> Written with [StackEdit](https://stackedit.io/).
