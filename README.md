# Public-land-hunting
Dennison mn
389769","share_with_app_devs":1,"roots_installed":0,"bug_type":"145","os_version":"iPhone OS 18.0 (22A5350a)","slice_uuid":"AA8EBB25-5216-3976-A7D4-B5652D7CE930","is_first_party":0,"incident_id":"4F4C8793-AE40-4D25-9E48-60C01F77F990","timestamp":"2024-09-05 19:13:15.00 -0500","app_name":"abm-helper","name":"abm-helper"}
Date/Time:        2024-09-05 19:06:42.727 -0500
End time:         2024-09-05 19:13:12.496 -0500
OS Version:       iPhone OS 18.0 (Build 22A5350a)
Architecture:     arm64e
Report Version:   53
Incident Identifier: 4F4C8793-AE40-4D25-9E48-60C01F77F990
Share With Devs:  Yes

Data Source:      Microstackshots
Shared Cache:     2AE032C1-A99E-3701-BF80-17541280C366 slid base address 0x196abc000, slide 0x16abc000

Command:          abm-helper
Path:             /System/Library/PrivateFrameworks/ABMHelper.framework/Support/abm-helper
Resource Coalition: "com.apple.abm-helper"(263)
Architecture:     arm64e
Parent:           UNKNOWN [1]
PID:              165

Event:            disk writes
Action taken:     none
Writes:           1073.75 MB of file backed memory dirtied over 390 seconds (2754.85 KB per second average), exceeding limit of 12.43 KB per second over 86400 seconds
Writes limit:     1073.74 MB
Limit duration:   86400s
Writes caused:    1073.75 MB
Writes duration:  390s
Duration:         389.77s
Duration Sampled: 386.36s (event starts 0.69s before samples, event ends 2.72s after samples)
Steps:            22 (10.49 MB/step)

Hardware model:   iPhone14,3
Active cpus:      6
HW page size:     16384
VM page size:     16384

Advisory levels:  Battery -> 1, User -> 3, ThermalPressure -> 0, Combined -> 1
Free disk space:  17.10 GB/118.09 GB, low space threshold 150 MB
Low Power Mode:   Enabled
Vnodes Available: 70.95% (17029/24000, 12000 allocated, 12000 soft limit)

Preferred User Language: en-US
Country Code:     US
Keyboards:        en_US QWERTY, autofillsignup
OS Cryptex File Extents: 13443

Heaviest stack for the target process:
  19  ??? (libsystem_pthread.dylib + 5256) [0x22099a488]
  19  ??? (libsystem_pthread.dylib + 19580) [0x22099dc7c]
  19  ??? (libdispatch.dylib + 92836) [0x1a155baa4]
  19  ??? (libdispatch.dylib + 94808) [0x1a155c258]
  19  ??? (libdispatch.dylib + 49632) [0x1a15511e0]
  19  ??? (libdispatch.dylib + 46808) [0x1a15506d8]
  19  ??? (libdispatch.dylib + 16592) [0x1a15490d0]
  19  ??? (libdispatch.dylib + 9072) [0x1a1547370]
  19  ??? (BasebandTraceHelper + 289936) [0x259d82c90]
  19  ??? (libsystem_kernel.dylib + 23744) [0x1e94ffcc0]

Powerstats for:   abm-helper [165]
UUID:             AA8EBB25-5216-3976-A7D4-B5652D7CE930
Path:             /System/Library/PrivateFrameworks/ABMHelper.framework/Support/abm-helper
Resource Coalition: 19 samples "com.apple.abm-helper"(263)
Architecture:     arm64e
Parent:           UNKNOWN [1]
UID:              25
Sudden Term:      Tracked
Footprint:        3776 KB -> 3792 KB (+16 KB) (max 4288 KB )
Start time:       2024-09-05 19:06:43.415 -0500
End time:         2024-09-05 19:13:09.773 -0500
Num samples:      19 (86%)
Num threads:      6
Primary state:    15 samples Non-Frontmost App, Non-Suppressed, Kernel mode, Effective Thread QoS Background, Requested Thread QoS Default, Override Thread QoS Unspecified, e-core
User Activity:    19 samples Idle, 0 samples Active
Power Source:     19 samples on Battery, 0 samples on AC
  19  ??? (libsystem_pthread.dylib + 5256) [0x22099a488]
    19  ??? (libsystem_pthread.dylib + 19580) [0x22099dc7c]
      19  ??? (libdispatch.dylib + 92836) [0x1a155baa4]
        19  ??? (libdispatch.dylib + 94808) [0x1a155c258]
          19  ??? (libdispatch.dylib + 49632) [0x1a15511e0]
            19  ??? (libdispatch.dylib + 46808) [0x1a15506d8]
              19  ??? (libdispatch.dylib + 16592) [0x1a15490d0]
                19  ??? (libdispatch.dylib + 9072) [0x1a1547370]
                  19  ??? (BasebandTraceHelper + 289936) [0x259d82c90]
                    19  ??? (libsystem_kernel.dylib + 23744) [0x1e94ffcc0]
                      4   <Effective Thread QoS Default>

  Binary Images:
           0x104980000 -                ???  abm-helper              <AA8EBB25-5216-3976-A7D4-B5652D7CE930>  /System/Library/PrivateFrameworks/ABMHelper.framework/Support/abm-helper
           0x1a1545000 -        0x1a158afff  libdispatch.dylib       <B8C15E69-D076-317D-9296-1279500738FC>  /usr/lib/system/libdispatch.dylib
           0x1e94fa000 -        0x1e9533ffb  libsystem_kernel.dylib  <8D929B3B-D4D6-39BF-ADBB-BE59E928B332>  /usr/lib/system/libsystem_kernel.dylib
           0x220999000 -        0x2209a5ff3  libsystem_pthread.dylib <FCC77EB0-558F-3703-9267-5419C4D33AE7>  /usr/lib/system/libsystem_pthread.dylib
           0x259d3c000 -        0x259d8ffff  BasebandTraceHelper     <517C24BF-492A-3FC3-919B-EAA116ACEC40>  /System/Library/PrivateFrameworks/BasebandTraceHelper.framework/BasebandTraceHelper


Powerstats for:   CommCenter
UUID:             9547A4E0-C8EA-3CC9-A53F-C6E8C9446B56
Path:             /System/Library/Frameworks/CoreTelephony.framework/Support/CommCenter
Resource Coalition: 2 samples "com.apple.CommCenter"(139)
Architecture:     arm64e
Start time:       2024-09-05 19:10:05.105 -0500
End time:         2024-09-05 19:10:06.067 -0500
Num samples:      2 (9%)
Primary state:    2 samples Non-Frontmost App, Non-Suppressed, Kernel mode, Effective Thread QoS Default, Requested Thread QoS Background, Override Thread QoS Unspecified, p-core
User Activity:    2 samples Idle, 0 samples Active
Power Source:     2 samples on Battery, 0 samples on AC
  2  ??? (libsystem_pthread.dylib + 5256) [0x22099a488]
    2  ??? (libsystem_pthread.dylib + 19580) [0x22099dc7c]
      2  ??? (libdispatch.dylib + 92836) [0x1a155baa4]
        2  ??? (libdispatch.dylib + 94808) [0x1a155c258]
          2  ??? (libdispatch.dylib + 54896) [0x1a1552670]
            2  ??? (libdispatch.dyl    2  ??? (libdispatch.dylib + 54896) [0x1a1552670]
            2  ??? (libdispatch.dylib + 49684) [0x1a1551214]
              2  ??? (libdispatch.dylib + 46432) [0x1a1550560]
                2  ??? (libdispatch.dylib + 106756) [0x1a155f104]
                  2  ??? (libdispatch.dylib + 111932) [0x1a156053c]
                    2  ??? (libdispatch.dylib + 30080) [0x1a154c580]
                      2  ??? (libdispatch.dylib + 16592) [0x1a15490d0]
                        2  ??? (libTelephonyUtilDynamic.dylib + 288004) [0x1a8a3c504]
                          2  ??? (CommCenter + 19461528) [0x10331f598]
                            2  ??? (CommCenter + 19463400) [0x10331fce8]
                              1  ??? (CommCenter + 19467516) [0x103320cfc]
                                1  ??? (CommCenter + 19466596) [0x103320964]
                                  1  ??? (SymptomAnalytics + 34140) [0x1e912055c]
                                    1  ??? (SymptomAnalytics + 19180) [0x1e911caec]
                                      1  ??? (CoreData + 789136) [0x1a1846a90]
                                        1  ??? (CoreData + 70440) [0x1a1797328]
                                          1  ??? (CoreData + 73476) [0x1a1797f04]
                                            1  ??? (CoreData + 1609656) [0x1a190efb8]
                                              1  ??? (CoreData + 224660) [0x1a17bcd94]
                                                1  ??? (CoreData + 143172) [0x1a17a8f44]
                                                  1  ??? (CoreData + 143680) [0x1a17a9140]
                                                    1  ??? (CoreData + 143992) [0x1a17a9278]
                                                      1  ??? (CoreData + 144308) [0x1a17a93b4]
                                                        1  ??? (libdispatch.dylib + 79696) [0x1a1558750]
                                                          1  ??? (libdispatch.dylib + 16592) [0x1a15490d0]
                                                            1  ??? (CoreData + 354120) [0x1a17dc748]
                                                              1  ??? (CoreData + 354320) [0x1a17dc810]
                                                                1  ??? (CoreData + 355048) [0x1a17dcae8]
                                                                  1  ??? (CoreData + 431988) [0x1a17ef774]
                                                                    1  ??? (CoreData + 561476) [0x1a180f144]
                                                                      1  ??? (CoreData + 566496) [0x1a18104e0]
                                                                        1  ??? (CoreData + 17612) [0x1a178a4cc]
                                                                          1  ??? (libsqlite3.dylib + 177992) [0x1c6b38748]
                                                                            1  ??? (libsqlite3.dylib + 222876) [0x1c6b4369c]
                                                                              1  ??? (libsqlite3.dylib + 88076) [0x1c6b2280c]
                                                                                1  ??? (libsqlite3.dylib + 245984) [0x1c6b490e0]
                                                                                  1  ??? (libsqlite3.dylib + 247064) [0x1c6b49518]
                                                                                    1  ??? (libsqlite3.dylib + 310152) [0x1c6b58b88]
                                                                                      1  ??? (libsqlite3.dylib + 629664) [0x1c6ba6ba0]
                                                                                        1  ??? (libsqlite3.dylib + 310888) [0x1c6b58e68]
                                                                                          1  ??? (libsystem_kernel.dylib + 30356) [0x1e9501694]
                              1  ??? (CommCenter + 19467236) [0x103320be4]
                                1  ??? (CommCenter + 19466932) [0x103320ab4]
                                  1  ??? (CommCenter + 19466596) [0x103320964]
                                    1  ??? (SymptomAnalytics + 34140) [0x1e912055c]
                                      1  ??? (SymptomAnalytics + 19180) [0x1e911caec]
                                        1  ??? (CoreData + 789136) [0x1a1846a90]
                                          1  ??? (CoreData + 70440) [0x1a1797328]
                                            1  ??? (CoreData + 73476) [0x1a1797f04]
                                              1  ??? (CoreData + 1609656) [0x1a190efb8]
                                                1  ??? (CoreData + 224660) [0x1a17bcd94]
                                                  1  ??? (CoreData + 143172) [0x1a17a8f44]
                                                    1  ??? (CoreData + 143680) [0x1a17a9140]
                                                      1  ??? (CoreData + 143 1  ??? (CoreData + 143992) [0x1a17a9278]
                                                        1  ??? (CoreData + 144308) [0x1a17a93b4]
                                                          1  ??? (libdispatch.dylib + 79696) [0x1a1558750]
                                                            1  ??? (libdispatch.dylib + 16592) [0x1a15490d0]
                                                              1  ??? (CoreData + 354120) [0x1a17dc748]
                                                                1  ??? (CoreData + 354320) [0x1a17dc810]
                                                                  1  ??? (CoreData + 355048) [0x1a17dcae8]
                                                                    1  ??? (CoreData + 431988) [0x1a17ef774]
                                                                      1  ??? (CoreData + 561476) [0x1a180f144]
                                                                        1  ??? (CoreData + 566496) [0x1a18104e0]
                                                                          1  ??? (CoreData + 17612) [0x1a178a4cc]
                                                                            1  ??? (libsqlite3.dylib + 177992) [0x1c6b38748]
                                                                              1  ??? (libsqlite3.dylib + 222876) [0x1c6b4369c]
                                                                                1  ??? (libsqlite3.dylib + 88076) [0x1c6b2280c]
                                                                                  1  ??? (libsqlite3.dylib + 245984) [0x1c6b490e0]
                                                                                    1  ??? (libsqlite3.dylib + 247064) [0x1c6b49518]
                                                                                      1  ??? (libsqlite3.dylib + 310152) [0x1c6b58b88]
                                                                                        1  ??? (libsqlite3.dylib + 629664) [0x1c6ba6ba0]
                                                                                          1  ??? (libsqlite3.dylib + 310888) [0x1c6b58e68]
                                                                                            1  ??? (libsystem_kernel.dylib + 30356) [0x1e9501694]

  Binary Images:
           0x102090000 -                ???  CommCenter                    <9547A4E0-C8EA-3CC9-A53F-C6E8C9446B56>  /System/Library/Frameworks/CoreTelephony.framework/Support/CommCenter
           0x1a1545000 -        0x1a158afff  libdispatch.dylib             <B8C15E69-D076-317D-9296-1279500738FC>  /usr/lib/system/libdispatch.dylib
           0x1a1786000 -        0x1a1b0efff  CoreData                      <E8FCE3F2-E6CF-3100-BCD1-D59DB9303428>  /System/Library/Frameworks/CoreData.framework/CoreData
           0x1a89f6000 -        0x1a8a7afff  libTelephonyUtilDynamic.dylib <C8A4A7A3-3098-3802-B4F9-E6DB290EF13F>  /usr/lib/libTelephonyUtilDynamic.dylib
           0x1c6b0d000 -        0x1c6c8dff3  libsqlite3.dylib              <27D9421E-C13A-3E09-A2C4-A5033278CBC4>  /usr/lib/libsqlite3.dylib
           0x1e9118000 -        0x1e912afff  SymptomAnalytics              <B5A97C74-404A-351A-A7F9-084BC0A18C4C>  /System/Library/PrivateFrameworks/Symptoms.framework/Frameworks/SymptomAnalytics.framework/SymptomAnalytics
           0x1e94fa000 -        0x1e9533ffb  libsystem_kernel.dylib        <8D929B3B-D4D6-39BF-ADBB-BE59E928B332>  /usr/lib/system/libsystem_kernel.dylib
           0x220999000 -        0x2209a5ff3  libsystem_pthread.dylib       <FCC77EB0-558F-3703-9267-5419C4D33AE7>  /usr/lib/system/libsystem_pthread.dylib
