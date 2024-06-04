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
# Warmup Iteration   1: 2.018 ops/ms
Iteration   1: 7.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.825 ops/ms


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
# Warmup Iteration   1: 5.970 ops/ms
Iteration   1: 13.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.927 ops/ms


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
# Warmup Iteration   1: 4.769 ops/ms
Iteration   1: 10.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.777 ops/ms


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
# Warmup Iteration   1: 4.141 ops/ms
Iteration   1: 7.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.779 ops/ms


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
# Warmup Iteration   1: 3.654 ±(99.9%) 0.076 ms/op
Iteration   1: 2.048 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.048 ms/op


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
# Warmup Iteration   1: 3.663 ±(99.9%) 0.057 ms/op
Iteration   1: 1.953 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.953 ms/op


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
# Warmup Iteration   1: 3.379 ±(99.9%) 0.064 ms/op
Iteration   1: 2.236 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.236 ms/op


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
# Warmup Iteration   1: 4.424 ±(99.9%) 0.115 ms/op
Iteration   1: 3.552 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.552 ms/op


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
# Warmup Iteration   1: 3.665 ±(99.9%) 0.089 ms/op
Iteration   1: 2.307 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   2.093 ms/op
                 createUser·p0.90:   2.613 ms/op
                 createUser·p0.95:   2.871 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  36.635 ms/op
                 createUser·p0.9999: 37.692 ms/op
                 createUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13859
  mean =      2.307 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11695 
    [ 2.500,  5.000) = 1943 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      2.093 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     36.635 ms/op
     p(99.9900) =     37.692 ms/op
     p(99.9990) =     37.945 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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
# Warmup Iteration   1: 2.752 ±(99.9%) 0.062 ms/op
Iteration   1: 1.907 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   1.860 ms/op
                 existUser·p0.90:   2.277 ms/op
                 existUser·p0.95:   2.396 ms/op
                 existUser·p0.99:   3.115 ms/op
                 existUser·p0.999:  12.419 ms/op
                 existUser·p0.9999: 12.588 ms/op
                 existUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16853
  mean =      1.907 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 242 
    [ 1.250,  2.500) = 16084 
    [ 2.500,  3.750) = 471 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      3.115 ms/op
     p(99.9000) =     12.419 ms/op
     p(99.9900) =     12.588 ms/op
     p(99.9990) =     12.599 ms/op
     p(99.9999) =     12.599 ms/op
    p(100.0000) =     12.599 ms/op


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
# Warmup Iteration   1: 3.489 ±(99.9%) 0.083 ms/op
Iteration   1: 2.180 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   2.122 ms/op
                 getUser·p0.90:   2.646 ms/op
                 getUser·p0.95:   2.810 ms/op
                 getUser·p0.99:   3.798 ms/op
                 getUser·p0.999:  16.078 ms/op
                 getUser·p0.9999: 16.655 ms/op
                 getUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14670
  mean =      2.180 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 12051 
    [ 2.500,  3.750) = 2341 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      3.798 ms/op
     p(99.9000) =     16.078 ms/op
     p(99.9900) =     16.655 ms/op
     p(99.9990) =     16.663 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 4.638 ±(99.9%) 0.129 ms/op
Iteration   1: 3.586 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.559 ms/op
                 listUser·p0.999:  22.386 ms/op
                 listUser·p0.9999: 22.544 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8920
  mean =      3.586 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 591 
    [ 2.500,  5.000) = 7924 
    [ 5.000,  7.500) = 309 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.559 ms/op
     p(99.9000) =     22.386 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     22.544 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.825          ops/ms
ClientSimple.existUser                       thrpt         13.927          ops/ms
ClientSimple.getUser                         thrpt         10.777          ops/ms
ClientSimple.listUser                        thrpt          7.779          ops/ms
ClientSimple.createUser                       avgt          2.048           ms/op
ClientSimple.existUser                        avgt          1.953           ms/op
ClientSimple.getUser                          avgt          2.236           ms/op
ClientSimple.listUser                         avgt          3.552           ms/op
ClientSimple.createUser                     sample  13859   2.307 ± 0.053   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.840           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.093           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.613           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.871           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.562           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.635           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.692           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.945           ms/op
ClientSimple.existUser                      sample  16853   1.907 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.823           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.860           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.115           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.419           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.588           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.599           ms/op
ClientSimple.getUser                        sample  14670   2.180 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.805           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.122           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.646           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.798           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.078           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.655           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.663           ms/op
ClientSimple.listUser                       sample   8920   3.586 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.102           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.596           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.841           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.559           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.386           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.544           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.544           ms/op

Benchmark result is saved to 1717524345034.json
