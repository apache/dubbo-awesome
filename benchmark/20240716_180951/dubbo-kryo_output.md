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
# Warmup Iteration   1: 1.549 ops/ms
Iteration   1: 6.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.278 ops/ms


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
# Warmup Iteration   1: 4.860 ops/ms
Iteration   1: 10.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.656 ops/ms


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
# Warmup Iteration   1: 5.403 ops/ms
Iteration   1: 11.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.178 ops/ms


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
# Warmup Iteration   1: 4.653 ops/ms
Iteration   1: 8.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.555 ops/ms


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
# Warmup Iteration   1: 4.466 ±(99.9%) 0.083 ms/op
Iteration   1: 2.280 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.280 ms/op


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
# Warmup Iteration   1: 3.091 ±(99.9%) 0.050 ms/op
Iteration   1: 2.102 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.102 ms/op


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
# Warmup Iteration   1: 3.497 ±(99.9%) 0.057 ms/op
Iteration   1: 2.132 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.132 ms/op


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
# Warmup Iteration   1: 4.770 ±(99.9%) 0.081 ms/op
Iteration   1: 3.471 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.471 ms/op


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
# Warmup Iteration   1: 3.469 ±(99.9%) 0.085 ms/op
Iteration   1: 2.209 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   2.025 ms/op
                 createUser·p0.90:   2.597 ms/op
                 createUser·p0.95:   2.906 ms/op
                 createUser·p0.99:   7.965 ms/op
                 createUser·p0.999:  14.785 ms/op
                 createUser·p0.9999: 17.957 ms/op
                 createUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14590
  mean =      2.209 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 12448 
    [ 2.500,  3.750) = 1650 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 114 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.906 ms/op
     p(99.0000) =      7.965 ms/op
     p(99.9000) =     14.785 ms/op
     p(99.9900) =     17.957 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 3.161 ±(99.9%) 0.076 ms/op
Iteration   1: 1.919 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   1.735 ms/op
                 existUser·p0.90:   2.572 ms/op
                 existUser·p0.95:   2.773 ms/op
                 existUser·p0.99:   3.784 ms/op
                 existUser·p0.999:  16.274 ms/op
                 existUser·p0.9999: 16.951 ms/op
                 existUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16727
  mean =      1.919 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 804 
    [ 1.250,  2.500) = 13877 
    [ 2.500,  3.750) = 1869 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      3.784 ms/op
     p(99.9000) =     16.274 ms/op
     p(99.9900) =     16.951 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 3.468 ±(99.9%) 0.092 ms/op
Iteration   1: 2.018 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.511 ms/op
                 getUser·p0.50:   1.958 ms/op
                 getUser·p0.90:   2.560 ms/op
                 getUser·p0.95:   2.859 ms/op
                 getUser·p0.99:   3.861 ms/op
                 getUser·p0.999:  13.289 ms/op
                 getUser·p0.9999: 14.206 ms/op
                 getUser·p1.00:   14.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15933
  mean =      2.018 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 357 
    [ 1.250,  2.500) = 13703 
    [ 2.500,  3.750) = 1702 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      3.861 ms/op
     p(99.9000) =     13.289 ms/op
     p(99.9900) =     14.206 ms/op
     p(99.9990) =     14.303 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 4.504 ±(99.9%) 0.140 ms/op
Iteration   1: 3.704 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   6.927 ms/op
                 listUser·p0.999:  8.204 ms/op
                 listUser·p0.9999: 8.356 ms/op
                 listUser·p1.00:   8.356 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8646
  mean =      3.704 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 122 
    [2.000, 2.500) = 533 
    [2.500, 3.000) = 774 
    [3.000, 3.500) = 1792 
    [3.500, 4.000) = 2675 
    [4.000, 4.500) = 1745 
    [4.500, 5.000) = 695 
    [5.000, 5.500) = 98 
    [5.500, 6.000) = 56 
    [6.000, 6.500) = 19 
    [6.500, 7.000) = 49 
    [7.000, 7.500) = 11 
    [7.500, 8.000) = 33 
    [8.000, 8.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      6.927 ms/op
     p(99.9000) =      8.204 ms/op
     p(99.9900) =      8.356 ms/op
     p(99.9990) =      8.356 ms/op
     p(99.9999) =      8.356 ms/op
    p(100.0000) =      8.356 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.278          ops/ms
ClientSimple.existUser                       thrpt         10.656          ops/ms
ClientSimple.getUser                         thrpt         11.178          ops/ms
ClientSimple.listUser                        thrpt          8.555          ops/ms
ClientSimple.createUser                       avgt          2.280           ms/op
ClientSimple.existUser                        avgt          2.102           ms/op
ClientSimple.getUser                          avgt          2.132           ms/op
ClientSimple.listUser                         avgt          3.471           ms/op
ClientSimple.createUser                     sample  14590   2.209 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.697           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.025           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.906           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.965           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.785           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.957           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.957           ms/op
ClientSimple.existUser                      sample  16727   1.919 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.560           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.735           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.773           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.784           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.274           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.951           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.039           ms/op
ClientSimple.getUser                        sample  15933   2.018 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.511           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.958           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.859           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.861           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.289           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.206           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.303           ms/op
ClientSimple.listUser                       sample   8646   3.704 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.118           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.690           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.825           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.927           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.204           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.356           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.356           ms/op

Benchmark result is saved to 1721153125959.json
