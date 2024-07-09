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
# Warmup Iteration   1: 1.958 ops/ms
Iteration   1: 7.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.245 ops/ms


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
# Warmup Iteration   1: 6.045 ops/ms
Iteration   1: 13.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.190 ops/ms


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
# Warmup Iteration   1: 5.079 ops/ms
Iteration   1: 12.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.316 ops/ms


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
# Warmup Iteration   1: 5.016 ops/ms
Iteration   1: 9.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.163 ops/ms


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.071 ms/op
Iteration   1: 2.229 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.229 ms/op


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
# Warmup Iteration   1: 3.025 ±(99.9%) 0.050 ms/op
Iteration   1: 1.900 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.900 ms/op


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
# Warmup Iteration   1: 3.279 ±(99.9%) 0.050 ms/op
Iteration   1: 1.893 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.893 ms/op


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.076 ms/op
Iteration   1: 3.016 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.016 ms/op


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
# Warmup Iteration   1: 3.467 ±(99.9%) 0.116 ms/op
Iteration   1: 2.185 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   2.064 ms/op
                 createUser·p0.90:   2.646 ms/op
                 createUser·p0.95:   2.982 ms/op
                 createUser·p0.99:   6.502 ms/op
                 createUser·p0.999:  15.902 ms/op
                 createUser·p0.9999: 16.712 ms/op
                 createUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14682
  mean =      2.185 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 280 
    [ 1.250,  2.500) = 12185 
    [ 2.500,  3.750) = 1918 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      6.502 ms/op
     p(99.9000) =     15.902 ms/op
     p(99.9900) =     16.712 ms/op
     p(99.9990) =     16.712 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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
# Warmup Iteration   1: 3.113 ±(99.9%) 0.079 ms/op
Iteration   1: 1.776 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   1.602 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.658 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  15.909 ms/op
                 existUser·p0.9999: 16.134 ms/op
                 existUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18096
  mean =      1.776 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1442 
    [ 1.250,  2.500) = 15446 
    [ 2.500,  3.750) = 1053 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      1.602 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     16.134 ms/op
     p(99.9990) =     16.187 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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
# Warmup Iteration   1: 3.257 ±(99.9%) 0.090 ms/op
Iteration   1: 1.779 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.499 ms/op
                 getUser·p0.50:   1.675 ms/op
                 getUser·p0.90:   2.236 ms/op
                 getUser·p0.95:   2.421 ms/op
                 getUser·p0.99:   3.053 ms/op
                 getUser·p0.999:  11.813 ms/op
                 getUser·p0.9999: 11.935 ms/op
                 getUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17966
  mean =      1.779 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 670 
    [ 1.250,  2.500) = 16684 
    [ 2.500,  3.750) = 462 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      1.675 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.421 ms/op
     p(99.0000) =      3.053 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     11.935 ms/op
     p(99.9990) =     12.091 ms/op
     p(99.9999) =     12.091 ms/op
    p(100.0000) =     12.091 ms/op


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
# Warmup Iteration   1: 4.173 ±(99.9%) 0.116 ms/op
Iteration   1: 3.430 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   0.811 ms/op
                 listUser·p0.50:   3.391 ms/op
                 listUser·p0.90:   4.248 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   8.420 ms/op
                 listUser·p0.999:  25.002 ms/op
                 listUser·p0.9999: 25.297 ms/op
                 listUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9404
  mean =      3.430 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1562 
    [ 2.500,  5.000) = 7503 
    [ 5.000,  7.500) = 243 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.248 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      8.420 ms/op
     p(99.9000) =     25.002 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     25.297 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.245          ops/ms
ClientSimple.existUser                       thrpt         13.190          ops/ms
ClientSimple.getUser                         thrpt         12.316          ops/ms
ClientSimple.listUser                        thrpt          9.163          ops/ms
ClientSimple.createUser                       avgt          2.229           ms/op
ClientSimple.existUser                        avgt          1.900           ms/op
ClientSimple.getUser                          avgt          1.893           ms/op
ClientSimple.listUser                         avgt          3.016           ms/op
ClientSimple.createUser                     sample  14682   2.185 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.666           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.064           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.646           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.982           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.502           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.902           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.712           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.712           ms/op
ClientSimple.existUser                      sample  18096   1.776 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.604           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.602           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.658           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.543           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.909           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.134           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.187           ms/op
ClientSimple.getUser                        sample  17966   1.779 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.499           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.675           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.236           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.421           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.053           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.813           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.935           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.091           ms/op
ClientSimple.listUser                       sample   9404   3.430 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.811           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.391           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.248           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.612           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.420           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.002           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.297           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.297           ms/op

Benchmark result is saved to 1720548327955.json
