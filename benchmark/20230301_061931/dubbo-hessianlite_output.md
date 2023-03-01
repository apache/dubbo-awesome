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
# Warmup Iteration   1: 1.238 ops/ms
Iteration   1: 2.870 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.870 ops/ms


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
# Warmup Iteration   1: 2.842 ops/ms
Iteration   1: 6.762 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.762 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.569 ops/ms
Iteration   1: 5.389 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.389 ops/ms


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
# Warmup Iteration   1: 1.126 ops/ms
Iteration   1: 1.775 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.775 ops/ms


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
# Warmup Iteration   1: 15.272 ±(99.9%) 0.265 ms/op
Iteration   1: 6.232 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.232 ms/op


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
# Warmup Iteration   1: 5.938 ±(99.9%) 0.089 ms/op
Iteration   1: 3.546 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.546 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.848 ±(99.9%) 0.115 ms/op
Iteration   1: 4.646 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.646 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 29.875 ±(99.9%) 0.621 ms/op
Iteration   1: 17.001 ±(99.9%) 0.047 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.001 ms/op


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
# Warmup Iteration   1: 10.922 ±(99.9%) 0.463 ms/op
Iteration   1: 5.681 ±(99.9%) 0.101 ms/op
                 createUser·p0.00:   1.249 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   7.763 ms/op
                 createUser·p0.95:   10.763 ms/op
                 createUser·p0.99:   13.766 ms/op
                 createUser·p0.999:  19.299 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5681
  mean =      5.681 ±(99.9%) 0.101 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 2554 
    [ 5.000,  7.500) = 2491 
    [ 7.500, 10.000) = 283 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      7.763 ms/op
     p(95.0000) =     10.763 ms/op
     p(99.0000) =     13.766 ms/op
     p(99.9000) =     19.299 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 6.008 ±(99.9%) 0.198 ms/op
Iteration   1: 3.388 ±(99.9%) 0.050 ms/op
                 existUser·p0.00:   0.525 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   11.606 ms/op
                 existUser·p0.999:  20.269 ms/op
                 existUser·p0.9999: 20.578 ms/op
                 existUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9453
  mean =      3.388 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 943 
    [ 2.500,  5.000) = 8127 
    [ 5.000,  7.500) = 255 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =     11.606 ms/op
     p(99.9000) =     20.269 ms/op
     p(99.9900) =     20.578 ms/op
     p(99.9990) =     20.578 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 10.381 ±(99.9%) 0.373 ms/op
Iteration   1: 4.233 ±(99.9%) 0.096 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.883 ms/op
                 getUser·p0.90:   4.915 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   18.153 ms/op
                 getUser·p0.999:  31.130 ms/op
                 getUser·p0.9999: 43.581 ms/op
                 getUser·p1.00:   43.581 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7547
  mean =      4.233 ±(99.9%) 0.096 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6898 
    [ 5.000, 10.000) = 525 
    [10.000, 15.000) = 28 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 21 
    [25.000, 30.000) = 16 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =     18.153 ms/op
     p(99.9000) =     31.130 ms/op
     p(99.9900) =     43.581 ms/op
     p(99.9990) =     43.581 ms/op
     p(99.9999) =     43.581 ms/op
    p(100.0000) =     43.581 ms/op


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
# Warmup Iteration   1: 25.800 ±(99.9%) 0.813 ms/op
Iteration   1: 15.655 ±(99.9%) 0.284 ms/op
                 listUser·p0.00:   3.551 ms/op
                 listUser·p0.50:   14.590 ms/op
                 listUser·p0.90:   19.857 ms/op
                 listUser·p0.95:   23.056 ms/op
                 listUser·p0.99:   31.413 ms/op
                 listUser·p0.999:  34.797 ms/op
                 listUser·p0.9999: 35.193 ms/op
                 listUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2046
  mean =     15.655 ±(99.9%) 0.284 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 7 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 877 
    [15.000, 17.500) = 526 
    [17.500, 20.000) = 299 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.551 ms/op
     p(50.0000) =     14.590 ms/op
     p(90.0000) =     19.857 ms/op
     p(95.0000) =     23.056 ms/op
     p(99.0000) =     31.413 ms/op
     p(99.9000) =     34.797 ms/op
     p(99.9900) =     35.193 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.870          ops/ms
Client.existUser                       thrpt         6.762          ops/ms
Client.getUser                         thrpt         5.389          ops/ms
Client.listUser                        thrpt         1.775          ops/ms
Client.createUser                       avgt         6.232           ms/op
Client.existUser                        avgt         3.546           ms/op
Client.getUser                          avgt         4.646           ms/op
Client.listUser                         avgt        17.001           ms/op
Client.createUser                     sample  5681   5.681 ± 0.101   ms/op
Client.createUser:createUser·p0.00    sample         1.249           ms/op
Client.createUser:createUser·p0.50    sample         5.087           ms/op
Client.createUser:createUser·p0.90    sample         7.763           ms/op
Client.createUser:createUser·p0.95    sample        10.763           ms/op
Client.createUser:createUser·p0.99    sample        13.766           ms/op
Client.createUser:createUser·p0.999   sample        19.299           ms/op
Client.createUser:createUser·p0.9999  sample        20.808           ms/op
Client.createUser:createUser·p1.00    sample        20.808           ms/op
Client.existUser                      sample  9453   3.388 ± 0.050   ms/op
Client.existUser:existUser·p0.00      sample         0.525           ms/op
Client.existUser:existUser·p0.50      sample         3.314           ms/op
Client.existUser:existUser·p0.90      sample         3.740           ms/op
Client.existUser:existUser·p0.95      sample         4.219           ms/op
Client.existUser:existUser·p0.99      sample        11.606           ms/op
Client.existUser:existUser·p0.999     sample        20.269           ms/op
Client.existUser:existUser·p0.9999    sample        20.578           ms/op
Client.existUser:existUser·p1.00      sample        20.578           ms/op
Client.getUser                        sample  7547   4.233 ± 0.096   ms/op
Client.getUser:getUser·p0.00          sample         1.083           ms/op
Client.getUser:getUser·p0.50          sample         3.883           ms/op
Client.getUser:getUser·p0.90          sample         4.915           ms/op
Client.getUser:getUser·p0.95          sample         5.317           ms/op
Client.getUser:getUser·p0.99          sample        18.153           ms/op
Client.getUser:getUser·p0.999         sample        31.130           ms/op
Client.getUser:getUser·p0.9999        sample        43.581           ms/op
Client.getUser:getUser·p1.00          sample        43.581           ms/op
Client.listUser                       sample  2046  15.655 ± 0.284   ms/op
Client.listUser:listUser·p0.00        sample         3.551           ms/op
Client.listUser:listUser·p0.50        sample        14.590           ms/op
Client.listUser:listUser·p0.90        sample        19.857           ms/op
Client.listUser:listUser·p0.95        sample        23.056           ms/op
Client.listUser:listUser·p0.99        sample        31.413           ms/op
Client.listUser:listUser·p0.999       sample        34.797           ms/op
Client.listUser:listUser·p0.9999      sample        35.193           ms/op
Client.listUser:listUser·p1.00        sample        35.193           ms/op
