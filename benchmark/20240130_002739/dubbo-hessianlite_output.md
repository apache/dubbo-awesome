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
# Warmup Iteration   1: 2.307 ops/ms
Iteration   1: 5.940 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.940 ops/ms


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
# Warmup Iteration   1: 5.914 ops/ms
Iteration   1: 12.865 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.865 ops/ms


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
# Warmup Iteration   1: 4.460 ops/ms
Iteration   1: 9.050 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.050 ops/ms


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
# Warmup Iteration   1: 2.171 ops/ms
Iteration   1: 3.657 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.657 ops/ms


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
# Warmup Iteration   1: 5.312 ±(99.9%) 0.079 ms/op
Iteration   1: 3.210 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.210 ms/op


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
# Warmup Iteration   1: 3.239 ±(99.9%) 0.040 ms/op
Iteration   1: 1.945 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.945 ms/op


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
# Warmup Iteration   1: 4.978 ±(99.9%) 0.063 ms/op
Iteration   1: 3.406 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.406 ms/op


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
# Warmup Iteration   1: 12.097 ±(99.9%) 0.195 ms/op
Iteration   1: 8.570 ±(99.9%) 0.124 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.570 ms/op


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
# Warmup Iteration   1: 5.002 ±(99.9%) 0.097 ms/op
Iteration   1: 3.130 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   8.452 ms/op
                 createUser·p0.999:  13.981 ms/op
                 createUser·p0.9999: 15.892 ms/op
                 createUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10213
  mean =      3.130 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2231 
    [ 2.500,  3.750) = 6512 
    [ 3.750,  5.000) = 1235 
    [ 5.000,  6.250) = 101 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      8.452 ms/op
     p(99.9000) =     13.981 ms/op
     p(99.9900) =     15.892 ms/op
     p(99.9990) =     15.892 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 3.451 ±(99.9%) 0.087 ms/op
Iteration   1: 2.034 ±(99.9%) 0.040 ms/op
                 existUser·p0.00:   0.479 ms/op
                 existUser·p0.50:   1.851 ms/op
                 existUser·p0.90:   2.589 ms/op
                 existUser·p0.95:   2.951 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  33.882 ms/op
                 existUser·p0.9999: 33.948 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15710
  mean =      2.034 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13856 
    [ 2.500,  5.000) = 1762 
    [ 5.000,  7.500) = 60 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.951 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =     33.882 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     33.948 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 4.806 ±(99.9%) 0.110 ms/op
Iteration   1: 2.898 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   2.810 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.959 ms/op
                 getUser·p0.99:   5.100 ms/op
                 getUser·p0.999:  7.192 ms/op
                 getUser·p0.9999: 8.298 ms/op
                 getUser·p1.00:   8.298 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11046
  mean =      2.898 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 5 
    [1.000, 1.500) = 75 
    [1.500, 2.000) = 436 
    [2.000, 2.500) = 2418 
    [2.500, 3.000) = 4036 
    [3.000, 3.500) = 2535 
    [3.500, 4.000) = 1039 
    [4.000, 4.500) = 299 
    [4.500, 5.000) = 83 
    [5.000, 5.500) = 38 
    [5.500, 6.000) = 27 
    [6.000, 6.500) = 26 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 11 
    [7.500, 8.000) = 5 
    [8.000, 8.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.959 ms/op
     p(99.0000) =      5.100 ms/op
     p(99.9000) =      7.192 ms/op
     p(99.9900) =      8.298 ms/op
     p(99.9990) =      8.298 ms/op
     p(99.9999) =      8.298 ms/op
    p(100.0000) =      8.298 ms/op


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
# Warmup Iteration   1: 13.271 ±(99.9%) 0.435 ms/op
Iteration   1: 8.552 ±(99.9%) 0.123 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   8.405 ms/op
                 listUser·p0.90:   11.321 ms/op
                 listUser·p0.95:   12.592 ms/op
                 listUser·p0.99:   15.440 ms/op
                 listUser·p0.999:  19.445 ms/op
                 listUser·p0.9999: 22.610 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3762
  mean =      8.552 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 118 
    [ 5.000,  7.500) = 1185 
    [ 7.500, 10.000) = 1611 
    [10.000, 12.500) = 650 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.997 ms/op
     p(50.0000) =      8.405 ms/op
     p(90.0000) =     11.321 ms/op
     p(95.0000) =     12.592 ms/op
     p(99.0000) =     15.440 ms/op
     p(99.9000) =     19.445 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     22.610 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.940          ops/ms
Client.existUser                       thrpt         12.865          ops/ms
Client.getUser                         thrpt          9.050          ops/ms
Client.listUser                        thrpt          3.657          ops/ms
Client.createUser                       avgt          3.210           ms/op
Client.existUser                        avgt          1.945           ms/op
Client.getUser                          avgt          3.406           ms/op
Client.listUser                         avgt          8.570           ms/op
Client.createUser                     sample  10213   3.130 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          1.284           ms/op
Client.createUser:createUser·p0.50    sample          2.974           ms/op
Client.createUser:createUser·p0.90    sample          3.924           ms/op
Client.createUser:createUser·p0.95    sample          4.293           ms/op
Client.createUser:createUser·p0.99    sample          8.452           ms/op
Client.createUser:createUser·p0.999   sample         13.981           ms/op
Client.createUser:createUser·p0.9999  sample         15.892           ms/op
Client.createUser:createUser·p1.00    sample         15.892           ms/op
Client.existUser                      sample  15710   2.034 ± 0.040   ms/op
Client.existUser:existUser·p0.00      sample          0.479           ms/op
Client.existUser:existUser·p0.50      sample          1.851           ms/op
Client.existUser:existUser·p0.90      sample          2.589           ms/op
Client.existUser:existUser·p0.95      sample          2.951           ms/op
Client.existUser:existUser·p0.99      sample          3.731           ms/op
Client.existUser:existUser·p0.999     sample         33.882           ms/op
Client.existUser:existUser·p0.9999    sample         33.948           ms/op
Client.existUser:existUser·p1.00      sample         33.948           ms/op
Client.getUser                        sample  11046   2.898 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.674           ms/op
Client.getUser:getUser·p0.50          sample          2.810           ms/op
Client.getUser:getUser·p0.90          sample          3.641           ms/op
Client.getUser:getUser·p0.95          sample          3.959           ms/op
Client.getUser:getUser·p0.99          sample          5.100           ms/op
Client.getUser:getUser·p0.999         sample          7.192           ms/op
Client.getUser:getUser·p0.9999        sample          8.298           ms/op
Client.getUser:getUser·p1.00          sample          8.298           ms/op
Client.listUser                       sample   3762   8.552 ± 0.123   ms/op
Client.listUser:listUser·p0.00        sample          1.997           ms/op
Client.listUser:listUser·p0.50        sample          8.405           ms/op
Client.listUser:listUser·p0.90        sample         11.321           ms/op
Client.listUser:listUser·p0.95        sample         12.592           ms/op
Client.listUser:listUser·p0.99        sample         15.440           ms/op
Client.listUser:listUser·p0.999       sample         19.445           ms/op
Client.listUser:listUser·p0.9999      sample         22.610           ms/op
Client.listUser:listUser·p1.00        sample         22.610           ms/op
