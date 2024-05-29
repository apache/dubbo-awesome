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
# Warmup Iteration   1: 1.593 ops/ms
Iteration   1: 7.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.626 ops/ms


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
# Warmup Iteration   1: 6.713 ops/ms
Iteration   1: 13.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.235 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.981 ops/ms
Iteration   1: 14.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.001 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.002 ops/ms
Iteration   1: 8.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.505 ops/ms


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.067 ms/op
Iteration   1: 2.445 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.445 ms/op


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
# Warmup Iteration   1: 3.084 ±(99.9%) 0.055 ms/op
Iteration   1: 1.574 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.574 ms/op


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
# Warmup Iteration   1: 3.248 ±(99.9%) 0.047 ms/op
Iteration   1: 1.876 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.876 ms/op


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
# Warmup Iteration   1: 4.464 ±(99.9%) 0.078 ms/op
Iteration   1: 3.301 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.301 ms/op


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
# Warmup Iteration   1: 3.936 ±(99.9%) 0.123 ms/op
Iteration   1: 2.011 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.254 ms/op
                 createUser·p0.50:   1.757 ms/op
                 createUser·p0.90:   2.458 ms/op
                 createUser·p0.95:   2.900 ms/op
                 createUser·p0.99:   10.758 ms/op
                 createUser·p0.999:  33.001 ms/op
                 createUser·p0.9999: 33.751 ms/op
                 createUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15937
  mean =      2.011 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14539 
    [ 2.500,  5.000) = 1128 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.254 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =     10.758 ms/op
     p(99.9000) =     33.001 ms/op
     p(99.9900) =     33.751 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.928 ±(99.9%) 0.066 ms/op
Iteration   1: 1.678 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.444 ms/op
                 existUser·p0.50:   1.632 ms/op
                 existUser·p0.90:   1.928 ms/op
                 existUser·p0.95:   2.224 ms/op
                 existUser·p0.99:   2.748 ms/op
                 existUser·p0.999:  10.371 ms/op
                 existUser·p0.9999: 10.471 ms/op
                 existUser·p1.00:   10.486 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19185
  mean =      1.678 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 532 
    [ 1.250,  2.500) = 18259 
    [ 2.500,  3.750) = 339 
    [ 3.750,  5.000) = 22 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      1.632 ms/op
     p(90.0000) =      1.928 ms/op
     p(95.0000) =      2.224 ms/op
     p(99.0000) =      2.748 ms/op
     p(99.9000) =     10.371 ms/op
     p(99.9900) =     10.471 ms/op
     p(99.9990) =     10.486 ms/op
     p(99.9999) =     10.486 ms/op
    p(100.0000) =     10.486 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.973 ±(99.9%) 0.070 ms/op
Iteration   1: 1.742 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.211 ms/op
                 getUser·p0.50:   1.556 ms/op
                 getUser·p0.90:   2.270 ms/op
                 getUser·p0.95:   2.638 ms/op
                 getUser·p0.99:   3.688 ms/op
                 getUser·p0.999:  18.874 ms/op
                 getUser·p0.9999: 20.780 ms/op
                 getUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18416
  mean =      1.742 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17229 
    [ 2.500,  5.000) = 1075 
    [ 5.000,  7.500) = 16 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.211 ms/op
     p(50.0000) =      1.556 ms/op
     p(90.0000) =      2.270 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.688 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     20.780 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.158 ±(99.9%) 0.120 ms/op
Iteration   1: 3.134 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   2.753 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.038 ms/op
                 listUser·p0.999:  20.113 ms/op
                 listUser·p0.9999: 20.315 ms/op
                 listUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10203
  mean =      3.134 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2126 
    [ 2.500,  5.000) = 7873 
    [ 5.000,  7.500) = 108 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      2.753 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     20.113 ms/op
     p(99.9900) =     20.315 ms/op
     p(99.9990) =     20.316 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.626          ops/ms
ClientSimple.existUser                       thrpt         13.235          ops/ms
ClientSimple.getUser                         thrpt         14.001          ops/ms
ClientSimple.listUser                        thrpt          8.505          ops/ms
ClientSimple.createUser                       avgt          2.445           ms/op
ClientSimple.existUser                        avgt          1.574           ms/op
ClientSimple.getUser                          avgt          1.876           ms/op
ClientSimple.listUser                         avgt          3.301           ms/op
ClientSimple.createUser                     sample  15937   2.011 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.254           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.757           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.458           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.758           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.001           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.751           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.751           ms/op
ClientSimple.existUser                      sample  19185   1.678 ± 0.011   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.444           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.632           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.928           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.224           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.748           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.371           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.471           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.486           ms/op
ClientSimple.getUser                        sample  18416   1.742 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.211           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.556           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.270           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.688           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.874           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.780           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.808           ms/op
ClientSimple.listUser                       sample  10203   3.134 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.053           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.753           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.084           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.038           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.113           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.315           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.316           ms/op

Benchmark result is saved to 1717005903509.json
