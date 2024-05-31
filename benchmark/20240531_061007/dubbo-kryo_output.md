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
# Warmup Iteration   1: 1.367 ops/ms
Iteration   1: 5.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.969 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.079 ops/ms
Iteration   1: 10.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.548 ops/ms


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
# Warmup Iteration   1: 4.871 ops/ms
Iteration   1: 11.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.758 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.458 ops/ms
Iteration   1: 7.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.396 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.851 ±(99.9%) 0.084 ms/op
Iteration   1: 2.306 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.306 ms/op


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
# Warmup Iteration   1: 3.093 ±(99.9%) 0.055 ms/op
Iteration   1: 1.787 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.787 ms/op


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
# Warmup Iteration   1: 4.047 ±(99.9%) 0.069 ms/op
Iteration   1: 1.982 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.982 ms/op


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
# Warmup Iteration   1: 5.110 ±(99.9%) 0.121 ms/op
Iteration   1: 3.299 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.299 ms/op


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
# Warmup Iteration   1: 3.586 ±(99.9%) 0.093 ms/op
Iteration   1: 2.159 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.535 ms/op
                 createUser·p0.50:   1.946 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.900 ms/op
                 createUser·p0.99:   8.729 ms/op
                 createUser·p0.999:  17.072 ms/op
                 createUser·p0.9999: 17.585 ms/op
                 createUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14819
  mean =      2.159 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 320 
    [ 1.250,  2.500) = 12891 
    [ 2.500,  3.750) = 1100 
    [ 3.750,  5.000) = 132 
    [ 5.000,  6.250) = 170 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      8.729 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     17.585 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 3.126 ±(99.9%) 0.088 ms/op
Iteration   1: 2.010 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.350 ms/op
                 existUser·p0.50:   1.831 ms/op
                 existUser·p0.90:   2.490 ms/op
                 existUser·p0.95:   2.761 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  27.262 ms/op
                 existUser·p0.9999: 27.938 ms/op
                 existUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16015
  mean =      2.010 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14478 
    [ 2.500,  5.000) = 1410 
    [ 5.000,  7.500) = 62 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.350 ms/op
     p(50.0000) =      1.831 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =     27.262 ms/op
     p(99.9900) =     27.938 ms/op
     p(99.9990) =     28.017 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 3.509 ±(99.9%) 0.083 ms/op
Iteration   1: 2.162 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.477 ms/op
                 getUser·p0.50:   1.964 ms/op
                 getUser·p0.90:   2.941 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  19.012 ms/op
                 getUser·p0.9999: 19.926 ms/op
                 getUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14802
  mean =      2.162 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 278 
    [ 1.250,  2.500) = 10297 
    [ 2.500,  3.750) = 3992 
    [ 3.750,  5.000) = 184 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =     19.012 ms/op
     p(99.9900) =     19.926 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 4.934 ±(99.9%) 0.148 ms/op
Iteration   1: 3.483 ±(99.9%) 0.062 ms/op
                 listUser·p0.00:   0.715 ms/op
                 listUser·p0.50:   3.211 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  22.938 ms/op
                 listUser·p0.9999: 25.723 ms/op
                 listUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9174
  mean =      3.483 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1031 
    [ 2.500,  5.000) = 7760 
    [ 5.000,  7.500) = 285 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     22.938 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.969          ops/ms
ClientSimple.existUser                       thrpt         10.548          ops/ms
ClientSimple.getUser                         thrpt         11.758          ops/ms
ClientSimple.listUser                        thrpt          7.396          ops/ms
ClientSimple.createUser                       avgt          2.306           ms/op
ClientSimple.existUser                        avgt          1.787           ms/op
ClientSimple.getUser                          avgt          1.982           ms/op
ClientSimple.listUser                         avgt          3.299           ms/op
ClientSimple.createUser                     sample  14819   2.159 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.535           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.946           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.729           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.072           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.585           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.727           ms/op
ClientSimple.existUser                      sample  16015   2.010 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.350           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.831           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.761           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.530           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.262           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.938           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.017           ms/op
ClientSimple.getUser                        sample  14802   2.162 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.477           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.964           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.941           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.121           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.104           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.012           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.926           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.988           ms/op
ClientSimple.listUser                       sample   9174   3.483 ± 0.062   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.715           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.211           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.760           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.093           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.938           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.723           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.723           ms/op

Benchmark result is saved to 1717135558450.json
