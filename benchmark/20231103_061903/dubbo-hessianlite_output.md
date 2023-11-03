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
# Warmup Iteration   1: 1.208 ops/ms
Iteration   1: 2.689 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.689 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.013 ops/ms
Iteration   1: 6.882 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.882 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.230 ops/ms
Iteration   1: 3.961 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.961 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 0.906 ops/ms
Iteration   1: 1.499 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.499 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 12.316 ±(99.9%) 0.271 ms/op
Iteration   1: 6.341 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.341 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 9.432 ±(99.9%) 0.117 ms/op
Iteration   1: 3.537 ±(99.9%) 0.094 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.537 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 14.476 ±(99.9%) 0.440 ms/op
Iteration   1: 6.172 ±(99.9%) 0.118 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.172 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 30.424 ±(99.9%) 1.033 ms/op
Iteration   1: 19.700 ±(99.9%) 0.165 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.700 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 10.702 ±(99.9%) 0.315 ms/op
Iteration   1: 4.782 ±(99.9%) 0.141 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   6.930 ms/op
                 createUser·p0.95:   11.534 ms/op
                 createUser·p0.99:   21.332 ms/op
                 createUser·p0.999:  33.430 ms/op
                 createUser·p0.9999: 47.186 ms/op
                 createUser·p1.00:   47.186 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6697
  mean =      4.782 ±(99.9%) 0.141 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 5330 
    [ 5.000, 10.000) = 941 
    [10.000, 15.000) = 255 
    [15.000, 20.000) = 92 
    [20.000, 25.000) = 36 
    [25.000, 30.000) = 10 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      6.930 ms/op
     p(95.0000) =     11.534 ms/op
     p(99.0000) =     21.332 ms/op
     p(99.9000) =     33.430 ms/op
     p(99.9900) =     47.186 ms/op
     p(99.9990) =     47.186 ms/op
     p(99.9999) =     47.186 ms/op
    p(100.0000) =     47.186 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.867 ±(99.9%) 0.224 ms/op
Iteration   1: 3.143 ±(99.9%) 0.086 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   5.620 ms/op
                 existUser·p0.95:   7.799 ms/op
                 existUser·p0.99:   11.338 ms/op
                 existUser·p0.999:  35.324 ms/op
                 existUser·p0.9999: 35.713 ms/op
                 existUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10321
  mean =      3.143 ±(99.9%) 0.086 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5771 
    [ 2.500,  5.000) = 3370 
    [ 5.000,  7.500) = 599 
    [ 7.500, 10.000) = 394 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      2.449 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      7.799 ms/op
     p(99.0000) =     11.338 ms/op
     p(99.9000) =     35.324 ms/op
     p(99.9900) =     35.713 ms/op
     p(99.9990) =     35.717 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 10.317 ±(99.9%) 0.280 ms/op
Iteration   1: 4.969 ±(99.9%) 0.165 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   7.003 ms/op
                 getUser·p0.95:   10.371 ms/op
                 getUser·p0.99:   20.910 ms/op
                 getUser·p0.999:  65.436 ms/op
                 getUser·p0.9999: 65.733 ms/op
                 getUser·p1.00:   65.733 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6630
  mean =      4.969 ±(99.9%) 0.165 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 5173 
    [ 5.000, 10.000) = 1074 
    [10.000, 15.000) = 291 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 30 
    [25.000, 30.000) = 25 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 25 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      7.003 ms/op
     p(95.0000) =     10.371 ms/op
     p(99.0000) =     20.910 ms/op
     p(99.9000) =     65.436 ms/op
     p(99.9900) =     65.733 ms/op
     p(99.9990) =     65.733 ms/op
     p(99.9999) =     65.733 ms/op
    p(100.0000) =     65.733 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 25.850 ±(99.9%) 1.098 ms/op
Iteration   1: 15.966 ±(99.9%) 0.475 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   15.254 ms/op
                 listUser·p0.90:   22.446 ms/op
                 listUser·p0.95:   25.092 ms/op
                 listUser·p0.99:   33.107 ms/op
                 listUser·p0.999:  122.837 ms/op
                 listUser·p0.9999: 123.208 ms/op
                 listUser·p1.00:   123.208 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2164
  mean =     15.966 ±(99.9%) 0.475 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 552 
    [ 12.500,  25.000) = 1504 
    [ 25.000,  37.500) = 99 
    [ 37.500,  50.000) = 3 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 3 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 0 
    [112.500, 125.000) = 3 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.269 ms/op
     p(50.0000) =     15.254 ms/op
     p(90.0000) =     22.446 ms/op
     p(95.0000) =     25.092 ms/op
     p(99.0000) =     33.107 ms/op
     p(99.9000) =    122.837 ms/op
     p(99.9900) =    123.208 ms/op
     p(99.9990) =    123.208 ms/op
     p(99.9999) =    123.208 ms/op
    p(100.0000) =    123.208 ms/op


# Run complete. Total time: 00:01:36

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           2.689          ops/ms
Client.existUser                       thrpt           6.882          ops/ms
Client.getUser                         thrpt           3.961          ops/ms
Client.listUser                        thrpt           1.499          ops/ms
Client.createUser                       avgt           6.341           ms/op
Client.existUser                        avgt           3.537           ms/op
Client.getUser                          avgt           6.172           ms/op
Client.listUser                         avgt          19.700           ms/op
Client.createUser                     sample   6697    4.782 ± 0.141   ms/op
Client.createUser:createUser·p0.00    sample           0.754           ms/op
Client.createUser:createUser·p0.50    sample           3.826           ms/op
Client.createUser:createUser·p0.90    sample           6.930           ms/op
Client.createUser:createUser·p0.95    sample          11.534           ms/op
Client.createUser:createUser·p0.99    sample          21.332           ms/op
Client.createUser:createUser·p0.999   sample          33.430           ms/op
Client.createUser:createUser·p0.9999  sample          47.186           ms/op
Client.createUser:createUser·p1.00    sample          47.186           ms/op
Client.existUser                      sample  10321    3.143 ± 0.086   ms/op
Client.existUser:existUser·p0.00      sample           0.710           ms/op
Client.existUser:existUser·p0.50      sample           2.449           ms/op
Client.existUser:existUser·p0.90      sample           5.620           ms/op
Client.existUser:existUser·p0.95      sample           7.799           ms/op
Client.existUser:existUser·p0.99      sample          11.338           ms/op
Client.existUser:existUser·p0.999     sample          35.324           ms/op
Client.existUser:existUser·p0.9999    sample          35.713           ms/op
Client.existUser:existUser·p1.00      sample          35.717           ms/op
Client.getUser                        sample   6630    4.969 ± 0.165   ms/op
Client.getUser:getUser·p0.00          sample           1.027           ms/op
Client.getUser:getUser·p0.50          sample           3.981           ms/op
Client.getUser:getUser·p0.90          sample           7.003           ms/op
Client.getUser:getUser·p0.95          sample          10.371           ms/op
Client.getUser:getUser·p0.99          sample          20.910           ms/op
Client.getUser:getUser·p0.999         sample          65.436           ms/op
Client.getUser:getUser·p0.9999        sample          65.733           ms/op
Client.getUser:getUser·p1.00          sample          65.733           ms/op
Client.listUser                       sample   2164   15.966 ± 0.475   ms/op
Client.listUser:listUser·p0.00        sample           2.269           ms/op
Client.listUser:listUser·p0.50        sample          15.254           ms/op
Client.listUser:listUser·p0.90        sample          22.446           ms/op
Client.listUser:listUser·p0.95        sample          25.092           ms/op
Client.listUser:listUser·p0.99        sample          33.107           ms/op
Client.listUser:listUser·p0.999       sample         122.837           ms/op
Client.listUser:listUser·p0.9999      sample         123.208           ms/op
Client.listUser:listUser·p1.00        sample         123.208           ms/op
