ကိုဖြိုး အရောင်းအဝယ်စာရင်း — Android APK ပြုလုပ်ရန်

ဒီ ZIP ထဲမှာ Android WebView project နဲ့ app ရဲ့ HTML ဖိုင် ပါပါတယ်။ ဒီနေရာမှာ Android SDK/Gradle မရှိလို့ APK ကို တိုက်ရိုက် compile မလုပ်နိုင်ပါ။ GitHub Actions အခမဲ့ workflow ထည့်ထားပါတယ်။

ဖုန်းနဲ့ APK ထုတ်နည်း
1. GitHub.com မှာ အကောင့်ဝင်ပါ (မရှိရင် အခမဲ့ဖွင့်ပါ)။
2. New repository ကိုနှိပ်ပြီး kophyo-ledger လို့နာမည်ပေးပါ။ Public သို့မဟုတ် Private ရွေးပြီး Create repository လုပ်ပါ။
3. ဒီ ZIP ကို ဖုန်းထဲမှာ Extract လုပ်ပါ။ Repository ထဲမှာ Add file > Upload files ကိုနှိပ်ပြီး ZIP ကို မတင်ဘဲ Extract လုပ်ထားတဲ့ ဖိုင်/ဖိုလ်ဒါများကို အပေါ်ဆုံးအဆင့်အတိုင်း upload လုပ်ပြီး Commit changes နှိပ်ပါ။ .github ဖိုလ်ဒါလည်း ပါရပါမယ်။
4. Repository ထဲက Actions tab ကိုဖွင့်ပါ။ Build Android APK workflow ကိုရွေးပြီး Run workflow နှိပ်ပါ။
5. Build ပြီးရင် workflow run ထဲက Artifacts အောက်ရှိ KoPhyo-Ledger-APK ကိုနှိပ်ပြီး download လုပ်ပါ။ ZIP artifact ကို extract လုပ်ပါ။ app-debug.apk ကို Android ဖုန်းမှာဖွင့်ပြီး တပ်ဆင်ပါ။ ဖုန်းက ခွင့်ပြုချက်တောင်းလျှင် ယုံကြည်ရတဲ့ ကိုယ်ပိုင် build အတွက်သာ install unknown apps ခွင့်ပြုပါ။

မှတ်ချက်များ
- ဒီ APK ဟာ debug APK ဖြစ်ပြီး ကိုယ်ပိုင်အသုံးပြုစမ်းသပ်ရန်ပါ။
- စာရင်းဒေတာက App ရဲ့ local storage ထဲမှာ သိမ်းထားပြီး app data ဖျက်လျှင် ပျောက်နိုင်ပါတယ်။ အရန်ဖိုင်ကို ပုံမှန်ထုတ်ထားပါ။
- Build မအောင်မြင်ပါက GitHub Actions မှ error log ကို ကူးယူပြီး အကူအညီတောင်းပါ။
