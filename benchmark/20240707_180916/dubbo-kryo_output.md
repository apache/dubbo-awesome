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
# Warmup Iteration   1: 1.673 ops/ms
Iteration   1: 7.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.425 ops/ms


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
# Warmup Iteration   1: 4.918 ops/ms
Iteration   1: 12.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.579 ops/ms


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
# Warmup Iteration   1: 5.109 ops/ms
Iteration   1: 13.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.535 ops/ms


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
# Warmup Iteration   1: 4.945 ops/ms
Iteration   1: 8.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.328 ops/ms


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
# Warmup Iteration   1: 4.344 ±(99.9%) 0.090 ms/op
Iteration   1: 2.392 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.392 ms/op


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
# Warmup Iteration   1: 3.269 ±(99.9%) 0.054 ms/op
Iteration   1: 1.937 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.937 ms/op


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
# Warmup Iteration   1: 3.382 ±(99.9%) 0.060 ms/op
Iteration   1: 2.227 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.227 ms/op


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
# Warmup Iteration   1: 4.579 ±(99.9%) 0.092 ms/op
Iteration   1: 3.475 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.475 ms/op


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
# Warmup Iteration   1: 3.454 ±(99.9%) 0.095 ms/op
Iteration   1: 2.219 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   1.942 ms/op
                 createUser·p0.90:   2.617 ms/op
                 createUser·p0.95:   2.941 ms/op
                 createUser·p0.99:   10.207 ms/op
                 createUser·p0.999:  21.810 ms/op
                 createUser·p0.9999: 22.499 ms/op
                 createUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14399
  mean =      2.219 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12335 
    [ 2.500,  5.000) = 1760 
    [ 5.000,  7.500) = 111 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      1.942 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     21.810 ms/op
     p(99.9900) =     22.499 ms/op
     p(99.9990) =     22.643 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 2.852 ±(99.9%) 0.065 ms/op
Iteration   1: 2.012 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.561 ms/op
                 existUser·p0.50:   1.890 ms/op
                 existUser·p0.90:   2.447 ms/op
                 existUser·p0.95:   2.712 ms/op
                 existUser·p0.99:   3.574 ms/op
                 existUser·p0.999:  21.823 ms/op
                 existUser·p0.9999: 22.239 ms/op
                 existUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16055
  mean =      2.012 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14591 
    [ 2.500,  5.000) = 1370 
    [ 5.000,  7.500) = 25 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.447 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      3.574 ms/op
     p(99.9000) =     21.823 ms/op
     p(99.9900) =     22.239 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 3.174 ±(99.9%) 0.076 ms/op
Iteration   1: 1.753 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.428 ms/op
                 getUser·p0.50:   1.688 ms/op
                 getUser·p0.90:   2.224 ms/op
                 getUser·p0.95:   2.355 ms/op
                 getUser·p0.99:   3.039 ms/op
                 getUser·p0.999:  12.903 ms/op
                 getUser·p0.9999: 13.533 ms/op
                 getUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18224
  mean =      1.753 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1319 
    [ 1.250,  2.500) = 16381 
    [ 2.500,  3.750) = 469 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      1.688 ms/op
     p(90.0000) =      2.224 ms/op
     p(95.0000) =      2.355 ms/op
     p(99.0000) =      3.039 ms/op
     p(99.9000) =     12.903 ms/op
     p(99.9900) =     13.533 ms/op
     p(99.9990) =     13.533 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


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
# Warmup Iteration   1: 4.508 ±(99.9%) 0.142 ms/op
Iteration   1: 3.444 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   3.445 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.235 ms/op
                 listUser·p0.999:  7.043 ms/op
                 listUser·p0.9999: 7.152 ms/op
                 listUser·p1.00:   7.152 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9295
  mean =      3.444 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 3 
    [1.500, 2.000) = 110 
    [2.000, 2.500) = 617 
    [2.500, 3.000) = 1663 
    [3.000, 3.500) = 2539 
    [3.500, 4.000) = 2775 
    [4.000, 4.500) = 1130 
    [4.500, 5.000) = 295 
    [5.000, 5.500) = 96 
    [5.500, 6.000) = 28 
    [6.000, 6.500) = 3 
    [6.500, 7.000) = 24 
    [7.000, 7.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =      7.043 ms/op
     p(99.9900) =      7.152 ms/op
     p(99.9990) =      7.152 ms/op
     p(99.9999) =      7.152 ms/op
    p(100.0000) =      7.152 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.425          ops/ms
ClientSimple.existUser                       thrpt         12.579          ops/ms
ClientSimple.getUser                         thrpt         13.535          ops/ms
ClientSimple.listUser                        thrpt          8.328          ops/ms
ClientSimple.createUser                       avgt          2.392           ms/op
ClientSimple.existUser                        avgt          1.937           ms/op
ClientSimple.getUser                          avgt          2.227           ms/op
ClientSimple.listUser                         avgt          3.475           ms/op
ClientSimple.createUser                     sample  14399   2.219 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.582           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.942           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.617           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.941           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.207           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.810           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.499           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.643           ms/op
ClientSimple.existUser                      sample  16055   2.012 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.561           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.890           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.447           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.712           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.574           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.823           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.239           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.675           ms/op
ClientSimple.getUser                        sample  18224   1.753 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.428           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.688           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.224           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.355           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.039           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.903           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.533           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.533           ms/op
ClientSimple.listUser                       sample   9295   3.444 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.862           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.445           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.497           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.235           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.043           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.152           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.152           ms/op

Benchmark result is saved to 1720375503559.json
