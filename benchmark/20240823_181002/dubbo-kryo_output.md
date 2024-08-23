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
# Warmup Iteration   1: 1.893 ops/ms
Iteration   1: 7.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.080 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.101 ops/ms
Iteration   1: 13.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.143 ops/ms


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
# Warmup Iteration   1: 5.916 ops/ms
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
# Warmup Iteration   1: 5.546 ops/ms
Iteration   1: 8.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.451 ops/ms


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
# Warmup Iteration   1: 3.591 ±(99.9%) 0.065 ms/op
Iteration   1: 2.280 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.280 ms/op


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
# Warmup Iteration   1: 2.799 ±(99.9%) 0.047 ms/op
Iteration   1: 1.862 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.862 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.100 ±(99.9%) 0.054 ms/op
Iteration   1: 1.999 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.999 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.365 ±(99.9%) 0.110 ms/op
Iteration   1: 3.165 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.165 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.443 ±(99.9%) 0.090 ms/op
Iteration   1: 2.231 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.531 ms/op
                 createUser·p0.50:   2.159 ms/op
                 createUser·p0.90:   2.789 ms/op
                 createUser·p0.95:   2.982 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  13.271 ms/op
                 createUser·p0.9999: 13.885 ms/op
                 createUser·p1.00:   14.254 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14327
  mean =      2.231 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 486 
    [ 1.250,  2.500) = 9597 
    [ 2.500,  3.750) = 4024 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     13.885 ms/op
     p(99.9990) =     14.254 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.963 ±(99.9%) 0.064 ms/op
Iteration   1: 2.033 ±(99.9%) 0.057 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   1.872 ms/op
                 existUser·p0.90:   2.267 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  50.856 ms/op
                 existUser·p0.9999: 59.132 ms/op
                 existUser·p1.00:   66.650 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15764
  mean =      2.033 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15640 
    [ 5.000, 10.000) = 50 
    [10.000, 15.000) = 15 
    [15.000, 20.000) = 23 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 17 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.267 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =     50.856 ms/op
     p(99.9900) =     59.132 ms/op
     p(99.9990) =     66.650 ms/op
     p(99.9999) =     66.650 ms/op
    p(100.0000) =     66.650 ms/op


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
# Warmup Iteration   1: 3.184 ±(99.9%) 0.074 ms/op
Iteration   1: 2.157 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   2.009 ms/op
                 getUser·p0.90:   2.548 ms/op
                 getUser·p0.95:   3.031 ms/op
                 getUser·p0.99:   4.005 ms/op
                 getUser·p0.999:  28.743 ms/op
                 getUser·p0.9999: 29.541 ms/op
                 getUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14820
  mean =      2.157 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13110 
    [ 2.500,  5.000) = 1639 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.009 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      4.005 ms/op
     p(99.9000) =     28.743 ms/op
     p(99.9900) =     29.541 ms/op
     p(99.9990) =     29.557 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.112 ms/op
Iteration   1: 3.609 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.491 ms/op
                 listUser·p0.999:  24.936 ms/op
                 listUser·p0.9999: 27.623 ms/op
                 listUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8854
  mean =      3.609 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 429 
    [ 2.500,  5.000) = 8152 
    [ 5.000,  7.500) = 188 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.491 ms/op
     p(99.9000) =     24.936 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.080          ops/ms
ClientSimple.existUser                       thrpt         13.143          ops/ms
ClientSimple.getUser                         thrpt         13.972          ops/ms
ClientSimple.listUser                        thrpt          8.451          ops/ms
ClientSimple.createUser                       avgt          2.280           ms/op
ClientSimple.existUser                        avgt          1.862           ms/op
ClientSimple.getUser                          avgt          1.999           ms/op
ClientSimple.listUser                         avgt          3.165           ms/op
ClientSimple.createUser                     sample  14327   2.231 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.531           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.159           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.982           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.415           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.271           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.885           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.254           ms/op
ClientSimple.existUser                      sample  15764   2.033 ± 0.057   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.701           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.872           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.267           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.596           ms/op
ClientSimple.existUser:existUser·p0.999     sample         50.856           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         59.132           ms/op
ClientSimple.existUser:existUser·p1.00      sample         66.650           ms/op
ClientSimple.getUser                        sample  14820   2.157 ± 0.037   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.545           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.009           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.548           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.031           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.005           ms/op
ClientSimple.getUser:getUser·p0.999         sample         28.743           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.541           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.557           ms/op
ClientSimple.listUser                       sample   8854   3.609 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.184           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.527           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.491           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.936           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.623           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.623           ms/op

Benchmark result is saved to 1724436325017.json
