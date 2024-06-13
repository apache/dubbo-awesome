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
# Warmup Iteration   1: 1.596 ops/ms
Iteration   1: 7.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.071 ops/ms


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
# Warmup Iteration   1: 6.728 ops/ms
Iteration   1: 12.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.687 ops/ms


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
# Warmup Iteration   1: 6.168 ops/ms
Iteration   1: 11.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.470 ops/ms


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
# Warmup Iteration   1: 4.943 ops/ms
Iteration   1: 8.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.565 ops/ms


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
# Warmup Iteration   1: 3.894 ±(99.9%) 0.079 ms/op
Iteration   1: 2.203 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.203 ms/op


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
# Warmup Iteration   1: 3.181 ±(99.9%) 0.051 ms/op
Iteration   1: 1.853 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.853 ms/op


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
# Warmup Iteration   1: 3.225 ±(99.9%) 0.056 ms/op
Iteration   1: 2.183 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.183 ms/op


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
# Warmup Iteration   1: 4.561 ±(99.9%) 0.094 ms/op
Iteration   1: 3.525 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.525 ms/op


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
# Warmup Iteration   1: 3.585 ±(99.9%) 0.093 ms/op
Iteration   1: 2.272 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.504 ms/op
                 createUser·p0.50:   2.064 ms/op
                 createUser·p0.90:   2.712 ms/op
                 createUser·p0.95:   2.994 ms/op
                 createUser·p0.99:   8.651 ms/op
                 createUser·p0.999:  19.956 ms/op
                 createUser·p0.9999: 20.326 ms/op
                 createUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14093
  mean =      2.272 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11516 
    [ 2.500,  5.000) = 2257 
    [ 5.000,  7.500) = 129 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     20.326 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 2.883 ±(99.9%) 0.071 ms/op
Iteration   1: 1.753 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   1.653 ms/op
                 existUser·p0.90:   1.939 ms/op
                 existUser·p0.95:   2.112 ms/op
                 existUser·p0.99:   2.662 ms/op
                 existUser·p0.999:  21.594 ms/op
                 existUser·p0.9999: 25.664 ms/op
                 existUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18306
  mean =      1.753 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18043 
    [ 2.500,  5.000) = 197 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      1.653 ms/op
     p(90.0000) =      1.939 ms/op
     p(95.0000) =      2.112 ms/op
     p(99.0000) =      2.662 ms/op
     p(99.9000) =     21.594 ms/op
     p(99.9900) =     25.664 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 3.517 ±(99.9%) 0.081 ms/op
Iteration   1: 2.251 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   2.183 ms/op
                 getUser·p0.90:   2.789 ms/op
                 getUser·p0.95:   2.937 ms/op
                 getUser·p0.99:   3.555 ms/op
                 getUser·p0.999:  9.798 ms/op
                 getUser·p0.9999: 10.356 ms/op
                 getUser·p1.00:   10.420 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14321
  mean =      2.251 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 6 
    [ 1.000,  2.000) = 5218 
    [ 2.000,  3.000) = 8535 
    [ 3.000,  4.000) = 468 
    [ 4.000,  5.000) = 33 
    [ 5.000,  6.000) = 23 
    [ 6.000,  7.000) = 1 
    [ 7.000,  8.000) = 5 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.183 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     10.356 ms/op
     p(99.9990) =     10.420 ms/op
     p(99.9999) =     10.420 ms/op
    p(100.0000) =     10.420 ms/op


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
# Warmup Iteration   1: 4.817 ±(99.9%) 0.149 ms/op
Iteration   1: 3.825 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.189 ms/op
                 listUser·p0.999:  20.480 ms/op
                 listUser·p0.9999: 20.546 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8369
  mean =      3.825 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 305 
    [ 2.500,  5.000) = 7795 
    [ 5.000,  7.500) = 203 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.189 ms/op
     p(99.9000) =     20.480 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.071          ops/ms
ClientSimple.existUser                       thrpt         12.687          ops/ms
ClientSimple.getUser                         thrpt         11.470          ops/ms
ClientSimple.listUser                        thrpt          8.565          ops/ms
ClientSimple.createUser                       avgt          2.203           ms/op
ClientSimple.existUser                        avgt          1.853           ms/op
ClientSimple.getUser                          avgt          2.183           ms/op
ClientSimple.listUser                         avgt          3.525           ms/op
ClientSimple.createUser                     sample  14093   2.272 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.504           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.064           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.712           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.994           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.651           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.956           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.326           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.447           ms/op
ClientSimple.existUser                      sample  18306   1.753 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.519           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.653           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.939           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.112           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.594           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.664           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.623           ms/op
ClientSimple.getUser                        sample  14321   2.251 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.775           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.183           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.555           ms/op
ClientSimple.getUser:getUser·p0.999         sample          9.798           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.356           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.420           ms/op
ClientSimple.listUser                       sample   8369   3.825 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.204           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.731           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.189           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.480           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.546           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.546           ms/op

Benchmark result is saved to 1718237765548.json
