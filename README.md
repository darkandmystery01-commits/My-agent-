Screen Editor Agent (Android)
Phone pe CapCut, InShot jaise apps ko screen dekh ke chalata hai. Command voice se ya likh ke. Ye Android Accessibility Service hai: Gemini screenshot dekhta hai, phir tap, swipe, type karta hai.
APK banane ka aasaan tareeka (GitHub, Android Studio ki zaroorat nahi)
github.com pe free account banao aur ek naya repository banao.
Is folder ki saari files (.github folder samet) us repository mein upload karo. Laptop pe browser se upload karna sabse aasaan hai.
Repository ke Actions tab mein "Build APK" chalne do (2-5 minute).
Complete hone pe us run mein neeche Artifacts se screen-editor-agent-apk download karo. Usme app-debug.apk hai.
Doosra tareeka: Android Studio mein ye folder kholo aur Build > Build APK.
Phone pe install aur setup
APK phone pe lao aur install karo ("Install unknown apps" allow karna padega).
App kholo, "Accessibility service chalu karo" dabao, list mein Screen Editor Agent chunke ON karo. Android 13+ pe agar option grey ho to: Settings > Apps > Screen Editor Agent > teen dot (upar-right) > Allow restricted settings, phir dobara try karo.
Gemini API key (Google AI Studio) app mein daalo.
Command likho ya "Mic se bolo" dabao, phir "Agent chalao". App peeche chala jata hai aur agent kaam shuru karta hai. Command mein app ka naam bolo: "CapCut kholo, project X kholo, clip ko 10 second pe split karo".
Safety
Chhote floating panel mein Roko hamesha hai. Export, delete jaise kaam se pehle panel mein Haan / Nahi puchta hai.
Har step ka screenshot Google Gemini ko jata hai, notification aur chats samet. Kaam ke time baaki private cheezein band rakho.
API key sirf phone mein save hoti hai (encrypt nahi). Kisi ko apna APK mat bhejna.
Max 40 step ke baad agent khud ruk jata hai.
Limits (imandari se)
Ye code maine yahan build ya test nahi kiya (yahan Android SDK nahi hai). Pehli baar build pe chhoti errors aa sakti hain. Build log bhej dena, theek kar dunga.
Ye Android 11 ya naye phone pe chalta hai.
Jo screens secure hain (banking apps) ka screenshot khali aata hai.
CapCut/InShot ka layout badalne pe ya timeline ke chhote handles pe agent galti kar sakta hai. Chhote kaam se shuru karo: split, trim, caption.
Har step mein 3-6 second lagte hain (screenshot, Gemini, action).
Model gemini-2.5-flash hai. Naya model chahiye to Agent.kt mein MODEL badlo.
