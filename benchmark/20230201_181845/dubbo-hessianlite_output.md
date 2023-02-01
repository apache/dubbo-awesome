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
# Warmup Iteration   1: 0.806 ops/ms
Iteration   1: 1.930 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.930 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 1.998 ops/ms
Iteration   1: 6.821 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.821 ops/ms


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
# Warmup Iteration   1: 1.399 ops/ms
Iteration   1: 3.827 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.827 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.817 ops/ms
Iteration   1: 1.207 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.207 ops/ms


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
# Warmup Iteration   1: 18.772 ±(99.9%) 0.341 ms/op
Iteration   1: 9.436 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.436 ms/op


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
# Warmup Iteration   1: 8.745 ±(99.9%) 0.133 ms/op
Iteration   1: 4.802 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.802 ms/op


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
# Warmup Iteration   1: 14.418 ±(99.9%) 0.232 ms/op
Iteration   1: 5.047 ±(99.9%) 0.046 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.047 ms/op


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
# Warmup Iteration   1: 35.072 ±(99.9%) 0.538 ms/op
Iteration   1: 21.665 ±(99.9%) 0.143 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  21.665 ms/op


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
# Warmup Iteration   1: 12.097 ±(99.9%) 0.480 ms/op
Iteration   1: 7.058 ±(99.9%) 0.147 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   6.554 ms/op
                 createUser·p0.90:   8.307 ms/op
                 createUser·p0.95:   14.742 ms/op
                 createUser·p0.99:   21.501 ms/op
                 createUser·p0.999:  25.231 ms/op
                 createUser·p0.9999: 25.297 ms/op
                 createUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4544
  mean =      7.058 ±(99.9%) 0.147 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 424 
    [ 5.000,  7.500) = 3412 
    [ 7.500, 10.000) = 354 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      6.554 ms/op
     p(90.0000) =      8.307 ms/op
     p(95.0000) =     14.742 ms/op
     p(99.0000) =     21.501 ms/op
     p(99.9000) =     25.231 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     25.297 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 7.216 ±(99.9%) 0.214 ms/op
Iteration   1: 4.083 ±(99.9%) 0.124 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   5.484 ms/op
                 existUser·p0.95:   8.651 ms/op
                 existUser·p0.99:   20.269 ms/op
                 existUser·p0.999:  41.691 ms/op
                 existUser·p0.9999: 41.746 ms/op
                 existUser·p1.00:   41.746 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7851
  mean =      4.083 ±(99.9%) 0.124 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6849 
    [ 5.000, 10.000) = 723 
    [10.000, 15.000) = 175 
    [15.000, 20.000) = 26 
    [20.000, 25.000) = 46 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      5.484 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     20.269 ms/op
     p(99.9000) =     41.691 ms/op
     p(99.9900) =     41.746 ms/op
     p(99.9990) =     41.746 ms/op
     p(99.9999) =     41.746 ms/op
    p(100.0000) =     41.746 ms/op


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
# Warmup Iteration   1: 9.104 ±(99.9%) 0.377 ms/op
Iteration   1: 4.690 ±(99.9%) 0.089 ms/op
                 getUser·p0.00:   0.372 ms/op
                 getUser·p0.50:   4.174 ms/op
                 getUser·p0.90:   5.673 ms/op
                 getUser·p0.95:   6.734 ms/op
                 getUser·p0.99:   15.741 ms/op
                 getUser·p0.999:  27.627 ms/op
                 getUser·p0.9999: 29.753 ms/op
                 getUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6824
  mean =      4.690 ±(99.9%) 0.089 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 5447 
    [ 5.000,  7.500) = 1038 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.372 ms/op
     p(50.0000) =      4.174 ms/op
     p(90.0000) =      5.673 ms/op
     p(95.0000) =      6.734 ms/op
     p(99.0000) =     15.741 ms/op
     p(99.9000) =     27.627 ms/op
     p(99.9900) =     29.753 ms/op
     p(99.9990) =     29.753 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 26.771 ±(99.9%) 0.889 ms/op
Iteration   1: 21.242 ±(99.9%) 0.399 ms/op
                 listUser·p0.00:   4.776 ms/op
                 listUser·p0.50:   21.201 ms/op
                 listUser·p0.90:   26.214 ms/op
                 listUser·p0.95:   27.754 ms/op
                 listUser·p0.99:   34.496 ms/op
                 listUser·p0.999:  40.410 ms/op
                 listUser·p0.9999: 40.829 ms/op
                 listUser·p1.00:   40.829 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1532
  mean =     21.242 ±(99.9%) 0.399 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1 
    [ 5.000, 10.000) = 35 
    [10.000, 15.000) = 124 
    [15.000, 20.000) = 224 
    [20.000, 25.000) = 863 
    [25.000, 30.000) = 244 
    [30.000, 35.000) = 28 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      4.776 ms/op
     p(50.0000) =     21.201 ms/op
     p(90.0000) =     26.214 ms/op
     p(95.0000) =     27.754 ms/op
     p(99.0000) =     34.496 ms/op
     p(99.9000) =     40.410 ms/op
     p(99.9900) =     40.829 ms/op
     p(99.9990) =     40.829 ms/op
     p(99.9999) =     40.829 ms/op
    p(100.0000) =     40.829 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.930          ops/ms
Client.existUser                       thrpt         6.821          ops/ms
Client.getUser                         thrpt         3.827          ops/ms
Client.listUser                        thrpt         1.207          ops/ms
Client.createUser                       avgt         9.436           ms/op
Client.existUser                        avgt         4.802           ms/op
Client.getUser                          avgt         5.047           ms/op
Client.listUser                         avgt        21.665           ms/op
Client.createUser                     sample  4544   7.058 ± 0.147   ms/op
Client.createUser:createUser·p0.00    sample         1.096           ms/op
Client.createUser:createUser·p0.50    sample         6.554           ms/op
Client.createUser:createUser·p0.90    sample         8.307           ms/op
Client.createUser:createUser·p0.95    sample        14.742           ms/op
Client.createUser:createUser·p0.99    sample        21.501           ms/op
Client.createUser:createUser·p0.999   sample        25.231           ms/op
Client.createUser:createUser·p0.9999  sample        25.297           ms/op
Client.createUser:createUser·p1.00    sample        25.297           ms/op
Client.existUser                      sample  7851   4.083 ± 0.124   ms/op
Client.existUser:existUser·p0.00      sample         0.578           ms/op
Client.existUser:existUser·p0.50      sample         3.379           ms/op
Client.existUser:existUser·p0.90      sample         5.484           ms/op
Client.existUser:existUser·p0.95      sample         8.651           ms/op
Client.existUser:existUser·p0.99      sample        20.269           ms/op
Client.existUser:existUser·p0.999     sample        41.691           ms/op
Client.existUser:existUser·p0.9999    sample        41.746           ms/op
Client.existUser:existUser·p1.00      sample        41.746           ms/op
Client.getUser                        sample  6824   4.690 ± 0.089   ms/op
Client.getUser:getUser·p0.00          sample         0.372           ms/op
Client.getUser:getUser·p0.50          sample         4.174           ms/op
Client.getUser:getUser·p0.90          sample         5.673           ms/op
Client.getUser:getUser·p0.95          sample         6.734           ms/op
Client.getUser:getUser·p0.99          sample        15.741           ms/op
Client.getUser:getUser·p0.999         sample        27.627           ms/op
Client.getUser:getUser·p0.9999        sample        29.753           ms/op
Client.getUser:getUser·p1.00          sample        29.753           ms/op
Client.listUser                       sample  1532  21.242 ± 0.399   ms/op
Client.listUser:listUser·p0.00        sample         4.776           ms/op
Client.listUser:listUser·p0.50        sample        21.201           ms/op
Client.listUser:listUser·p0.90        sample        26.214           ms/op
Client.listUser:listUser·p0.95        sample        27.754           ms/op
Client.listUser:listUser·p0.99        sample        34.496           ms/op
Client.listUser:listUser·p0.999       sample        40.410           ms/op
Client.listUser:listUser·p0.9999      sample        40.829           ms/op
Client.listUser:listUser·p1.00        sample        40.829           ms/op
