# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.103 ops/ms
Iteration   1: 6.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.230 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.884 ops/ms
Iteration   1: 12.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.158 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.140 ops/ms
Iteration   1: 13.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.158 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.564 ops/ms
Iteration   1: 8.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.743 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.312 ±(99.9%) 0.140 ms/op
Iteration   1: 2.240 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.240 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.362 ±(99.9%) 0.051 ms/op
Iteration   1: 1.945 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.945 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.193 ±(99.9%) 0.067 ms/op
Iteration   1: 1.973 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.973 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.393 ±(99.9%) 0.102 ms/op
Iteration   1: 3.653 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.653 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.302 ±(99.9%) 0.076 ms/op
Iteration   1: 2.398 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   2.154 ms/op
                 createUser·p0.90:   2.732 ms/op
                 createUser·p0.95:   3.031 ms/op
                 createUser·p0.99:   8.421 ms/op
                 createUser·p0.999:  28.596 ms/op
                 createUser·p0.9999: 29.262 ms/op
                 createUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13340
  mean =      2.398 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10443 
    [ 2.500,  5.000) = 2626 
    [ 5.000,  7.500) = 64 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.154 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     28.596 ms/op
     p(99.9900) =     29.262 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.310 ±(99.9%) 0.099 ms/op
Iteration   1: 2.013 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.596 ms/op
                 existUser·p0.50:   1.966 ms/op
                 existUser·p0.90:   2.490 ms/op
                 existUser·p0.95:   2.748 ms/op
                 existUser·p0.99:   4.327 ms/op
                 existUser·p0.999:  12.485 ms/op
                 existUser·p0.9999: 13.278 ms/op
                 existUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15879
  mean =      2.013 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 749 
    [ 1.250,  2.500) = 13594 
    [ 2.500,  3.750) = 1323 
    [ 3.750,  5.000) = 129 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      4.327 ms/op
     p(99.9000) =     12.485 ms/op
     p(99.9900) =     13.278 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.399 ±(99.9%) 0.084 ms/op
Iteration   1: 1.988 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.435 ms/op
                 getUser·p0.50:   1.860 ms/op
                 getUser·p0.90:   2.458 ms/op
                 getUser·p0.95:   2.658 ms/op
                 getUser·p0.99:   3.351 ms/op
                 getUser·p0.999:  27.772 ms/op
                 getUser·p0.9999: 28.835 ms/op
                 getUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16157
  mean =      1.988 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14725 
    [ 2.500,  5.000) = 1363 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      3.351 ms/op
     p(99.9000) =     27.772 ms/op
     p(99.9900) =     28.835 ms/op
     p(99.9990) =     29.360 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.638 ±(99.9%) 0.435 ms/op
Iteration   1: 3.427 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.379 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  20.578 ms/op
                 listUser·p0.9999: 26.968 ms/op
                 listUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9335
  mean =      3.427 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1135 
    [ 2.500,  5.000) = 7910 
    [ 5.000,  7.500) = 221 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     20.578 ms/op
     p(99.9900) =     26.968 ms/op
     p(99.9990) =     26.968 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.230          ops/ms
ClientSimple.existUser                       thrpt         12.158          ops/ms
ClientSimple.getUser                         thrpt         13.158          ops/ms
ClientSimple.listUser                        thrpt          8.743          ops/ms
ClientSimple.createUser                       avgt          2.240           ms/op
ClientSimple.existUser                        avgt          1.945           ms/op
ClientSimple.getUser                          avgt          1.973           ms/op
ClientSimple.listUser                         avgt          3.653           ms/op
ClientSimple.createUser                     sample  13340   2.398 ± 0.054   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.693           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.154           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.732           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.031           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.421           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.596           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.262           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.262           ms/op
ClientSimple.existUser                      sample  15879   2.013 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.596           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.966           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.748           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.327           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.485           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.278           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.287           ms/op
ClientSimple.getUser                        sample  16157   1.988 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.435           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.860           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.351           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.772           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.835           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.360           ms/op
ClientSimple.listUser                       sample   9335   3.427 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.069           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.379           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.162           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.898           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.578           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.968           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.968           ms/op

Benchmark result is saved to 1713809115227.json
