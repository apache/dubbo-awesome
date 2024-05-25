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
# Warmup Iteration   1: 1.487 ops/ms
Iteration   1: 6.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.209 ops/ms


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
# Warmup Iteration   1: 5.809 ops/ms
Iteration   1: 13.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.152 ops/ms


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
# Warmup Iteration   1: 6.494 ops/ms
Iteration   1: 13.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.059 ops/ms


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
# Warmup Iteration   1: 5.638 ops/ms
Iteration   1: 8.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.195 ops/ms


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
# Warmup Iteration   1: 4.837 ±(99.9%) 0.091 ms/op
Iteration   1: 2.246 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.246 ms/op


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
# Warmup Iteration   1: 3.146 ±(99.9%) 0.046 ms/op
Iteration   1: 1.859 ±(99.9%) 0.009 ms/op


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
# Warmup Iteration   1: 3.285 ±(99.9%) 0.059 ms/op
Iteration   1: 1.836 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.836 ms/op


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
# Warmup Iteration   1: 4.636 ±(99.9%) 0.097 ms/op
Iteration   1: 3.289 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.289 ms/op


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
# Warmup Iteration   1: 3.492 ±(99.9%) 0.083 ms/op
Iteration   1: 2.246 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   2.025 ms/op
                 createUser·p0.90:   2.728 ms/op
                 createUser·p0.95:   3.019 ms/op
                 createUser·p0.99:   11.321 ms/op
                 createUser·p0.999:  20.438 ms/op
                 createUser·p0.9999: 20.803 ms/op
                 createUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14276
  mean =      2.246 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11838 
    [ 2.500,  5.000) = 2140 
    [ 5.000,  7.500) = 42 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     20.438 ms/op
     p(99.9900) =     20.803 ms/op
     p(99.9990) =     20.873 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 3.088 ±(99.9%) 0.075 ms/op
Iteration   1: 2.068 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.199 ms/op
                 existUser·p0.50:   2.022 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   3.318 ms/op
                 existUser·p0.999:  12.386 ms/op
                 existUser·p0.9999: 13.834 ms/op
                 existUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15456
  mean =      2.068 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 284 
    [ 1.250,  2.500) = 13561 
    [ 2.500,  3.750) = 1527 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.199 ms/op
     p(50.0000) =      2.022 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.318 ms/op
     p(99.9000) =     12.386 ms/op
     p(99.9900) =     13.834 ms/op
     p(99.9990) =     13.861 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


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
# Warmup Iteration   1: 3.369 ±(99.9%) 0.082 ms/op
Iteration   1: 2.012 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   1.825 ms/op
                 getUser·p0.90:   2.575 ms/op
                 getUser·p0.95:   2.798 ms/op
                 getUser·p0.99:   3.872 ms/op
                 getUser·p0.999:  21.365 ms/op
                 getUser·p0.9999: 22.435 ms/op
                 getUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15963
  mean =      2.012 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14148 
    [ 2.500,  5.000) = 1701 
    [ 5.000,  7.500) = 18 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.575 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      3.872 ms/op
     p(99.9000) =     21.365 ms/op
     p(99.9900) =     22.435 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 4.617 ±(99.9%) 0.186 ms/op
Iteration   1: 3.694 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   6.530 ms/op
                 listUser·p0.999:  14.702 ms/op
                 listUser·p0.9999: 15.663 ms/op
                 listUser·p1.00:   15.663 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8647
  mean =      3.694 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 471 
    [ 2.500,  3.750) = 4101 
    [ 3.750,  5.000) = 3879 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.530 ms/op
     p(99.9000) =     14.702 ms/op
     p(99.9900) =     15.663 ms/op
     p(99.9990) =     15.663 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.209          ops/ms
ClientSimple.existUser                       thrpt         13.152          ops/ms
ClientSimple.getUser                         thrpt         13.059          ops/ms
ClientSimple.listUser                        thrpt          8.195          ops/ms
ClientSimple.createUser                       avgt          2.246           ms/op
ClientSimple.existUser                        avgt          1.859           ms/op
ClientSimple.getUser                          avgt          1.836           ms/op
ClientSimple.listUser                         avgt          3.289           ms/op
ClientSimple.createUser                     sample  14276   2.246 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.593           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.025           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.019           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.321           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.438           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.803           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.873           ms/op
ClientSimple.existUser                      sample  15456   2.068 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.199           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.022           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.318           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.386           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.834           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.861           ms/op
ClientSimple.getUser                        sample  15963   2.012 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.781           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.825           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.575           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.798           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.872           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.365           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.435           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.708           ms/op
ClientSimple.listUser                       sample   8647   3.694 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.804           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.715           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.710           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.530           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.702           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.663           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.663           ms/op

Benchmark result is saved to 1716617133793.json
