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
# Warmup Iteration   1: 1.780 ops/ms
Iteration   1: 5.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.987 ops/ms


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
# Warmup Iteration   1: 5.498 ops/ms
Iteration   1: 12.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.808 ops/ms


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
# Warmup Iteration   1: 6.012 ops/ms
Iteration   1: 13.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.044 ops/ms


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
# Warmup Iteration   1: 4.115 ops/ms
Iteration   1: 8.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.301 ops/ms


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
# Warmup Iteration   1: 4.288 ±(99.9%) 0.120 ms/op
Iteration   1: 2.362 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.362 ms/op


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
# Warmup Iteration   1: 3.164 ±(99.9%) 0.057 ms/op
Iteration   1: 1.953 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.953 ms/op


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
# Warmup Iteration   1: 3.312 ±(99.9%) 0.061 ms/op
Iteration   1: 2.342 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.342 ms/op


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
# Warmup Iteration   1: 4.526 ±(99.9%) 0.091 ms/op
Iteration   1: 3.362 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.362 ms/op


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.139 ms/op
Iteration   1: 2.151 ±(99.9%) 0.056 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   1.909 ms/op
                 createUser·p0.90:   2.478 ms/op
                 createUser·p0.95:   2.761 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  42.992 ms/op
                 createUser·p0.9999: 44.467 ms/op
                 createUser·p1.00:   44.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14948
  mean =      2.151 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14768 
    [ 5.000, 10.000) = 116 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     42.992 ms/op
     p(99.9900) =     44.467 ms/op
     p(99.9990) =     44.564 ms/op
     p(99.9999) =     44.564 ms/op
    p(100.0000) =     44.564 ms/op


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
# Warmup Iteration   1: 3.279 ±(99.9%) 0.078 ms/op
Iteration   1: 2.004 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.420 ms/op
                 existUser·p0.50:   1.870 ms/op
                 existUser·p0.90:   2.314 ms/op
                 existUser·p0.95:   2.589 ms/op
                 existUser·p0.99:   5.214 ms/op
                 existUser·p0.999:  12.447 ms/op
                 existUser·p0.9999: 13.337 ms/op
                 existUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15984
  mean =      2.004 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 14915 
    [ 2.500,  3.750) = 628 
    [ 3.750,  5.000) = 117 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      5.214 ms/op
     p(99.9000) =     12.447 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     13.337 ms/op
     p(99.9999) =     13.337 ms/op
    p(100.0000) =     13.337 ms/op


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
# Warmup Iteration   1: 3.312 ±(99.9%) 0.077 ms/op
Iteration   1: 2.123 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   1.944 ms/op
                 getUser·p0.90:   2.728 ms/op
                 getUser·p0.95:   2.978 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  16.908 ms/op
                 getUser·p0.9999: 17.170 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15049
  mean =      2.123 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 11891 
    [ 2.500,  3.750) = 2754 
    [ 3.750,  5.000) = 125 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 5.442 ±(99.9%) 0.291 ms/op
Iteration   1: 3.524 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.486 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.065 ms/op
                 listUser·p0.999:  11.658 ms/op
                 listUser·p0.9999: 11.944 ms/op
                 listUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9058
  mean =      3.524 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 954 
    [ 2.500,  3.750) = 4918 
    [ 3.750,  5.000) = 2845 
    [ 5.000,  6.250) = 199 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.065 ms/op
     p(99.9000) =     11.658 ms/op
     p(99.9900) =     11.944 ms/op
     p(99.9990) =     11.944 ms/op
     p(99.9999) =     11.944 ms/op
    p(100.0000) =     11.944 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.987          ops/ms
ClientSimple.existUser                       thrpt         12.808          ops/ms
ClientSimple.getUser                         thrpt         13.044          ops/ms
ClientSimple.listUser                        thrpt          8.301          ops/ms
ClientSimple.createUser                       avgt          2.362           ms/op
ClientSimple.existUser                        avgt          1.953           ms/op
ClientSimple.getUser                          avgt          2.342           ms/op
ClientSimple.listUser                         avgt          3.362           ms/op
ClientSimple.createUser                     sample  14948   2.151 ± 0.056   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.883           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.909           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.478           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.972           ms/op
ClientSimple.createUser:createUser·p0.999   sample         42.992           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         44.467           ms/op
ClientSimple.createUser:createUser·p1.00    sample         44.564           ms/op
ClientSimple.existUser                      sample  15984   2.004 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.420           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.870           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.314           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.214           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.447           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.337           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.337           ms/op
ClientSimple.getUser                        sample  15049   2.123 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.829           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.944           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.978           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.833           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.908           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.170           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.170           ms/op
ClientSimple.listUser                       sample   9058   3.524 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.171           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.486           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.866           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.065           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.658           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.944           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.944           ms/op

Benchmark result is saved to 1717481132462.json
