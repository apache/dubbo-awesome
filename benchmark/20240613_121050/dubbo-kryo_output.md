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
# Warmup Iteration   1: 1.386 ops/ms
Iteration   1: 6.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.509 ops/ms


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
# Warmup Iteration   1: 5.769 ops/ms
Iteration   1: 12.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.025 ops/ms


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
# Warmup Iteration   1: 5.264 ops/ms
Iteration   1: 13.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.031 ops/ms


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
# Warmup Iteration   1: 4.420 ops/ms
Iteration   1: 8.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.520 ops/ms


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
# Warmup Iteration   1: 4.514 ±(99.9%) 0.084 ms/op
Iteration   1: 2.065 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.065 ms/op


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
# Warmup Iteration   1: 3.494 ±(99.9%) 0.066 ms/op
Iteration   1: 2.395 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.395 ms/op


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
# Warmup Iteration   1: 3.386 ±(99.9%) 0.059 ms/op
Iteration   1: 2.167 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.167 ms/op


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
# Warmup Iteration   1: 4.735 ±(99.9%) 0.096 ms/op
Iteration   1: 3.184 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.184 ms/op


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.085 ms/op
Iteration   1: 2.389 ±(99.9%) 0.061 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   2.040 ms/op
                 createUser·p0.90:   2.642 ms/op
                 createUser·p0.95:   3.006 ms/op
                 createUser·p0.99:   12.567 ms/op
                 createUser·p0.999:  29.065 ms/op
                 createUser·p0.9999: 29.961 ms/op
                 createUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13379
  mean =      2.389 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11347 
    [ 2.500,  5.000) = 1710 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.040 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =     12.567 ms/op
     p(99.9000) =     29.065 ms/op
     p(99.9900) =     29.961 ms/op
     p(99.9990) =     29.983 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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
# Warmup Iteration   1: 2.963 ±(99.9%) 0.094 ms/op
Iteration   1: 1.849 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   1.704 ms/op
                 existUser·p0.90:   2.281 ms/op
                 existUser·p0.95:   2.589 ms/op
                 existUser·p0.99:   5.003 ms/op
                 existUser·p0.999:  20.185 ms/op
                 existUser·p0.9999: 24.725 ms/op
                 existUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17321
  mean =      1.849 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16332 
    [ 2.500,  5.000) = 816 
    [ 5.000,  7.500) = 73 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      1.704 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      5.003 ms/op
     p(99.9000) =     20.185 ms/op
     p(99.9900) =     24.725 ms/op
     p(99.9990) =     33.194 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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
# Warmup Iteration   1: 3.189 ±(99.9%) 0.073 ms/op
Iteration   1: 2.168 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   2.003 ms/op
                 getUser·p0.90:   2.826 ms/op
                 getUser·p0.95:   2.990 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  13.763 ms/op
                 getUser·p0.9999: 13.969 ms/op
                 getUser·p1.00:   13.992 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14734
  mean =      2.168 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 11615 
    [ 2.500,  3.750) = 2844 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      2.003 ms/op
     p(90.0000) =      2.826 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =     13.763 ms/op
     p(99.9900) =     13.969 ms/op
     p(99.9990) =     13.992 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 4.418 ±(99.9%) 0.132 ms/op
Iteration   1: 4.203 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.625 ms/op
                 listUser·p0.50:   4.235 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.231 ms/op
                 listUser·p0.99:   6.566 ms/op
                 listUser·p0.999:  11.960 ms/op
                 listUser·p0.9999: 14.172 ms/op
                 listUser·p1.00:   14.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7648
  mean =      4.203 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 113 
    [ 2.500,  3.750) = 1674 
    [ 3.750,  5.000) = 5144 
    [ 5.000,  6.250) = 580 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.231 ms/op
     p(99.0000) =      6.566 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     14.172 ms/op
     p(99.9990) =     14.172 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.509          ops/ms
ClientSimple.existUser                       thrpt         12.025          ops/ms
ClientSimple.getUser                         thrpt         13.031          ops/ms
ClientSimple.listUser                        thrpt          8.520          ops/ms
ClientSimple.createUser                       avgt          2.065           ms/op
ClientSimple.existUser                        avgt          2.395           ms/op
ClientSimple.getUser                          avgt          2.167           ms/op
ClientSimple.listUser                         avgt          3.184           ms/op
ClientSimple.createUser                     sample  13379   2.389 ± 0.061   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.743           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.040           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.642           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.006           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.567           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.065           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.961           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.983           ms/op
ClientSimple.existUser                      sample  17321   1.849 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.737           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.704           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.281           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.003           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.185           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.725           ms/op
ClientSimple.existUser:existUser·p1.00      sample         33.194           ms/op
ClientSimple.getUser                        sample  14734   2.168 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.799           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.003           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.826           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.990           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.838           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.763           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.969           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.992           ms/op
ClientSimple.listUser                       sample   7648   4.203 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.625           ms/op
ClientSimple.listUser:listUser·p0.50        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.973           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.231           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.566           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.960           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.172           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.172           ms/op

Benchmark result is saved to 1718280400731.json
