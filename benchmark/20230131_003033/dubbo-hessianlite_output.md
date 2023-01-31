# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.133 ops/ms
Iteration   1: 2.379 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.379 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.474 ops/ms
Iteration   1: 5.238 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.238 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.359 ops/ms
Iteration   1: 4.636 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.636 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.714 ops/ms
Iteration   1: 1.163 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.163 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 21.109 ±(99.9%) 0.278 ms/op
Iteration   1: 7.940 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.940 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.864 ±(99.9%) 0.095 ms/op
Iteration   1: 4.230 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.230 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.827 ±(99.9%) 0.124 ms/op
Iteration   1: 5.192 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.192 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 29.297 ±(99.9%) 1.308 ms/op
Iteration   1: 19.226 ±(99.9%) 0.189 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.226 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.250 ±(99.9%) 0.391 ms/op
Iteration   1: 7.521 ±(99.9%) 0.118 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   7.037 ms/op
                 createUser·p0.90:   8.995 ms/op
                 createUser·p0.95:   9.448 ms/op
                 createUser·p0.99:   16.704 ms/op
                 createUser·p0.999:  25.019 ms/op
                 createUser·p0.9999: 25.231 ms/op
                 createUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4246
  mean =      7.521 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 308 
    [ 5.000,  7.500) = 2050 
    [ 7.500, 10.000) = 1692 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      7.037 ms/op
     p(90.0000) =      8.995 ms/op
     p(95.0000) =      9.448 ms/op
     p(99.0000) =     16.704 ms/op
     p(99.9000) =     25.019 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.358 ±(99.9%) 0.225 ms/op
Iteration   1: 4.291 ±(99.9%) 0.054 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   11.698 ms/op
                 existUser·p0.999:  15.991 ms/op
                 existUser·p0.9999: 16.499 ms/op
                 existUser·p1.00:   16.499 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7450
  mean =      4.291 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 174 
    [ 2.500,  3.750) = 1843 
    [ 3.750,  5.000) = 4951 
    [ 5.000,  6.250) = 207 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =     11.698 ms/op
     p(99.9000) =     15.991 ms/op
     p(99.9900) =     16.499 ms/op
     p(99.9990) =     16.499 ms/op
     p(99.9999) =     16.499 ms/op
    p(100.0000) =     16.499 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 9.334 ±(99.9%) 0.289 ms/op
Iteration   1: 5.126 ±(99.9%) 0.232 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   4.514 ms/op
                 getUser·p0.90:   5.698 ms/op
                 getUser·p0.95:   7.094 ms/op
                 getUser·p0.99:   20.128 ms/op
                 getUser·p0.999:  83.624 ms/op
                 getUser·p0.9999: 88.474 ms/op
                 getUser·p1.00:   88.474 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6274
  mean =      5.126 ±(99.9%) 0.232 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 5234 
    [ 5.000, 10.000) = 971 
    [10.000, 15.000) = 5 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 6 
    [25.000, 30.000) = 12 
    [30.000, 35.000) = 14 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 5 
    [75.000, 80.000) = 20 
    [80.000, 85.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.698 ms/op
     p(95.0000) =      7.094 ms/op
     p(99.0000) =     20.128 ms/op
     p(99.9000) =     83.624 ms/op
     p(99.9900) =     88.474 ms/op
     p(99.9990) =     88.474 ms/op
     p(99.9999) =     88.474 ms/op
    p(100.0000) =     88.474 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 28.016 ±(99.9%) 0.901 ms/op
Iteration   1: 18.304 ±(99.9%) 0.350 ms/op
                 listUser·p0.00:   10.469 ms/op
                 listUser·p0.50:   18.612 ms/op
                 listUser·p0.90:   24.350 ms/op
                 listUser·p0.95:   26.706 ms/op
                 listUser·p0.99:   30.875 ms/op
                 listUser·p0.999:  35.747 ms/op
                 listUser·p0.9999: 35.848 ms/op
                 listUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1768
  mean =     18.304 ±(99.9%) 0.350 ms/op

  Histogram, ms/op:
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 252 
    [17.500, 20.000) = 523 
    [20.000, 22.500) = 298 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =     10.469 ms/op
     p(50.0000) =     18.612 ms/op
     p(90.0000) =     24.350 ms/op
     p(95.0000) =     26.706 ms/op
     p(99.0000) =     30.875 ms/op
     p(99.9000) =     35.747 ms/op
     p(99.9900) =     35.848 ms/op
     p(99.9990) =     35.848 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.379          ops/ms
Client.existUser                       thrpt         5.238          ops/ms
Client.getUser                         thrpt         4.636          ops/ms
Client.listUser                        thrpt         1.163          ops/ms
Client.createUser                       avgt         7.940           ms/op
Client.existUser                        avgt         4.230           ms/op
Client.getUser                          avgt         5.192           ms/op
Client.listUser                         avgt        19.226           ms/op
Client.createUser                     sample  4246   7.521 ± 0.118   ms/op
Client.createUser:createUser·p0.00    sample         1.057           ms/op
Client.createUser:createUser·p0.50    sample         7.037           ms/op
Client.createUser:createUser·p0.90    sample         8.995           ms/op
Client.createUser:createUser·p0.95    sample         9.448           ms/op
Client.createUser:createUser·p0.99    sample        16.704           ms/op
Client.createUser:createUser·p0.999   sample        25.019           ms/op
Client.createUser:createUser·p0.9999  sample        25.231           ms/op
Client.createUser:createUser·p1.00    sample        25.231           ms/op
Client.existUser                      sample  7450   4.291 ± 0.054   ms/op
Client.existUser:existUser·p0.00      sample         0.653           ms/op
Client.existUser:existUser·p0.50      sample         4.211           ms/op
Client.existUser:existUser·p0.90      sample         4.628           ms/op
Client.existUser:existUser·p0.95      sample         5.333           ms/op
Client.existUser:existUser·p0.99      sample        11.698           ms/op
Client.existUser:existUser·p0.999     sample        15.991           ms/op
Client.existUser:existUser·p0.9999    sample        16.499           ms/op
Client.existUser:existUser·p1.00      sample        16.499           ms/op
Client.getUser                        sample  6274   5.126 ± 0.232   ms/op
Client.getUser:getUser·p0.00          sample         0.807           ms/op
Client.getUser:getUser·p0.50          sample         4.514           ms/op
Client.getUser:getUser·p0.90          sample         5.698           ms/op
Client.getUser:getUser·p0.95          sample         7.094           ms/op
Client.getUser:getUser·p0.99          sample        20.128           ms/op
Client.getUser:getUser·p0.999         sample        83.624           ms/op
Client.getUser:getUser·p0.9999        sample        88.474           ms/op
Client.getUser:getUser·p1.00          sample        88.474           ms/op
Client.listUser                       sample  1768  18.304 ± 0.350   ms/op
Client.listUser:listUser·p0.00        sample        10.469           ms/op
Client.listUser:listUser·p0.50        sample        18.612           ms/op
Client.listUser:listUser·p0.90        sample        24.350           ms/op
Client.listUser:listUser·p0.95        sample        26.706           ms/op
Client.listUser:listUser·p0.99        sample        30.875           ms/op
Client.listUser:listUser·p0.999       sample        35.747           ms/op
Client.listUser:listUser·p0.9999      sample        35.848           ms/op
Client.listUser:listUser·p1.00        sample        35.848           ms/op
