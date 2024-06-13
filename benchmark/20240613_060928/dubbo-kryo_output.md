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
# Warmup Iteration   1: 1.088 ops/ms
Iteration   1: 4.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  4.689 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.319 ops/ms
Iteration   1: 9.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  9.143 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.131 ops/ms
Iteration   1: 8.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  8.037 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.392 ops/ms
Iteration   1: 6.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  6.369 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.987 ±(99.9%) 0.178 ms/op
Iteration   1: 2.681 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.681 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.867 ±(99.9%) 0.086 ms/op
Iteration   1: 2.404 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.404 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.426 ±(99.9%) 0.109 ms/op
Iteration   1: 2.373 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.373 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 5.712 ±(99.9%) 0.129 ms/op
Iteration   1: 4.581 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.581 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.597 ±(99.9%) 0.133 ms/op
Iteration   1: 2.558 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   2.281 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.651 ms/op
                 createUser·p0.99:   11.028 ms/op
                 createUser·p0.999:  27.297 ms/op
                 createUser·p0.9999: 35.111 ms/op
                 createUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12492
  mean =      2.558 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8574 
    [ 2.500,  5.000) = 3597 
    [ 5.000,  7.500) = 147 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.281 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.651 ms/op
     p(99.0000) =     11.028 ms/op
     p(99.9000) =     27.297 ms/op
     p(99.9900) =     35.111 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 3.219 ±(99.9%) 0.084 ms/op
Iteration   1: 2.376 ±(99.9%) 0.045 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   2.167 ms/op
                 existUser·p0.90:   2.781 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   6.786 ms/op
                 existUser·p0.999:  26.771 ms/op
                 existUser·p0.9999: 27.739 ms/op
                 existUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 13464
  mean =      2.376 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10830 
    [ 2.500,  5.000) = 2325 
    [ 5.000,  7.500) = 187 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.781 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      6.786 ms/op
     p(99.9000) =     26.771 ms/op
     p(99.9900) =     27.739 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.113 ms/op
Iteration   1: 2.458 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   2.339 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.426 ms/op
                 getUser·p0.99:   6.330 ms/op
                 getUser·p0.999:  16.597 ms/op
                 getUser·p0.9999: 18.471 ms/op
                 getUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13011
  mean =      2.458 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 7735 
    [ 2.500,  3.750) = 4722 
    [ 3.750,  5.000) = 177 
    [ 5.000,  6.250) = 127 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.339 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.426 ms/op
     p(99.0000) =      6.330 ms/op
     p(99.9000) =     16.597 ms/op
     p(99.9900) =     18.471 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 5.091 ±(99.9%) 0.154 ms/op
Iteration   1: 3.609 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   3.461 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   8.281 ms/op
                 listUser·p0.999:  23.364 ms/op
                 listUser·p0.9999: 25.952 ms/op
                 listUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8905
  mean =      3.609 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 840 
    [ 2.500,  5.000) = 7659 
    [ 5.000,  7.500) = 273 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      8.281 ms/op
     p(99.9000) =     23.364 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# Run complete. Total time: 00:01:28

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          4.689          ops/ms
ClientSimple.existUser                       thrpt          9.143          ops/ms
ClientSimple.getUser                         thrpt          8.037          ops/ms
ClientSimple.listUser                        thrpt          6.369          ops/ms
ClientSimple.createUser                       avgt          2.681           ms/op
ClientSimple.existUser                        avgt          2.404           ms/op
ClientSimple.getUser                          avgt          2.373           ms/op
ClientSimple.listUser                         avgt          4.581           ms/op
ClientSimple.createUser                     sample  12492   2.558 ± 0.054   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.809           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.281           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.002           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.651           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.028           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.297           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.111           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.127           ms/op
ClientSimple.existUser                      sample  13464   2.376 ± 0.045   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.547           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.167           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.781           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.117           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.786           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.771           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.739           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.853           ms/op
ClientSimple.getUser                        sample  13011   2.458 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.804           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.339           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.125           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.426           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.330           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.597           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.471           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.481           ms/op
ClientSimple.listUser                       sample   8905   3.609 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.031           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.461           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.932           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.281           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.364           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.952           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.952           ms/op

Benchmark result is saved to 1718258733773.json
