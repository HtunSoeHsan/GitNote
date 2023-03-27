
# git and git hub

### Git ဆိုတာ?
 Git ဆိုတာ project ရဲ့ ပြောင်းလဲ မှုတွေကို မှတ်တမ်းတင်ပေးတဲ့(tracking)software တစ်ခုဖြစ်ပါတယ်။
 
 ### GitHub ဆိုတာ?
 GitHub ဆိုတာ microsoft ကပိုင်တဲ့(git system ကိုသုံးထားတဲ့) web application တစ်ခုဖြစ်ပါတယ်။ project တစ်ခုကို Team လိုက် လုပ်တဲ့အခါ source code တွေကို sharing လုပ်နိုင်ဖို့သုံးပါတယ်။
>**Note:** programming လုပ်မယ်ဆို git နဲ့ github အကြောင်းကိုသိ	     ကိုသိရပါမယ်။

	



>  git areas <br>
![enter image description here](https://github.com/HtunSoeHsan/GitNote/blob/main/img/gitarea.PNG?raw=true)

>  git workflow<br>
![enter image description here](https://github.com/HtunSoeHsan/GitNote/blob/main/img/git-workflow.png?raw=true)

git မှာ area ၃ ခု ရှိပါတယ်
1. working directory( အလုပ်လုပ်နေသောနေရာ )
2. staging area (ပြောင်းလဲမှုတွေကိုယာယီသိမ်းပေးပြီးမှတ်တမ်းတင်ပေးတဲ့နေရာ)
3. repository (မှတ်တမ်းတင်ထားတဲ့ ပြောင်းလဲမှုတွေကို စုစည်းသိမ်းဆည်းတဲ့နေရာ)
>git cmd lists<br>
- `git init `- git ကို project folder ထဲတွင် စတင်သည်။
- `git add file_name` - working directory မှ file ကို staging area သို့ ပို့သည်။
- `git add . `- working directory မှ file အားလုံး ကို  staging area သို့ ပို့သည်။
- `git commit -m "commit note"`- ပြောင်းလဲမှု မှတ်တမ်းတင်(ပုံရိုက်ထားလိုက်)သည်။
- `git commit -am "commit note"`- `git add .` နှင့် `git commit -m "commit note"` ကို တစ် ပြိုင်တည်းလုပ်သည်။
- `git status` - working dir နဲ့ staging area မှာ ရှိ သော file အခြေနေကိုကြည့်သည်။(file က working dir မှာ ရှိရင် အနီရောင် နဲ့ ပြပြီး staging area မှာ ရှိရင် အစိမ်းရောင်နဲ့ ပြပါတယ်)
- `git log`- commit တွေကိုကြည့်(ဘယ်နှစ်ခုရှိ၊ဘယ်သူလုပ်၊ဘယ်ချိန်လုပ်etc...)
- `git log --oneline`- commit တွေကို တစ် line တည်းနဲ့ကြည့်(only commit id and message)
- `git checkout commit_id` - မှတ်တမ်းတင်ထားတဲ့ commit မှာ ဘာတွေဖြစ်ခဲ့လဲ သွာကြည့်(သွားလည်)။
- `git restore --staged file_name`- staging area မှ file ကို working dir သို ပြန်ပို့ ။
- `git restore --staged .`-staging area မှ file အားလုံး ကို working dir သို ပြန်ပို့ ။
- `git restore .`- working dir ထဲ မှာရှိတဲ့ ပြောင်းလဲမှုတွေကို ပစ်လိုက်ပြီး အရင် commit(နောက်ဆုံး commit) တိုင်း ပြန်ထား။
- ![enter image description here](https://github.com/HtunSoeHsan/GitNote/blob/main/img/reset.PNG?raw=true)
- `git reset --hard commit_id` - နောက်ဆုံး commit ကနေ commit_id ထိ ပြောင်းလဲမှု ကို ဖျက်ပြီး commit_id သို့ သွား(commit_id ကိုနောက်ဆုံး commit အဖြစ်ထား)။(working dir ထိဖျက်)
- `git reset --mixed commit_id`-  commit ကိုဖျက်ပြီး၊နောက်ဆုံး commit ကနေ commit_id ထိ ပြောင်းလဲမှုကို commit_id ရဲ့ working dir ထဲသို့ ပို့။(staging area ထိဖျက်)
- `git reset --soft commit_id`-  commit ကိုဖျက်ပြီး နောက်ဆုံး commit ကနေ commit_id ထိ ပြောင်းလဲမှုကို commit_id ရဲ့  staging area ထဲသို့ ပို့။(commit history ထိဖျက်)
- `git reset`commit_id  = git reset --mixed commit_id
>  #cerdit to  [MSquareProgramming](https://www.youtube.com/@MSquareProgramming/playlists).
>  > Written with [StackEdit](https://stackedit.io/).