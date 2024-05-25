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
# Warmup Iteration   1: 1.868 ops/ms
Iteration   1: 8.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.018 ops/ms


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
# Warmup Iteration   1: 5.463 ops/ms
Iteration   1: 11.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.952 ops/ms


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
# Warmup Iteration   1: 6.012 ops/ms
Iteration   1: 13.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.800 ops/ms


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
# Warmup Iteration   1: 4.560 ops/ms
Iteration   1: 8.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.981 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.879 ±(99.9%) 0.074 ms/op
Iteration   1: 2.192 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.192 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.249 ±(99.9%) 0.055 ms/op
Iteration   1: 1.843 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.843 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.352 ±(99.9%) 0.058 ms/op
Iteration   1: 2.229 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.439 ±(99.9%) 0.101 ms/op
Iteration   1: 3.460 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.460 ms/op


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
# Warmup Iteration   1: 3.443 ±(99.9%) 0.078 ms/op
Iteration   1: 2.155 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.604 ms/op
                 createUser·p0.50:   1.896 ms/op
                 createUser·p0.90:   2.441 ms/op
                 createUser·p0.95:   2.728 ms/op
                 createUser·p0.99:   9.487 ms/op
                 createUser·p0.999:  33.762 ms/op
                 createUser·p0.9999: 34.899 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14827
  mean =      2.155 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13575 
    [ 2.500,  5.000) = 1006 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      9.487 ms/op
     p(99.9000) =     33.762 ms/op
     p(99.9900) =     34.899 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 2.996 ±(99.9%) 0.074 ms/op
Iteration   1: 1.942 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.343 ms/op
                 existUser·p0.50:   1.962 ms/op
                 existUser·p0.90:   2.724 ms/op
                 existUser·p0.95:   2.953 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  11.199 ms/op
                 existUser·p0.9999: 11.502 ms/op
                 existUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16443
  mean =      1.942 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2945 
    [ 1.250,  2.500) = 10708 
    [ 2.500,  3.750) = 2635 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 3 
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
      p(0.0000) =      0.343 ms/op
     p(50.0000) =      1.962 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =     11.199 ms/op
     p(99.9900) =     11.502 ms/op
     p(99.9990) =     11.502 ms/op
     p(99.9999) =     11.502 ms/op
    p(100.0000) =     11.502 ms/op


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
# Warmup Iteration   1: 3.482 ±(99.9%) 0.093 ms/op
Iteration   1: 2.202 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.657 ms/op
                 getUser·p0.50:   2.150 ms/op
                 getUser·p0.90:   2.662 ms/op
                 getUser·p0.95:   2.925 ms/op
                 getUser·p0.99:   3.700 ms/op
                 getUser·p0.999:  17.203 ms/op
                 getUser·p0.9999: 17.352 ms/op
                 getUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14556
  mean =      2.202 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 12053 
    [ 2.500,  3.750) = 2321 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      3.700 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     17.352 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 4.400 ±(99.9%) 0.120 ms/op
Iteration   1: 3.175 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   6.062 ms/op
                 listUser·p0.999:  22.544 ms/op
                 listUser·p0.9999: 23.560 ms/op
                 listUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10078
  mean =      3.175 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2732 
    [ 2.500,  5.000) = 7052 
    [ 5.000,  7.500) = 252 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     22.544 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.018          ops/ms
ClientSimple.existUser                       thrpt         11.952          ops/ms
ClientSimple.getUser                         thrpt         13.800          ops/ms
ClientSimple.listUser                        thrpt          8.981          ops/ms
ClientSimple.createUser                       avgt          2.192           ms/op
ClientSimple.existUser                        avgt          1.843           ms/op
ClientSimple.getUser                          avgt          2.229           ms/op
ClientSimple.listUser                         avgt          3.460           ms/op
ClientSimple.createUser                     sample  14827   2.155 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.604           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.896           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.441           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.487           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.762           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.899           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.931           ms/op
ClientSimple.existUser                      sample  16443   1.942 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.343           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.962           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.724           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.953           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.690           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.199           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.502           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.502           ms/op
ClientSimple.getUser                        sample  14556   2.202 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.657           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.150           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.662           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.925           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.700           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.203           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.352           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.367           ms/op
ClientSimple.listUser                       sample  10078   3.175 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.188           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.957           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.694           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.062           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.544           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.560           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.560           ms/op

Benchmark result is saved to 1716660281227.json
