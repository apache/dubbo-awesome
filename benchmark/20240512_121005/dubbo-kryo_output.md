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
# Warmup Iteration   1: 1.874 ops/ms
Iteration   1: 7.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.161 ops/ms


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
# Warmup Iteration   1: 6.351 ops/ms
Iteration   1: 12.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.453 ops/ms


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
# Warmup Iteration   1: 6.041 ops/ms
Iteration   1: 14.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.409 ops/ms


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
# Warmup Iteration   1: 5.968 ops/ms
Iteration   1: 8.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.517 ops/ms


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
# Warmup Iteration   1: 3.743 ±(99.9%) 0.073 ms/op
Iteration   1: 2.145 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.145 ms/op


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
# Warmup Iteration   1: 3.094 ±(99.9%) 0.044 ms/op
Iteration   1: 1.859 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.859 ms/op


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
# Warmup Iteration   1: 3.439 ±(99.9%) 0.061 ms/op
Iteration   1: 1.976 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.976 ms/op


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
# Warmup Iteration   1: 4.305 ±(99.9%) 0.104 ms/op
Iteration   1: 3.381 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.381 ms/op


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
# Warmup Iteration   1: 3.315 ±(99.9%) 0.095 ms/op
Iteration   1: 2.038 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   1.880 ms/op
                 createUser·p0.90:   2.507 ms/op
                 createUser·p0.95:   2.728 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  22.512 ms/op
                 createUser·p0.9999: 23.921 ms/op
                 createUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15692
  mean =      2.038 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14091 
    [ 2.500,  5.000) = 1460 
    [ 5.000,  7.500) = 13 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      4.768 ms/op
     p(99.9000) =     22.512 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     24.052 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 2.906 ±(99.9%) 0.061 ms/op
Iteration   1: 1.715 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.499 ms/op
                 existUser·p0.50:   1.604 ms/op
                 existUser·p0.90:   2.118 ms/op
                 existUser·p0.95:   2.245 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  10.639 ms/op
                 existUser·p0.9999: 11.256 ms/op
                 existUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18643
  mean =      1.715 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1443 
    [ 1.250,  2.500) = 16739 
    [ 2.500,  3.750) = 211 
    [ 3.750,  5.000) = 133 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      1.604 ms/op
     p(90.0000) =      2.118 ms/op
     p(95.0000) =      2.245 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =     10.639 ms/op
     p(99.9900) =     11.256 ms/op
     p(99.9990) =     11.256 ms/op
     p(99.9999) =     11.256 ms/op
    p(100.0000) =     11.256 ms/op


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
# Warmup Iteration   1: 3.185 ±(99.9%) 0.071 ms/op
Iteration   1: 1.646 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.551 ms/op
                 getUser·p0.50:   1.499 ms/op
                 getUser·p0.90:   2.097 ms/op
                 getUser·p0.95:   2.310 ms/op
                 getUser·p0.99:   3.424 ms/op
                 getUser·p0.999:  16.908 ms/op
                 getUser·p0.9999: 17.520 ms/op
                 getUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 19613
  mean =      1.646 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3162 
    [ 1.250,  2.500) = 15905 
    [ 2.500,  3.750) = 381 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      1.499 ms/op
     p(90.0000) =      2.097 ms/op
     p(95.0000) =      2.310 ms/op
     p(99.0000) =      3.424 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     17.520 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 4.242 ±(99.9%) 0.111 ms/op
Iteration   1: 3.331 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   3.162 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.611 ms/op
                 listUser·p0.99:   6.300 ms/op
                 listUser·p0.999:  17.116 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9661
  mean =      3.331 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 758 
    [ 2.500,  3.750) = 6065 
    [ 3.750,  5.000) = 2619 
    [ 5.000,  6.250) = 112 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.611 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     17.116 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.161          ops/ms
ClientSimple.existUser                       thrpt         12.453          ops/ms
ClientSimple.getUser                         thrpt         14.409          ops/ms
ClientSimple.listUser                        thrpt          8.517          ops/ms
ClientSimple.createUser                       avgt          2.145           ms/op
ClientSimple.existUser                        avgt          1.859           ms/op
ClientSimple.getUser                          avgt          1.976           ms/op
ClientSimple.listUser                         avgt          3.381           ms/op
ClientSimple.createUser                     sample  15692   2.038 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.709           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.880           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.507           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.768           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.512           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.921           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.052           ms/op
ClientSimple.existUser                      sample  18643   1.715 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.499           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.604           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.118           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.245           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.760           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.639           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.256           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.256           ms/op
ClientSimple.getUser                        sample  19613   1.646 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.551           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.499           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.097           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.310           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.424           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.908           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.520           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.055           ms/op
ClientSimple.listUser                       sample   9661   3.331 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.298           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.162           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.611           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.300           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.116           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.400           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.400           ms/op

Benchmark result is saved to 1715515560335.json
