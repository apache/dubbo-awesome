# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.093 ops/ms
Iteration   1: 1.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.962 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.130 ops/ms
Iteration   1: 5.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  5.508 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.285 ops/ms
Iteration   1: 3.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  3.644 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.741 ops/ms
Iteration   1: 2.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.912 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 14.479 ±(99.9%) 0.286 ms/op
Iteration   1: 7.600 ±(99.9%) 0.073 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.600 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 5.900 ±(99.9%) 0.078 ms/op
Iteration   1: 3.348 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  3.348 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.767 ±(99.9%) 0.216 ms/op
Iteration   1: 7.350 ±(99.9%) 0.064 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  7.350 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.798 ±(99.9%) 0.348 ms/op
Iteration   1: 10.493 ±(99.9%) 0.092 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  10.493 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.544 ±(99.9%) 0.413 ms/op
Iteration   1: 7.348 ±(99.9%) 0.143 ms/op
                 createUser·p0.00:   3.121 ms/op
                 createUser·p0.50:   6.652 ms/op
                 createUser·p0.90:   9.902 ms/op
                 createUser·p0.95:   11.685 ms/op
                 createUser·p0.99:   19.269 ms/op
                 createUser·p0.999:  24.904 ms/op
                 createUser·p0.9999: 28.705 ms/op
                 createUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 4395
  mean =      7.348 ±(99.9%) 0.143 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 325 
    [ 5.000,  7.500) = 2687 
    [ 7.500, 10.000) = 966 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.121 ms/op
     p(50.0000) =      6.652 ms/op
     p(90.0000) =      9.902 ms/op
     p(95.0000) =     11.685 ms/op
     p(99.0000) =     19.269 ms/op
     p(99.9000) =     24.904 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     28.705 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.480 ±(99.9%) 0.115 ms/op
Iteration   1: 3.323 ±(99.9%) 0.062 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   13.386 ms/op
                 existUser·p0.999:  17.945 ms/op
                 existUser·p0.9999: 18.842 ms/op
                 existUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 9679
  mean =      3.323 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 2117 
    [ 2.500,  3.750) = 5536 
    [ 3.750,  5.000) = 1561 
    [ 5.000,  6.250) = 105 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =     13.386 ms/op
     p(99.9000) =     17.945 ms/op
     p(99.9900) =     18.842 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 9.405 ±(99.9%) 0.320 ms/op
Iteration   1: 7.117 ±(99.9%) 0.182 ms/op
                 getUser·p0.00:   1.780 ms/op
                 getUser·p0.50:   6.775 ms/op
                 getUser·p0.90:   8.651 ms/op
                 getUser·p0.95:   9.388 ms/op
                 getUser·p0.99:   13.854 ms/op
                 getUser·p0.999:  53.459 ms/op
                 getUser·p0.9999: 74.449 ms/op
                 getUser·p1.00:   74.449 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 4541
  mean =      7.117 ±(99.9%) 0.182 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 415 
    [ 5.000, 10.000) = 3965 
    [10.000, 15.000) = 117 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 8 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 9 
    [45.000, 50.000) = 11 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 1 
    [60.000, 65.000) = 2 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.780 ms/op
     p(50.0000) =      6.775 ms/op
     p(90.0000) =      8.651 ms/op
     p(95.0000) =      9.388 ms/op
     p(99.0000) =     13.854 ms/op
     p(99.9000) =     53.459 ms/op
     p(99.9900) =     74.449 ms/op
     p(99.9990) =     74.449 ms/op
     p(99.9999) =     74.449 ms/op
    p(100.0000) =     74.449 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 13.475 ±(99.9%) 0.463 ms/op
Iteration   1: 9.929 ±(99.9%) 0.169 ms/op
                 listUser·p0.00:   4.145 ms/op
                 listUser·p0.50:   9.241 ms/op
                 listUser·p0.90:   12.812 ms/op
                 listUser·p0.95:   14.696 ms/op
                 listUser·p0.99:   23.940 ms/op
                 listUser·p0.999:  26.916 ms/op
                 listUser·p0.9999: 33.063 ms/op
                 listUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 3301
  mean =      9.929 ±(99.9%) 0.169 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 24 
    [ 5.000,  7.500) = 352 
    [ 7.500, 10.000) = 1728 
    [10.000, 12.500) = 746 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      4.145 ms/op
     p(50.0000) =      9.241 ms/op
     p(90.0000) =     12.812 ms/op
     p(95.0000) =     14.696 ms/op
     p(99.0000) =     23.940 ms/op
     p(99.9000) =     26.916 ms/op
     p(99.9900) =     33.063 ms/op
     p(99.9990) =     33.063 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode   Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt         1.962          ops/ms
ClientSimple.existUser                       thrpt         5.508          ops/ms
ClientSimple.getUser                         thrpt         3.644          ops/ms
ClientSimple.listUser                        thrpt         2.912          ops/ms
ClientSimple.createUser                       avgt         7.600           ms/op
ClientSimple.existUser                        avgt         3.348           ms/op
ClientSimple.getUser                          avgt         7.350           ms/op
ClientSimple.listUser                         avgt        10.493           ms/op
ClientSimple.createUser                     sample  4395   7.348 ± 0.143   ms/op
ClientSimple.createUser:createUser·p0.00    sample         3.121           ms/op
ClientSimple.createUser:createUser·p0.50    sample         6.652           ms/op
ClientSimple.createUser:createUser·p0.90    sample         9.902           ms/op
ClientSimple.createUser:createUser·p0.95    sample        11.685           ms/op
ClientSimple.createUser:createUser·p0.99    sample        19.269           ms/op
ClientSimple.createUser:createUser·p0.999   sample        24.904           ms/op
ClientSimple.createUser:createUser·p0.9999  sample        28.705           ms/op
ClientSimple.createUser:createUser·p1.00    sample        28.705           ms/op
ClientSimple.existUser                      sample  9679   3.323 ± 0.062   ms/op
ClientSimple.existUser:existUser·p0.00      sample         0.764           ms/op
ClientSimple.existUser:existUser·p0.50      sample         2.904           ms/op
ClientSimple.existUser:existUser·p0.90      sample         4.243           ms/op
ClientSimple.existUser:existUser·p0.95      sample         4.825           ms/op
ClientSimple.existUser:existUser·p0.99      sample        13.386           ms/op
ClientSimple.existUser:existUser·p0.999     sample        17.945           ms/op
ClientSimple.existUser:existUser·p0.9999    sample        18.842           ms/op
ClientSimple.existUser:existUser·p1.00      sample        18.842           ms/op
ClientSimple.getUser                        sample  4541   7.117 ± 0.182   ms/op
ClientSimple.getUser:getUser·p0.00          sample         1.780           ms/op
ClientSimple.getUser:getUser·p0.50          sample         6.775           ms/op
ClientSimple.getUser:getUser·p0.90          sample         8.651           ms/op
ClientSimple.getUser:getUser·p0.95          sample         9.388           ms/op
ClientSimple.getUser:getUser·p0.99          sample        13.854           ms/op
ClientSimple.getUser:getUser·p0.999         sample        53.459           ms/op
ClientSimple.getUser:getUser·p0.9999        sample        74.449           ms/op
ClientSimple.getUser:getUser·p1.00          sample        74.449           ms/op
ClientSimple.listUser                       sample  3301   9.929 ± 0.169   ms/op
ClientSimple.listUser:listUser·p0.00        sample         4.145           ms/op
ClientSimple.listUser:listUser·p0.50        sample         9.241           ms/op
ClientSimple.listUser:listUser·p0.90        sample        12.812           ms/op
ClientSimple.listUser:listUser·p0.95        sample        14.696           ms/op
ClientSimple.listUser:listUser·p0.99        sample        23.940           ms/op
ClientSimple.listUser:listUser·p0.999       sample        26.916           ms/op
ClientSimple.listUser:listUser·p0.9999      sample        33.063           ms/op
ClientSimple.listUser:listUser·p1.00        sample        33.063           ms/op

Benchmark result is saved to 1715234730643.json
