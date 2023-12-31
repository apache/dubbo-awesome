# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.547 ops/ms
Iteration   1: 6.349 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.349 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.434 ops/ms
Iteration   1: 12.943 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.943 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.618 ops/ms
Iteration   1: 9.042 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.042 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.182 ops/ms
Iteration   1: 3.849 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.849 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.976 ±(99.9%) 0.104 ms/op
Iteration   1: 3.032 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.032 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.393 ±(99.9%) 0.038 ms/op
Iteration   1: 1.870 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.870 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.442 ±(99.9%) 0.046 ms/op
Iteration   1: 3.212 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.212 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.173 ±(99.9%) 0.224 ms/op
Iteration   1: 8.175 ±(99.9%) 0.091 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.175 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.353 ±(99.9%) 0.130 ms/op
Iteration   1: 3.153 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.469 ms/op
                 createUser·p0.50:   2.879 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   8.858 ms/op
                 createUser·p0.999:  18.280 ms/op
                 createUser·p0.9999: 25.213 ms/op
                 createUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10136
  mean =      3.153 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1819 
    [ 2.500,  5.000) = 7876 
    [ 5.000,  7.500) = 268 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.469 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      8.858 ms/op
     p(99.9000) =     18.280 ms/op
     p(99.9900) =     25.213 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.969 ±(99.9%) 0.063 ms/op
Iteration   1: 2.015 ±(99.9%) 0.056 ms/op
                 existUser·p0.00:   0.609 ms/op
                 existUser·p0.50:   1.810 ms/op
                 existUser·p0.90:   2.405 ms/op
                 existUser·p0.95:   2.552 ms/op
                 existUser·p0.99:   4.380 ms/op
                 existUser·p0.999:  42.878 ms/op
                 existUser·p0.9999: 44.291 ms/op
                 existUser·p1.00:   44.368 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15867
  mean =      2.015 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15724 
    [ 5.000, 10.000) = 41 
    [10.000, 15.000) = 3 
    [15.000, 20.000) = 67 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.405 ms/op
     p(95.0000) =      2.552 ms/op
     p(99.0000) =      4.380 ms/op
     p(99.9000) =     42.878 ms/op
     p(99.9900) =     44.291 ms/op
     p(99.9990) =     44.368 ms/op
     p(99.9999) =     44.368 ms/op
    p(100.0000) =     44.368 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.284 ±(99.9%) 0.099 ms/op
Iteration   1: 2.985 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.875 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   5.582 ms/op
                 getUser·p0.999:  8.651 ms/op
                 getUser·p0.9999: 9.036 ms/op
                 getUser·p1.00:   9.044 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10720
  mean =      2.985 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 223 
    [ 2.000,  3.000) = 6018 
    [ 3.000,  4.000) = 3819 
    [ 4.000,  5.000) = 478 
    [ 5.000,  6.000) = 128 
    [ 6.000,  7.000) = 16 
    [ 7.000,  8.000) = 3 
    [ 8.000,  9.000) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.582 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =      9.036 ms/op
     p(99.9990) =      9.044 ms/op
     p(99.9999) =      9.044 ms/op
    p(100.0000) =      9.044 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.583 ±(99.9%) 0.300 ms/op
Iteration   1: 7.945 ±(99.9%) 0.158 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   7.389 ms/op
                 listUser·p0.90:   9.961 ms/op
                 listUser·p0.95:   11.644 ms/op
                 listUser·p0.99:   22.441 ms/op
                 listUser·p0.999:  31.771 ms/op
                 listUser·p0.9999: 35.783 ms/op
                 listUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4022
  mean =      7.945 ±(99.9%) 0.158 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 110 
    [ 5.000,  7.500) = 1991 
    [ 7.500, 10.000) = 1529 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.001 ms/op
     p(50.0000) =      7.389 ms/op
     p(90.0000) =      9.961 ms/op
     p(95.0000) =     11.644 ms/op
     p(99.0000) =     22.441 ms/op
     p(99.9000) =     31.771 ms/op
     p(99.9900) =     35.783 ms/op
     p(99.9990) =     35.783 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.349          ops/ms
Client.existUser                       thrpt         12.943          ops/ms
Client.getUser                         thrpt          9.042          ops/ms
Client.listUser                        thrpt          3.849          ops/ms
Client.createUser                       avgt          3.032           ms/op
Client.existUser                        avgt          1.870           ms/op
Client.getUser                          avgt          3.212           ms/op
Client.listUser                         avgt          8.175           ms/op
Client.createUser                     sample  10136   3.153 ± 0.047   ms/op
Client.createUser:createUser·p0.00    sample          0.469           ms/op
Client.createUser:createUser·p0.50    sample          2.879           ms/op
Client.createUser:createUser·p0.90    sample          3.797           ms/op
Client.createUser:createUser·p0.95    sample          4.588           ms/op
Client.createUser:createUser·p0.99    sample          8.858           ms/op
Client.createUser:createUser·p0.999   sample         18.280           ms/op
Client.createUser:createUser·p0.9999  sample         25.213           ms/op
Client.createUser:createUser·p1.00    sample         25.264           ms/op
Client.existUser                      sample  15867   2.015 ± 0.056   ms/op
Client.existUser:existUser·p0.00      sample          0.609           ms/op
Client.existUser:existUser·p0.50      sample          1.810           ms/op
Client.existUser:existUser·p0.90      sample          2.405           ms/op
Client.existUser:existUser·p0.95      sample          2.552           ms/op
Client.existUser:existUser·p0.99      sample          4.380           ms/op
Client.existUser:existUser·p0.999     sample         42.878           ms/op
Client.existUser:existUser·p0.9999    sample         44.291           ms/op
Client.existUser:existUser·p1.00      sample         44.368           ms/op
Client.getUser                        sample  10720   2.985 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.971           ms/op
Client.getUser:getUser·p0.50          sample          2.875           ms/op
Client.getUser:getUser·p0.90          sample          3.727           ms/op
Client.getUser:getUser·p0.95          sample          4.121           ms/op
Client.getUser:getUser·p0.99          sample          5.582           ms/op
Client.getUser:getUser·p0.999         sample          8.651           ms/op
Client.getUser:getUser·p0.9999        sample          9.036           ms/op
Client.getUser:getUser·p1.00          sample          9.044           ms/op
Client.listUser                       sample   4022   7.945 ± 0.158   ms/op
Client.listUser:listUser·p0.00        sample          2.001           ms/op
Client.listUser:listUser·p0.50        sample          7.389           ms/op
Client.listUser:listUser·p0.90        sample          9.961           ms/op
Client.listUser:listUser·p0.95        sample         11.644           ms/op
Client.listUser:listUser·p0.99        sample         22.441           ms/op
Client.listUser:listUser·p0.999       sample         31.771           ms/op
Client.listUser:listUser·p0.9999      sample         35.783           ms/op
Client.listUser:listUser·p1.00        sample         35.783           ms/op
