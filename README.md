- 👋 Hi, I’m @anjan9635
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
anjan9635/anjan9635 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
com.google.android.apps.gsa.tasks.m: EXCLUSIVE background task UPDATE_HOTWORD_MODELS crashed.
	at com.google.android.apps.gsa.tasks.n.gb(SourceFile:7)
	at com.google.android.libraries.gsa.j.a.n.gb(SourceFile:2)
	at com.google.common.w.a.bv.run(SourceFile:6)
	at com.google.android.apps.gsa.shared.util.c.a.bt.b(SourceFile:1)
	at com.google.android.apps.gsa.shared.util.c.a.bw.run(SourceFile:1)
	at com.google.android.libraries.g.aa.run(SourceFile:1)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1167)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:641)
	at com.google.android.libraries.g.m.run(SourceFile:2)
	at com.google.android.libraries.g.e.run(SourceFile:2)
	at java.lang.Thread.run(Thread.java:919)
	Suppressed: com.google.android.apps.gsa.shared.util.c.a.bv: Unchecked exception happened while running task: n[UPDATE_HOTWORD_MODELS-failure-handler]
		at com.google.android.apps.gsa.shared.util.c.a.bw.run(SourceFile:6)
		... 6 more
Caused by: com.google.android.apps.gsa.tasks.k: java.lang.IllegalArgumentException: Multiple entries with same key: en-AE=https://www.gstatic.com/android-search/hotword/x_google/9b74550b2fb24680fdac9ec59c56e828/hotword.data and en-AE=https://www.gstatic.com/android-search/hotword/x_google/9b74550b2fb24680fdac9ec59c56e828/hotword.data
	at com.google.android.apps.gsa.tasks.b.c.b(SourceFile:2)
	at com.google.android.apps.gsa.tasks.b.a.a(Unknown Source:4)
	at com.google.android.libraries.gsa.j.a.g.a(SourceFile:2)
	at com.google.common.w.a.dr.a(SourceFile:1)
	at com.google.common.w.a.co.run(SourceFile:4)
	at com.google.common.w.a.dt.run(SourceFile:1)
	... 6 more
Caused by: java.lang.IllegalArgumentException: Multiple entries with same key: en-AE=https://www.gstatic.com/android-search/hotword/x_google/9b74550b2fb24680fdac9ec59c56e828/hotword.data and en-AE=https://www.gstatic.com/android-search/hotword/x_google/9b74550b2fb24680fdac9ec59c56e828/hotword.data
	at com.google.common.b.pt.v(SourceFile:1)
	at com.google.common.b.pt.g(SourceFile:20)
	at com.google.common.b.pt.e(SourceFile:6)
	at com.google.common.b.gy.b(SourceFile:1)
	at com.google.android.apps.gsa.shared.speech.hotword.c.a(SourceFile:9)
	at com.google.android.apps.gsa.speech.hotword.b.a.a(SourceFile:8)
	at com.google.android.apps.gsa.speech.hotword.b.a.b(SourceFile:3)
	at com.google.android.apps.gsa.staticplugins.microdetection.b.p.e(SourceFile:1)
	at com.google.android.apps.gsa.staticplugins.microdetection.b.p.b(SourceFile:2)
	at com.google.android.apps.gsa.staticplugins.microdetection.b.p.a(SourceFile:28)
	at com.google.android.apps.gsa.tasks.b.c.b(SourceFile:1)
	... 11 more
