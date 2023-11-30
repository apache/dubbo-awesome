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
# Warmup Iteration   1: 2.441 ops/ms
Iteration   1: 6.649 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.649 ops/ms


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
# Warmup Iteration   1: 6.222 ops/ms
Iteration   1: 13.304 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.304 ops/ms


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
# Warmup Iteration   1: 4.680 ops/ms
Iteration   1: 8.622 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.622 ops/ms


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
# Warmup Iteration   1: 2.462 ops/ms
Iteration   1: 4.127 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.127 ops/ms


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
# Warmup Iteration   1: 5.817 ±(99.9%) 0.077 ms/op
Iteration   1: 3.112 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.112 ms/op


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
# Warmup Iteration   1: 3.071 ±(99.9%) 0.030 ms/op
Iteration   1: 1.901 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.901 ms/op


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
# Warmup Iteration   1: 4.939 ±(99.9%) 0.049 ms/op
Iteration   1: 3.435 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.435 ms/op


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
# Warmup Iteration   1: 13.305 ±(99.9%) 0.255 ms/op
Iteration   1: 7.844 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.844 ms/op


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
# Warmup Iteration   1: 5.061 ±(99.9%) 0.116 ms/op
Iteration   1: 2.846 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.838 ms/op
                 createUser·p0.999:  15.737 ms/op
                 createUser·p0.9999: 15.854 ms/op
                 createUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11233
  mean =      2.846 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 4205 
    [ 2.500,  3.750) = 6087 
    [ 3.750,  5.000) = 665 
    [ 5.000,  6.250) = 132 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.838 ms/op
     p(99.9000) =     15.737 ms/op
     p(99.9900) =     15.854 ms/op
     p(99.9990) =     15.860 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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
# Warmup Iteration   1: 3.055 ±(99.9%) 0.076 ms/op
Iteration   1: 1.765 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.478 ms/op
                 existUser·p0.50:   1.686 ms/op
                 existUser·p0.90:   2.208 ms/op
                 existUser·p0.95:   2.347 ms/op
                 existUser·p0.99:   3.133 ms/op
                 existUser·p0.999:  6.176 ms/op
                 existUser·p0.9999: 6.432 ms/op
                 existUser·p1.00:   6.472 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18100
  mean =      1.765 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 73 
    [1.000, 1.500) = 4433 
    [1.500, 2.000) = 9437 
    [2.000, 2.500) = 3637 
    [2.500, 3.000) = 313 
    [3.000, 3.500) = 81 
    [3.500, 4.000) = 38 
    [4.000, 4.500) = 30 
    [4.500, 5.000) = 21 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 3 
    [6.000, 6.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      1.686 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.347 ms/op
     p(99.0000) =      3.133 ms/op
     p(99.9000) =      6.176 ms/op
     p(99.9900) =      6.432 ms/op
     p(99.9990) =      6.472 ms/op
     p(99.9999) =      6.472 ms/op
    p(100.0000) =      6.472 ms/op


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.115 ms/op
Iteration   1: 3.077 ±(99.9%) 0.052 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   2.867 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.765 ms/op
                 getUser·p0.999:  28.627 ms/op
                 getUser·p0.9999: 29.520 ms/op
                 getUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10379
  mean =      3.077 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2918 
    [ 2.500,  5.000) = 7188 
    [ 5.000,  7.500) = 226 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.765 ms/op
     p(99.9000) =     28.627 ms/op
     p(99.9900) =     29.520 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 10.701 ±(99.9%) 0.329 ms/op
Iteration   1: 7.904 ±(99.9%) 0.114 ms/op
                 listUser·p0.00:   3.064 ms/op
                 listUser·p0.50:   7.594 ms/op
                 listUser·p0.90:   10.191 ms/op
                 listUser·p0.95:   11.256 ms/op
                 listUser·p0.99:   18.088 ms/op
                 listUser·p0.999:  21.008 ms/op
                 listUser·p0.9999: 22.839 ms/op
                 listUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4099
  mean =      7.904 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 155 
    [ 5.000,  7.500) = 1820 
    [ 7.500, 10.000) = 1658 
    [10.000, 12.500) = 344 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.064 ms/op
     p(50.0000) =      7.594 ms/op
     p(90.0000) =     10.191 ms/op
     p(95.0000) =     11.256 ms/op
     p(99.0000) =     18.088 ms/op
     p(99.9000) =     21.008 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.649          ops/ms
Client.existUser                       thrpt         13.304          ops/ms
Client.getUser                         thrpt          8.622          ops/ms
Client.listUser                        thrpt          4.127          ops/ms
Client.createUser                       avgt          3.112           ms/op
Client.existUser                        avgt          1.901           ms/op
Client.getUser                          avgt          3.435           ms/op
Client.listUser                         avgt          7.844           ms/op
Client.createUser                     sample  11233   2.846 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          1.075           ms/op
Client.createUser:createUser·p0.50    sample          2.597           ms/op
Client.createUser:createUser·p0.90    sample          3.539           ms/op
Client.createUser:createUser·p0.95    sample          4.342           ms/op
Client.createUser:createUser·p0.99    sample          6.838           ms/op
Client.createUser:createUser·p0.999   sample         15.737           ms/op
Client.createUser:createUser·p0.9999  sample         15.854           ms/op
Client.createUser:createUser·p1.00    sample         15.860           ms/op
Client.existUser                      sample  18100   1.765 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.478           ms/op
Client.existUser:existUser·p0.50      sample          1.686           ms/op
Client.existUser:existUser·p0.90      sample          2.208           ms/op
Client.existUser:existUser·p0.95      sample          2.347           ms/op
Client.existUser:existUser·p0.99      sample          3.133           ms/op
Client.existUser:existUser·p0.999     sample          6.176           ms/op
Client.existUser:existUser·p0.9999    sample          6.432           ms/op
Client.existUser:existUser·p1.00      sample          6.472           ms/op
Client.getUser                        sample  10379   3.077 ± 0.052   ms/op
Client.getUser:getUser·p0.00          sample          0.880           ms/op
Client.getUser:getUser·p0.50          sample          2.867           ms/op
Client.getUser:getUser·p0.90          sample          3.961           ms/op
Client.getUser:getUser·p0.95          sample          4.473           ms/op
Client.getUser:getUser·p0.99          sample          6.765           ms/op
Client.getUser:getUser·p0.999         sample         28.627           ms/op
Client.getUser:getUser·p0.9999        sample         29.520           ms/op
Client.getUser:getUser·p1.00          sample         29.524           ms/op
Client.listUser                       sample   4099   7.904 ± 0.114   ms/op
Client.listUser:listUser·p0.00        sample          3.064           ms/op
Client.listUser:listUser·p0.50        sample          7.594           ms/op
Client.listUser:listUser·p0.90        sample         10.191           ms/op
Client.listUser:listUser·p0.95        sample         11.256           ms/op
Client.listUser:listUser·p0.99        sample         18.088           ms/op
Client.listUser:listUser·p0.999       sample         21.008           ms/op
Client.listUser:listUser·p0.9999      sample         22.839           ms/op
Client.listUser:listUser·p1.00        sample         22.839           ms/op
