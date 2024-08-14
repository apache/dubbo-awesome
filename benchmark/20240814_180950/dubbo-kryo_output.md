# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.732 ops/ms
Iteration   1: 6.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.544 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.794 ops/ms
Iteration   1: 13.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.552 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.965 ops/ms
Iteration   1: 13.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.271 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.788 ops/ms
Iteration   1: 8.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.599 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.357 ±(99.9%) 0.057 ms/op
Iteration   1: 2.238 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.238 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.193 ±(99.9%) 0.050 ms/op
Iteration   1: 1.867 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.867 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.391 ±(99.9%) 0.102 ms/op
Iteration   1: 2.154 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.154 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.480 ±(99.9%) 0.098 ms/op
Iteration   1: 3.859 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.859 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.689 ±(99.9%) 0.102 ms/op
Iteration   1: 2.297 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.396 ms/op
                 createUser·p0.50:   2.089 ms/op
                 createUser·p0.90:   2.896 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   5.791 ms/op
                 createUser·p0.999:  28.443 ms/op
                 createUser·p0.9999: 29.179 ms/op
                 createUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13904
  mean =      2.297 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9613 
    [ 2.500,  5.000) = 4028 
    [ 5.000,  7.500) = 167 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.396 ms/op
     p(50.0000) =      2.089 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      5.791 ms/op
     p(99.9000) =     28.443 ms/op
     p(99.9900) =     29.179 ms/op
     p(99.9990) =     29.295 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.895 ±(99.9%) 0.065 ms/op
Iteration   1: 1.819 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   1.747 ms/op
                 existUser·p0.90:   2.359 ms/op
                 existUser·p0.95:   2.520 ms/op
                 existUser·p0.99:   3.030 ms/op
                 existUser·p0.999:  11.010 ms/op
                 existUser·p0.9999: 11.076 ms/op
                 existUser·p1.00:   11.076 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17613
  mean =      1.819 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 645 
    [ 1.250,  2.500) = 16005 
    [ 2.500,  3.750) = 841 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.520 ms/op
     p(99.0000) =      3.030 ms/op
     p(99.9000) =     11.010 ms/op
     p(99.9900) =     11.076 ms/op
     p(99.9990) =     11.076 ms/op
     p(99.9999) =     11.076 ms/op
    p(100.0000) =     11.076 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.352 ±(99.9%) 0.091 ms/op
Iteration   1: 2.056 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   2.005 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   2.806 ms/op
                 getUser·p0.99:   3.181 ms/op
                 getUser·p0.999:  11.223 ms/op
                 getUser·p0.9999: 11.722 ms/op
                 getUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15547
  mean =      2.056 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 260 
    [ 1.250,  2.500) = 12357 
    [ 2.500,  3.750) = 2822 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      3.181 ms/op
     p(99.9000) =     11.223 ms/op
     p(99.9900) =     11.722 ms/op
     p(99.9990) =     11.731 ms/op
     p(99.9999) =     11.731 ms/op
    p(100.0000) =     11.731 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.604 ±(99.9%) 0.142 ms/op
Iteration   1: 3.396 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   3.330 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   5.896 ms/op
                 listUser·p0.999:  22.568 ms/op
                 listUser·p0.9999: 24.216 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9429
  mean =      3.396 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1416 
    [ 2.500,  5.000) = 7719 
    [ 5.000,  7.500) = 262 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      5.896 ms/op
     p(99.9000) =     22.568 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.544          ops/ms
ClientSimple.existUser                       thrpt         13.552          ops/ms
ClientSimple.getUser                         thrpt         13.271          ops/ms
ClientSimple.listUser                        thrpt          8.599          ops/ms
ClientSimple.createUser                       avgt          2.238           ms/op
ClientSimple.existUser                        avgt          1.867           ms/op
ClientSimple.getUser                          avgt          2.154           ms/op
ClientSimple.listUser                         avgt          3.859           ms/op
ClientSimple.createUser                     sample  13904   2.297 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.396           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.089           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.896           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.154           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.791           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.443           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.179           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.295           ms/op
ClientSimple.existUser                      sample  17613   1.819 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.794           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.747           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.520           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.030           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.010           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.076           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.076           ms/op
ClientSimple.getUser                        sample  15547   2.056 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.754           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.005           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.181           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.223           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.722           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.731           ms/op
ClientSimple.listUser                       sample   9429   3.396 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.971           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.330           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.896           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.568           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.216           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.216           ms/op

Benchmark result is saved to 1723658730799.json
