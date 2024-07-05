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
# Warmup Iteration   1: 0.900 ops/ms
Iteration   1: 5.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.828 ops/ms


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
# Warmup Iteration   1: 6.219 ops/ms
Iteration   1: 13.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.161 ops/ms


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
# Warmup Iteration   1: 5.641 ops/ms
Iteration   1: 13.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.048 ops/ms


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
# Warmup Iteration   1: 6.176 ops/ms
Iteration   1: 8.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.273 ops/ms


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
# Warmup Iteration   1: 3.943 ±(99.9%) 0.069 ms/op
Iteration   1: 1.887 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.887 ms/op


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
# Warmup Iteration   1: 3.205 ±(99.9%) 0.057 ms/op
Iteration   1: 1.773 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.773 ms/op


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.058 ms/op
Iteration   1: 2.264 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.264 ms/op


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
# Warmup Iteration   1: 4.396 ±(99.9%) 0.089 ms/op
Iteration   1: 3.252 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.252 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.077 ms/op
Iteration   1: 2.078 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.397 ms/op
                 createUser·p0.50:   1.786 ms/op
                 createUser·p0.90:   2.662 ms/op
                 createUser·p0.95:   2.945 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  35.193 ms/op
                 createUser·p0.9999: 37.971 ms/op
                 createUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15379
  mean =      2.078 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13450 
    [ 2.500,  5.000) = 1753 
    [ 5.000,  7.500) = 81 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     35.193 ms/op
     p(99.9900) =     37.971 ms/op
     p(99.9990) =     38.076 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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
# Warmup Iteration   1: 3.125 ±(99.9%) 0.080 ms/op
Iteration   1: 2.159 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.105 ms/op
                 existUser·p0.90:   2.666 ms/op
                 existUser·p0.95:   2.839 ms/op
                 existUser·p0.99:   3.624 ms/op
                 existUser·p0.999:  14.896 ms/op
                 existUser·p0.9999: 15.313 ms/op
                 existUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14828
  mean =      2.159 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 136 
    [ 1.250,  2.500) = 12308 
    [ 2.500,  3.750) = 2283 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      3.624 ms/op
     p(99.9000) =     14.896 ms/op
     p(99.9900) =     15.313 ms/op
     p(99.9990) =     15.385 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 3.425 ±(99.9%) 0.082 ms/op
Iteration   1: 2.073 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   1.921 ms/op
                 getUser·p0.90:   2.503 ms/op
                 getUser·p0.95:   2.666 ms/op
                 getUser·p0.99:   5.203 ms/op
                 getUser·p0.999:  22.348 ms/op
                 getUser·p0.9999: 22.512 ms/op
                 getUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15420
  mean =      2.073 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13866 
    [ 2.500,  5.000) = 1384 
    [ 5.000,  7.500) = 98 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      5.203 ms/op
     p(99.9000) =     22.348 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     22.512 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.122 ms/op
Iteration   1: 3.122 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   0.632 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.035 ms/op
                 listUser·p0.99:   7.181 ms/op
                 listUser·p0.999:  21.554 ms/op
                 listUser·p0.9999: 21.659 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10208
  mean =      3.122 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 646 
    [ 2.500,  5.000) = 9336 
    [ 5.000,  7.500) = 157 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      7.181 ms/op
     p(99.9000) =     21.554 ms/op
     p(99.9900) =     21.659 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.828          ops/ms
ClientSimple.existUser                       thrpt         13.161          ops/ms
ClientSimple.getUser                         thrpt         13.048          ops/ms
ClientSimple.listUser                        thrpt          8.273          ops/ms
ClientSimple.createUser                       avgt          1.887           ms/op
ClientSimple.existUser                        avgt          1.773           ms/op
ClientSimple.getUser                          avgt          2.264           ms/op
ClientSimple.listUser                         avgt          3.252           ms/op
ClientSimple.createUser                     sample  15379   2.078 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.397           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.786           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.945           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.505           ms/op
ClientSimple.createUser:createUser·p0.999   sample         35.193           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.971           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.076           ms/op
ClientSimple.existUser                      sample  14828   2.159 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.694           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.105           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.666           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.839           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.624           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.896           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.313           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.385           ms/op
ClientSimple.getUser                        sample  15420   2.073 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.761           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.921           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.503           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.203           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.348           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.512           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.512           ms/op
ClientSimple.listUser                       sample  10208   3.122 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.632           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.888           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.768           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.035           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.181           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.554           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.659           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.660           ms/op

Benchmark result is saved to 1720159538681.json
