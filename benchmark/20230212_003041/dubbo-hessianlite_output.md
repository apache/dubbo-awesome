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
# Warmup Iteration   1: 1.004 ops/ms
Iteration   1: 2.485 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.485 ops/ms


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
# Warmup Iteration   1: 4.235 ops/ms
Iteration   1: 6.535 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.535 ops/ms


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
# Warmup Iteration   1: 2.145 ops/ms
Iteration   1: 5.146 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.146 ops/ms


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
# Warmup Iteration   1: 0.916 ops/ms
Iteration   1: 1.432 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.432 ops/ms


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
# Warmup Iteration   1: 14.664 ±(99.9%) 0.259 ms/op
Iteration   1: 5.820 ±(99.9%) 0.053 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.820 ms/op


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
# Warmup Iteration   1: 5.698 ±(99.9%) 0.099 ms/op
Iteration   1: 3.638 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.638 ms/op


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
# Warmup Iteration   1: 7.012 ±(99.9%) 0.119 ms/op
Iteration   1: 4.066 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.066 ms/op


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
# Warmup Iteration   1: 28.555 ±(99.9%) 0.392 ms/op
Iteration   1: 14.912 ±(99.9%) 0.066 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  14.912 ms/op


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
# Warmup Iteration   1: 10.011 ±(99.9%) 0.318 ms/op
Iteration   1: 5.921 ±(99.9%) 0.115 ms/op
                 createUser·p0.00:   1.401 ms/op
                 createUser·p0.50:   6.283 ms/op
                 createUser·p0.90:   7.001 ms/op
                 createUser·p0.95:   8.471 ms/op
                 createUser·p0.99:   18.874 ms/op
                 createUser·p0.999:  26.613 ms/op
                 createUser·p0.9999: 26.935 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5413
  mean =      5.921 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 587 
    [ 2.500,  5.000) = 547 
    [ 5.000,  7.500) = 3906 
    [ 7.500, 10.000) = 250 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      6.283 ms/op
     p(90.0000) =      7.001 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     18.874 ms/op
     p(99.9000) =     26.613 ms/op
     p(99.9900) =     26.935 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 5.646 ±(99.9%) 0.158 ms/op
Iteration   1: 3.647 ±(99.9%) 0.049 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   10.826 ms/op
                 existUser·p0.999:  16.519 ms/op
                 existUser·p0.9999: 18.907 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8760
  mean =      3.647 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 1026 
    [ 2.500,  3.750) = 3989 
    [ 3.750,  5.000) = 3376 
    [ 5.000,  6.250) = 207 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =     10.826 ms/op
     p(99.9000) =     16.519 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 9.821 ±(99.9%) 0.336 ms/op
Iteration   1: 4.645 ±(99.9%) 0.050 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   4.538 ms/op
                 getUser·p0.90:   5.439 ms/op
                 getUser·p0.95:   6.207 ms/op
                 getUser·p0.99:   9.980 ms/op
                 getUser·p0.999:  13.664 ms/op
                 getUser·p0.9999: 13.664 ms/op
                 getUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6885
  mean =      4.645 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 265 
    [ 2.500,  3.750) = 395 
    [ 3.750,  5.000) = 4806 
    [ 5.000,  6.250) = 1090 
    [ 6.250,  7.500) = 128 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      6.207 ms/op
     p(99.0000) =      9.980 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     13.664 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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
# Warmup Iteration   1: 23.581 ±(99.9%) 0.768 ms/op
Iteration   1: 15.946 ±(99.9%) 0.299 ms/op
                 listUser·p0.00:   9.028 ms/op
                 listUser·p0.50:   16.581 ms/op
                 listUser·p0.90:   19.104 ms/op
                 listUser·p0.95:   24.101 ms/op
                 listUser·p0.99:   28.606 ms/op
                 listUser·p0.999:  31.885 ms/op
                 listUser·p0.9999: 32.408 ms/op
                 listUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1996
  mean =     15.946 ±(99.9%) 0.299 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 522 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 816 
    [17.500, 20.000) = 363 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      9.028 ms/op
     p(50.0000) =     16.581 ms/op
     p(90.0000) =     19.104 ms/op
     p(95.0000) =     24.101 ms/op
     p(99.0000) =     28.606 ms/op
     p(99.9000) =     31.885 ms/op
     p(99.9900) =     32.408 ms/op
     p(99.9990) =     32.408 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.485          ops/ms
Client.existUser                       thrpt         6.535          ops/ms
Client.getUser                         thrpt         5.146          ops/ms
Client.listUser                        thrpt         1.432          ops/ms
Client.createUser                       avgt         5.820           ms/op
Client.existUser                        avgt         3.638           ms/op
Client.getUser                          avgt         4.066           ms/op
Client.listUser                         avgt        14.912           ms/op
Client.createUser                     sample  5413   5.921 ± 0.115   ms/op
Client.createUser:createUser·p0.00    sample         1.401           ms/op
Client.createUser:createUser·p0.50    sample         6.283           ms/op
Client.createUser:createUser·p0.90    sample         7.001           ms/op
Client.createUser:createUser·p0.95    sample         8.471           ms/op
Client.createUser:createUser·p0.99    sample        18.874           ms/op
Client.createUser:createUser·p0.999   sample        26.613           ms/op
Client.createUser:createUser·p0.9999  sample        26.935           ms/op
Client.createUser:createUser·p1.00    sample        26.935           ms/op
Client.existUser                      sample  8760   3.647 ± 0.049   ms/op
Client.existUser:existUser·p0.00      sample         0.777           ms/op
Client.existUser:existUser·p0.50      sample         3.088           ms/op
Client.existUser:existUser·p0.90      sample         4.555           ms/op
Client.existUser:existUser·p0.95      sample         4.874           ms/op
Client.existUser:existUser·p0.99      sample        10.826           ms/op
Client.existUser:existUser·p0.999     sample        16.519           ms/op
Client.existUser:existUser·p0.9999    sample        18.907           ms/op
Client.existUser:existUser·p1.00      sample        18.907           ms/op
Client.getUser                        sample  6885   4.645 ± 0.050   ms/op
Client.getUser:getUser·p0.00          sample         1.079           ms/op
Client.getUser:getUser·p0.50          sample         4.538           ms/op
Client.getUser:getUser·p0.90          sample         5.439           ms/op
Client.getUser:getUser·p0.95          sample         6.207           ms/op
Client.getUser:getUser·p0.99          sample         9.980           ms/op
Client.getUser:getUser·p0.999         sample        13.664           ms/op
Client.getUser:getUser·p0.9999        sample        13.664           ms/op
Client.getUser:getUser·p1.00          sample        13.664           ms/op
Client.listUser                       sample  1996  15.946 ± 0.299   ms/op
Client.listUser:listUser·p0.00        sample         9.028           ms/op
Client.listUser:listUser·p0.50        sample        16.581           ms/op
Client.listUser:listUser·p0.90        sample        19.104           ms/op
Client.listUser:listUser·p0.95        sample        24.101           ms/op
Client.listUser:listUser·p0.99        sample        28.606           ms/op
Client.listUser:listUser·p0.999       sample        31.885           ms/op
Client.listUser:listUser·p0.9999      sample        32.408           ms/op
Client.listUser:listUser·p1.00        sample        32.408           ms/op
