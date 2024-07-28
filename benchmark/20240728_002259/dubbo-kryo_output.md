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
# Warmup Iteration   1: 1.843 ops/ms
Iteration   1: 7.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.359 ops/ms


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
# Warmup Iteration   1: 6.961 ops/ms
Iteration   1: 12.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.713 ops/ms


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
# Warmup Iteration   1: 6.363 ops/ms
Iteration   1: 13.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.972 ops/ms


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
# Warmup Iteration   1: 5.293 ops/ms
Iteration   1: 9.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.184 ops/ms


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.079 ms/op
Iteration   1: 2.045 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.045 ms/op


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
# Warmup Iteration   1: 3.258 ±(99.9%) 0.056 ms/op
Iteration   1: 1.751 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.751 ms/op


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
# Warmup Iteration   1: 3.683 ±(99.9%) 0.085 ms/op
Iteration   1: 1.768 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.768 ms/op


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
# Warmup Iteration   1: 4.535 ±(99.9%) 0.093 ms/op
Iteration   1: 3.092 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.092 ms/op


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
# Warmup Iteration   1: 3.804 ±(99.9%) 0.095 ms/op
Iteration   1: 2.082 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   1.860 ms/op
                 createUser·p0.90:   2.413 ms/op
                 createUser·p0.95:   2.822 ms/op
                 createUser·p0.99:   7.193 ms/op
                 createUser·p0.999:  28.377 ms/op
                 createUser·p0.9999: 28.995 ms/op
                 createUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15696
  mean =      2.082 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14331 
    [ 2.500,  5.000) = 1084 
    [ 5.000,  7.500) = 159 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     28.377 ms/op
     p(99.9900) =     28.995 ms/op
     p(99.9990) =     29.032 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 2.792 ±(99.9%) 0.065 ms/op
Iteration   1: 1.704 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.342 ms/op
                 existUser·p0.50:   1.581 ms/op
                 existUser·p0.90:   2.118 ms/op
                 existUser·p0.95:   2.294 ms/op
                 existUser·p0.99:   2.679 ms/op
                 existUser·p0.999:  10.256 ms/op
                 existUser·p0.9999: 10.922 ms/op
                 existUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18742
  mean =      1.704 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 460 
    [ 1.250,  2.500) = 17799 
    [ 2.500,  3.750) = 396 
    [ 3.750,  5.000) = 5 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.342 ms/op
     p(50.0000) =      1.581 ms/op
     p(90.0000) =      2.118 ms/op
     p(95.0000) =      2.294 ms/op
     p(99.0000) =      2.679 ms/op
     p(99.9000) =     10.256 ms/op
     p(99.9900) =     10.922 ms/op
     p(99.9990) =     10.994 ms/op
     p(99.9999) =     10.994 ms/op
    p(100.0000) =     10.994 ms/op


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
# Warmup Iteration   1: 3.097 ±(99.9%) 0.074 ms/op
Iteration   1: 2.138 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.429 ms/op
                 getUser·p0.50:   1.987 ms/op
                 getUser·p0.90:   2.531 ms/op
                 getUser·p0.95:   2.716 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  18.219 ms/op
                 getUser·p0.9999: 19.777 ms/op
                 getUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14974
  mean =      2.138 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13324 
    [ 2.500,  5.000) = 1487 
    [ 5.000,  7.500) = 67 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     19.777 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.121 ms/op
Iteration   1: 3.432 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.416 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.291 ms/op
                 listUser·p0.999:  16.222 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9373
  mean =      3.432 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1003 
    [ 2.500,  3.750) = 5357 
    [ 3.750,  5.000) = 2786 
    [ 5.000,  6.250) = 125 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     16.222 ms/op
     p(99.9900) =     16.810 ms/op
     p(99.9990) =     16.810 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.359          ops/ms
ClientSimple.existUser                       thrpt         12.713          ops/ms
ClientSimple.getUser                         thrpt         13.972          ops/ms
ClientSimple.listUser                        thrpt          9.184          ops/ms
ClientSimple.createUser                       avgt          2.045           ms/op
ClientSimple.existUser                        avgt          1.751           ms/op
ClientSimple.getUser                          avgt          1.768           ms/op
ClientSimple.listUser                         avgt          3.092           ms/op
ClientSimple.createUser                     sample  15696   2.082 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.689           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.860           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.413           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.193           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.377           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.995           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.032           ms/op
ClientSimple.existUser                      sample  18742   1.704 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.342           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.581           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.118           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.294           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.679           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.256           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.922           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.994           ms/op
ClientSimple.getUser                        sample  14974   2.138 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.429           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.987           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.531           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.489           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.219           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.777           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.054           ms/op
ClientSimple.listUser                       sample   9373   3.432 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.163           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.416           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.291           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.222           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.810           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.810           ms/op

Benchmark result is saved to 1722125920074.json
