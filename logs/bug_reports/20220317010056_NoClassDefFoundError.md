<!--- Please do not ask questions or create discussion in the bug tracker. Use https://nukkitx.com -->
<!--- ONLY POST ISSUES WITH A CLEAN SERVER ON THE LATEST VERSION -->
## Generated Bug Report

<!--- DO NOT OPEN A ISSUE IF THIS IS A PLUGIN ERROR -->
PLUGIN ERROR: TRUE

### Expected Behavior
<!--- What would you expect to happen -->


### Actual Behavior
<!--- What actually happened -->


### Steps to Reproduce
<!--- Reliable steps which someone can use to reproduce the issue. Please do not create issues for non reproducible bug! -->


### OS and Versions

* Nukkit Version: git-8a276f8 
* Java Version: Java HotSpot(TM) 64-Bit Server VM (17.0.2+8-LTS-86)

* Host Configuration: 

| Item | Value |
|:----:|:-----:|
| Host OS | Windows Server 2022-amd64 [10.0] |  
| Memory(RAM) | 4.3 GB | 
| Storage Size | 144.4 GB | 
| Storage Type | Disk 0:(avail=77.2 GB, total=135.8 GB) Disk 1:(avail=7.6 GB, total=8.6 GB)  | 
| CPU Type | Intel64 Family 6 Model 85 Stepping 4, GenuineIntel | 
| CPU Core Count | 2 | 

### Crashdump, Backtrace or Other Files

```
java.lang.NoClassDefFoundError: de/theamychan/scoreboard/api/ScoreboardAPI
	at me.petterim1.scoreboards.ScoreboardUpdater.run(ScoreboardUpdater.java:27)
	at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1136)
	at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	at java.base/java.lang.Thread.run(Thread.java:833)
Caused by: java.lang.ClassNotFoundException: de.theamychan.scoreboard.api.ScoreboardAPI
	... 4 more

```