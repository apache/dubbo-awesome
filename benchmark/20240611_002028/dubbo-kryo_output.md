# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.072 ops/ms
Iteration   1: 6.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.519 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.498 ops/ms
Iteration   1: 10.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.786 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.693 ops/ms
Iteration   1: 15.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.445 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.278 ops/ms
Iteration   1: 8.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.637 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.907 ±(99.9%) 0.066 ms/op
Iteration   1: 2.185 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.185 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.206 ±(99.9%) 0.063 ms/op
Iteration   1: 2.042 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.042 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.362 ±(99.9%) 0.071 ms/op
Iteration   1: 1.880 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.880 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.993 ±(99.9%) 0.139 ms/op
Iteration   1: 3.501 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.501 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.639 ±(99.9%) 0.083 ms/op
Iteration   1: 2.171 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   2.013 ms/op
                 createUser·p0.90:   2.531 ms/op
                 createUser·p0.95:   2.920 ms/op
                 createUser·p0.99:   6.912 ms/op
                 createUser·p0.999:  18.293 ms/op
                 createUser·p0.9999: 19.125 ms/op
                 createUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14727
  mean =      2.171 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 173 
    [ 1.250,  2.500) = 12962 
    [ 2.500,  3.750) = 1152 
    [ 3.750,  5.000) = 150 
    [ 5.000,  6.250) = 123 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      6.912 ms/op
     p(99.9000) =     18.293 ms/op
     p(99.9900) =     19.125 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.237 ±(99.9%) 0.077 ms/op
Iteration   1: 2.033 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   1.958 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.695 ms/op
                 existUser·p0.99:   3.035 ms/op
                 existUser·p0.999:  29.000 ms/op
                 existUser·p0.9999: 30.014 ms/op
                 existUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15772
  mean =      2.033 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14402 
    [ 2.500,  5.000) = 1306 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.035 ms/op
     p(99.9000) =     29.000 ms/op
     p(99.9900) =     30.014 ms/op
     p(99.9990) =     30.147 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.468 ±(99.9%) 0.098 ms/op
Iteration   1: 2.041 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   1.878 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   2.834 ms/op
                 getUser·p0.99:   3.725 ms/op
                 getUser·p0.999:  20.120 ms/op
                 getUser·p0.9999: 20.991 ms/op
                 getUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15650
  mean =      2.041 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13629 
    [ 2.500,  5.000) = 1898 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      3.725 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     20.991 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.753 ±(99.9%) 0.142 ms/op
Iteration   1: 3.563 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   0.736 ms/op
                 listUser·p0.50:   3.461 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.166 ms/op
                 listUser·p0.99:   7.551 ms/op
                 listUser·p0.999:  19.793 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8986
  mean =      3.563 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1156 
    [ 2.500,  5.000) = 7292 
    [ 5.000,  7.500) = 447 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.166 ms/op
     p(99.0000) =      7.551 ms/op
     p(99.9000) =     19.793 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.519          ops/ms
ClientSimple.existUser                       thrpt         10.786          ops/ms
ClientSimple.getUser                         thrpt         15.445          ops/ms
ClientSimple.listUser                        thrpt          8.637          ops/ms
ClientSimple.createUser                       avgt          2.185           ms/op
ClientSimple.existUser                        avgt          2.042           ms/op
ClientSimple.getUser                          avgt          1.880           ms/op
ClientSimple.listUser                         avgt          3.501           ms/op
ClientSimple.createUser                     sample  14727   2.171 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.821           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.013           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.531           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.920           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.912           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.293           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.125           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.202           ms/op
ClientSimple.existUser                      sample  15772   2.033 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.560           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.958           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.695           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.035           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.000           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.014           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.147           ms/op
ClientSimple.getUser                        sample  15650   2.041 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.743           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.878           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.834           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.725           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.120           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.991           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.103           ms/op
ClientSimple.listUser                       sample   8986   3.563 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.736           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.461           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.588           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.166           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.551           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.793           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.496           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.496           ms/op

Benchmark result is saved to 1718064950212.json
