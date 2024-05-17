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
Iteration   1: 6.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.273 ops/ms


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
# Warmup Iteration   1: 6.982 ops/ms
Iteration   1: 13.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.257 ops/ms


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
# Warmup Iteration   1: 6.971 ops/ms
Iteration   1: 13.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.174 ops/ms
Iteration   1: 8.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.931 ops/ms


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
# Warmup Iteration   1: 4.299 ±(99.9%) 0.089 ms/op
Iteration   1: 2.088 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.088 ms/op


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
# Warmup Iteration   1: 3.108 ±(99.9%) 0.051 ms/op
Iteration   1: 2.180 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.180 ms/op


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
# Warmup Iteration   1: 3.091 ±(99.9%) 0.055 ms/op
Iteration   1: 1.935 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.935 ms/op


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
# Warmup Iteration   1: 4.929 ±(99.9%) 0.106 ms/op
Iteration   1: 3.166 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.166 ms/op


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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.123 ms/op
Iteration   1: 2.062 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   1.866 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.822 ms/op
                 createUser·p0.99:   8.004 ms/op
                 createUser·p0.999:  12.688 ms/op
                 createUser·p0.9999: 13.388 ms/op
                 createUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15575
  mean =      2.062 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 539 
    [ 1.250,  2.500) = 12882 
    [ 2.500,  3.750) = 1810 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     12.688 ms/op
     p(99.9900) =     13.388 ms/op
     p(99.9990) =     13.763 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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
# Warmup Iteration   1: 3.316 ±(99.9%) 0.102 ms/op
Iteration   1: 1.891 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.583 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.531 ms/op
                 existUser·p0.99:   3.224 ms/op
                 existUser·p0.999:  19.562 ms/op
                 existUser·p0.9999: 19.910 ms/op
                 existUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16907
  mean =      1.891 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 708 
    [ 1.250,  2.500) = 15189 
    [ 2.500,  3.750) = 886 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.531 ms/op
     p(99.0000) =      3.224 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     19.910 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 3.274 ±(99.9%) 0.071 ms/op
Iteration   1: 1.941 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.314 ms/op
                 getUser·p0.50:   1.843 ms/op
                 getUser·p0.90:   2.454 ms/op
                 getUser·p0.95:   2.675 ms/op
                 getUser·p0.99:   3.362 ms/op
                 getUser·p0.999:  11.862 ms/op
                 getUser·p0.9999: 12.009 ms/op
                 getUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16527
  mean =      1.941 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 278 
    [ 1.250,  2.500) = 14780 
    [ 2.500,  3.750) = 1337 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.314 ms/op
     p(50.0000) =      1.843 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      3.362 ms/op
     p(99.9000) =     11.862 ms/op
     p(99.9900) =     12.009 ms/op
     p(99.9990) =     12.009 ms/op
     p(99.9999) =     12.009 ms/op
    p(100.0000) =     12.009 ms/op


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
# Warmup Iteration   1: 4.664 ±(99.9%) 0.130 ms/op
Iteration   1: 3.611 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.531 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.434 ms/op
                 listUser·p0.999:  16.022 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8852
  mean =      3.611 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 694 
    [ 2.500,  3.750) = 4925 
    [ 3.750,  5.000) = 2874 
    [ 5.000,  6.250) = 194 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.434 ms/op
     p(99.9000) =     16.022 ms/op
     p(99.9900) =     16.876 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.273          ops/ms
ClientSimple.existUser                       thrpt         13.257          ops/ms
ClientSimple.getUser                         thrpt         13.235          ops/ms
ClientSimple.listUser                        thrpt          8.931          ops/ms
ClientSimple.createUser                       avgt          2.088           ms/op
ClientSimple.existUser                        avgt          2.180           ms/op
ClientSimple.getUser                          avgt          1.935           ms/op
ClientSimple.listUser                         avgt          3.166           ms/op
ClientSimple.createUser                     sample  15575   2.062 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.762           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.866           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.004           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.688           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.388           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.763           ms/op
ClientSimple.existUser                      sample  16907   1.891 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.583           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.778           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.224           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.562           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.910           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.956           ms/op
ClientSimple.getUser                        sample  16527   1.941 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.314           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.843           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.454           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.675           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.362           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.862           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.009           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.009           ms/op
ClientSimple.listUser                       sample   8852   3.611 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.061           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.531           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.434           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.022           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.876           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.876           ms/op

Benchmark result is saved to 1715969125504.json
