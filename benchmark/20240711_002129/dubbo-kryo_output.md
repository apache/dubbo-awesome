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
# Warmup Iteration   1: 2.157 ops/ms
Iteration   1: 7.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.889 ops/ms


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
# Warmup Iteration   1: 6.036 ops/ms
Iteration   1: 11.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.836 ops/ms


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
# Warmup Iteration   1: 7.142 ops/ms
Iteration   1: 16.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  16.916 ops/ms


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
# Warmup Iteration   1: 5.013 ops/ms
Iteration   1: 8.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.663 ops/ms


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.099 ms/op
Iteration   1: 2.160 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.160 ms/op


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
# Warmup Iteration   1: 3.141 ±(99.9%) 0.052 ms/op
Iteration   1: 1.966 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.966 ms/op


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
# Warmup Iteration   1: 3.466 ±(99.9%) 0.062 ms/op
Iteration   1: 1.998 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.998 ms/op


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
# Warmup Iteration   1: 4.550 ±(99.9%) 0.093 ms/op
Iteration   1: 3.632 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.632 ms/op


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
# Warmup Iteration   1: 3.589 ±(99.9%) 0.117 ms/op
Iteration   1: 2.138 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   1.948 ms/op
                 createUser·p0.90:   2.449 ms/op
                 createUser·p0.95:   2.728 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  27.137 ms/op
                 createUser·p0.9999: 32.524 ms/op
                 createUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14972
  mean =      2.138 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13683 
    [ 2.500,  5.000) = 1060 
    [ 5.000,  7.500) = 100 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      1.948 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     27.137 ms/op
     p(99.9900) =     32.524 ms/op
     p(99.9990) =     32.768 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 2.814 ±(99.9%) 0.058 ms/op
Iteration   1: 1.992 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.513 ms/op
                 existUser·p0.50:   1.903 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.703 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  25.880 ms/op
                 existUser·p0.9999: 27.197 ms/op
                 existUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16071
  mean =      1.992 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14381 
    [ 2.500,  5.000) = 1625 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      3.461 ms/op
     p(99.9000) =     25.880 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 3.212 ±(99.9%) 0.071 ms/op
Iteration   1: 2.185 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   2.146 ms/op
                 getUser·p0.90:   2.630 ms/op
                 getUser·p0.95:   2.843 ms/op
                 getUser·p0.99:   3.178 ms/op
                 getUser·p0.999:  15.896 ms/op
                 getUser·p0.9999: 16.622 ms/op
                 getUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14789
  mean =      2.185 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 185 
    [ 1.250,  2.500) = 11953 
    [ 2.500,  3.750) = 2589 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.843 ms/op
     p(99.0000) =      3.178 ms/op
     p(99.9000) =     15.896 ms/op
     p(99.9900) =     16.622 ms/op
     p(99.9990) =     16.630 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 4.514 ±(99.9%) 0.122 ms/op
Iteration   1: 3.027 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.714 ms/op
                 listUser·p0.50:   2.716 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.709 ms/op
                 listUser·p0.999:  23.374 ms/op
                 listUser·p0.9999: 25.850 ms/op
                 listUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10555
  mean =      3.027 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3019 
    [ 2.500,  5.000) = 7359 
    [ 5.000,  7.500) = 144 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.716 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.709 ms/op
     p(99.9000) =     23.374 ms/op
     p(99.9900) =     25.850 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.889          ops/ms
ClientSimple.existUser                       thrpt         11.836          ops/ms
ClientSimple.getUser                         thrpt         16.916          ops/ms
ClientSimple.listUser                        thrpt          8.663          ops/ms
ClientSimple.createUser                       avgt          2.160           ms/op
ClientSimple.existUser                        avgt          1.966           ms/op
ClientSimple.getUser                          avgt          1.998           ms/op
ClientSimple.listUser                         avgt          3.632           ms/op
ClientSimple.createUser                     sample  14972   2.138 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.752           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.948           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.449           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.038           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.137           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.524           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.768           ms/op
ClientSimple.existUser                      sample  16071   1.992 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.513           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.903           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.461           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.880           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.197           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.312           ms/op
ClientSimple.getUser                        sample  14789   2.185 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.579           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.146           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.843           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.178           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.896           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.622           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.630           ms/op
ClientSimple.listUser                       sample  10555   3.027 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.714           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.716           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.973           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.709           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.374           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.850           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.887           ms/op

Benchmark result is saved to 1720657022700.json
