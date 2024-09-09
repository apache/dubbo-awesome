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
# Warmup Iteration   1: 1.799 ops/ms
Iteration   1: 6.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.687 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.201 ops/ms
Iteration   1: 13.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.194 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.296 ops/ms
Iteration   1: 11.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.364 ops/ms


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
# Warmup Iteration   1: 4.736 ops/ms
Iteration   1: 8.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.447 ops/ms


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.077 ms/op
Iteration   1: 2.174 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.174 ms/op


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
# Warmup Iteration   1: 3.310 ±(99.9%) 0.071 ms/op
Iteration   1: 1.890 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.890 ms/op


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
# Warmup Iteration   1: 3.486 ±(99.9%) 0.063 ms/op
Iteration   1: 2.032 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.032 ms/op


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
# Warmup Iteration   1: 4.827 ±(99.9%) 0.106 ms/op
Iteration   1: 3.600 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.600 ms/op


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
# Warmup Iteration   1: 3.512 ±(99.9%) 0.087 ms/op
Iteration   1: 2.519 ±(99.9%) 0.077 ms/op
                 createUser·p0.00:   0.430 ms/op
                 createUser·p0.50:   2.281 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.342 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  48.284 ms/op
                 createUser·p0.9999: 51.538 ms/op
                 createUser·p1.00:   51.577 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12974
  mean =      2.519 ±(99.9%) 0.077 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12697 
    [ 5.000, 10.000) = 210 
    [10.000, 15.000) = 3 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 20 
    [50.000, 55.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.430 ms/op
     p(50.0000) =      2.281 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.342 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     48.284 ms/op
     p(99.9900) =     51.538 ms/op
     p(99.9990) =     51.577 ms/op
     p(99.9999) =     51.577 ms/op
    p(100.0000) =     51.577 ms/op


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
# Warmup Iteration   1: 2.939 ±(99.9%) 0.069 ms/op
Iteration   1: 1.922 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.580 ms/op
                 existUser·p0.50:   1.798 ms/op
                 existUser·p0.90:   2.519 ms/op
                 existUser·p0.95:   2.687 ms/op
                 existUser·p0.99:   4.103 ms/op
                 existUser·p0.999:  10.980 ms/op
                 existUser·p0.9999: 11.665 ms/op
                 existUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16818
  mean =      1.922 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 814 
    [ 1.250,  2.500) = 14148 
    [ 2.500,  3.750) = 1622 
    [ 3.750,  5.000) = 118 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      4.103 ms/op
     p(99.9000) =     10.980 ms/op
     p(99.9900) =     11.665 ms/op
     p(99.9990) =     11.698 ms/op
     p(99.9999) =     11.698 ms/op
    p(100.0000) =     11.698 ms/op


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
# Warmup Iteration   1: 3.415 ±(99.9%) 0.095 ms/op
Iteration   1: 1.911 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   1.765 ms/op
                 getUser·p0.90:   2.183 ms/op
                 getUser·p0.95:   2.609 ms/op
                 getUser·p0.99:   3.946 ms/op
                 getUser·p0.999:  22.671 ms/op
                 getUser·p0.9999: 24.299 ms/op
                 getUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16716
  mean =      1.911 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15735 
    [ 2.500,  5.000) = 885 
    [ 5.000,  7.500) = 31 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.946 ms/op
     p(99.9000) =     22.671 ms/op
     p(99.9900) =     24.299 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 4.306 ±(99.9%) 0.119 ms/op
Iteration   1: 3.252 ±(99.9%) 0.065 ms/op
                 listUser·p0.00:   0.713 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   5.939 ms/op
                 listUser·p0.999:  35.333 ms/op
                 listUser·p0.9999: 35.389 ms/op
                 listUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9854
  mean =      3.252 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1036 
    [ 2.500,  5.000) = 8650 
    [ 5.000,  7.500) = 101 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     35.333 ms/op
     p(99.9900) =     35.389 ms/op
     p(99.9990) =     35.389 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.687          ops/ms
ClientSimple.existUser                       thrpt         13.194          ops/ms
ClientSimple.getUser                         thrpt         11.364          ops/ms
ClientSimple.listUser                        thrpt          8.447          ops/ms
ClientSimple.createUser                       avgt          2.174           ms/op
ClientSimple.existUser                        avgt          1.890           ms/op
ClientSimple.getUser                          avgt          2.032           ms/op
ClientSimple.listUser                         avgt          3.600           ms/op
ClientSimple.createUser                     sample  12974   2.519 ± 0.077   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.430           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.281           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.342           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.283           ms/op
ClientSimple.createUser:createUser·p0.999   sample         48.284           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         51.538           ms/op
ClientSimple.createUser:createUser·p1.00    sample         51.577           ms/op
ClientSimple.existUser                      sample  16818   1.922 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.580           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.798           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.687           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.103           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.980           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.665           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.698           ms/op
ClientSimple.getUser                        sample  16716   1.911 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.805           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.765           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.183           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.946           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.671           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.299           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.805           ms/op
ClientSimple.listUser                       sample   9854   3.252 ± 0.065   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.713           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.978           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.969           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.174           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.939           ms/op
ClientSimple.listUser:listUser·p0.999       sample         35.333           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         35.389           ms/op
ClientSimple.listUser:listUser·p1.00        sample         35.389           ms/op

Benchmark result is saved to 1725905146854.json
