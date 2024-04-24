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
# Warmup Iteration   1: 1.792 ops/ms
Iteration   1: 6.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.799 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.528 ops/ms
Iteration   1: 12.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.015 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.219 ops/ms
Iteration   1: 12.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.981 ops/ms


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
# Warmup Iteration   1: 5.239 ops/ms
Iteration   1: 8.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.408 ops/ms


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.064 ms/op
Iteration   1: 2.153 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.153 ms/op


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.075 ms/op
Iteration   1: 1.622 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.622 ms/op


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
# Warmup Iteration   1: 3.202 ±(99.9%) 0.066 ms/op
Iteration   1: 1.873 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.873 ms/op


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
# Warmup Iteration   1: 4.508 ±(99.9%) 0.085 ms/op
Iteration   1: 3.430 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.430 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.097 ±(99.9%) 0.112 ms/op
Iteration   1: 2.149 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   1.948 ms/op
                 createUser·p0.90:   2.564 ms/op
                 createUser·p0.95:   2.751 ms/op
                 createUser·p0.99:   6.839 ms/op
                 createUser·p0.999:  17.993 ms/op
                 createUser·p0.9999: 18.728 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14907
  mean =      2.149 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 178 
    [ 1.250,  2.500) = 12874 
    [ 2.500,  3.750) = 1468 
    [ 3.750,  5.000) = 145 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      1.948 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.751 ms/op
     p(99.0000) =      6.839 ms/op
     p(99.9000) =     17.993 ms/op
     p(99.9900) =     18.728 ms/op
     p(99.9990) =     18.776 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 2.925 ±(99.9%) 0.068 ms/op
Iteration   1: 1.970 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   1.894 ms/op
                 existUser·p0.90:   2.425 ms/op
                 existUser·p0.95:   2.617 ms/op
                 existUser·p0.99:   3.375 ms/op
                 existUser·p0.999:  18.219 ms/op
                 existUser·p0.9999: 19.230 ms/op
                 existUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16270
  mean =      1.970 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 403 
    [ 1.250,  2.500) = 14628 
    [ 2.500,  3.750) = 1132 
    [ 3.750,  5.000) = 11 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      3.375 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     19.230 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 3.248 ±(99.9%) 0.100 ms/op
Iteration   1: 2.178 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   2.134 ms/op
                 getUser·p0.90:   2.626 ms/op
                 getUser·p0.95:   2.826 ms/op
                 getUser·p0.99:   3.546 ms/op
                 getUser·p0.999:  13.156 ms/op
                 getUser·p0.9999: 13.877 ms/op
                 getUser·p1.00:   13.992 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14665
  mean =      2.178 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 12182 
    [ 2.500,  3.750) = 2307 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      3.546 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     13.877 ms/op
     p(99.9990) =     13.992 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 4.653 ±(99.9%) 0.127 ms/op
Iteration   1: 3.315 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   9.977 ms/op
                 listUser·p0.999:  25.330 ms/op
                 listUser·p0.9999: 26.116 ms/op
                 listUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9634
  mean =      3.315 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1301 
    [ 2.500,  5.000) = 8148 
    [ 5.000,  7.500) = 84 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      9.977 ms/op
     p(99.9000) =     25.330 ms/op
     p(99.9900) =     26.116 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.799          ops/ms
ClientSimple.existUser                       thrpt         12.015          ops/ms
ClientSimple.getUser                         thrpt         12.981          ops/ms
ClientSimple.listUser                        thrpt          8.408          ops/ms
ClientSimple.createUser                       avgt          2.153           ms/op
ClientSimple.existUser                        avgt          1.622           ms/op
ClientSimple.getUser                          avgt          1.873           ms/op
ClientSimple.listUser                         avgt          3.430           ms/op
ClientSimple.createUser                     sample  14907   2.149 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.754           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.948           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.564           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.751           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.839           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.993           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.728           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.776           ms/op
ClientSimple.existUser                      sample  16270   1.970 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.655           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.894           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.425           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.617           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.375           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.219           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.230           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.333           ms/op
ClientSimple.getUser                        sample  14665   2.178 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.708           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.134           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.826           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.546           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.156           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.877           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.992           ms/op
ClientSimple.listUser                       sample   9634   3.315 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.026           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.027           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.121           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.977           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.330           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.116           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.116           ms/op

Benchmark result is saved to 1713938778805.json
