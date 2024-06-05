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
# Warmup Iteration   1: 1.819 ops/ms
Iteration   1: 8.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.108 ops/ms


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
# Warmup Iteration   1: 5.472 ops/ms
Iteration   1: 12.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.497 ops/ms


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
# Warmup Iteration   1: 6.241 ops/ms
Iteration   1: 13.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.853 ops/ms


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
# Warmup Iteration   1: 5.132 ops/ms
Iteration   1: 8.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.609 ops/ms


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.078 ms/op
Iteration   1: 1.990 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.990 ms/op


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
# Warmup Iteration   1: 3.046 ±(99.9%) 0.043 ms/op
Iteration   1: 2.046 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.046 ms/op


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
# Warmup Iteration   1: 3.172 ±(99.9%) 0.060 ms/op
Iteration   1: 2.236 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.236 ms/op


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
# Warmup Iteration   1: 4.710 ±(99.9%) 0.095 ms/op
Iteration   1: 3.442 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.442 ms/op


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
# Warmup Iteration   1: 3.458 ±(99.9%) 0.088 ms/op
Iteration   1: 2.128 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   1.907 ms/op
                 createUser·p0.90:   2.572 ms/op
                 createUser·p0.95:   2.912 ms/op
                 createUser·p0.99:   7.406 ms/op
                 createUser·p0.999:  21.889 ms/op
                 createUser·p0.9999: 23.625 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15022
  mean =      2.128 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13162 
    [ 2.500,  5.000) = 1653 
    [ 5.000,  7.500) = 76 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     21.889 ms/op
     p(99.9900) =     23.625 ms/op
     p(99.9990) =     23.757 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 2.886 ±(99.9%) 0.064 ms/op
Iteration   1: 1.794 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.447 ms/op
                 existUser·p0.50:   1.675 ms/op
                 existUser·p0.90:   2.097 ms/op
                 existUser·p0.95:   2.228 ms/op
                 existUser·p0.99:   2.949 ms/op
                 existUser·p0.999:  19.169 ms/op
                 existUser·p0.9999: 19.235 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17886
  mean =      1.794 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 174 
    [ 1.250,  2.500) = 17399 
    [ 2.500,  3.750) = 198 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      1.675 ms/op
     p(90.0000) =      2.097 ms/op
     p(95.0000) =      2.228 ms/op
     p(99.0000) =      2.949 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 3.675 ±(99.9%) 0.091 ms/op
Iteration   1: 2.038 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.666 ms/op
                 getUser·p0.50:   1.921 ms/op
                 getUser·p0.90:   2.564 ms/op
                 getUser·p0.95:   2.777 ms/op
                 getUser·p0.99:   3.966 ms/op
                 getUser·p0.999:  13.030 ms/op
                 getUser·p0.9999: 20.036 ms/op
                 getUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15686
  mean =      2.038 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13820 
    [ 2.500,  5.000) = 1732 
    [ 5.000,  7.500) = 50 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      3.966 ms/op
     p(99.9000) =     13.030 ms/op
     p(99.9900) =     20.036 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 4.475 ±(99.9%) 0.126 ms/op
Iteration   1: 3.064 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.757 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   4.809 ms/op
                 listUser·p0.999:  20.185 ms/op
                 listUser·p0.9999: 20.604 ms/op
                 listUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10429
  mean =      3.064 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1478 
    [ 2.500,  5.000) = 8876 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      2.757 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =     20.185 ms/op
     p(99.9900) =     20.604 ms/op
     p(99.9990) =     20.611 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.108          ops/ms
ClientSimple.existUser                       thrpt         12.497          ops/ms
ClientSimple.getUser                         thrpt         13.853          ops/ms
ClientSimple.listUser                        thrpt          8.609          ops/ms
ClientSimple.createUser                       avgt          1.990           ms/op
ClientSimple.existUser                        avgt          2.046           ms/op
ClientSimple.getUser                          avgt          2.236           ms/op
ClientSimple.listUser                         avgt          3.442           ms/op
ClientSimple.createUser                     sample  15022   2.128 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.723           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.907           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.912           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.406           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.889           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.625           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.757           ms/op
ClientSimple.existUser                      sample  17886   1.794 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.447           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.675           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.097           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.228           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.949           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.169           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.235           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.235           ms/op
ClientSimple.getUser                        sample  15686   2.038 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.666           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.921           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.564           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.966           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.030           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.036           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.185           ms/op
ClientSimple.listUser                       sample  10429   3.064 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.911           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.757           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.084           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.185           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.604           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.611           ms/op

Benchmark result is saved to 1717589200562.json
