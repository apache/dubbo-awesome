# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.555 ops/ms
Iteration   1: 6.213 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.213 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.429 ops/ms
Iteration   1: 11.217 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.217 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.036 ops/ms
Iteration   1: 8.800 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.800 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.238 ops/ms
Iteration   1: 3.267 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.267 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.825 ±(99.9%) 0.096 ms/op
Iteration   1: 3.230 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.230 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.414 ±(99.9%) 0.038 ms/op
Iteration   1: 1.804 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.804 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.379 ±(99.9%) 0.053 ms/op
Iteration   1: 3.385 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.385 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.362 ±(99.9%) 0.195 ms/op
Iteration   1: 8.269 ±(99.9%) 0.096 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.269 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.830 ±(99.9%) 0.101 ms/op
Iteration   1: 3.204 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.085 ms/op
                 createUser·p0.999:  7.726 ms/op
                 createUser·p0.9999: 10.355 ms/op
                 createUser·p1.00:   10.355 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9940
  mean =      3.204 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 232 
    [ 2.000,  3.000) = 4007 
    [ 3.000,  4.000) = 4386 
    [ 4.000,  5.000) = 1050 
    [ 5.000,  6.000) = 157 
    [ 6.000,  7.000) = 42 
    [ 7.000,  8.000) = 59 
    [ 8.000,  9.000) = 6 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.085 ms/op
     p(99.9000) =      7.726 ms/op
     p(99.9900) =     10.355 ms/op
     p(99.9990) =     10.355 ms/op
     p(99.9999) =     10.355 ms/op
    p(100.0000) =     10.355 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.123 ±(99.9%) 0.084 ms/op
Iteration   1: 1.777 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   1.645 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.544 ms/op
                 existUser·p0.99:   3.400 ms/op
                 existUser·p0.999:  13.418 ms/op
                 existUser·p0.9999: 13.484 ms/op
                 existUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18097
  mean =      1.777 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1369 
    [ 1.250,  2.500) = 15644 
    [ 2.500,  3.750) = 953 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      1.645 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      3.400 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     13.484 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.685 ±(99.9%) 0.128 ms/op
Iteration   1: 3.084 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.112 ms/op
                 getUser·p0.999:  6.609 ms/op
                 getUser·p0.9999: 10.049 ms/op
                 getUser·p1.00:   10.076 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10421
  mean =      3.084 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 4 
    [ 1.000,  2.000) = 872 
    [ 2.000,  3.000) = 3587 
    [ 3.000,  4.000) = 5170 
    [ 4.000,  5.000) = 658 
    [ 5.000,  6.000) = 99 
    [ 6.000,  7.000) = 25 
    [ 7.000,  8.000) = 2 
    [ 8.000,  9.000) = 2 
    [ 9.000, 10.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.112 ms/op
     p(99.9000) =      6.609 ms/op
     p(99.9900) =     10.049 ms/op
     p(99.9990) =     10.076 ms/op
     p(99.9999) =     10.076 ms/op
    p(100.0000) =     10.076 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.747 ±(99.9%) 0.392 ms/op
Iteration   1: 7.768 ±(99.9%) 0.130 ms/op
                 listUser·p0.00:   1.937 ms/op
                 listUser·p0.50:   7.303 ms/op
                 listUser·p0.90:   10.076 ms/op
                 listUser·p0.95:   11.256 ms/op
                 listUser·p0.99:   20.394 ms/op
                 listUser·p0.999:  27.722 ms/op
                 listUser·p0.9999: 29.426 ms/op
                 listUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4162
  mean =      7.768 ±(99.9%) 0.130 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 148 
    [ 5.000,  7.500) = 2149 
    [ 7.500, 10.000) = 1427 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.937 ms/op
     p(50.0000) =      7.303 ms/op
     p(90.0000) =     10.076 ms/op
     p(95.0000) =     11.256 ms/op
     p(99.0000) =     20.394 ms/op
     p(99.9000) =     27.722 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     29.426 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.213          ops/ms
Client.existUser                       thrpt         11.217          ops/ms
Client.getUser                         thrpt          8.800          ops/ms
Client.listUser                        thrpt          3.267          ops/ms
Client.createUser                       avgt          3.230           ms/op
Client.existUser                        avgt          1.804           ms/op
Client.getUser                          avgt          3.385           ms/op
Client.listUser                         avgt          8.269           ms/op
Client.createUser                     sample   9940   3.204 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          1.130           ms/op
Client.createUser:createUser·p0.50    sample          3.150           ms/op
Client.createUser:createUser·p0.90    sample          4.125           ms/op
Client.createUser:createUser·p0.95    sample          4.383           ms/op
Client.createUser:createUser·p0.99    sample          6.085           ms/op
Client.createUser:createUser·p0.999   sample          7.726           ms/op
Client.createUser:createUser·p0.9999  sample         10.355           ms/op
Client.createUser:createUser·p1.00    sample         10.355           ms/op
Client.existUser                      sample  18097   1.777 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.670           ms/op
Client.existUser:existUser·p0.50      sample          1.645           ms/op
Client.existUser:existUser·p0.90      sample          2.331           ms/op
Client.existUser:existUser·p0.95      sample          2.544           ms/op
Client.existUser:existUser·p0.99      sample          3.400           ms/op
Client.existUser:existUser·p0.999     sample         13.418           ms/op
Client.existUser:existUser·p0.9999    sample         13.484           ms/op
Client.existUser:existUser·p1.00      sample         13.484           ms/op
Client.getUser                        sample  10421   3.084 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.853           ms/op
Client.getUser:getUser·p0.50          sample          3.129           ms/op
Client.getUser:getUser·p0.90          sample          3.912           ms/op
Client.getUser:getUser·p0.95          sample          4.166           ms/op
Client.getUser:getUser·p0.99          sample          5.112           ms/op
Client.getUser:getUser·p0.999         sample          6.609           ms/op
Client.getUser:getUser·p0.9999        sample         10.049           ms/op
Client.getUser:getUser·p1.00          sample         10.076           ms/op
Client.listUser                       sample   4162   7.768 ± 0.130   ms/op
Client.listUser:listUser·p0.00        sample          1.937           ms/op
Client.listUser:listUser·p0.50        sample          7.303           ms/op
Client.listUser:listUser·p0.90        sample         10.076           ms/op
Client.listUser:listUser·p0.95        sample         11.256           ms/op
Client.listUser:listUser·p0.99        sample         20.394           ms/op
Client.listUser:listUser·p0.999       sample         27.722           ms/op
Client.listUser:listUser·p0.9999      sample         29.426           ms/op
Client.listUser:listUser·p1.00        sample         29.426           ms/op
