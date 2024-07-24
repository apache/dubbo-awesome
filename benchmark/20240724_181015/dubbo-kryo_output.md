# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.183 ops/ms
Iteration   1: 5.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.820 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.757 ops/ms
Iteration   1: 11.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.222 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.686 ops/ms
Iteration   1: 13.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.702 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.867 ops/ms
Iteration   1: 8.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.301 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.404 ±(99.9%) 0.057 ms/op
Iteration   1: 2.273 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.273 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.049 ±(99.9%) 0.048 ms/op
Iteration   1: 2.167 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.167 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.185 ±(99.9%) 0.051 ms/op
Iteration   1: 1.935 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.935 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.211 ±(99.9%) 0.080 ms/op
Iteration   1: 3.368 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.368 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.204 ±(99.9%) 0.110 ms/op
Iteration   1: 2.543 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   2.281 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.441 ms/op
                 createUser·p0.99:   9.765 ms/op
                 createUser·p0.999:  30.141 ms/op
                 createUser·p0.9999: 31.765 ms/op
                 createUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12578
  mean =      2.543 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7922 
    [ 2.500,  5.000) = 4399 
    [ 5.000,  7.500) = 58 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      2.281 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.441 ms/op
     p(99.0000) =      9.765 ms/op
     p(99.9000) =     30.141 ms/op
     p(99.9900) =     31.765 ms/op
     p(99.9990) =     31.883 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.920 ±(99.9%) 0.065 ms/op
Iteration   1: 1.697 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   1.593 ms/op
                 existUser·p0.90:   2.159 ms/op
                 existUser·p0.95:   2.322 ms/op
                 existUser·p0.99:   2.723 ms/op
                 existUser·p0.999:  10.748 ms/op
                 existUser·p0.9999: 10.928 ms/op
                 existUser·p1.00:   10.928 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18828
  mean =      1.697 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 846 
    [ 1.250,  2.500) = 17645 
    [ 2.500,  3.750) = 242 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
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
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      1.593 ms/op
     p(90.0000) =      2.159 ms/op
     p(95.0000) =      2.322 ms/op
     p(99.0000) =      2.723 ms/op
     p(99.9000) =     10.748 ms/op
     p(99.9900) =     10.928 ms/op
     p(99.9990) =     10.928 ms/op
     p(99.9999) =     10.928 ms/op
    p(100.0000) =     10.928 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.653 ±(99.9%) 0.087 ms/op
Iteration   1: 2.142 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   2.064 ms/op
                 getUser·p0.90:   2.753 ms/op
                 getUser·p0.95:   3.015 ms/op
                 getUser·p0.99:   3.976 ms/op
                 getUser·p0.999:  11.775 ms/op
                 getUser·p0.9999: 12.173 ms/op
                 getUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14920
  mean =      2.142 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 12050 
    [ 2.500,  3.750) = 2553 
    [ 3.750,  5.000) = 163 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 1 
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
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      3.976 ms/op
     p(99.9000) =     11.775 ms/op
     p(99.9900) =     12.173 ms/op
     p(99.9990) =     12.173 ms/op
     p(99.9999) =     12.173 ms/op
    p(100.0000) =     12.173 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.216 ±(99.9%) 0.132 ms/op
Iteration   1: 3.422 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   0.719 ms/op
                 listUser·p0.50:   3.342 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  22.643 ms/op
                 listUser·p0.9999: 23.527 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9330
  mean =      3.422 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1820 
    [ 2.500,  5.000) = 7200 
    [ 5.000,  7.500) = 187 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      9.912 ms/op
     p(99.9000) =     22.643 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.820          ops/ms
ClientSimple.existUser                       thrpt         11.222          ops/ms
ClientSimple.getUser                         thrpt         13.702          ops/ms
ClientSimple.listUser                        thrpt          8.301          ops/ms
ClientSimple.createUser                       avgt          2.273           ms/op
ClientSimple.existUser                        avgt          2.167           ms/op
ClientSimple.getUser                          avgt          1.935           ms/op
ClientSimple.listUser                         avgt          3.368           ms/op
ClientSimple.createUser                     sample  12578   2.543 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.669           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.281           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.035           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.441           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.765           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.141           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.765           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.883           ms/op
ClientSimple.existUser                      sample  18828   1.697 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.556           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.593           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.159           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.723           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.748           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.928           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.928           ms/op
ClientSimple.getUser                        sample  14920   2.142 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.798           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.064           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.015           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.976           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.775           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.173           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.173           ms/op
ClientSimple.listUser                       sample   9330   3.422 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.719           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.342           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.190           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.912           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.643           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.527           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.527           ms/op

Benchmark result is saved to 1721844376979.json
