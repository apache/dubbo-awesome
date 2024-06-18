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
# Warmup Iteration   1: 1.412 ops/ms
Iteration   1: 6.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.565 ops/ms


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
# Warmup Iteration   1: 5.779 ops/ms
Iteration   1: 12.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.117 ops/ms


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
# Warmup Iteration   1: 5.835 ops/ms
Iteration   1: 13.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.438 ops/ms


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
# Warmup Iteration   1: 5.684 ops/ms
Iteration   1: 8.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.680 ops/ms


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
# Warmup Iteration   1: 4.712 ±(99.9%) 0.172 ms/op
Iteration   1: 2.111 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.111 ms/op


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
# Warmup Iteration   1: 3.569 ±(99.9%) 0.078 ms/op
Iteration   1: 1.744 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.744 ms/op


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
# Warmup Iteration   1: 4.515 ±(99.9%) 0.079 ms/op
Iteration   1: 1.891 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.891 ms/op


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
# Warmup Iteration   1: 4.459 ±(99.9%) 0.085 ms/op
Iteration   1: 3.264 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.264 ms/op


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
# Warmup Iteration   1: 3.489 ±(99.9%) 0.083 ms/op
Iteration   1: 2.009 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   1.829 ms/op
                 createUser·p0.90:   2.421 ms/op
                 createUser·p0.95:   2.761 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  15.533 ms/op
                 createUser·p0.9999: 15.840 ms/op
                 createUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15922
  mean =      2.009 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 14507 
    [ 2.500,  3.750) = 872 
    [ 3.750,  5.000) = 176 
    [ 5.000,  6.250) = 115 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     15.533 ms/op
     p(99.9900) =     15.840 ms/op
     p(99.9990) =     15.860 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.088 ms/op
Iteration   1: 2.066 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.418 ms/op
                 existUser·p0.50:   2.054 ms/op
                 existUser·p0.90:   2.650 ms/op
                 existUser·p0.95:   2.822 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  13.337 ms/op
                 existUser·p0.9999: 14.316 ms/op
                 existUser·p1.00:   14.352 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15510
  mean =      2.066 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 817 
    [ 1.250,  2.500) = 11828 
    [ 2.500,  3.750) = 2671 
    [ 3.750,  5.000) = 94 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     14.316 ms/op
     p(99.9990) =     14.352 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 3.254 ±(99.9%) 0.081 ms/op
Iteration   1: 2.220 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   2.037 ms/op
                 getUser·p0.90:   2.896 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   5.226 ms/op
                 getUser·p0.999:  13.763 ms/op
                 getUser·p0.9999: 14.712 ms/op
                 getUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14408
  mean =      2.220 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 251 
    [ 1.250,  2.500) = 9915 
    [ 2.500,  3.750) = 3993 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 129 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.037 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     13.763 ms/op
     p(99.9900) =     14.712 ms/op
     p(99.9990) =     15.008 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 5.061 ±(99.9%) 0.187 ms/op
Iteration   1: 3.510 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   6.242 ms/op
                 listUser·p0.999:  13.923 ms/op
                 listUser·p0.9999: 14.795 ms/op
                 listUser·p1.00:   14.795 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9104
  mean =      3.510 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 786 
    [ 2.500,  3.750) = 5465 
    [ 3.750,  5.000) = 2558 
    [ 5.000,  6.250) = 197 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     13.923 ms/op
     p(99.9900) =     14.795 ms/op
     p(99.9990) =     14.795 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.565          ops/ms
ClientSimple.existUser                       thrpt         12.117          ops/ms
ClientSimple.getUser                         thrpt         13.438          ops/ms
ClientSimple.listUser                        thrpt          8.680          ops/ms
ClientSimple.createUser                       avgt          2.111           ms/op
ClientSimple.existUser                        avgt          1.744           ms/op
ClientSimple.getUser                          avgt          1.891           ms/op
ClientSimple.listUser                         avgt          3.264           ms/op
ClientSimple.createUser                     sample  15922   2.009 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.562           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.829           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.421           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.743           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.533           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.840           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.860           ms/op
ClientSimple.existUser                      sample  15510   2.066 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.418           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.054           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.822           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.399           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.337           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.316           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.352           ms/op
ClientSimple.getUser                        sample  14408   2.220 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.584           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.037           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.896           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.154           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.226           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.763           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.712           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.008           ms/op
ClientSimple.listUser                       sample   9104   3.510 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.804           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.543           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.141           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.588           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.242           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.923           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.795           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.795           ms/op

Benchmark result is saved to 1718669784318.json
