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
# Warmup Iteration   1: 1.532 ops/ms
Iteration   1: 6.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.608 ops/ms


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
# Warmup Iteration   1: 6.150 ops/ms
Iteration   1: 11.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.957 ops/ms


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
# Warmup Iteration   1: 4.681 ops/ms
Iteration   1: 11.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.777 ops/ms


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
# Warmup Iteration   1: 4.767 ops/ms
Iteration   1: 9.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.465 ops/ms


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.067 ms/op
Iteration   1: 2.283 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.283 ms/op


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
# Warmup Iteration   1: 3.228 ±(99.9%) 0.058 ms/op
Iteration   1: 1.860 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.860 ms/op


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
# Warmup Iteration   1: 3.809 ±(99.9%) 0.079 ms/op
Iteration   1: 2.080 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.080 ms/op


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
# Warmup Iteration   1: 6.276 ±(99.9%) 0.125 ms/op
Iteration   1: 3.431 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.431 ms/op


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
# Warmup Iteration   1: 3.685 ±(99.9%) 0.099 ms/op
Iteration   1: 2.207 ±(99.9%) 0.059 ms/op
                 createUser·p0.00:   0.479 ms/op
                 createUser·p0.50:   1.991 ms/op
                 createUser·p0.90:   2.568 ms/op
                 createUser·p0.95:   2.781 ms/op
                 createUser·p0.99:   9.522 ms/op
                 createUser·p0.999:  38.506 ms/op
                 createUser·p0.9999: 48.553 ms/op
                 createUser·p1.00:   48.759 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14480
  mean =      2.207 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14217 
    [ 5.000, 10.000) = 139 
    [10.000, 15.000) = 48 
    [15.000, 20.000) = 29 
    [20.000, 25.000) = 15 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      1.991 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      9.522 ms/op
     p(99.9000) =     38.506 ms/op
     p(99.9900) =     48.553 ms/op
     p(99.9990) =     48.759 ms/op
     p(99.9999) =     48.759 ms/op
    p(100.0000) =     48.759 ms/op


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
# Warmup Iteration   1: 3.359 ±(99.9%) 0.075 ms/op
Iteration   1: 2.095 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.304 ms/op
                 existUser·p0.50:   1.782 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   3.949 ms/op
                 existUser·p0.999:  22.151 ms/op
                 existUser·p0.9999: 22.282 ms/op
                 existUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15337
  mean =      2.095 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12147 
    [ 2.500,  5.000) = 3120 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.304 ms/op
     p(50.0000) =      1.782 ms/op
     p(90.0000) =      3.219 ms/op
     p(95.0000) =      3.494 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =     22.151 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     22.282 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 3.308 ±(99.9%) 0.105 ms/op
Iteration   1: 2.279 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.521 ms/op
                 getUser·p0.50:   2.171 ms/op
                 getUser·p0.90:   2.900 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   4.282 ms/op
                 getUser·p0.999:  13.468 ms/op
                 getUser·p0.9999: 15.149 ms/op
                 getUser·p1.00:   15.155 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14063
  mean =      2.279 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 10517 
    [ 2.500,  3.750) = 3287 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      4.282 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     15.149 ms/op
     p(99.9990) =     15.155 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 5.064 ±(99.9%) 0.149 ms/op
Iteration   1: 3.321 ±(99.9%) 0.049 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   3.183 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  21.430 ms/op
                 listUser·p0.9999: 22.053 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9628
  mean =      3.321 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2237 
    [ 2.500,  5.000) = 7047 
    [ 5.000,  7.500) = 277 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     21.430 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.608          ops/ms
ClientSimple.existUser                       thrpt         11.957          ops/ms
ClientSimple.getUser                         thrpt         11.777          ops/ms
ClientSimple.listUser                        thrpt          9.465          ops/ms
ClientSimple.createUser                       avgt          2.283           ms/op
ClientSimple.existUser                        avgt          1.860           ms/op
ClientSimple.getUser                          avgt          2.080           ms/op
ClientSimple.listUser                         avgt          3.431           ms/op
ClientSimple.createUser                     sample  14480   2.207 ± 0.059   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.479           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.991           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.522           ms/op
ClientSimple.createUser:createUser·p0.999   sample         38.506           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         48.553           ms/op
ClientSimple.createUser:createUser·p1.00    sample         48.759           ms/op
ClientSimple.existUser                      sample  15337   2.095 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.304           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.782           ms/op
ClientSimple.existUser:existUser·p0.90      sample          3.219           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.494           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.949           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.151           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.282           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.282           ms/op
ClientSimple.getUser                        sample  14063   2.279 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.521           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.171           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.125           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.282           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.468           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.149           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.155           ms/op
ClientSimple.listUser                       sample   9628   3.321 ± 0.049   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.958           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.183           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.086           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.430           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.053           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.053           ms/op

Benchmark result is saved to 1719015354562.json
