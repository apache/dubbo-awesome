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
# Warmup Iteration   1: 1.566 ops/ms
Iteration   1: 6.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.961 ops/ms


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
# Warmup Iteration   1: 6.176 ops/ms
Iteration   1: 11.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.959 ops/ms


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
# Warmup Iteration   1: 5.067 ops/ms
Iteration   1: 11.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.811 ops/ms


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
# Warmup Iteration   1: 4.840 ops/ms
Iteration   1: 8.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.646 ops/ms


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.066 ms/op
Iteration   1: 2.238 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.238 ms/op


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
# Warmup Iteration   1: 3.022 ±(99.9%) 0.048 ms/op
Iteration   1: 1.979 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.979 ms/op


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
# Warmup Iteration   1: 3.298 ±(99.9%) 0.064 ms/op
Iteration   1: 2.275 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.275 ms/op


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
# Warmup Iteration   1: 4.371 ±(99.9%) 0.096 ms/op
Iteration   1: 3.849 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.849 ms/op


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.101 ms/op
Iteration   1: 2.280 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   2.085 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  16.450 ms/op
                 createUser·p0.9999: 17.792 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14021
  mean =      2.280 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 186 
    [ 1.250,  2.500) = 11112 
    [ 2.500,  3.750) = 2255 
    [ 3.750,  5.000) = 166 
    [ 5.000,  6.250) = 129 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      2.085 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     17.792 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 3.351 ±(99.9%) 0.073 ms/op
Iteration   1: 2.008 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   1.853 ms/op
                 existUser·p0.90:   2.568 ms/op
                 existUser·p0.95:   2.895 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  14.173 ms/op
                 existUser·p0.9999: 14.402 ms/op
                 existUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15925
  mean =      2.008 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 14086 
    [ 2.500,  3.750) = 1598 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.895 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =     14.173 ms/op
     p(99.9900) =     14.402 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 3.516 ±(99.9%) 0.103 ms/op
Iteration   1: 2.192 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.597 ms/op
                 getUser·p0.50:   2.138 ms/op
                 getUser·p0.90:   2.695 ms/op
                 getUser·p0.95:   2.953 ms/op
                 getUser·p0.99:   3.814 ms/op
                 getUser·p0.999:  11.426 ms/op
                 getUser·p0.9999: 11.650 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14590
  mean =      2.192 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 11540 
    [ 2.500,  3.750) = 2817 
    [ 3.750,  5.000) = 113 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.138 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      3.814 ms/op
     p(99.9000) =     11.426 ms/op
     p(99.9900) =     11.650 ms/op
     p(99.9990) =     11.665 ms/op
     p(99.9999) =     11.665 ms/op
    p(100.0000) =     11.665 ms/op


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
# Warmup Iteration   1: 4.199 ±(99.9%) 0.113 ms/op
Iteration   1: 3.363 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.154 ms/op
                 listUser·p0.90:   4.034 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   8.583 ms/op
                 listUser·p0.999:  19.153 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9511
  mean =      3.363 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 995 
    [ 2.500,  5.000) = 8278 
    [ 5.000,  7.500) = 141 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      4.034 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      8.583 ms/op
     p(99.9000) =     19.153 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.961          ops/ms
ClientSimple.existUser                       thrpt         11.959          ops/ms
ClientSimple.getUser                         thrpt         11.811          ops/ms
ClientSimple.listUser                        thrpt          8.646          ops/ms
ClientSimple.createUser                       avgt          2.238           ms/op
ClientSimple.existUser                        avgt          1.979           ms/op
ClientSimple.getUser                          avgt          2.275           ms/op
ClientSimple.listUser                         avgt          3.849           ms/op
ClientSimple.createUser                     sample  14021   2.280 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.591           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.085           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.101           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.389           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.450           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.792           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.924           ms/op
ClientSimple.existUser                      sample  15925   2.008 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.748           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.853           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.895           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.998           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.173           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.402           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.451           ms/op
ClientSimple.getUser                        sample  14590   2.192 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.597           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.138           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.953           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.814           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.426           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.650           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.665           ms/op
ClientSimple.listUser                       sample   9511   3.363 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.143           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.154           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.034           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.583           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.153           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.101           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.101           ms/op

Benchmark result is saved to 1720484174318.json
