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
# Warmup Iteration   1: 0.717 ops/ms
Iteration   1: 5.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.857 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.662 ops/ms
Iteration   1: 13.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.106 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.461 ops/ms
Iteration   1: 13.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.449 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.093 ops/ms
Iteration   1: 8.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.559 ops/ms


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.074 ms/op
Iteration   1: 1.998 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.998 ms/op


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
# Warmup Iteration   1: 3.328 ±(99.9%) 0.055 ms/op
Iteration   1: 1.915 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.915 ms/op


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
# Warmup Iteration   1: 3.114 ±(99.9%) 0.051 ms/op
Iteration   1: 1.935 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.935 ms/op


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
# Warmup Iteration   1: 4.687 ±(99.9%) 0.081 ms/op
Iteration   1: 3.820 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.820 ms/op


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
# Warmup Iteration   1: 3.467 ±(99.9%) 0.085 ms/op
Iteration   1: 2.091 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   1.800 ms/op
                 createUser·p0.90:   2.421 ms/op
                 createUser·p0.95:   2.732 ms/op
                 createUser·p0.99:   7.569 ms/op
                 createUser·p0.999:  29.350 ms/op
                 createUser·p0.9999: 36.025 ms/op
                 createUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15304
  mean =      2.091 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14096 
    [ 2.500,  5.000) = 969 
    [ 5.000,  7.500) = 80 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     29.350 ms/op
     p(99.9900) =     36.025 ms/op
     p(99.9990) =     36.372 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 3.310 ±(99.9%) 0.080 ms/op
Iteration   1: 2.076 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   1.954 ms/op
                 existUser·p0.90:   2.650 ms/op
                 existUser·p0.95:   2.900 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  10.561 ms/op
                 existUser·p0.9999: 10.991 ms/op
                 existUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15412
  mean =      2.076 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 205 
    [ 1.250,  2.500) = 12945 
    [ 2.500,  3.750) = 1993 
    [ 3.750,  5.000) = 173 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =     10.561 ms/op
     p(99.9900) =     10.991 ms/op
     p(99.9990) =     11.026 ms/op
     p(99.9999) =     11.026 ms/op
    p(100.0000) =     11.026 ms/op


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
# Warmup Iteration   1: 3.204 ±(99.9%) 0.085 ms/op
Iteration   1: 2.139 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   1.962 ms/op
                 getUser·p0.90:   2.580 ms/op
                 getUser·p0.95:   2.851 ms/op
                 getUser·p0.99:   4.981 ms/op
                 getUser·p0.999:  17.468 ms/op
                 getUser·p0.9999: 17.894 ms/op
                 getUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14919
  mean =      2.139 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 13048 
    [ 2.500,  3.750) = 1499 
    [ 3.750,  5.000) = 169 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      1.962 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      4.981 ms/op
     p(99.9000) =     17.468 ms/op
     p(99.9900) =     17.894 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 4.438 ±(99.9%) 0.124 ms/op
Iteration   1: 3.541 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   0.771 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   8.574 ms/op
                 listUser·p0.999:  13.446 ms/op
                 listUser·p0.9999: 15.860 ms/op
                 listUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9068
  mean =      3.541 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 1152 
    [ 2.500,  3.750) = 4700 
    [ 3.750,  5.000) = 2690 
    [ 5.000,  6.250) = 352 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      8.574 ms/op
     p(99.9000) =     13.446 ms/op
     p(99.9900) =     15.860 ms/op
     p(99.9990) =     15.860 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.857          ops/ms
ClientSimple.existUser                       thrpt         13.106          ops/ms
ClientSimple.getUser                         thrpt         13.449          ops/ms
ClientSimple.listUser                        thrpt          8.559          ops/ms
ClientSimple.createUser                       avgt          1.998           ms/op
ClientSimple.existUser                        avgt          1.915           ms/op
ClientSimple.getUser                          avgt          1.935           ms/op
ClientSimple.listUser                         avgt          3.820           ms/op
ClientSimple.createUser                     sample  15304   2.091 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.644           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.800           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.421           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.732           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.569           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.350           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.025           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.372           ms/op
ClientSimple.existUser                      sample  15412   2.076 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.614           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.954           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.900           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.465           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.561           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.991           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.026           ms/op
ClientSimple.getUser                        sample  14919   2.139 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.837           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.962           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.851           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.981           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.468           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.894           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.088           ms/op
ClientSimple.listUser                       sample   9068   3.541 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.771           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.465           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.574           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.446           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.860           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.860           ms/op

Benchmark result is saved to 1724846874029.json
